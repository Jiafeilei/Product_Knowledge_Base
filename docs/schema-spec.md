# Markdown Schema 字段规范

本文件是产品知识 Markdown 的**权威字段规范**。采集入口、ERP、AI 均须遵守。

## 1. 文件结构

```markdown
---
<YAML Front Matter>
---

# {品牌} {型号} {版本}

## 产品介绍
...

## 技术参数
...

## 兼容性        # 可选
...

## 官方资料      # 可选
...
```

## 2. YAML Front Matter 字段

### 必填字段

| 字段 | 类型 | 说明 | 示例 |
|---|---|---|---|
| `product_id` | string | 全局唯一 ID，格式 `{品牌缩写}-{型号}-{版本}` | `BF-A65-C` |
| `brand` | string | 品牌名（自动识别 + 人工确认） | `BETAFPV` |
| `model` | string | 型号 | `Air65 II` |
| `variant` | string | 版本/SKU 变体名 | `Champion` |
| `source_url` | string | 原始商品链接 | `https://...` |
| `source_platform` | enum | 来源平台 | 见下方枚举 |
| `collected_at` | datetime | 采集时间，ISO 8601 | `2026-11-07T00:41:53+08:00` |
| `status` | enum | 审核状态 | 见下方枚举 |

### 可选字段

| 字段 | 类型 | 说明 | 示例 |
|---|---|---|---|
| `category` | string | AI 归一分类 | `micro-whoop` |
| `collected_by` | string | 采集人昵称 | `运营A` |
| `confidence` | float | 识别置信度 0–1 | `0.92` |
| `specifications` | map | 规格知识（无价格/库存） | 见 3 |
| `skus` | list | 逐 SKU 记录（多规格展开） | 见 4 |
| `sources` | list | 官方来源引用 | 见 5 |
| `images` | list | 图片引用（本期预留，不采） | 见 6 |
| `tags` | list | 标签 | `["fpv","whoop"]` |

### 枚举

**source_platform**
- `1688` / `taobao` / `tmall` / `brand` / `other`

**status**
- `verified` —— 经人工确认，可用于自动上架
- `unverified` —— 低置信度或未确认，仅供参考
- `draft` —— 未完成校验，禁止下游读取

## 3. specifications（规格知识）

键值结构。值可为标量，或含单位的对象：

```yaml
specifications:
  weight: { value: 16.6, unit: g }
  wheelbase: { value: 65, unit: mm }
  motor: { model: "0702", kv: 36000 }
  receiver: { protocol: ExpressLRS, frequency: 2.4GHz }
  color: 黑色            # 标量亦可
```

规则：
- 只放**知识/技术参数**，不放价格、库存（价格库存进 MySQL）。
- 保留原文数值与单位，不改写事实。
- 单位用英文缩写。

## 4. skus（逐 SKU 记录）

多规格商品按颜色×尺码等**全展开**，每个 SKU 一条：

```yaml
skus:
  - sku_code: BF-A65-C-01
    attributes:
      color: 黑
      size: null
  - sku_code: BF-A65-C-02
    attributes:
      color: 白
      size: null
```

规则：
- `sku_code` 全局唯一，`{product_id}-{序号}`。
- 单一 SKU 商品（如 BETAFPV 版本即 SKU）`skus` 至少一条。
- 价格/库存**不在此**，MySQL 用 `product_id + sku_code` 关联。

## 5. sources（官方来源）

```yaml
sources:
  - type: official          # official | manual | spec
    url: "https://betafpv.com/..."
```

## 6. images（预留）

本期不采图片，字段预留。后续接对象存储后启用：

```yaml
images:
  - type: main              # main | detail | spec | package
    url: ""                 # 对象存储地址
```

## 7. 校验规则

1. YAML 必须可解析（严格语法校验）。
2. 必填字段不得缺失，`source_platform`/`status` 必须落在枚举内。
3. `status=verified` 要求 `confidence ≥ 0.8` 且经人工确认。
4. `skus` 数组非空；多规格商品必须全展开。
5. 价格/库存严禁写入 Markdown。

## 8. 命名规范

- 目录：`products/{品牌}/{型号}/{版本}.md`
- 品牌/型号/版本用 `-` 连字符，ASCII，无空格。
- 大小写与官方保持一致（如 `Air65 II` → `Air65-II`）。
