---
product_id: vxyZarBdQOzgTRtvSd
brand: BETAFPV
model: F4 1S 12A AIO Brushless Flight Controller 2022
variant: All Variants
source_url: https://betafpv.com/products/f4-1s-12a-flight-controller
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications:
  FRSKY_D: Frsky D8
  FRSKY _X: Frsky D16 FCC (ACCST 1.X version)
  FRSKY_X_LBT: Frsky D16 LBT (ACCST 1.X version)
  SFHSS: Futaba S-FHSS
skus:
- sku_code: vxyZarBdQOzgTRtvSd-01
  attributes:
    Built in Rx Version: SPI ELRS 2.4G
- sku_code: vxyZarBdQOzgTRtvSd-02
  attributes:
    Built in Rx Version: SPI Frsky
sources:
- type: official
  url: https://betafpv.com/products/f4-1s-12a-flight-controller
images: []
tags:
- Discontinued
---

# BETAFPV F4 1S 12A AIO Brushless Flight Controller 2022

## 产品介绍

F4 1S 12A AIO Brushless Flight Controller V2.2 is the default FC for Cetus X brushless whoop quadcopter, also great for 85mm whoop drones like Meteor85 and 3" toothpick drones like HX115 SE Toothpick Drone and HX115 LR Toothpick Drone. We updated the FC to V2.2 with BMI270 gyro and BB51 ESC hardware in place of ICM20689 gyro and BB21 ESC hardware.

Please click here to page F4 1S 12A AIO SPI ELRS V2.0 if you need information about it.

Tons of ExpressLRS items are available now!

### Bullet Point

-
F4 1S 12A AIO Flight Controller is the best choice for building ultra-lightweight 3" toothpick drones like HX115 SE FPV Quad and 85mm whoop drones. Recommend Meteor85.

- Most of the 1S flight controllers on the market come with 5A ESC by now, but this FC especially integrates 1S 12A ESC, providing more sufficient power for 3" toothpick drones or 85mm whoop drones.

- Built-in current meter, 2 programmable RGB LEDs, and SPI ELRS or Frsky receiver. At the same time, all the pads are left for the external receivers with UART1 and UART2, for buzzers, etc.

- Large pads are reserved for solder motor cables, this design will make solder easier.

### Specification of FC

- Item: F4 1S 12A AIO FC

- Weight: 4.74 g (without power cable and BT2.0 connector)

- CPU: STM32F411CEU6 (100MHZ )

- Six-Axis: BMI270 (SPI connection)

- Firmware version: betaflight_4.3.1_BETAFPVF4SX1280 (ELRS) /betaflight_4.2.11_BETAFPVF411RX (Frsky)

- OSD: Built-in BetaFlight OSD (STM32 controls OSD chip over SPI in DMA mode)

- Receiver: SPI ELRS 2.4G Receiver/SPI Frsky

- Motor Pin Connector: 1.25mm Header Pins

- Mounting Hole Size: 26mm x 26mm (suitable for whoop pattern mounting hole)

- USB Port: SH1.0 4-Pin

### Specification of 1S 12A ESC

- Built-in ESC with 12A continuous and peak 25A current

- Input voltage: 1S-2S

- ESC firmware: C_X_30_48_V0.18.1.hex for Bluejay BB51 hardware

- Signal support: D-shot150, D- shot300, D-shot600, Oneshot125, Multishot, PWM

The Bluejay firmware could support the BB51 hardware now. Both ELRS and Frsky boards are powered by BB51 hardware. If you want to setup the ESC specification, please use the BLHeliSuite16714902A_Beta or ESC-Configurator.

- ESC-Configurator: https://preview.esc-configurator.com/

- Download BLHeliSuite16714902A_Beta here.

- Download the Bluejay ESC firmware. Please choose C_X_30.HEX.

Note: Only SPI ELRS 2.4G version supports motor direction set through Betaflight Configurator and SPI Frsky version does not support it. BLHeli Configurator and Bluejay Configurator are invalid for the BB51 ESC (both versions).

### Diagram for F4 1S 12A AIO FC

Below is the diagram for SPI ELRS 2.4G board.

Below is the diagram for SPI Frsky board.

The current meter is integrated on the FC board. Here is the configuration in Betaflight Configurator.

### 12A 1S ESC

Should we really need a 12A ESC for 1S drones? If it is a 65mm or 75mm Whoop drone-like Meteor65, 5A ESC is enough for all actions. But how about with 3" propellers and 1102/1202.5 motors? Still, want smooth and powerful flying actions? The 5A ESC has developed about 3 years ago and was designed for whoop drones with 0603/0802 motors. For the past year, the BETAFPV team has been cooperating with BLHeli author Steffen on the 12A 1S ESC for 3" toothpick drones. Finally, it is here!

