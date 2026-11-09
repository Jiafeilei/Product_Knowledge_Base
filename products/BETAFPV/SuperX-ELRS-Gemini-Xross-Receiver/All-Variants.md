---
product_id: wP2KgjVJwB4M6vwGmA
brand: BETAFPV
model: SuperX ELRS Gemini Xross Receiver
variant: All Variants
source_url: https://betafpv.com/products/superx-elrs-gemini-xross-receiver
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: RC Receiver
collected_by: workbuddy
confidence: 0.6
specifications:
  MCU: ESP32-C3
  Telemetry Power: 20dBm
  Input Voltage: 5V
  Protocols: CRSF, SBUS, SUMD, DJI RS2 Pro, MAVLink
  RF Chip: Single LR1121
  Reception Mode: Single
  Frequency Band: 900M/2.4G
  Antenna Connector: U.FL x1
  Weight: 0.82g
  Dimensions: 12.3 x 18.6mm
  LUA Name: BFPV SuperX Mon
  Recommended: 2''- 5'' drones (racing, freestyle, long-range)
skus:
- sku_code: wP2KgjVJwB4M6vwGmA-01
  attributes:
    Version: Nano (ELRS 2.4G+915M)
- sku_code: wP2KgjVJwB4M6vwGmA-02
  attributes:
    Version: Nano (ELRS 2.4G+868M)
- sku_code: wP2KgjVJwB4M6vwGmA-03
  attributes:
    Version: Mono (ELRS 2.4G/915M)
sources:
- type: official
  url: https://betafpv.com/products/superx-elrs-gemini-xross-receiver
images: []
tags:
- elrs
- RC
- rx
---

# BETAFPV SuperX ELRS Gemini Xross Receiver

## 产品介绍

Powered by Semtech’s LR1121 RF chips and Espressif’s ESP32-C3, the SuperX pioneers BETAFPV’s first Gemini Xrossband receiver – mastering 900M (868/915MHz) and 2.4G bands via LoRa and blistering 1000Hz FSK modes. Conquer race gates and long-range horizons with unshakeable signal reliability, where lesser links fail. Choose the dual-band mastery of SuperX Nano or the band-switching agility of SuperX Mono for precision-tuned performance in any flying scenario.

### Bullet Points

- Semtech LR1121 RF chips + Espressif ESP32-C3

- LoRa and blistering 1000Hz FSK modes

- Supports 900M Gemini, 2.4G Gemini, 900M+2.4G GemX

- SuperX Nano: Dual-band mastery for RF-challenged environments

- SuperX Mono: Band-switching for micro builds

- Works with Micro/Micro V2/Nano V2/SuperG TX modules

- Compact and lightweight

### Specifications

### Diagram

SuperX Nano Receiver:

SuperX Mono Receiver:

### Gemini

ExpressLRS Gemini revolutionizes RC control by leveraging true diversity hardware to simultaneously transmit across 2.4GHz and/or 900MHz frequencies. Unlike conventional systems, Gemini utilizes dual independent transmit/receive chains - delivering superior link quality (LQ) that thrives in challenging environments like race courses or urban areas.

Gemini offers three modes: 900M Gemini, 2.4G Gemini, and 900M+2.4G Gemini Xrossband (GemX). With GemX, you no longer need to choose between performance traits—it combines 2.4GHz's low latency and 900MHz's long-range in a single, seamless link.

Note: The GemX mode requires a dual-band TX.

### SuperX Nano: 900M+2.4G Dual Band

Powered by dual LR1121 chips from Semtech, the SuperX Nano Receiver delivers uncompromising signal reliability with three modes: 900M Gemini (long-range penetration), 2.4G Gemini (ultra-low latency), and 900M+2.4G GemX (simultaneous operation). The included dual-band T antennas eliminate frequency-switching hassles, while advanced diversity processing ensures rock-solid stability in RF-challenged environments. Built for mission-critical applications, it's the ultimate solution for competitive racers, long-range explorers, and professional aerial photographers who demand zero-compromise performance.

### SuperX Mono: Band-switching Agility

The compact and lightweight SuperX Mono Receiver harnesses a single LR1121 chip with a dual-band antenna, enabling seamless switching between 900M and 2.4G. This cost-effective solution maintains impressive 1000Hz packet rates (in FSK mode) while offering exceptional value, making it ideal for micro builds and budget-conscious pilots who need versatile performance in both close-range freestyle and long-distance applications.

### TX Compatibility

