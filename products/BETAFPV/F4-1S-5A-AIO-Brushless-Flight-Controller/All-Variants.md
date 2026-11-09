---
product_id: nBhpntDAa6dv6TNfLJ
brand: BETAFPV
model: F4 1S 5A AIO Brushless Flight Controller
variant: All Variants
source_url: https://betafpv.com/products/f4-1s-5a-aio-brushless-flight-controller-elrs-2-4g
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications:
  Weight: 2.96g
  Board Thickness: 0.8mm
  Motor Connectors: Not Solder
skus:
- sku_code: nBhpntDAa6dv6TNfLJ-01
  attributes:
    Version: Classical Version
    RX: Serial ELRS 2.4G
- sku_code: nBhpntDAa6dv6TNfLJ-02
  attributes:
    Version: Classical Version
    RX: SPI Frsky
- sku_code: nBhpntDAa6dv6TNfLJ-03
  attributes:
    Version: Light Version
    RX: Serial ELRS 2.4G
- sku_code: nBhpntDAa6dv6TNfLJ-04
  attributes:
    Version: Light Version
    RX: SPI Frsky
sources:
- type: official
  url: https://betafpv.com/products/f4-1s-5a-aio-brushless-flight-controller-elrs-2-4g
images: []
tags:
- 1s brushless fc
- brushless fc
- Discontinued
- fc
---

# BETAFPV F4 1S 5A AIO Brushless Flight Controller

## 产品介绍

The F4 1S 5A AIO Brushless Flight Controller is back in stock with new and upgraded features. The new board integrates Serial ExpressLRS 2.4G receiver. Compared with the original built-in SPI ELRS 2.4G receiver, it could flash the newest ELRS official firmware like V3.0 easily. Also, we updated the FC with high-quality BMI270 gyro, BB51 ESC hardware with Bluejay ESC firmware, and 8MB Betaflight Blackbox flash.

Please click here to F4 1S 5A AIO (SPI ELRS 2.4G) if you need information about it.

Tons of ExpressLRS items are available now!

Two version choices for the FC board. Weighing only 2.96 grams, the Light version comes with NO motor connectors soldered. Therefore, pilots could directly solder the motor cables to the FC board, getting an ultimate lightweight drone for fast speed FPV racing.

### Bullet Point

- Come with a Serial ExpressLRS 2.4G receiver, which can be updated via Wi-Fi or Betaflight serial passthrough. It is convenient for pilots to flash any version of ELRS RX firmware and especially can flash ExpressLRS V3.0 without updating flight controller firmware.

- The SPI Frsky version board reserves an SBUS port and a UART port, which is available for the SBUS protocol receiver or other external receivers.

- Built-in an 8MB flash memory chip dedicated to Blackbox logging. It’s an extremely powerful tool for tuning and troubleshooting an FPV drone.

- Particular design with a weight of 3.64g (Classical) and 2.96g (Light), reasonable layout, and easy to build. With a 26*26mm mounting hole size, it is fully compatible with the whoop frame in the current market.

- The Light version requires soldering motor wires to the pad directly, which allows lower resistance for more current on motors. It also comes with motor pin connectors for convenience to use.

### Specification of FC

- CPU: STM32F411CEU6 (100MHZ)

- Six-Axis: BMI270

- Built-in Receiver: Serial ExpressLRS 2.4G/SPI CC2500 (Frsky)

- Receiver antenna: Line antenna

- FC Size: 30*30mm

- Mounting Hole Size: 26*26mm

- Firmware version: betaflight_4.3.0_BETAFPVF411 (ELRS)/betaflight_4.2.11_BETAFPVF411RX (Frsky)

- OSD: Built-in BetaFlight OSD

- Blackbox: 8MB

- Recommend VTX: >=200mW, like BETAFPV M03 350mW VTX or TBS Unify VTX

- Power Cable: 55mm, with BT2.0 connector

- Weight: 2.96g (without motor connectors) / 3.64g (with motor connectors), excluding power cable

### Specification of ESC

- Power supply: 1S

- Current: 5A continuous and peak 6A (3 seconds)

- ESC firmware: A_X_5_.HEX for Bluejay BB51 hardware

- Signal Support: D-shot300, D-shot600

### Diagram

Below is the diagram for Serial ELRS 2.4G RX. The diagram for the Classical and Light versions is the same.

Below is the diagram for SPI Frsky RX. The diagram for the Classical and Light versions is the same.

### Serial ELRS 2.4G RX

Serial ELRS 2.4G RX uses the Crossfire serial protocol (CRSF protocol) to communicate between the receiver and the flight controller board. So the Serial ELRS 2.4G RX is available to support upgrading to ELRS V3.0 with no need to flash Betaflight flight controller firmware. Enter binding status by power on/off three times.

- Plugin and unplug the flight controller three times;

- Make sure the RX LED is doing a quick double blink, which indicates the receiver is in bind mode;

