---
product_id: h5UHVaamObYekr07dn
brand: BETAFPV
model: SuperD ELRS Diversity Receiver
variant: All Variants
source_url: https://betafpv.com/products/superd-elrs-2-4g-diversity-receiver
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: RC Receiver
collected_by: workbuddy
confidence: 0.6
specifications:
  Weight: 1.1g (2.4G Hz ) , 1.2g (915/868MHz)
  Antenna: U.FL + T antenna
  MCU: ESP32-PICO-D4
  RF Chip: Dual SX128X + Dual PA (2.4GHz), Dual SX1276 (915/868MHz)
  Frequency: 2.4GHz ISM, 915MHz (FCC), 868MHz (EU)
  Telemetry Power: 100mW
  Serial Output Protocol: CRSF
  Model Type: FPV Drone, Fixed-wing aircraft
skus:
- sku_code: h5UHVaamObYekr07dn-01
  attributes:
    Receiver: ELRS 2.4GHz
- sku_code: h5UHVaamObYekr07dn-02
  attributes:
    Receiver: ELRS 915MHz
- sku_code: h5UHVaamObYekr07dn-03
  attributes:
    Receiver: ELRS 868MHz
sources:
- type: official
  url: https://betafpv.com/products/superd-elrs-2-4g-diversity-receiver
images: []
tags:
- elrs
- RC
- rx
---

# BETAFPV SuperD ELRS Diversity Receiver

## 产品介绍

BETAFPV SuperD ELRS is the first True Diversity Receiver that applies two antennas, dual receiver chains, and TCXO (temperature compensated crystal oscillator) tech, achieving a super accurate frequency rate and excellent performance in extreme temperature environments. It offers 2.4GHz and 915MHz/868MHz versions, and greatly fulfills the requirements of reliability for long-range flying, aerial photography, or FPV freestyle tricks.

A ton of ExpressLRS items are available now!

Recommend ExpressLRS Recovery Dongle for flashing or recovering the receiver.

### Bullet Points

- A true diversity receiver with two complete RF receiver chains (referring to dual SX1280/SX1281 or dual SX1276), based on the latest official ExprssLRS. It comes with ExpressLRS V3.0.0 firmware.

- Ultralight weight is only 1.1g without the antenna. The receiver board features a reasonable layout and is impeccably clean. Very easy to solder.

- Two Dipole T antennas will create an omnidirectional signal for good signal transmission. Placing the antenna separately and vertically as far apart as possible to get a better signal is recommended.

- Not only it is used for FPV drones but also for FPV fixed-wing, or other FPV aircraft. It has superb performance in long-range flying.

- The first true diversity receiver for the 915MHz/868MHz frequency bands, with two separate receiving modules working together to improve signal reception quality and overall reliability.

- The 900MHz radio system exhibits greater diffraction ability due to its lower frequency, while the 2.4GHz systems tend to be directional and susceptible to attenuation caused by buildings, foliage, or moisture.

### Specification

- Item: BETAFPV SuperD ELRS 2.4GHz/915MHz/868MHz Diversity Receiver

- MCU: ESP32 PICO D4, dual SX1280(SX1281) (2.4GHz) / dual SX1276 (915MHz/868MHz)

- Telemetry power: 20dBm (2.4GHz) / 17dBm (915MHz/868MHz)

- Weight excluding antenna: 1.1g (2.4GHz) / 1.2g (915MHz/868MHz)

- RF Frequency: 2.4GHz (ISM) / 915MHz FCC/868MHz EU

- Antenna connector: U.FL

- Input voltage: +5V DC @ “+” pad

- Receiver protocol: CRSF

- PCB size: 22mm x 14mm

### First True Diversity Receiver with TCXO

SuperD ELRS 2.4GHz Diversity Receiver is built-in a TCXO (temperature compensated crystal oscillator), which is shared by two RF chips for a super accurate clock source. The true diversity receiver including two RF chips and PA+LNA will generate a large amount of heat when working. With the high-quality TCXO, it can withstand extreme temperatures with no fear of heat and cold, continuously outputting accurate frequency for long-range flight. Click to learn more about the TCXO.

### BETAFPV ExpressLRS Receivers

SuperD ELRS 2.4GHz Diversity Receiver has dual RF receiver chains with two antennas, ensuring longer and more stable flying for FPV drones and RC airplanes. Choosing a suitable receiver to fly quadcopter or other RC models is very important. BETAFPV ExpressLRS Receivers including ELRS Lite, Nano, Micro, and the newest SuperD, greatly fulfill pilots' requirements for FPV flying.

### Diagram

The SuperD receiver 2.4GHz version diagram is shown below.

The SuperD receiver 915MHz/868MHz version diagram is shown below.

SuperD receiver RGB status indication is shown below.

The RGB light color corresponding to the packet rate is shown in the figure below.

2.4GHz:

Note: F1000 and F500 are packet rates in FLRC mode, providing faster modulation and lower latency, but at the same time having shorter reception distance than normal Lora mode. This mode is great for racers.

