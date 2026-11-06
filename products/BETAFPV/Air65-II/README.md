# BETAFPV Air65 II

超轻 1S 室内 whoop，三种动力版本：Champion / Racing / Freestyle。

## 版本对比

| 参数 | Champion | Racing | Freestyle |
|---|---|---|---|
| 价格(USD) | 104.99 | 99.99 | 99.99 |
| 重量 | 16.6g | 17.7g | 17.8g |
| 机架 | Air65 Champion | Air65 II | Air65 II |
| 电机 | 0702 36000KV 双滚珠 | 0702 30000KV 黄铜 | 0702 25000KV 黄铜 |
| 电机连接 | 焊接 | JST1.25 3Pin | JST1.25 3Pin |
| 桨叶 | GF 1207 3-B | GF 1207 3-B | GF 1219S 3-B |
| 续航(320mAh) | 4:40 | 4:30 | 5:00 |
| 天线 | Whip | Copper pipe | 未确认 |
| 推重比 | 6.3:1 | — | — |

> 价格/库存属交易数据，不入本仓库，写入 MySQL（`product_id + sku_code` 关联）。

## 文件

- [champion.md](champion.md)
- [racing.md](racing.md)
- [freestyle.md](freestyle.md)

## 通用说明

- 三版本均用 Matrix 1S 5IN1 II 飞控（1S 12A 18A 峰值）、板载 ELRS 2.4G、C03 摄像头、BT2.0 接口。
- 因 IMU 芯片短缺换用 ICM42622/BMI270/LSM6DSK320X，部分芯片 Betaflight 官方固件未兼容，勿刷官方固件。
- 来源：https://betafpv.com/products/air65-ii-brushless-whoop-quadcopter