- Make sure the RF TX module or radio transmitter enters binding status, which sends out a binding pulse;

- If the receiver has a solid light, it's bound.

The Serial ELRS 2.4G RX can be updated via Wi-Fi or Betaflight serial passthrough. Here is the way to update the Serial ELRS 2.4G RX firmware through passthrough.

- Plug in your FC to your computer, but do NOT connect to betaflight configurator.

- Choose target "BETAFPV 2.4GHz AIO RX".

- Flash using the BetaflightPassthrough option in ExpressLRS Configurator.

How to flash firmware via Wi-Fi here.

### SPI Frsky RX

Come with the built-in SPI Frsky Receiver (CC2500 chip), F4 1S 5A AIO FC can be compatible with Futaba S-FHSS, Frsky D8, and D16 protocol. The default protocol is configured to Frsky D16 FCC out of the factory. Pilots could set up the protocol according to your own need in Betaflight Configurator.

How to Bind with Betaflight FC with SPI Frsky Receiver.

### Betaflight Firmware and CLI

F4 1S 5A AIO Brushless Flight Controller comes with the default firmware betaflight_4.3.0_BETAFPVF411 (ELRS) or betaflight_4.2.11_BETAFPVF411RX (Frsky). The default firmware for Serial ExpressLRS 2.4G RX version supports ELRS V2.4 RX.

Pay attention, For the Serial ExpressLRS 2.4G version, ONLY the Betaflight firmware 4.3.0 and up start to support this BMI270 gyro. For the SPI Frsky version, DO NOT flash the other firmware, otherwise, the RX will be lost in control at a very close range. We have already built our own firmware betaflight_4.2.11_BETAFPVF411RX for SPI Frsky RX version to support BMI270 gyro. Please check the below link to download the firmware.

-
Download the firmware and CLI dump file for the F4 1S 5A FC ELRS/Frsky board. (Both Light and Classical versions share the same firmware)

Note: The RX RSSI values drop when the flight controller is installed on the quadcopter with HD digital VTX (Walksnail or HDZero). For example, the theoretical failsafe RSSI values for 250Hz packet rate are -108dBm. Actually, the RX will be possibly lost in control when the RX RSSI values reach about -92dBm.

### Bluejay ESC Firmware

F4 1S 5A flight controller with BB51 ESC hardware could flash the Bluejay ESC firmware now, which is based on BLHeli_S revision 16.7. With Bluejay ESC firmware, it supports bidirectional D-shot and RPM filtering in Betaflight, offers 24KHz, 48KHz, and 96KHz fixed PWM frequency for options, and custom start-up melodies. By using Bluejay ESC firmware on Meteor65 and Meteor65 Pro whoop drones with 0802SE 19500KV motors, the flight time is increasing effectively. The default firmware for F4 1S 5A FC will be changed to Bluejay ESC firmware.

For pilots who want to flash Bluejay ESC firmware for F4 1S 5A FC, please use the BLHeliSuite16714902A_Beta or ESC-Configurator and download Bluejay ESC firmware A_X_5_.HEX from the below links. (Both Light and Classical versions share the same firmware)

- ESC-Configurator: https://preview.esc-configurator.com/

- Download BLHeliSuite16714902A_Beta here.

- Download the Bluejay ESC firmware. Please choose A_X_5.HEX.

Note: Only SPI ELRS 2.4G version supports motor direction set through Betaflight Configurator and SPI Frsky version does not support it. BLHeli Configurator and Bluejay Configurator are invalid for the BB51 ESC (both versions).

### Connecting External RX/HD Digital or Analog VTX

Both Serial ExpressLRS 2.4G RX and SPI Frsky RX version support external HD digital VTX or Analog VTX. Please note that the SPI Frsky RX version reserves an SBUS port and a UART port, which is available for the SBUS protocol receiver or other external receivers. You can refer to the below picture. The diagram is the same for Classical and Light version.

### Recommend Parts

- Battery: BT2.0 300mAh 1S Battery

- Frame:  Meteor65 frame / Meteor65 Pro frame / Meteor75 frame

- Props: 31mm 4-Blades props (for 65mm frame) / 35mm 3-blade props (for 65mm frame) / 40mm 4-blades props (for 75mm frame)

- Motors: 0802SE motors / 1102 brushless motors

- VTX: M03 25-350mW VTX

### Package

- 1 * F4 1S 5A AIO Brushless Flight Controller (ELRS or Frsky)

- 4 * M1.2x4mm Screws

- 4 * M1.4x5mm Screws

- 4 * Anti-vibration Rubber Dampers

- 8 * Motor Pin Connectors (Light version included)

## 技术参数

| Light Version | Classical Version |  |
|---|---|---|
| Weight | 2.96g | 3.64g |
| Board Thickness | 0.8mm | 0.8mm |
| Motor Connectors | Not Solder | Soldered |

## 官方资料

https://betafpv.com/products/f4-1s-5a-aio-brushless-flight-controller-elrs-2-4g