D500 and D250 are packet rates in DVDA (Deja Vu Diversity Aid) mode. This mode works at the F1000 data packet rate of FLRC mode, providing better link connection in the case of complex interference by sending the same data packet multiple times. D500 and D250 indicate that the same data packet is sent twice and four times respectively.

915MHz/868MHz:

Note: D50 is a unique mode of ELRS Team900. Under the 200Hz refresh rate of Lora mode, the same data packet is repeatedly sent four times, and the receiving distance is equivalent to 200Hz.

100Hz Full is a mode that realizes 16-channel full-resolution output at the 200Hz refresh rate of Lora mode, and the receiving distance is equivalent to 200Hz.

### Configuration & Bind

ExpressLRS uses the Crossfire serial protocol (AKA CRSF protocol) to communicate between the SuperD diversity receiver and the flight controller board. Take the flight controller using the Betaflight firmware as an example to introduce its wiring and port configuration.

The connection between the SuperD diversity receiver and the flight controller is shown in the figure below

Connect the flight controller to the Betaflight Configurator for basic configuration. First, on the "Port" page, enable the flight controller serial port (take UART1 as an example) as "Serial Rx".

On the configuration page, set Receiver Mode to Serial (via UART) and Serial Receiver Provider to CRSF.

The default firmware of the SuperD diversity receiver uses the ExpressLRS V3.0.0 protocol and has no preset binding phrase.  Therefore, the firmware version of the transmitter module must be ExpressLRS V3.0.0 or later versions. Both the receiver and transmitter module should not have any binding phrase.

- Power on and off the receiver 3 times, each step pausing 2 seconds to enter binding mode;

- When the indicator starts fast blink with orange twice, the receiving is at binding mode;

- Enter the radio or transmitter module's binding mode to bind with the receiver; if the Indicator has turned solid, it indicates that the device has been bound successfully.

Note: After binding once, the receiver will remember the autosaved binding phrase and device. Further restarting of the device will be bound automatically without the need for a rebinding process.

The 2.4GHz default firmware is ELRS V3.0.0. If you would like to bind with a remote control or transmitter module, please upgrade it to V3.0.0 or above. If you would like to flash the latest official ELRS firmware for the SuperD receiver, please upgrade ELRS Configurator to V1.5.2 or above. Select the target device "BETAFPV SuperD 2.4GHz RX".

The 915MHz/868MHz default firmware is ELRS V3.3.0. The official version has not yet been released. It will be updated synchronously with the ELRS V3.3 version. Then you can click the latest ELRS Configurator Nightly to operate. Select the target device ''BETAFPV SuperD 900MHz RX''.

Note: Firmware for 915MHz/868MHz is currently self-compiled firmware.

### FAQ

- BETAFPV SuperD ELRS 2.4GHz Diversity Receiver user manual for download.

- Download the Firmware for SuperD ELRS 2.4GHz/915MHz/868MHz Diversity Receiver.

- How to flash the firmware via Passthrough or WIFI for SuperD Receiver.

- Download TPU holders 3D-printing STL file for SuperD ELRS 2.4GHz Diversity RX.

### Know More About ExpressLRS

ExpressLRS is an open-source RC link for RC applications. Everyone could find this project on Github or join the discussion in Facebook Group.

### Package

- 1* SuperD 2.4GHz Diversity Receiver

- 2* 2.4GHz T Antenna

- 1* 4-Pin Header

- 1* 4-Pin Wire Harness

- 1* Instruction Manual

- 2* Heat Shrink Tubing

- 1* SuperD 915MHz/868MHz Diversity Receiver

- 2* 915MHz/868MHz T Antenna

- 1* 4-Pin Header

- 1* 4-Pin Wire Harness

- 1* Instruction Manual

- 2* Heat Shrink Tubing

## 技术参数

| SuperD RX | Micro RX | Nano RX | Lite RX |  |
|---|---|---|---|---|
| Weight | 1.1g (2.4G Hz ) , 1.2g (915/868MHz) | 3.5g (RX only) | 0.7g (RX only) | 0.46g (Flat V1.2) |
| Antenna | U.FL + T antenna | U.FL + T antenna | U.FL + T antenna | SMD ceramic antenna |
| MCU | ESP32-PICO-D4 | ESP8285 | ESP8285 | ESP8285 |
| RF Chip | Dual SX128X + Dual PA (2.4GHz), Dual SX1276 (915/868MHz) | SX128X | SX128X + PA, SX1276 + PA | SX128X |
| Frequency | 2.4GHz ISM, 915MHz (FCC), 868MHz (EU) | 2.4GHz ISM | 2.4GHz ISM, 915MHz (FCC), 868MHz (EU) | 2.4GHz ISM |
| Telemetry Power | 100mW | 17mW | 100mW | 17mW |
| Serial Output Protocol | CRSF | PWM or CRSF | CRSF | CRSF |
| Model Type | FPV Drone, Fixed-wing aircraft | Fixed-wing aircraft, Helicopter, RC Cars, RC Boats | FPV Drone | Whoop Drone |

## 官方资料

https://betafpv.com/products/superd-elrs-2-4g-diversity-receiver
