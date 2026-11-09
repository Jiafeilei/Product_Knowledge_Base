---
product_id: xdgqaCJOCd7IIyign7
brand: BETAFPV
model: F4 1S 12A AIO Brushless Flight Controller
variant: All Variants
source_url: https://betafpv.com/products/f4-1s-12a-flight-controller-v2-0
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
- sku_code: xdgqaCJOCd7IIyign7-01
  attributes:
    Built in Rx Version: ELRS 2.4G V2.0
- sku_code: xdgqaCJOCd7IIyign7-02
  attributes:
    Built in Rx Version: ELRS 2.4G V1.0
- sku_code: xdgqaCJOCd7IIyign7-03
  attributes:
    Built in Rx Version: SPI Frsky
- sku_code: xdgqaCJOCd7IIyign7-04
  attributes:
    Built in Rx Version: SPI FrSky with Motor Connectors
sources:
- type: official
  url: https://betafpv.com/products/f4-1s-12a-flight-controller-v2-0
images: []
tags:
- Discontinued
- sale
---

# BETAFPV F4 1S 12A AIO Brushless Flight Controller

## 产品介绍

The SPI FrSky with Motor Connectors version features connectors soldered to the sides at a 90° angle, as shown below.

What is the update of the ELRS 2.4G V2.0 board?

- Support both 1S and 2S battery now. Only 1S supported on V1.0.

- Use SPI ExpressLRS 2.4 receiver with Betaflight firmware.

- Modify the shape of the board to support 85mm whoop frame. Only toothpick frame supported on V1.0.

- Use the lighter and smaller SH connector instead of USB Type-C.

F4 1S 12A AIO Flight Controller - A 1S 12A FC for building lightweight 3" toothpick drones like HX115 SE Toothpick Drone and HX115 LR Toothpick Drone. If you want to try a bigger FPV drone than 65mm/75mm on 1S power, and still want smooth and powerful flying actions, this FC that integrates 1S 12A ESC is definitely your best choice.

Now the default firmware for F4 1S 12A AIO Brushless Flight Controller is updated to Betaflight V4.3.0 Official version, which supports ELRS V2.0. Please check the below link to download the firmware.

Download the betaflight_4.3.0_BETAFPVF4SX1280.hex

Tons of ExpressLRS items are available now!

### Bullet Point

-
F4 1S 12A AIO Flight Controller is the best choice for building ultra-lightweight 3" toothpick drones like HX115 SE FPV Quad.

- Most of the 1S flight controllers on the market come with 5A ESC by now, but this FC especially integrates 1S 12A ESC, it can provide more sufficient power for 3" toothpick drones.

- Built-in current meter, 2 programmable RGB LEDs, and SPI Frsky receiver. At the same time, all the pads are left for the external receivers with UART1 and UART2, for buzzers, etc.

- Whoop mounting hole pattern, be compatible with most 1S 3" frames. Large pads are reserved for solder motor cables, this design will make solder easier.

### Specification of FC

- Item: F4 1S 12A AIO FC

- Weight: 4.74 g (without power cable and BT2.0 connector)

- CPU: STM32F411CEU6 (100MHZ )

- Six-Axis: MPU6000 (SPI connection)

- Firmware version: betaflight_4.2.0_STM32F411

- OSD: Built-in BetaFlight OSD (STM32 controls OSD chip over SPI in DMA mode)

- Receiver: Integrated SPI Frsky Receiver / Futaba Receiver / ELRS Receiver

- Motor Pin Connecter: 1.25mm Header Pins

- Mounting Hole Size: 26mm x 26mm (suitable for whoop pattern mounting hole)

- USB Port: Type-C (V1.0 board), SH1.0 4-Pin (V2.0 board)

### Specification of 1S 12A ESC

- Built-in ESC with 12A continuous and peak 25A current

- Input voltage: 1S Lipo (V1.0 board), 1S-2S (V2.0 board)

- ESC firmware: Z_H_30_REV16_7.HEX

- Signal support: D-shot150, D- shot300, D-shot600, Oneshot125, Multishot, PWM

This new BLHeli_S firmware (named Z_H_30_REV16_7.HEX) is supported by BLHeli Configurator, BLHeliSuite, and Bluejay Configurator for setup.

For download and flash, update to the newest BLHeliSuite-16714902a to support this ESC firmware online. For BLHeli Configurator or Bluejay Configurator, you need to load it local. The ESC firmware is available for download here.

### Diagram for F4 1S 12A AIO FC

Below is the diagram for the SPI Frsky version board. UART1, UART2, and SBUS pads are left for external receivers like Frsky XM+, TBS Nano receiver so that a long receiver range is available.

Buzz pads (BUZZ+ and BUZZ-) are invalid directly. It needs some modification to make it works.

