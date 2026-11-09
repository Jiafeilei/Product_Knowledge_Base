---
product_id: jSqmNDFRYQWuxb7yKi
brand: BETAFPV
model: F4 1-2S AIO Brushless Flight Controller
variant: All Variants
source_url: https://betafpv.com/products/f4-2s-aio-brushless-flight-controller-frsky-rx-osd-esc
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications:
  Receiver LED ( Green): Flashing
  Power LED ( Blue ): Solid
  Status LED ( Red ): Solid
skus:
- sku_code: jSqmNDFRYQWuxb7yKi-01
  attributes:
    RX Version: SPI Frsky
- sku_code: jSqmNDFRYQWuxb7yKi-02
  attributes:
    RX Version: SPI Futaba
- sku_code: jSqmNDFRYQWuxb7yKi-03
  attributes:
    RX Version: No Rx
sources:
- type: official
  url: https://betafpv.com/products/f4-2s-aio-brushless-flight-controller-frsky-rx-osd-esc
images: []
tags:
- Discontinued
---

# BETAFPV F4 1-2S AIO Brushless Flight Controller

## 产品介绍

We are sorry to announce that F4 1-2S AIO Brushless FC is discontinued and will not be available for sales anymore. We recommend you buy its great alternative F4 1S AIO FC.

This AIO F4 FC is suitable for a lighter 1-2S whoop drone perfectly, like Beta65 Pro 2 or Beta75 Pro 2, etc. It is integrated with a Betaflight F411 processor FC, Betaflight OSD, SPI Frsky receiver, and 1-2S 5A ESC. So the 1-2S drone could save much weight for a faster fly experience.

This FC is available for 1S whoop drones also. You need to solder JST-PH 2.0 Cable in a wires solder pad to replace the initial power cable. At the same time, you need to use higher than 12000KV motors, such as 0802 17500KV / 19500KV Motors to provide more power.

### SPECIFICATIONS OF FC

- CPU: STM32F411CEU6 (100MHZ )

- Six-Axis: MPU-6000 triaxial accelerometer / triaxial gyroscope (SPI connection)

- Size: 26mm x 26mm, fully compatible with the all whoop drone mounting pattern, recommend the Beta65X frame and Beta75 Pro frame.

- Firmware version: betaflight_matekf411rx_4.0.0 (Development Version)

- OSD: Built-in BetaFlight OSD (STM32 controls OSD chip over SPI in DMA mode)

- Built-in SPI Frsky D16 protocol native receiver, compatible with almost ALL Frsky FCC radios(e.g. Taranis X9D/X9D Plus/X7) or Frsky compatible transmitter module. Not compatible with Frsky LBT protocol.

- Power Cable: 55mm, with 2pcs JST-PH 2.0 connector, AKA PowerWhoop connector

- Weight: 4.5g

### DIAGRAM FOR F4 2S AIO FC (FRSKY/FUTABA RX)

Updated: For easier self-assembly, we added another set of 5V&GND solder pads on Frsky/Futaba FC.

### SPECIFICATIONS OF ESC

- Built-in ESC with 5A continuous and peak 6A current

- Power supply: 1-2S

- Support BLHeliSuite programmable

- Factory firmware: S_H_50_REV16_7.HEX

- Signal Support: D-shot150, D-shot300, D-shot600, Oneshot125, Multishot, PWM

### Status LED

There are 3 LEDs on the bottom of the board to indicate the status, including Receiver LED ( Green), FC Status LED ( Red ), and FC Power LED ( Blue ).

###

### SPI Frsky Receiver

Currently, the built-in Frsky receiver is compatible with Taranis, Taranis Plus, X9E, Horus X12S, XJT Modules. Pay attention, this is an SPI connection receiver. In Betaflight Configuration, it should be set as FRSKY_D receiver (aka Frsky D8 mode) or FRSKY_X receiver (aka Frsky D16 mode) in SPI RX mode.

The Frsky D16 unstable connection issue is totally resolved since Betaflight 3.4.1. Nowadays, the default configuration from the factory is Frsky D16 mode (FRSKY_X).

Note: If you are using an EU-LBT firmware radio controller, you might find that you can't bind successfully to this SPI Frsky receiver. Here are the solutions we provide for you. Thanks to Sebastian Abramowski for giving us the important feedback about binding to the EU-LBT firmware radio controller.

### Binding Procedure

The binding procedure is reversed as usual. No need to click the bind button when powering on.

- Power on the board, either by connecting the battery or USB power. Then the green receiver LED starts to flash.

- In the second step, click the bind button for 3s. Then the green receiver LED will be solid on. This means that the receiver is in bind mode and you could start to bind your radio transmitter.

For a detailed procedure of binding, please check the SPI Frsky Receiver Binding Manual.

Note: This FC board could support the SPI Futaba protocol with this firmware.

Some pilots would complain that it is definitely not a long range FC. It loses signal with my transmitter far too often and for what appears to be no reason. This issue is often caused by the location of the antenna. You should keep the antenna away from the FC board to get a stronger signal. For example, run the signal upwards. Thanks for Harley Finberg's advice.

### CLI DUMP of F4 2S Brushless FC

You can get the Cli dump of F4 AIO 2S Brushless FC here on the BETAFPV Support Freshdesk.

### DIAGRAM FOR F4 2S AIO FC (NO RX)

### HOW TO CONNECT THE EXTERNAL RX TO THE FC

For detailed information on other external receivers, please find out on our support page.

### FAQ

1. Can this FC be used on the Beta75X with 1103 motors?

Yes, we have tested this FC board with 1103 motors on Beta75X. It performed very well and almost no wash-out issue then. So if you already have a Beta75X, you could just take this AIO FC to replace the stock FC&ESC stack.

Note: because of the built-in ESC and Frsky receiver, you will lose some remote range and a little bit of power on Beta75X with this AIO FC.

2. About the alarm buzzer and LED port?

No alarm buzzer is supported on this FC board. Programmable LED is supported.

### RECOMMENDED PARTS LIST

- Frame:  Beta65X frame / Beta75 Pro 2 frame

- Props: 31mm 4-Blades props (for Beta65 X frame) / 40mm 4-blades props (for Beta75 Pro 2 frame)

- Motors: 0802 motors

- Battery: 2pcs 300mAh 1S batteries

### PACKAGE

- 1 * F4 2S brushless flight controller

- 4 * M1.2x4mm screws

- 4 * M1.4x5mm screws

- 4 * Anti-vibration rubber dampers

## 技术参数

| LED | Status | Description |
|---|---|---|
| Receiver LED ( Green) | Solid | Connected or in bind mode |
| Receiver LED ( Green) | Flashing | Not connected |
| Power LED ( Blue ) | Solid | Power on |
| Status LED ( Red ) | Solid | Motor Armed |

## 官方资料

https://betafpv.com/products/f4-2s-aio-brushless-flight-controller-frsky-rx-osd-esc