### SPI ELRS 2.4G RX

This board integrates the receiver with the most popular radio link ExpressLRS since 2021. ExpressLRS aims to achieve the best possible link performance in both speeds, latency, and range. Know more about the ExpressLRS project on Github or join the discussion in the Facebook Group.

This board is designed for long-range 3inch ultralight toothpick drones or 2S whoop drones. If you want to try ExpressLRS on 65mm/75mm whoop drones, please build it with our F4 1S FC board with a built-in SPI ExpressLRS receiver.

F4 1S 12A AIO V2.2 integrates SPI ELRS 2.4G RX. The configuration is as follows.

How to Bind with Betaflight FC with SPI ExpressLRS Receiver.

How to Bind with Betaflight FC with External ExpressLRS Receiver.

More details and discussion on Github about SPI ELRS receiver.

### SPI Frsky RX

Come with the built-in SPI Frsky Receiver (CC2500 chip), F4 1S 12A AIO FC can be compatible with Futaba S-FHSS, Frsky D8, and D16 protocol. The default protocol is configured to Frsky D16 FCC out of the factory. Pilots could set up the protocol according to your own need in Betaflight Configurator.

How to Bind with Betaflight FC with SPI Frsky Receiver.

### Betaflight Firmware and CLI

F4 1S 12A FC board comes with the default firmware betaflight_4.3.1_BETAFPVF4SX1280 (ELRS) or betaflight_4.2.11_BETAFPVF411RX (Frsky). The default firmware for SPI ELRS 2.4G RX version supports ELRS V2.0 RX.

Pay attention, For the SPI ELRS 2.4G version, ONLY the Betaflight firmware 4.3.0 and up start to support this BMI270 gyro. For the SPI Frsky version, DO NOT flash the other firmware. We have already built our own firmware betaflight_4.2.11_BETAFPVF411RX for SPI Frsky RX version to support BMI270 gyro. Please check the below link to download the firmware.

Download the firmware and CLI dump file for the F4 1S 12A FC board (ELRS and Frsky).

### Bluejay ESC Firmware

F4 1S 12A flight controller with BB51 ESC hardware could flash the Bluejay ESC firmware now, which is based on BLHeli_S revision 16.7. With Bluejay ESC firmware, it supports bidirectional D-shot and RPM filtering in Betaflight, offers 24KHz, 48KHz, and 96KHz fixed PWM frequency for options, and custom start-up melodies. By using Bluejay ESC firmware on Cetus X and Meteor85 whoop drones with 1103 11000KV motors, the flight time is increasing effectively.

For pilots who want to flash Bluejay ESC firmware for F4 1S 12A FC, please use the BLHeliSuite16714902A_Beta or ESC-Configurator and download Bluejay ESC firmware C_X_30_.HEX from the below links.

- ESC-Configurator: https://preview.esc-configurator.com/

- Download BLHeliSuite16714902A_Beta here.

- Download the Bluejay ESC firmware. Please choose C_X_30.HEX.

Note: Only SPI ELRS 2.4G version supports motor direction set through Betaflight Configurator and SPI Frsky version does not support it. BLHeli Configurator and Bluejay Configurator are invalid for the BB51 ESC (both versions).

### Connecting External RX/HD Digital or Analog VTX

Both SPI ELRS 2.4G RX and SPI Frsky RX version support external HD digital VTX or Analog VTX. Please note that the board reserves an SBUS port and a UART port, which is available for the SBUS protocol receiver or other external receivers. You can refer to the below picture.

### Recommend Parts

If you want to try the popular ExpressLRS receiver version for long-range performance, highly recommend you check the items for the ExpressLRS series.

- Drones: Cetus X, 85mm whoop frame like Meteor85, Meteor85 HD, 3" toothpick drones

- Battery: BT2.0 450mAh 1S 30C Battery, 450mAh 2S 45C Battery

- Motor: 1102 18000KV motor, 1103 11000KV motor

- Propeller: HQ3020 2-blade Props, 2020 4-blade Props

### Package

- 1 * F4 1S 12A AIO FC

- 4 * Anti-vibration Rubber Dampers

- 4 * M2 x 10mm Screws

- 4 * M2 x 10mm Screws

- 4 * M2 Screw Nut

- 8 * PH-1.25 Connectors for Motor

- 1 * SH1.0 4-Pin Cable

- 1 * SH1.0 4-Pin to USB Type-C Adapter

## 技术参数

| Configuration | Protocol |
|---|---|
| FRSKY_D | Frsky D8 |
| FRSKY _X | Frsky D16 FCC (ACCST 1.X version) |
| FRSKY_X_LBT | Frsky D16 LBT (ACCST 1.X version) |
| SFHSS | Futaba S-FHSS |

## 官方资料

https://betafpv.com/products/f4-1s-12a-flight-controller
