---
product_id: qZ8HU68dycOoX3CRd1
brand: BETAFPV
model: Cube 2-4S Brushless Flight Controller
variant: All Variants
source_url: https://betafpv.com/products/cube-2-4s-brushless-flight-controller
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications:
  MCU: STM32G473CEU6
  MCU Frequency: 168MHz
  OSD: /
  Blackbox Memory: 16MB
  RX: Onboard serial ELRS 2.4GHz
  VTX: Support HD VTX
  Circuit Board Thickness: 1.2mm
  ESC: Continuous 30A
  Motor Connector: Gold plated JST1.25
  Weight (VTX antenna excluded): 6.8±0.2g
skus:
- sku_code: qZ8HU68dycOoX3CRd1-01
  attributes:
    Version: 3IN1
sources:
- type: official
  url: https://betafpv.com/products/cube-2-4s-brushless-flight-controller
images: []
tags:
- 2-4s brushless fc
- brushless fc
- fc
---

# BETAFPV Cube 2-4S Brushless Flight Controller

## 产品介绍

The Cube Brushless Flight Controller is BETAFPV's brand-new 2-4S AIO FC, engineered specifically for propulsion upgrades of Pavo whoops. This 3IN1 board integrates the STM32G473 MCU, a powerful 2-4S 30A ESC, and Serial ELRS 2.4GHz RX into a single compact design, tailored for digital VTX whoops. Featuring a robust 30A continuous ESC—upgraded from 20A with 2oz copper thickness for superior thermal efficiency—the Cube FC reliably meets the surge demands of 2-4S whoops during aggressive freestyle maneuvers. Powered by a 168MHz MCU with exceptional computing capacity, it delivers responsive flight control and silky-smooth handling for both freestyle and cinematic flying. Whether you're upgrading an existing build or starting from scratch, the Cube FC provides a powerful, affordable, and reliable foundation for the ultimate digital whoop experience.

###  Attention

- Flight controllers are covered for manufacturer defects. Issues arising from user errors, physical crash damage, damage during installation or dismantling, modifications, power surges, electrical fires, or water exposure are not covered.

### Bullet Points

- 3-in-1 Integration: Combines STM32G473 MCU, 2-4S 30A ESC, and Serial ELRS 2.4GHz RX in a single compact board.

- Continuous 30A ESC: Upgraded to a robust 30A continuous current with 2oz copper thickness for reliable power.

- High-Performance MCU: STM32G473 processor running at 168MHz delivers excellent computing capacity for responsive flight performance.

- Digital VTX Optimized: An affordable, streamlined solution specifically designed for digital HD whoop builds.

-
Future-Proof Expandability: Additional serial ports reserved for external devices like GPS modules, offering room for customization and upgrades.

### Specifications

### FC

-
MCU: STM32G473CEU6

- Gyro: ICM42605, 8KHz

- Blackbox memory: 16MB

- Sensor: Voltage & Current, Barometer (TCBP001TA)

- BEC: 9V@2A, 5V@3A

- UART: UART 1, UART 2, UART 3 (For RX), UART 4 (For HD VTX)

- Betaflight OSD: /

- ESC: 30A continuous

- RX: Serial ELRS 2.4GHz (V3.5.6)

-
FC firmware: 2025.12.0-beta_BETAFPVG473_V3

- USB port: SH1.0-4Pin

- Motor connector: JST1.25

- Battery connector: XT30

- Mounting hole size: 26mm x 26mm

-
Weight: 6.8±0.2g

### ESC

-
Power input: 2-4S Lipo/LiHV

- Current: 30A continuous

- ESC firmware: v0.19.2 48KHz Bluejay

-
Firmware target: C-X-70 48KHz.hex

- Digital signal protocol: DShot150, DShot300, DShot600

### RX

- RX: Serial ExpressLRS 2.4GHz

- Antenna: Copper wire 31mm length

- Firmware target: BETAFPV 2.4G AIO RX

- Telemetry output power: <12dBm

- ELRS firmware version: ELRS 3.5.6

- Flash firmware via WIFI: Support

### Diagram

### Digital-Ready 3IN1 FC

Engineered specifically for digital VTX whoops, the Cube 3IN1 FC consolidates the STM32G473 MCU, 2-4S 30A ESC, and Serial ELRS 2.4GHz RX into a single compact board—streamlining builds while reducing complexity. The STM32G473 MCU running at 168MHz delivers excellent computing capacity for responsive flight performance, while additional serial ports reserved for external devices like GPS modules offer room for customization and upgrades.

