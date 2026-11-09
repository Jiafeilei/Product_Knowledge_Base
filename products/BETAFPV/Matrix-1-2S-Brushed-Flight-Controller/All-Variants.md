---
product_id: fOecUcaIcJp6OgrIvI
brand: BETAFPV
model: Matrix 1-2S Brushed Flight Controller
variant: All Variants
source_url: https://betafpv.com/products/matrix-brushed-flight-controller
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushed FC
collected_by: workbuddy
confidence: 0.6
specifications: {}
skus:
- sku_code: fOecUcaIcJp6OgrIvI-01
  attributes:
    Version: 5IN1
- sku_code: fOecUcaIcJp6OgrIvI-02
  attributes:
    Version: 4IN1
sources:
- type: official
  url: https://betafpv.com/products/matrix-brushed-flight-controller
images: []
tags:
- brushed fc
- fc
---

# BETAFPV Matrix 1-2S Brushed Flight Controller

## 产品介绍

The Matrix Brushed Flight Controller is a long‑awaited upgrade for brushed whoops and FPV drone soccer. This compact powerhouse is specifically engineered for both competitive racing and everyday flying. The onboard brushed ESC delivers a continuous 12A current and supports Turtle Mode, while the MCU is upgraded to the latest STM32G473, offering a 55% increase in computing speed. Choose between the fully integrated 5IN1 version (FC + brushed ESC + 400mW 5.8GHz VTX + serial ELRS RX + OSD) for a clean, hassle-free build, or the 4IN1 version with an external VTX port for custom VTX setups.

### Attention

- Flight controllers are covered for manufacturer defects. Issues arising from user errors, physical crash damage, damage during installation or dismantling, modifications, power surges, electrical fires, or water exposure are not covered.

### Bullet Points

- Powerful Brushed ESC – Supports continuous 12A current output (peak 18A) and is fully compatible with 1‑2S batteries for versatile micro drone builds.

- STM32G473 MCU – Upgraded from STM32F411 to the latest STM32G473, delivering a 55% increase in processing speed for smoother flight performance.

- Turtle Mode Support – Flip over after a crash without walking to your drone.

- All‑in‑One Flexibility – Choose the 5IN1 version for simplified installation and maintenance, or the 4IN1 version which retains an external VTX port.

- Race‑Ready 5.8GHz VTX (5IN1 only) – High‑quality VTX with a maximum output of 400mW, providing stable frequency and precise power control.

### Specifications

### FC

- MCU: STM32G473CEU6

- Gyro: BMI270 (3.2KHz)

- Blackbox Memory: 16MB

- Sensor: Voltage & current

- BEC: 5V, max. 3A

- UART (5IN1): UART 1, UART 2 (for VTX), UART 3 (for RX), UART 4

- UART (4IN1): UART 1 (for VTX), UART 2 , UART 3 (for RX)

- BetaFlight OSD: AT7456E

- ESC: Continuous 12A

- RX: Serial ELRS 2.4GHz (V3.4.3)

- VTX: 5.8GHz 48 channels, max. 400mW

- FC Firmware: Betaflight_4.5.2_BETAFPVG473_V3 (5IN1), Betaflight_4.5.2_BETAFPVG473_V2 (4IN1)

- USB Port: SH1.0-4Pin

- Motor Plug: JST1.25

- Battery Connector: BT2.0

- Mounting Size: 26mm x 26mm

- Weight: 3.80±0.1g (5IN1), 3.56±0.1g (4IN1)

### ESC

- Power Input: 1-2S

- Current: Continuous 12A, peak 18A

- Digital Signal Protocol: Brushed

### VTX (5IN1 Only)

- Output Power: 25/100/200/400/PIT

- Frequency: 5.8GHz 48 channels, with raceband 5658-5917MHz

- Channel SEL: SmartAudio2.0

- Modulation Type: FM

- Frequency Control: PLL

- All Harmonic: Max -50dBm

- Frequency Stability: ±100KHz (Typ.)

- Frequency Precision: ±200KHz (Typ.)

- Channel Ccarrier Error: ±1.5dB

- Antenna Port: 50Ω

- Operating Temperature: -10℃ to +80℃