Below is the diagram for ELRS 2.4G V1.0 board.

Below is the diagram for ELRS 2.4G V2.0 board.

The current meter is integrated on the FC board. Here is the configuration in Betaflight Configurator.

### 12A 1S ESC

Should we really need a 12A ESC for 1S drones? If it is a 65mm or 75mm Whoop drone-like Meteor65, 5A ESC is enough for all actions. But how about with 3" propellers and 1102/1202.5 motors? Still, want smooth and powerful flying actions? The 5A ESC has developed about 3 years ago and was designed for whoop drones with 0603/0802 motors. For the past year, the BETAFPV team has been cooperating with BLHeli author Steffen on the 12A 1S ESC for 3" toothpick drones. Finally, it is here!

It marks "1-2S" on the board, could this FC board support 2S?

The V1.0 board is NOT support 2S battery. Please choose the V2.0 board for both 1S and 2S battery supported.

### ELRS 2.4G RX

This board integrates the receiver with the most popular radio link ExpressLRS in 2021. ExpressLRS aims to achieve the best possible link performance in both speeds, latency, and range. Know more about the ExpressLRS project on Github or join the discussion in the Facebook Group.

This board is designed for long-range 3inch ultralight toothpick drones or 2S whoop drones. If you want to try ExpressLRS on 65mm/75mm whoop drones, please stay tuned on our F4 1S FC board with a built-in SPI ExpressLRS receiver.

How to Bind with Betaflight FC with ExpressLRS Receiver.

How to update the ELRS RX on the AIO board. (For ELRS 2.4G V1.0 version, ELRS receiver communicates with FC F411 via CRSF protocol. )

CLI command for the FC board.

### Betaflight Firmware and CLI (SPI ELRS 2.4G)

This paragraph is only for ELRS 2.4G V2.0 board, with SPI ELRS 2.4G receiver integrated.

Since Betaflight has not yet released the official firmware that could supports the SPI ExpressLRS protocol, the current version is the Beta version. Please use the firmware and the CLI dump file below to recovery the FC board if needed. Betaflight will update to their official target soon. Please feel free to contact with us if you have any issues with this Beta version Firmware.

It is normal that there is no any option on Betaflight Configurator Receiver. As show below, the checkbox is blank.

Please change the “PID loop frequency” to “4KHZ” , sometimes it would make the SPI receiver not working correct while the value is “8KHZ”.

New released firmware BTFL_4.3.0_BETAFPVF4SX1280_0265565fa uses external GPIO interrupt triggers to process ELRS data reception, increasing the stability of the signal link. Now it can perfectly support LiteRadio 2 SE 500Hz link and modify the accuracy of signal strength.

The new CLI file is named BTFL_cli_F4 12A ELRS_V2.0_NEW. Please check.

Note: The new firmware supports only ELRS 1.0.0, 1.0.1, 1.1.0, 1.2.0, 1.2.1.

Download the firmware and CLI dump file for the F4 1S 12A FC (ELRS 2.4G) board.

How to Bind with Betaflight FC with SPI ExpressLRS Receiver.

More details and discussion on Github about SPI ELRS receiver.

### SPI Frsky RX

Come with the build-in SPI Frsky Receiver (CC2500 chip), F4 1S 12A AIO FC can be compatible with Futaba S-FHSS, Frsky D8, and D16 protocol. The default protocol is configured to Frsky D16 FCC out of the factory. Pilots could set up the protocol according to your own need in Betaflight Configurator.

How to Bind with Betaflight FC with SPI Frsky Receiver.

### Recommend Parts

If you want to try the popular ExpressLRS receiver version for long-range performance, highly recommend you to check the items for the ExpressLRS series.

- Recommend for drones like HX115 SE Toothpick Drone / HX115 LR Toothpick Drone

- Battery: BT2.0 450mAh 1S 30C Battery

- Motor: 1102 18000KV motor

- Propeller: HQ3020 2-blade props

### Package

- 1 * F4 1S 12A AIO FC

- 4 * Anti-vibration rubber dampers

- 4 * M2 x 10mm screws

- 4 * M2 x 10mm screws

- 8 * M2 screw nut

- 1 * BETAFPV dipole T antenna (2.4G/46mm, only for ELRS RX version board)

- 8 * PH-1.25 connector for motor (not soldered, only for ELRS RX version board)

## 技术参数

| Configuration | Protocol |
|---|---|
| FRSKY_D | Frsky D8 |
| FRSKY _X | Frsky D16 FCC (ACCST 1.X version) |
| FRSKY_X_LBT | Frsky D16 LBT (ACCST 1.X version) |
| SFHSS | Futaba S-FHSS |

## 官方资料

https://betafpv.com/products/f4-1s-12a-flight-controller-v2-0
