---
product_id: b5f3nfRydZGDOoBnte
brand: BETAFPV
model: F411 4S 20A Toothpick Brushless Flight Controller V5 BLHeli_S (BMI270)
variant: All Variants
source_url: https://betafpv.com/products/f411-4s-20a-toothpick-brushless-flight-controller-v5-blheli_s-bmi270
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications:
  Power LED (Red): Solid
  FC LED (Blue): Solid
  Receiver LED (Orange): Solid
skus:
- sku_code: b5f3nfRydZGDOoBnte-01
  attributes:
    SIX AXIS VERSION: BMI270
sources:
- type: official
  url: https://betafpv.com/products/f411-4s-20a-toothpick-brushless-flight-controller-v5-blheli_s-bmi270
images: []
tags:
- Discontinued
---

# BETAFPV F411 4S 20A Toothpick Brushless Flight Controller V5 BLHeli_S (BMI270)

## 产品介绍

As a continuance of the F411 chip, the V5 FC board is upgraded from the F4 20A V3 FC board. F411 4S 20A Toothpick Brushless Flight Controller V5 adopts BMI270 gyro instead of MPU6000 on V3 board. With two integrated plug&play ports for receiver and HD digital VTX, it is easy to install and requires less solder work. Besides, the board is a solid value for durable use thanks to the high-quality PCB material and enhanced production process.

### Bullet Point

- With a large pad to solder, it is easy to solder external electronics. In addition, the V5 board features plug&play ports for the receiver and HD digital VTX, which requires less solder work for convenient installation.

- High-quality MOSFETs are applied to F411 4S 20A FC V5 to handle 20A continuous current and reach 25A peak current.

- The motor solder pads are reinforced by thick copper and edge plating technology, allowing lower resistance for more current on motors.

- F411 4S 20A FC V5 reserves the UART ports layout, UART1 for RX, UART2 for DJI OSD or Analog VTX, and UART6 for spare usage, more convenient for pilots to solder.

- Come with a 25.5*25.5mm whoop mounting pattern, this board can be added to both the toothpick drone and the cinematic whoop quadcopter frame like Pavo25 and X-knight 35.

### Specification

Flight Controller

- CPU: STM32F411CEU6 (100MHZ)

- Six-Axis: BMI270 (SPI connection)

- Mounting Size: 25.5*25.5mm (M2 Anti-vibration rubber damper available)

- FC Firmware: betaflight_4.3.x_BETAFPVF411

- OSD: Built-in Betaflight OSD (OSD chip: AT7456E)

- Receiver: SBUS/CRSF/DSMX Receiver

- BEC: 5V 3A

- Built-in current sensor

- Weight: 8.15g

ESC

- ESC Chip: SILABS EFM8BB21F16G-C

- Support D-shot150, D-shot300, D-shot600, Oneshot125, Multishot, PWM

- Input voltage: 2S-4S Lipo

- Continuous current: 20A

- Peak current: 25A

- Firmware: G_H_20_REV16_7.HEX (Default BLHeli_S), BLUEJAY (Optional)

Note: F411 4S 20A FC V5 is available to flash both BLHeli_S and BLUEJAY ESC firmware and it comes with default BLHeliI_S firmware. The main difference is that the BLUEJAY firmware supports bidirectional D-shot, while BLHeli_S does not support it.

### Comparison to F411 4S 20A V3 FC

We upgraded the F411 4S 20A V3 board to V5 by adopting BMI270 gyro instead of MPU6000 and adding some new features. BMI270 gyro works great in most cases, especially in low frequency. Unlike the V3 board that supports JST1.25 connectors, the motor solder pads on V5 board are solderable only and reinforced by thick copper and edge plating technology, allowing lower resistance for more current on motors. Besides, the V5 FC board features high-quality material for the stability of the solder and durability of use. The below pictures show the difference between the two flight controllers.

### Diagram for Toothpick F411 4S 20A Brushless FC V5

The board integrates 3 LEDs, including the Power LED (Red), FC LED(Blue) and Receiver LED.

### Connecting External RX/HD Digital VTX

F411 4S 20A FC V5 integrates the Plug & Play port for the external RX and HD digital VTX, and there will be a 4-pin connector for RX and a 6-pin connector for HD digital VTX in the package. Thus, we highly recommend pilots use the port to save the solder work.

### FC & ESC Firmware

The default firmware is including CLI dump file. But if you flash firmware from the Betaflight configurator official site, please flash a CLI dump file for F411 4S 20A FC V5. We offer the default firmware and CLI dump file to download.

- Download the FC default firmware betaflight_4.3.x_BETAFPVF411 and CLI dump file.

BMI270 gyro will need more software filters and is sensitive in high frequency. This can be solved by adjusting filter settings in PID tuning. The Betaflight official or BETAFPV default FC firmware and CLI dump file do not include the filter settings. For pilots who want to configure it, we recommend setting gyro lowpass 2 at 145Hz and choosing filter type at PT2.

F411 4S 20A FC V5 is available to flash both BLHeli_S and BLUEJAY ESC firmware and it comes with default BLHeliI_S firmware. The main difference is that the BLUEJAY firmware supports bidirectional D-shot, while BLHeli_S does not support it. Here are the download links for two firmware.

When using BLHeli_S ESC firmware, please configure the settings on BLHeli - Configurator software.

- Download the BLHeli_S ESC firmware.

-
Download the BLHeliSuite16714902a.

- Download the BLHeli - Configurator.

- Download the ESC - Configurator.

We offer the BLUEJAY ESC firmware for pilots. When using BLUEJAY ESC firmware, please configure the ESC on ESC-Configurator software.

- Download the BLUEJAY ESC firmware.

- Download the ESC - Configurator.

-
Download the Bluejay Configurator.

### Recommend Parts

- Motors: 1404 Brushless Motors, 1506 Brushless Motors

- Battery: 2S 600mAh, 3S/4S 850mAh, 4S 750mAh, or 4S 1000mAh

- Frame: Pavo25 Frame, X-knight 35, or other frames with whoop mounting pattern.

### Package

- 1 * F411 4S 20A Toothpick Brushless Flight Controller V5 BLHeli_S (BMI270)

- 1 * Cable Pigtail (XT30)

- 1 * 6-Pin Connector for Digital VTX

- 1 * 4-Pin Connector for RX

- 4 * M2x12 Screws

- 8 * M2 Nuts

- 4 * M2 Anti-vibration rubber dampers

## 技术参数

| LED | Status | Description |
|---|---|---|
| Power LED (Red) | Solid | Power on |
| FC LED (Blue) | Flashing | Motor Disarmed |
| FC LED (Blue) | Solid | Motor Armed |
| Receiver LED (Orange) | Solid | Connected Successfully |

## 官方资料

https://betafpv.com/products/f411-4s-20a-toothpick-brushless-flight-controller-v5-blheli_s-bmi270
