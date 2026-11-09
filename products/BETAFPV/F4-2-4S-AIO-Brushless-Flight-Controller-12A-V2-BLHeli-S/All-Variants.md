---
product_id: CH10baC04wbSDwoiuy
brand: BETAFPV
model: F4 2-4S AIO Brushless Flight Controller 12A V2 (BLHeli_S)
variant: All Variants
source_url: https://betafpv.com/products/f4-2-4s-aio-brushless-flight-controller-12a-blheli_s
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless FC
collected_by: workbuddy
confidence: 0.6
specifications:
  2S: 1103 11000KV / 0802 12000KV / 08028 12000KV
  3S: 1103 8000KV / 1105 6000KV
  4S: 1105 5000KV / 1204 5000KV / 1404 3800KV
skus:
- sku_code: CH10baC04wbSDwoiuy-01
  attributes:
    Version: Default
sources:
- type: official
  url: https://betafpv.com/products/f4-2-4s-aio-brushless-flight-controller-12a-blheli_s
images: []
tags:
- Discontinued
---

# BETAFPV F4 2-4S AIO Brushless Flight Controller 12A V2 (BLHeli_S)

## 产品介绍

F4 AIO FC 12A V2 is upgraded in these 2 spark points.

- Add 8M Flash chip for Betaflight Black Box. More details please check it here.

- 3 full UARTs (UART1, UART2 and UART6) are available. Pilots could use one UART for DJI digital FPV unit or Caddx Vista digital FPV unit and the other UART for external receiver like TBS Crossfire.

Also this board is light only 5.07g and suitable for brushless whoop like 2S Pro 2 Series/ X Series. Integrated with a Betaflight MATEKF411 processor FC, Betaflight OSD and 2-4S 12A ESC which can support 4S battery for fast flying experience.

###

### Recommended Battery and Motor combo

### Comparison of Toothpick 12A AIO FC and F4 12A AIO FC

### Testing Video by Totofpv

Are you curious about how it performs with a toothpick build? Let us enjoy the testing by Totofpv.

Amazing, See how the FC handle 3S on full throttle!!

###

###

### SPECIFICATIONS OF FC

- CPU: STM32F411CEU6 (100MHZ )

- Six-Axis: MPU6000 (SPI connection)

- Size: 26mm x 26mm, whoop mounting pattern

- Firmware version: BETAFPVF411 (BEFH)

- OSD: Built-in BetaFlight OSD (STM32 controls OSD chip over SPI in DMA mode)

- Receiver: Support Frsky XM/XM+ Receiver/ Futaba Receiver/ Flysky Receiver/ TBS Crossfire Receiver. Add Frsky R9M Receiver and BETAFPV Micro DSMX Receiver (Don't support DSMX RX with 3.3V solder pad ) since V1.2.

- Support programmable LED like WS2812 etc

- Built-in current sensor

- Weight: 5.07g

### DIAGRAM FOR F4 2-4S AIO FC V2

###

### SPECIFICATIONS OF ESC

- Support BLheli/BLHELI_S suite Pass-through ready

- Support PWM, Oneshot125, Oneshot42, Multishot, Dshot150, Dshot300, Dshot600

- Input voltage: 2S-4S Lipo

- Continue current: 12A

- Peak current: 13A

- Firmware: BLHELI_S

- Processor: SILABS EFM8BB21F16G

- Motor Connectors: 1.25mm header pins connector

- Factory firmware: G-H-30-16.7

Could the ESC on this AIO board support really 4S battery?

Yes. But please pay more attention to the motors. Here are two situations that the motor will burn itself and then the ESC frequently.

Situation 1: The motor's KV value is too high and could not stand the 4S power. For example, the BETAFPV 1105 6000KV motors could not stand the 4S power in aggressive flying. So we are working on a lower KV 1105 motor that could use with 4S battery. It will be released soon.

Situation 2: A poor quality motor will result in the fire accident in 4S power.

For the moment, no 0x0x/1102/1103 motors could stand 4S power for the moment in the market. Please make sure your motors could support the 4S battery before any try.

### HOW TO CONNECT THE EXTERNAL RX TO THE FC

Here is the connection diagram with Frsky XM+ receiver.

Here is the connection diagram with FS-RX2A receiver.

Here is the connection diagram with Futabe-X-BOSS AC900 receiver.

Here is the connection diagram with TBS Crossfire receiver.

Here is the connection diagram with DSMX FullSpeed receiver.

### Status LED

There are 3 LEDs on the bottom of the board to indicate the status, including Receiver LED ( Green), FC Status LED ( Blue ) and FC Power LED ( Red ).

### Built-in Current Meter

This is our first whoop FC board that have current sensor built-in. So no need to use the virtual current meter and you could get a more accurate current value. In order to use this current sensor hardware, some configurations in Betaflight GUI are needed. In the "Power & Battery" tab:

Then when flying, you could find the real current value from the OSD information. Of course, the current sensor is configured well in the factory and you do not need to change it as usual.

Know more about current sensor and calibration.

### PACKAGE

1 * F4 2-4S brushless flight controller with XT30 Plug
4 * M1.2x4mm screws
4 * M1.4x5mm screws
4 * Anti-vibration rubber dampers

## 技术参数

| Battery | Motor Combo |
|---|---|
| 2S | 1103 11000KV / 0802 12000KV / 08028 12000KV |
| 3S | 1103 8000KV / 1105 6000KV |
| 4S | 1105 5000KV / 1204 5000KV / 1404 3800KV |

## 官方资料

https://betafpv.com/products/f4-2-4s-aio-brushless-flight-controller-12a-blheli_s