### 2-4S Continuous 30A ESC

By integrating 2oz thick copper on the board to enhance thermal efficiency and current handling, the Cube FC features a significantly upgraded 2-4S Bluejay ESC—delivering a robust 30A continuous current, up from 20A in F405 FCs. This ensures reliable power delivery to meet the surge demands of Pavo whoops during aggressive freestyle maneuvers, giving pilots the confidence to push their limits.

### Cube 2-4S 30A FC vs. F4 2-3S 20A FC

### Serial ELRS 2.4G RX

Serial ELRS 2.4G RX uses the Crossfire serial protocol (CRSF protocol) to communicate between the receiver and the flight controller board. So the Serial ELRS 2.4G RX is available to support upgrading to ELRS V3.0 with no need to flash Betaflight flight controller firmware. Enter binding status by power on/off three times.

- Plugin and unplug the flight controller three times;

- Make sure the RX LED is doing a quick double blink, which indicates the receiver is in bind mode;

- Make sure the RF TX module or radio transmitter enters binding status, which sends out a binding pulse;

- If the receiver has a solid light, it's bound.

The Serial ELRS 2.4G RX can be updated via Wi-Fi or Betaflight serial passthrough. Here is the way to update the Serial ELRS 2.4G RX firmware through passthrough.

- Plug in your FC to your computer, connect to ExpressLRS Configurator instead of Betaflight Configurator;

- Choose target "BETAFPV 2.4GHz AIO RX";

- Flash using the BetaflightPassthrough option in ExpressLRS Configurator.

How to flash firmware via Wi-Fi here.

### Bluejay ESC Firmware

With BB51 ESC solution, Cube Brushless Flight Controller is based on V0.19.2 48KHz Bluejay, it supports DShot150, DShot300, DShot600, and even RPM filtering in Betaflight, offers 24KHz, 48KHz, and 96KHz fixed PWM frequency for options, and custom start-up melodies.

DO NOT flash the firmware with a shorter interval, otherwise, there will be a certain chance of stalling and burning the flight controller.

- ESC-Configurator: https://preview.esc-configurator.com/

- Download BLHeliSuite16714903

- Download the Bluejay ESC firmware. Please choose C_X_70_48_v0.19.2.hex

### How to Use Serial Ports, Intergrated RX and VTX

Please note that by default, UART3 is connected to the RX and UART4 is connected to the HD VTX. To release UART3, please remove the resistor. Additionally, this FC reserves 2 complete full-featured serial ports that can be used for external CRSF/SBUS receivers, GPS, or other serial devices. You can refer to the below pictures.

### Recommended Parts

- Drones: Pavo20 Pro II, Pavo Pico II, Pavo Femto

- Frames: Pavo20 Pro II Frame, Pavo Pico II Frame, Pavo Femto Frame

- Motors: LAVA 1104 Motors, LAVA 1102 Motors

### Package

- 1 * Cube Brushless Flight Controller

- 1 * 220uF 25V Capacitor

- 1 * 30mm Connector Cable for Digital VTX

- 1 * 50mm Connector Cable for Digital VTX

-
1 * 50mm XT30 Cable

- 1 * USB Adapter

- 1 * USB Adapter Cable

- 4 * 8mm Shock Absorbing Balls

- 4 * 6.6mm Shock Absorbing Balls

- 4 * M2 Nuts

- 4 * M2*10 Screws

- 2 * 0.8mm Heat Shrink Tubing

## 技术参数

| Cube 2-4S 30A FC | F4 2-3S 20A FC |  |
|---|---|---|
| MCU | STM32G473CEU6 | STM32F405RGT6 |
| MCU Frequency | 168MHz |  |
| OSD | / |  |
| Blackbox Memory | 16MB |  |
| RX | Onboard serial ELRS 2.4GHz |  |
| VTX | Support HD VTX |  |
| Circuit Board Thickness | 1.2mm | 1.0mm |
| ESC | Continuous 30A | Continuous 20A |
| Motor Connector | Gold plated JST1.25 | JST1.25 |
| Weight (VTX antenna excluded) | 6.8±0.2g | 5.7±0.2g |

## 官方资料

https://betafpv.com/products/cube-2-4s-brushless-flight-controller