### SuperX vs. SuperD vs. Nano

### BETAFPV ExpressLRS Receivers

Choosing the right receiver is critical for optimal FPV performance. BETAFPV’s ExpressLRS lineup offers tailored solutions for every pilot: ELRS Lite, Micro, Nano, SuperP, SuperD, and the newest SuperX. From whoop racing to long-range cinematography, we engineer the low-latency links and interference-proof performance you demand.

### Configuration

The SuperX Receiver currently supports CRSF/SBUS/SUMD protocols. The following takes CRSF protocol as an example to introduce its connection and pin configuration with Betaflight firmware flight controller.

Wiring diagram:

JST SH connector pin configuration:

Note: Betaflight and ExpressLRS use different JST SH connector pin configurations. Betaflight: 5V (V+), GND, RX, TX; ExpressLRS: GND, 5V (V+), TX, RX. When using the terminal wires for connection, please check the sequence.

Connect the flight controller to the Betaflight Configurator for basic configuration. First, on the "Port" tab, enable the flight controller serial port like UART1 as Serial Rx.

On the "Configuration" tab, set Receiver Mode to Serial (via UART) and Serial Receiver Provider to CRSF.

### Bind

The SuperX Receiver uses ExpressLRS V3.x official protocol as its default firmware without a pre-set binding phrase. For successful operation, ensure the transmitter module also uses ExpressLRS V3.x or later firmware with no pre-set binding phrase.

- Power-cycle the receiver 3 times with a 1-second interval or press and hold the BOOT button for 2 seconds to enter binding mode.

- The RGB indicator flashes orange twice, which indicates the receiver is in bind mode.

- Configure remote control or transmitter module to bind with the receiver. If the RGB indicator is a solid light, it's bound!

Notes:

● After binding once, the receiver will remember the autosaved binding phrase and device. Further restarting of the device will be bound automatically without the need for a rebinding process.

● If you have flashed firmware to the SuperX and configured the binding phrase, you will not be able to bind using the method above. Please set the same binding phrase for the transmitter module, this allows the receiver to be bound to the device automatically.

● It is recommended to place the two antennas as far apart as possible for better reception.

### Know More About ExpressLRS

ExpressLRS is an open-source RC link for RC applications. Everyone could find this project on Github or join the discussion in Facebook Group.

### File

-
User Manual for BETAFPV SuperX ELRS Gemini Xross Receiver

- Firmware for SuperX ELRS Gemini Xross Receiver

- How to flash the firmware of SuperX Receiver via Passthrough or WIFI?

-
To minimize GPS interference when using 868MHz, X150, or LowBand packet rates, avoid setting the telemetry ratio to 1:2 unless absolutely necessary—especially at 100mW telemetry power.

If you require MAVLink or a 1:2 telemetry ratio, please position the SuperX receiver as far as possible from the GPS and avoid pointing the receiver antenna toward the GPS during satellite acquisition.

### Package

Item: SuperX ELRS Gemini Xross Receiver - Nano

- 1* SuperX Nano Receiver

- 2* Dual-band T Antenna

- 1* SH1.0 Connector (Double Ended)

- 2* Heat Shrink Tubing

- 1* User Manual

Item: SuperX ELRS Gemini Xross Receiver - Mono

- 1* SuperX Mono Receiver

- 1* Dual-band T Antenna

- 1* SH1.0 Connector (Single Ended)

- 2* Heat Shrink Tubing

- 1* User Manual

## 技术参数

| SuperX Mono RX | SuperX Nano RX |  |
|---|---|---|
| MCU | ESP32-C3 |  |
| Telemetry Power | 20dBm |  |
| Input Voltage | 5V |  |
| Protocols | CRSF, SBUS, SUMD, DJI RS2 Pro, MAVLink |  |
| RF Chip | Single LR1121 | Dual LR1121 |
| Reception Mode | Single | Diversity/Gemini |
| Frequency Band | 900M/2.4G | 900M+2.4G |
| Antenna Connector | U.FL x1 | U.FL x2 |
| Weight | 0.82g | 1.45g |
| Dimensions | 12.3 x 18.6mm | 16.3 x 21.4mm |
| LUA Name | BFPV SuperX Mon | BFPV SuperX Nan |
| Recommended | 2''- 5'' drones (racing, freestyle, long-range) | 5'' + drones (freestyle, photography, long-range) |

## 官方资料

https://betafpv.com/products/superx-elrs-gemini-xross-receiver
