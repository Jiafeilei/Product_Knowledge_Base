---
product_id: Q600qtl3oQJ3jPAB2H
brand: BETAFPV
model: P Series PWM Receiver
variant: All Variants
source_url: https://betafpv.com/products/p-series-pwm-receiver
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: RC Receiver
collected_by: workbuddy
confidence: 0.6
specifications:
  MCU: ESP32-C3
  RF Chip: SX1281
  Protocol: ELRS 2.4G
  PWM Channels: '4'
  Telemetry Power: 17mW
  Input Voltage: 1-2S
  Voltage Detection Range: 3.0-27V
  Barometer: Onboard
  Serial Output: CRSF / SBUS
  Serial Port: Shared PWM port
  USB Port: '-'
  Expander: '-'
  Antenna Connector: U.FL
  Antenna: 15cm whip antenna
  Dimensions: 35.6*10.6*7.6mm
  Weight (Antenna Excluded): 2.05g
skus:
- sku_code: Q600qtl3oQJ3jPAB2H-01
  attributes:
    Version: P4 2.4G RX
- sku_code: Q600qtl3oQJ3jPAB2H-02
  attributes:
    Version: P6 2.4G RX
- sku_code: Q600qtl3oQJ3jPAB2H-03
  attributes:
    Version: P6D 2.4G Diversity RX
- sku_code: Q600qtl3oQJ3jPAB2H-04
  attributes:
    Version: P8D 2.4G Diversity RX
sources:
- type: official
  url: https://betafpv.com/products/p-series-pwm-receiver
images: []
tags:
- elrs
- RC
- rx
---

# BETAFPV P Series PWM Receiver

## 产品介绍

Engineered for fixed-wing aircraft, RC helicopters, cars, boats, and more, the P Series PWM Receivers combine reliable ExpressLRS 2.4 GHz connectivity with long-range performance and flexible configuration. PWM outputs, CRSF/SBUS serial output, and voltage telemetry provide versatile control and essential flight data. Choose the P6D or P8D for true diversity reception powered by dual SX1281 chips and dual antennas—ideal for larger models and demanding flights. For builds where space and weight matter most, the compact, lightweight P4 and P6 are the perfect fit.

### Bullet Points

- Versatile Compatibility: For fixed-wing aircraft, RC helicopters, cars, boats, and more.

- ExpressLRS 2.4 GHz: Reliable connectivity and long-range performance for confident control.

- Flexible Outputs: PWM outputs and CRSF/SBUS serial output support a wide range of setups.

- Voltage Telemetry: Monitor voltage in real time to stay informed during operation.

- P6D & P8D True Diversity: Dual SX1281 chips and dual antennas provide dependable reception, with 100 mW telemetry power.

- Compact P4 & P6: Weighing just 2.05g and 2.72g without antennas, respectively—ideal for builds where space and weight matter.

### Specifications

### Diagram

P4 2.4G RX:

P6 2.4G RX:

P6D 2.4G Diversity RX:

P8D 2.4G Diversity RX:

### P6D & P8D: Reliable True Diversity

Powered by dual SX1281 chips, P6D and P8D 2.4G RX feature two independent RF channels and dual antennas for dependable reception across a wide range of aircraft orientations. With 100 mW telemetry power, they deliver reliable connectivity for large RC aircraft, long-range flights, and complex aerobatic maneuvers.

### P4 & P6: Compact and Lightweight

Weighing just 2.05 g (P4) and 2.72 g (P6) without antenna, these compact receivers keep weight to a minimum. They are ideal for F3P indoor aerobatic aircraft, F3K hand-launch gliders, indoor RC helicopters, and other builds that demand a small, lightweight receiver.

### Bind

The Receiver uses ExpressLRS V3.x official protocol as its default firmware without a pre-set binding phrase. For successful operation, ensure the transmitter module also uses ExpressLRS V3.x or later firmware with no pre-set binding phrase.

- Power-cycle the receiver 3 times with a 1-second interval to enter binding mode.

- The RGB indicator flashes orange twice, which indicates the receiver is in bind mode.

- Configure remote control or transmitter module to bind with the receiver. If the RGB indicator is a solid light, it's bound!

Notes:

● After binding once, the receiver will remember the autosaved binding phrase and device. Further restarting of the device will be bound automatically without the need for a rebinding process.

● If you have flashed firmware to the receiver and configured the binding phrase, you will not be able to bind using the method above. Please set the same binding phrase for the transmitter module, this allows the receiver to be bound to the device automatically.

● It is recommended to place the two antennas as far apart as possible for better reception.

### Know More About ExpressLRS

ExpressLRS is an open-source RC link for RC applications. Everyone could find this project on Github or join the discussion in Facebook Group.

### File

- User Manual

- Firmware for P Series PWM Receiver

### Package

P Series PWM Receiver - P4 / P6

- 1* P Series PWM Receiver (P4 / P6)

- 1* Antenna

- 1* Voltage Detector

- 2* Heat Shrink Tubing

- 1* User Manual

P Series PWM Diversity Receiver - P6D / P8D

- 1* P Series PWM Diversity Receiver (P6D / P8D)

- 2* Antenna

- 1* Voltage Detector

- 1* CRSF Cable

- 1* SBUS Cable

- 1* Type-C Adapter

- 1* SH1.0 4-Pin Cable

- 2* Heat Shrink Tubing

- 1* User Manual

## 技术参数

| P4 | P6 | P6D | P8D |  |
|---|---|---|---|---|
| MCU | ESP32-C3 | ESP32-C3 | ESP32-S3 | ESP32-S3 |
| RF Chip | SX1281 | SX1281 | Dual SX1281 | Dual SX1281 |
| Protocol | ELRS 2.4G | ELRS 2.4G | ELRS 2.4G | ELRS 2.4G |
| PWM Channels | 4 | 6 | 6 | 8 |
| Telemetry Power | 17mW | 17mW | 100mW | 100mW |
| Input Voltage | 1-2S | 1-2S | 1-2S | 1-2S |
| Voltage Detection Range | 3.0-27V | 3.0-27V | 3.0-27V | 3.0-27V |
| Barometer | Onboard | - | Onboard | Onboard |
| Serial Output | CRSF / SBUS | CRSF / SBUS | CRSF / SBUS | CRSF / SBUS |
| Serial Port | Shared PWM port | Shared PWM port | NH1.0 4-Pin | NH1.0 4-Pin |
| USB Port | - | - | SH1.0 4-Pin | SH1.0 4-Pin |
| Expander | - | - | - | I2C pad |
| Antenna Connector | U.FL | U.FL | U.FL *2 | U.FL *2 |
| Antenna | 15cm whip antenna | 15cm whip antenna | 15cm whip antenna *2 | 15cm whip antenna *2 |
| Dimensions | 35.6*10.6*7.6mm | 30.9*16.0*7.6mm | 45.5*16.0*7.6mm | 45.5*20.8*7.6mm |
| Weight (Antenna Excluded) | 2.05g | 2.72g | 4.02g | 5.08g |

## 官方资料

https://betafpv.com/products/p-series-pwm-receiver
