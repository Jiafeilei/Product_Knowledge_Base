# Product Knowledge Base

产品知识库 —— 产品「知识」的唯一数据源（Single Source of Truth）。

> 采集入口（微信/飞书智能体）把产品链接的信息提取后，规范化为 Markdown 存入本仓库。
> 供 ERP、数据驾驶舱、AI 跨平台读取与迁移。

## 目录结构

```
Product_Knowledge_Base/
├── products/                 # 产品知识（按 品牌/型号/版本 三级）
│   └── {品牌}/
│       └── {型号}/
│           └── {版本}.md
├── docs/
│   └── schema-spec.md        # Markdown Schema 字段规范（权威）
├── _template.md              # 标准模板（复制使用）
└── README.md
```

## 数据边界（重要）

| 内容 | 唯一来源 | 是否入本仓库 |
|---|---|---|
| 产品知识（描述/参数/兼容性） | Markdown | ✅ 本仓库 |
| SKU 规格结构（颜色/尺码组合） | Markdown | ✅ 本仓库 |
| 内部采购价（跨平台固定、时间范围内固定） | MySQL | ❌ 不入仓库 |
| 货号映射（内部货号 + 平台链接货号） | MySQL（预留） | ❌ 不入仓库 |
| 图片 | 对象存储（预留） | ❌ 本期不采，字段预留 |

采购价经 `product_id` 关联，存在 MySQL `product_purchase_price` 表（库存不存）。
货号映射预留 `product_articles` 表：`RC1-1`（内部标准货号）与 `RC1-1 / RC1-1_2026 / RC1-1_202601`（平台链接货号）是同一商品的不同上架货号。

## 规范速查

- 字段规范：见 [`docs/schema-spec.md`](docs/schema-spec.md)
- 标准模板：见 [`_template.md`](_template.md)
- 命名：目录/文件名用 `-` 连字符、ASCII、无空格
- 语言：保留来源原文（中文/英文），不做翻译
- 状态：`verified`（人工确认）/ `unverified`（低置信待审）/ `draft`
