---
product_id: 6nTJAE1afmAnlR4ujM
brand: BETAFPV
model: F4 1S 12A AIO Brushless Flight Controller V3
variant: All Variants
source_url: https://betafpv.com/products/f4-1s-12a-aio-brushless-flight-controller-v3-0
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications:
  Weight: 4.23g
  Motor Connectors: Not Solder
skus:
- sku_code: 6nTJAE1afmAnlR4ujM-01
  attributes:
    VERSION: Light Version
    MCU: AT32F435
- sku_code: 6nTJAE1afmAnlR4ujM-02
  attributes:
    VERSION: Light Version
    MCU: STM32F405
- sku_code: 6nTJAE1afmAnlR4ujM-03
  attributes:
    VERSION: Classical Version
    MCU: STM32F405
sources:
- type: official
  url: https://betafpv.com/products/f4-1s-12a-aio-brushless-flight-controller-v3-0
images: []
tags:
- 1s brushless fc
- brushless fc
- Discontinued
- fc
---

# BETAFPV F4 1S 12A AIO Brushless Flight Controller V3

## 产品介绍

F4 1S 12A AIO Brushless FC V3, the FIRST flight controller designed specifically for HD VTX. This powerful controller features an STM32F405/AT32F435 chip for high-performance calculations and a 5V 3A BEC solution for the HD VTX. It weighs only 4.2 grams and includes a Serial ELRS 2.4G receiver, 16MB Black Box, Barometer, and Current meter. Designed for HD VTX, it removes the OSD chip AT7456E and also added support for external GPS through Betaflight 4.4.0.

### Bullet Point

-
F4 1S 12A AIO Brushless FC V3 is specially designed for HD VTX, the MCU with stronger performance and computing power, and the new BEC solution with 5V 3A output supports HD VTX power supply.

- Integrate Serial ELRS 2.4G receiver, 16M black box, barometer, current meter, reserve 2 complete serial ports, and 1 standard SBUS. It is compatible with various devices such as GPS, HD VTX, and external receivers, which reduces the overall weight and complexity of the build.

- With a lighter weight of 4.2g, it improves flight performance and agility.

- There are 2 main control MCUs available: the STM32F405 and the AT32F435. The AT32F435 has a stronger performance, with a COREMARK score that is even comparable to that of the STM32F722.

### Specification of FC

- Six-Axis: ICM42688P (SPI connection)

- MCU: STM32F405RGT6 (168MHz) / AT32F435RGT7 (288MHz)

- Firmware version: Betaflight_4.4.1_BETAFPVF405 (STM32F405) / ATBetaflight_4.3.2_BETAFPVF435_RC3 (AT32F435)

- Receiver: Serial ELRS 2.4G Receiver

- Receiver firmware version: BETAFPV AIO 2400 RX ELRS V2.5.2

- Antenna: Enameled wire

- Blackbox Memory: 16MB

- Sensor: Barometer (BMP280), Voltage&Current

- Mounting Hole Size: 26mm x 26mm (suitable for whoop pattern mounting hole)

- BEC*: 5V 2A@4V supply, 5V 3A@8V supply

- USB Port: SH1.0 4-Pin

- Built-in ESC with 12A continuous and peak 25A current

- ESC input voltage: 1-2S

- ESC firmware: C_X_70_48_V0.19.2.hex for BB51 Bluejay hardware

- Signal support: D-shot300, D-shot600

- Weight: 4.23g (without motor connectors) / 4.68g (with motor connectors), excluding power cable

*The output current of BEC will decrease as the temperature increases

### Diagram for F4 1S 12A AIO FC V3

### Comparison

The F4 1S 12A V3 FC is specifically designed for HD VTX and features an upgraded STM32F405/AT32F435 chip for high-performance calculations. It also includes a Serial ELRS 2.4G receiver for increased range and reliability, as well as a 16MB Black Box for easy flight data recording and analysis. These upgrades aim to enhance the overall flying experience for pilots.

### About ATBetaflight

ATBetaflight is a fork ported to Artery Tek AT32F435/7 based on betaflight 4.3. The biggest difference from the Betaflight firmware is that the sensitivity of the BMI270 gyroscope is optimized, and the measured sensitivity error is reduced from about 2% to less than 0.04%, which is consistent with the specification table in the datasheet. Phenomena such as "horizon drift" and "wrong direction of GPS rescue" basically no longer appear in the actual flight.

