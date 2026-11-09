---
product_id: PbvRrc3CtEif2MOas8
brand: BETAFPV
model: F4 1S 5A AIO Brushless Flight Controller (ELRS 2.4G)
variant: All Variants
source_url: https://betafpv.com/products/f4-1s-5a-aio-brushless-flight-controller
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications: {}
skus:
- sku_code: PbvRrc3CtEif2MOas8-01
  attributes:
    Version: Default
sources:
- type: official
  url: https://betafpv.com/products/f4-1s-5a-aio-brushless-flight-controller
images: []
tags:
- Discontinued
---

# BETAFPV F4 1S 5A AIO Brushless Flight Controller (ELRS 2.4G)

## 产品介绍

The classical ultralight F4 1S brushless FC comes back with SPI ExpressLRS 2.4G receiver.

Now the default firmware for F4 1S 5A AIO Brushless Flight Controller (ELRS 2.4G) is updated to Betaflight V4.3.0 Official version, which supports ELRS V2.0. Please check the below link to download the firmware.

Download the betaflight_4.3.0_BETAFPVF4SX1280.hex

### SPECIFICATIONS OF FC

- CPU: STM32F411CEU6 (100MHZ)

- Six-Axis: ICM-20689/MPU-6000

- Built-in Receiver: SPI ExpressLRS 2.4G

- Receiver antenna: 2.4GHz SMD ceramic antenna

- Size: 29mm x 29mm, fully mounting pattern compatible with the whoop frame in the current market

- Firmware version: betaflight_4.3.0_STM32F411_norevision

- OSD: Built-in BetaFlight OSD

- Recommend VTX: >=200mW, like BETAFPV M03 350mW VTX or TBS Unify VTX

- Power Cable: 55mm, with BT2.0 connector

- Weight: 3.13g (no power cable included)

### SPECIFICATIONS OF ESC

- Power supply: 1S

- Current: 5A continuous and peak 6A (3 seconds)

- Support BLHeliSuite programmable

- Factory firmware: O_H_5_48_REV16_8.HEX

- Signal Support: D-shot150, D-shot300, D-shot600, Oneshot125, Multishot, PWM

Something you should know to protect the ESC SMD ceramic antenna.

- Recommend using BETAFPV Camera Canopy, which reserves sufficient space between Camera and ESC. Therefore, the SMD ceramic antenna will be protected very well.

- Please make sure there is enough space between the camera and the antenna. If the camera position is too low, it will damage the antenna. So the whole FC should be reversed 180 degrees for installation and all motor positions should be reversed too.

- The antenna shouldn't be exposed. It will be fragile without canopy protection.

### Betaflight Firmware and CLI

Since Betaflight has not yet released the official firmware that could support the SPI ExpressLRS protocol, the current version is the Beta version. Please use the firmware and the CLI dump file below to recover the FC board if needed. Betaflight will update its official target soon. Please feel free to contact us if you have any issues with this Beta version Firmware.

It is normal that there is no option on Betaflight Configurator Receiver. As is shown below, the checkbox is blank.

Please change the “PID loop frequency” to “4KHZ” , sometimes it would make the SPI receiver not working correct while the value is “8KHZ”.

The firmware BTFL_4.3.0_BETAFPVF4SX1280_0265565fa uses external GPIO interrupt triggers to process ELRS data reception, increasing the stability of the signal link. Now it can perfectly support LiteRadio 2 SE 500Hz link and modify the accuracy of signal strength.

The new CLI file is named BTFL_cli_F4 5A ELRS_NEW. Please check.

Note: This firmware supports only ELRS 1.0.0, 1.0.1, 1.1.0, 1.2.0, 1.2.1.

Download the firmware and CLI dump file for the F4 1S 5A FC (ELRS 2.4G) board.

How to Bind with Betaflight FC with SPI ExpressLRS Receiver.

More details and discussion on Github about SPI ELRS receiver.

### RECOMMENDED PARTS LIST

- Battery: BT2.0 300mAh 1S Battery

- Frame:  Meteor65 frame / Meteor75 frame

- Props: 31mm 4-Blades props (for 65mm frame) / 40mm 4-blades props (for 75mm frame)

- Motors: 0603 motors / 0703 motors / 0802 motors

- VTX: M03 25-350mW VTX

### DIAGRAM

Larger motor pad for convenience solder directly.

###

### PACKAGE

- 1 * F4 1S brushless flight controller (BT2.0 Connector)

- 4 * M1.2x4mm screws

- 4 * M1.4x5mm screws

- 4 * Anti-vibration rubber dampers

## 技术参数

（来源页未提供规格表）

## 官方资料

https://betafpv.com/products/f4-1s-5a-aio-brushless-flight-controller
