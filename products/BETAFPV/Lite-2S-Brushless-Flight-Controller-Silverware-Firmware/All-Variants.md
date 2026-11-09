---
product_id: MbXhKWwfgn38xzIAaR
brand: BETAFPV
model: Lite 2S Brushless Flight Controller (Silverware Firmware)
variant: All Variants
source_url: https://betafpv.com/products/lite-2s-brushless-flight-controller-frsky
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications: {}
skus:
- sku_code: MbXhKWwfgn38xzIAaR-01
  attributes:
    Receiver: Frsky D8
- sku_code: MbXhKWwfgn38xzIAaR-02
  attributes:
    Receiver: Bayang
sources:
- type: official
  url: https://betafpv.com/products/lite-2s-brushless-flight-controller-frsky
images: []
tags:
- Discontinued
---

# BETAFPV Lite 2S Brushless Flight Controller (Silverware Firmware)

## 产品介绍

After continuous optimization and research, the high-anticipated Silverware 2S FC has been released now! We provide 2 built in receiver for choice, Frsky D8 (SBUS protocol) and SPI Bayang.

For fans of Silverware firmware, now you could try it with brushless drone like Beta85 Pro 2. The stock firmware is based on brushed NFE_Silverware, which is used on popular ZER0 board.

After 2 months of beta test and upgrade, now it is available for all the pilots. Thanks to all the pilot s who took part in our beta test and gave us feedback and advice.

Full user manual download

Source code on the Github

Beta Test Page

### UPGRADED POINTS

There are tons of upgrade in the final release Lite 2S FC board, both in software and hardware.

Software:

- Add Butterworth Filter on the accelerometer data, solve the issue of drift in level mode.

- Add Smart Audio function for the VTX.

- Solve the issue of vibration and overheat on 110x motors.

- Solve the issue of statics and flash on the OSD information.

Hardware:

- Since to use orange color on the FC with Silverware firmware.

- Built-in physical current sensor.

- Smart Audio port for the VTX included.

- Added the JST SH 1.0 4-pins programming port for the flight controller.

- Built-in Frsky D8 native receiver for option.

### BULLET POINTS

- The first 2S Brushless FC board with Silverware firmware in the current market, can totally support 2S brushless motor. This must be the most simple and affordable method to try whoop FPV racing hobby.

- Supports Acromode, Levelmode, Racemode_Angle, Racemode_Horizon, Horizonmode and Turtle mode. Also it has the ability to change settings for custom builds or to adapt the personal preferences by OSD menu.

- Build-in OSD, allows you to select viewing options, such as voltage of battery, flight time, flight mode and setting menu. Includes OSD menu, supports PID tuning, motor rotation changing and channel mapping of AETR/TAER switching via OSD menu.

-
Convenient operation for switching receiver communication protocol: SBUS / DSMX, since you can switch it directly by button.

- The flight controller board comes pre-flashed with Silverware firmware, and pre-soldered 55mm power cable pigtail withXT30 cable.

### SPECIFICATIONS OF FC

- CPU: STM32F042G6U6 (Frsky version) / STM32F031F6P6 (Bayang version)

- Six-Axis: MPU6050

- Size: 26mm x 26mm, whoop mounting pattern

- Firmware version: BETAFPV LiteSilverware firmware

- OSD: BETAFPV LiteOSD

- Build-in receiver: Frsky D8 RX (SBUS protocol) / SPI Bayang

- Supported external receiver:  SBUS / DSMX protocol

- Power Cable: 55mm, with XT30 cable

- Weight: 5.39g with XT30 cable

### SPECIFICATIONS OF ESC

- Built-in BB21 ESC with 5A continuous and peak 6A current

- Input voltage: 2S lipo

- Support BLHeliSuite programmable

- Motor Connectors: 1.25mm header pins connector

- Factory firmware: S_H_50_REV16_7.HEX

- Signal Support:D-shot150, D-shot300, D-shot600(Default), Oneshot125

### DIAGRAM FOR LITE 2S BRUSHLESS FC (Frsky)

### DIAGRAM FOR LITE 2S BRUSHLESS FC (Bayang)

###

###

### BUTTERWORTH FILTER

Original Silverware firmware has the bug that accelerometer based drift entering the fusion which manifests as a slower and slower yaw response. This is noticeable in level mode for almost all the Silverware based FC boards.

Now we have fixed it. Filter the accelerometer data first with low pass Butterworth filter and let it participating in flight.

Below is the gravity vector value GEstG[x] drift graph when no correct accelerometer data participates.

### OSD MENU

Lite 2S Brushless FC is with build-in OSD which is convenient for changing settings. It supports PID tuning, motor spinning direction changing and channel mapping of AETR in default. The power and frequency of VTX can be switched directly. The operation of OSD Menu on Lite 2S Brushless FC is the same as Betaflight.

For more detailed info, kindly check Full user manual to download

### FIRMWARE DOWNLOAD

###

Easily program the Lite 2S Flight Controller with a ST-LINK programmer. Simple plug-n-play operation allows you to update the firmware on your flight controller. The programming port is also compatible with the NewBeeDrone BeeLink USB Flasher.

### RECEIVER / VTX CONNECTION & STATUS LED

Here is the connection diagram with external receiver (SBUS protocol):

Here is the connection diagram with A01 VTX:

For other connection diagram with DSMX receiver or M01 VTX, please check the User Manual.

### Built-in Current Meter

With build-in current meter,  there is no need to use the virtual current meter and you could get a more accurate current value.

Then when flying, you could find the real current value from the OSD information. Of course, the current sensor is configured well in the factory and you do not need to change it as usual.

The built-in current meter is ONLY available on the Frsky version now.

### Package

- 1 * Lite 2S brushless flight controller

- 4 * M1.2x4mm screws (Fit for stock Inductrix frame)

- 4 * M1.4x5mm screws (Fit for Eachine black E010 frame / 75mm / 85mm frames.)

- 4 * Anti-vibration ruber dampers

## 技术参数

（来源页未提供规格表）

## 官方资料

https://betafpv.com/products/lite-2s-brushless-flight-controller-frsky