The current release of ATBetaflight 4.3.2 RC3 already supports all hardware functions but does not support the new functions or optimization problems of subsequent versions of Betaflight 4.3.1. For more information, please refer to: https://github.com/flightng/atbetaflight

### Betaflight Firmware and CLI

For STM32F405 Version

FC firmware: Betaflight_4.4.1_BETAFVF405

Reference link:

https://github.com/betaflight/betaflight/releases/tag/4.4.1

For AT32F435 Version

FC firmware: ATBetaflight_4.3.2_BETAFPVF435_RC3

Reference link:

https://github.com/flightng/atbetaflight/releases/tag/v4.3.2-rc3

Pay attention, DO NOT flash the other firmware for AT32F435 version. Betaflight official firmware for the AT32F435 is still in the development process, only the currently released ATBetaflight 4.3.2 RC3 has bidirectional Dshot, PRM, and RGB functions.

If you need to use the Betaflight configurator, please use Betaflight_10.10.0 and follow the steps below to open the "Show all serial devices" in the "Options" first to recognize the port.

Download the firmware and CLI dump file.

### ESC Firmware

With BB51 ESC solution, F4 1S 12A FC V3 is based on BLHeliSuite16714903 with Bluejay ESC firmware, it supports bidirectional D-shot and RPM filtering in Betaflight, offers 24KHz, 48KHz, and 96KHz fixed PWM frequency for options, and custom start-up melodies. F4 1S 12A FC V3 default factory setting is 48KHz and it doesn’t recommend upgrading the 96KHz, or it might cause an error in the motor idle setting, not spinning when disarmed.

DO NOT flash the firmware with a shorter interval, otherwise, there will be a certain chance of stalling and burning the flight controller.

- ESC-Configurator: https://preview.esc-configurator.com/

- Download BLHeliSuite16714903

- Download the Bluejay ESC firmware. Please choose C_X_70.HEX

### Serial ELRS 2.4G RX

Serial ELRS 2.4G RX uses the Crossfire serial protocol (CRSF protocol) to communicate between the receiver and the flight controller board. So the Serial ELRS 2.4G RX is available to support upgrading to ELRS V3 with no need to flash Betaflight flight controller firmware.

- Enter binding status by power on/off three times.

- Plugin and unplug the flight controller three times;

- Make sure the RX LED is doing a quick double blink, which indicates the receiver is in bind mode;

- Make sure the RF TX module or radio transmitter enters binding status, which sends out a binding pulse;

- If the receiver has a solid light, it's bound.

The Serial ELRS 2.4G RX can be updated via Wi-Fi or Betaflight serial passthrough. Here is the way to update the Serial ELRS 2.4G RX firmware through passthrough.

- Plug in your FC to your computer, but do NOT connect to betaflight configurator.

- Choose target "BETAFPV 2.4GHz AIO RX".

- Flash using the BetaflightPassthrough option in ExpressLRS Configurator.

How to flash firmware via Wi-Fi here.

### Connecting External RX/HD Digital

Both STM32F405 and AT32F435 version support external HD digital VTX. Please note that the board reserves two serial ports and a standard SBUS port, which is available for the external CRSF protocol receiver or GPS module, and SBUS protocol receiver. You can refer to the below picture.

### Recommend Parts

If you want to try the popular ExpressLRS receiver version for long-range performance, highly recommend you check the items for the ExpressLRS series.

- Drones:  Meteor75 HD, Meteor75 Pro HD, Pavo Pico Brushless Whoop Quadcopter, 85mm whoop frame like Meteor85 HD, 3" toothpick drones

- Battery: BT2.0 450mAh 1S 30C Battery, 450mAh 2S 45C Battery

- Motor: 1102 18000KV motor, 1103 11000KV motor

- Propeller: HQ3020 2-blade Props, 2020 4-blade Props

### Package

- 1 * F4 1S 12A AIO FC V3

- 4 * M2*10 machine screw

- 4 * M2*10 nylon screw

- 4 * M2 nuts

- 4 * shock absorbing ball

- 4 * JST1.25mm angle socket

- 4 * JST1.25mm straight socket

- 1 * SH1.0 4Pin adapter cable

- 1 * Type-C to SH1.0 adapter

- 1 * XT30 power cord

- 1 * filter capacitor

## 技术参数

| Light Version | Classical Version |  |
|---|---|---|
| Weight | 4.23g | 4.68g |
| Motor Connectors | Not Solder | Soldered |

## 官方资料

https://betafpv.com/products/f4-1s-12a-aio-brushless-flight-controller-v3-0