### Diagram

Matrix Brushed Flight Controller (5IN1):

Matrix Brushed Flight Controller (4IN1):

### Highly-Integration 5IN1 & 4IN1

The Matrix Brushed Flight Controller is available in two versions: 5IN1 and 4IN1. The 5IN1 integrates flight controller, brushed ESC, VTX, serial ELRS receiver, OSD, and Blackbox for easy installation and maintenance. The high‑quality 400mW 5.8GHz VTX delivers precise and stable frequency, meeting the demands of racing while being perfectly suitable for everyday flight. And the 4IN1 retains a port for an external VTX, giving you the freedom to use your preferred video transmitter.

### 12A Brushed ESC with Turtle Mode

The onboard ESC provides 12A continuous (18A peak) output and supports 1‑2S battery operation. Turtle Mode is also available — after a crash, simply flip the drone over and continue flying.

Firmware Note: Betaflight has not yet released official firmware compatible with this brushed FC board, so please do not flash the official Betaflight firmware and pay attention to future support update.

- Click to download the firmware for Matrix Brushed Flight Controller.

Turtle Mode Instructions:

- In Betaflight, go to the Modes tab and find "FLIP OVER AFTER CRASH".

- Assign an AUX channel (AUX4 by default) and set the activation range.

- After a crash, enable the Turtle Mode switch, then arm the motors. Use your radio to flip the drone over.

- Disable Turtle Mode, then re‑arm the motors to resume normal flight.

### Enhanced MCU Performance

The MCU has been upgraded from the STM32F411 (used in the F4 1S 5A FC) to the latest STM32G473C, resulting in a 55% increase in computing speed. This means smoother control response and a more locked‑in flight experience.

### Serial ELRS 2.4G RX

Serial ELRS 2.4G RX uses the Crossfire serial protocol (CRSF protocol) to communicate between the receiver and the flight controller board. So the Serial ELRS 2.4G RX is available to support upgrading to ELRS V3.0 with no need to flash Betaflight flight controller firmware. Enter binding status by power on/off three times.

- Plugin and unplug the flight controller three times;

- Make sure the RX LED is doing a quick double blink, which indicates the receiver is in bind mode;

- Make sure the RF TX module or radio transmitter enters binding status, which sends out a binding pulse;

- If the receiver has a solid light, it's bound.

The Serial ELRS 2.4G RX can be updated via Wi-Fi or Betaflight serial passthrough. Here is the way to update the Serial ELRS 2.4G RX firmware through passthrough.

- Plug in your FC to your computer, connect to ExpressLRS Configurator instead of Betaflight Configurator;

- Choose target "BETAFPV 2.4GHz AIO RX";

- Flash using the BetaflightPassthrough option in ExpressLRS Configurator.

How to flash firmware via Wi-Fi here.

### How to Use Serial Ports, Intergrated RX and VTX

Please note that by default UART3 is connected to the RX. To release UART3, please remove the resistor. Additionally, this FC reserves 3 complete full-featured serial ports that can be used for external CRSF/SBUS receivers, GPS, HD VTX, or other serial devices. You can refer to the picture below.

Matrix Brushed Flight Controller (5IN1):

Matrix Brushed Flight Controller (4IN1):

### Recommeded Parts

- Motors: 7x16mm Brushed Motors

- Camera: Air Camera, C03 FPV Micro Camera

### Package

- 1 * Matrix Brushed Flight Controller (5IN1)

-
1 * 5.8G Antenna

- 1 * Type-C to SH1.0 Adapter

- 1 * SH1.0-4Pin Adapter Cable

- 4 * M1.2*4 Self-tapping Screws

- 4 * M1.4*5 Self-tapping Screws

- 4 * Shock Absorbing Balls

- 1 * Matrix Brushed Flight Controller (4IN1)

- 1 * Type-C to SH1.0 Adapter

- 1 * SH1.0-4Pin Adapter Cable

- 4 * M1.2*4 Self-tapping Screws

- 4 * M1.4*5 Self-tapping Screws

- 4 * Shock Absorbing Balls

## 技术参数

（来源页未提供规格表）

## 官方资料

https://betafpv.com/products/matrix-brushed-flight-controller
