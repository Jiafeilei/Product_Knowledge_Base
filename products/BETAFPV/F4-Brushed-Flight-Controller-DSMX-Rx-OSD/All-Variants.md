---
product_id: CeAfPx8OsLSDEhEJDE
brand: BETAFPV
model: F4 Brushed Flight Controller (DSMX Rx + OSD)
variant: All Variants
source_url: https://betafpv.com/products/f4-brushed-flight-controller-dsmx-rx-osd
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushed FC
collected_by: workbuddy
confidence: 0.6
specifications:
  Receiver LED ( Orange): 'OFF'
  Status LED ( Red ): Flashing
  Status LED ( Blue ): Solid
skus:
- sku_code: CeAfPx8OsLSDEhEJDE-01
  attributes:
    Version: Default
sources:
- type: official
  url: https://betafpv.com/products/f4-brushed-flight-controller-dsmx-rx-osd
images: []
tags:
- Discontinued
---

# BETAFPV F4 Brushed Flight Controller (DSMX Rx + OSD)

## 产品介绍

BETAFPV's F4 DSMX Brushed FC board takes a big step further compared with F3 DSMX Brushed FC.

With STM32F411CEU6 CPU and 30A maximum of all FETs, the F4 DSMX Brushed FC gives the drone noticable perfomance and power improvement.

### Key Features

- High performance CPU: STM32F411CEU6 CPU

- Battery polarity reversed connection protection. The fc board remains perfect even if you plug the battery in wrong way.

- Fully programmable through Betaflight, using the onboard USB port, tune all the parameters, PID's, and rates to your perfect settings

- Designed to work with current Whoop Drone or Blade Inductrix setups

- Built in DSMX protocol native receiver (SBUS), compatible with almost ALL Spektrum radios(e.g. Spektrum DX6/DX6i/DX8...) or DSMX compatible transmitter module

- The flight controller board comes pre-flashed with Betaflight firmware, and pre-soldered 55mm power cable pigtail with JST-PH 2.0 connector, AKA PowerWhoop connector.

### Specifications

- CPU: STM32F411CEU6

- Six-Axis: MPU6000

- ESC: All FETs are rated at 30A maximum. Support 6x15mm/7x20mm/8x20mm/8.5x20mm etc motors.

- Size: 26mm x 26mm, fully compatible with the Inductrix quad frame and mounting pattern

- Firmware version: Betaflight MATEKF411 3.5.0

- OSD: Built-in BetaFlight OSD (STM32 controls OSD chip over SPI in DMA mode)

- Receiver: DSM2/DSMX

- Power Cable: 55mm, with JST-PH 2.0 connector, AKA PowerWhoop connector

- Weight: 3.8g

HOW TO CONNECT THE FC TO Z02

### BetaFlight OSD

Betaflight OSD (on screen display) is integrated in BETAFPV F4 brushed flight controllers that shows important flight data on your FPV feed, such as battery voltage, current draw and much more. You can even use it as a menu to change your quad’s PID, rates, filters and other settings.

How to do an OSD with the AIO cameras?

There is a video in and out on the fc itself, labeled CAM and VTX as show below. There should be a video in and out on the AIO camera, like BETAFPV H02 etc. If not, you would have to modify the camera for sure but it would totally be worth it. Here is an example.

BETAFPV H02 Camera, FX806TC, VM275, FX805, Eachine XT02 etc aio camera vtx are available to use the OSD function.

BETAFPV Support Freshdesk for BetaFlight OSD Setup.

Tips: There is no current sensor on the FC boards. So the amperage value on the OSD is invalid.

Binding Procedure

Step 1

Connet the receiver to FC and run the Betaflight. On Betaflight GUI, configure the UART1 port to serial port in Ports tab. Then click the Save and Reboot button in the lower right corner.

Step 2

In the Configuration tab, for Receiver Mode, choose Serial_based receiver (SPEKSAT, SBUS, SUMD); Serial Receiver Provider, choose SPEKTRUM2048. And click the Save and Reboot button in the lower right corner.

Step3
Type: set spektrum_sat_bind=9 in CLI and save.

Step 4
Repower the receiver. The orange light on the receiver will flash rapidly, which means it's on binding mode.

Step 5
Turn on the radio and select bind mode. Wait a moment. It means bind successfully if the orange light on receiver is solid on.

Status LED

This board has 3 LEDs to indicate the status, including Receiver LED ( Orange ), FC Status LED ( Red ) and FC Status LED ( Blue ). These three LEDs are all at the bottom of the FC board.

### DSMX Receiver

Some pilots would complaint that it is definitely not a long range FC. It looses signal with my transmitter far too often and for what appears to be no reason. This issue is often caused by the location of the antenna. You should keep the antenna away from the FC board to get a stronger signal. For example, run the singal upwards. Thanks for Harley Finberg's advice.

This integrated DSMX receiver is NOT compatible with Spektrum DXe radio transmitter and OrangeRX RF module. For some Spektrum radio transmitter like DX6i/DX6e etc, the DSMX receiver may have a horrible range with your radio transmitter, please change the mode to DSM2 (DSMX in default). This issue is figured out by Micro Motor Warehouse.

### FAQ

Find Cli Dump of F4 Brushed FC (DSMX Rx) on our support page.

### Package

- 1 * F4 OSD brushed flight controller DSMX Rx version ( 55mm PH-JST 2.0 power cable soldered)

- 4 * M1.2x4mm screws (Fit for stock Inductrix frame)

- 4 * M1.4x5mm screws (Fit for Beta75 etc 75mm frame)

- 4 * Anti-vibration ruber dampers

- 1 * 55mm PH-JST 1.25 power cable pigtail

###

## 技术参数

| LED | Status | Description |
|---|---|---|
| Receiver LED ( Orange) | Solid | Bind Successfully |
| Receiver LED ( Orange) | Flashing | On Bind Mode |
| Receiver LED ( Orange) | OFF | Not connected |
| Status LED ( Red ) | Solid | Motor Armed |
| Status LED ( Red ) | Flashing | Arming Disable Flags |
| Status LED ( Blue ) | Solid | Motor Armed |

## 官方资料

https://betafpv.com/products/f4-brushed-flight-controller-dsmx-rx-osd
