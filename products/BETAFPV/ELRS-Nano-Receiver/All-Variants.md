---
product_id: WI2USlvO8gAojV3sbd
brand: BETAFPV
model: ELRS Nano Receiver
variant: All Variants
source_url: https://betafpv.com/products/elrs-nano-receiver
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: RC Receiver
collected_by: workbuddy
confidence: 0.6
specifications:
  Weight: 1.1g (RX only)
  Antenna: U.FL + T antenna
  MCU: ESP32-PICO-D4, dual SX1280
  RF Chip: Dual SX1280 + Dual PA
  Frequency: 2.4GHz ISM
  Telemetry Power: 100mW
  Serial Output Protocol: CRSF
  Model Type: FPV Drone, Fixed-wing aircraft
skus:
- sku_code: WI2USlvO8gAojV3sbd-01
  attributes:
    RF Version: ELRS 2.4GHz
    Cable Length: 46mm
- sku_code: WI2USlvO8gAojV3sbd-02
  attributes:
    RF Version: ELRS 915MHz
    Cable Length: 46mm
- sku_code: WI2USlvO8gAojV3sbd-03
  attributes:
    RF Version: ELRS 868MHz
    Cable Length: 46mm
- sku_code: WI2USlvO8gAojV3sbd-04
  attributes:
    RF Version: ELRS 2.4GHz
    Cable Length: 80mm
- sku_code: WI2USlvO8gAojV3sbd-05
  attributes:
    RF Version: ELRS 915MHz
    Cable Length: 120mm
- sku_code: WI2USlvO8gAojV3sbd-06
  attributes:
    RF Version: ELRS 868MHz
    Cable Length: 120mm
sources:
- type: official
  url: https://betafpv.com/products/elrs-nano-receiver
images: []
tags:
- elrs
- RC
- rx
- sale
---

# BETAFPV ELRS Nano Receiver

## 产品介绍

BETAFPV Nano receiver is based on the ExpressLRS project, an open-source RC link for RC applications. ExpressLRS aims to achieve the best possible link performance in both speeds, latency, and range. This makes ExpressLRS one of the fastest RC links available while still offering long-range performance.

A ton of ExpressLRS items are available now!

For micro drones, highly recommend the smaller Lite receiver.

Recommend ExpressLRS Recovery Dongle for unbricking the receiver.

### Specifications

- Weight: 0.7g (receiver only)

- Size: 12mm*19mm

- Telemetry power: 20dbm (100mW, 2.4G Version)

- Frequency bands (2.4G version): 2.4GHz ISM

- Frequency bands (915MHz/868MHz version): 915MHz FCC/868MHz EU

- Input voltage: 5V

- Antenna connector: U.FL MHF

### BETAFPV ExpressLRS Receivers

Choosing a suitable receiver to fly quadcopter or other RC models is very important. BETAFPV ExpressLRS Receivers including ELRS Lite, Nano, Micro, and the newest SuperD, greatly fulfill pilots' requirements for FPV flying.

### Diagram

Nano receiver 2.4G version:

Nano receiver 868MHz/915MHz version:

Note: Now the firmware version of the Nano receiver and module manufactured by our company is ELRS 3.3.0.;
ELRS Innovative team has officially released version 1.0.0, based on the version, we have some updates:

- 2.4G Nano TX Module supports 500Hz refresh rate；

- Short press the button on the Nano module 3 times to get into the binding status.

We suggest our customers upgrade their modules and receivers' ELRS version to 3.3.0. Significantly, the module and receiver have to be in the same ELRS version, otherwise, the frequency cannot match successfully.

Click to download the firmware of the ELRS Nano Receiver(V3.3.0 Version).

### Know More About ExpressLRS

ExpressLRS is an open-source RC link for RC applications. Everyone could find this project on Github or join the discussion in Facebook Group.

ExpressLRS is based on Semtech Lora SX127x or SX1280 hardware for RX and TX respectively. it aims to achieve the best possible link performance in both speeds, latency, and range. At 900 MHz a maximum of 200 Hz packet rate is supported. At 2.4 GHz a blistering 500Hz is currently supported with a custom OpenTX build. This makes ExpressLRS one of the fastest RC links available while still offering long-range performance.

More and more vendors start to support the ExpressLRS radio protocol in different parts, like radio transmitter with ELRS in stock, drone with built-in ELRS receiver, ELRS TX module for JR bay, or Nano bay. BETAFPV team take part in this project and provide a series of ExpressLRS components.

### Configuration & Bind

ExpressLRS uses the Crossfire serial protocol (AKA CRSF protocol) to communicate between the receiver and the flight controller board. So make sure your flight controller board supports the CRSF serial protocol. Next, we use the flight controller with Betaflight firmware to show how to set up the CRSF protocol.

The connection between the ELRS Nano receiver and the FC board is shown below.

Enable the corresponding UART (e.g. UART3 below) as a Serial Rx on Betaflight Configurator "Ports" tab.

On the "Configuration" tab, select "Serial-based receiver" on the "Receiver" panel, and select "CRSF" as the protocol. Telemetry is optional here and will reduce your stick update rate due to those transmit slots being used for telemetry.

Nano receiver could enter binding status by power on/off three times.

- Plugin and unplug nano receiver three times;

- Make sure the LED is doing a quick double blink, which indicates the receiver is in bind mode;

- Make sure the RF TX module or radio transmitter enter binding status, which sends out a binding pulse;

- If the receiver has a solid light, it's bound.

Note: Binding once and the receiver will store the binding information. Re-power and the connect successfully auto.

BETAFPV ELRS Nano receiver user manual download.

These folding TPU holders for BETAFPV's ExpressLRS 2.4G receiver have been designed by Ridwan Hughes to be reusable and easily printable. You could download the STL file on Thingiverse.

### Package

- 1 * BETAFPV ELRS Nano receiver

- 1 * BETAFPV T antenna

- 2 * Spare shrink tube

- 4 * 30awg silicon connection wires (1 black, 1 red, 1 white, 1 yellow)

- 1 * pin header 1x4

- 1 * Nano receiver user manual

## 技术参数

| SuperD RX | Micro RX | Nano RX | Lite RX |  |
|---|---|---|---|---|
| Weight | 1.1g (RX only) | 3.5g (RX only) | 0.7g (RX only) | 0.46g (Flat V1.2) |
| Antenna | U.FL + T antenna | U.FL + T antenna | U.FL + T antenna | SMD ceramic antenna |
| MCU | ESP32-PICO-D4, dual SX1280 | ESP8285 | ESP8285 | ESP8285 |
| RF Chip | Dual SX1280 + Dual PA | SX128X | SX1280 + PA, SX1276 + PA | SX128X |
| Frequency | 2.4GHz ISM | 2.4GHz ISM | 2.4GHz ISM, 915MHz (FCC), 868MHz (EU) | 2.4GHz ISM |
| Telemetry Power | 100mW | 17mW | 100mW | 17mW |
| Serial Output Protocol | CRSF | PWM or CRSF | CRSF | CRSF |
| Model Type | FPV Drone, Fixed-wing aircraft | Fixed-wing aircraft, Helicopter, RC Cars, RC Boats | FPV Drone | Whoop Drone |

## 官方资料

https://betafpv.com/products/elrs-nano-receiver
