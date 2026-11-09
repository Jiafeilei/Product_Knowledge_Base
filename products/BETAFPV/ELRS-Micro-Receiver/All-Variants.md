---
product_id: OgVcaMNTJUXbJcp1IA
brand: BETAFPV
model: ELRS Micro Receiver
variant: All Variants
source_url: https://betafpv.com/products/elrs-micro-receiver
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
- sku_code: OgVcaMNTJUXbJcp1IA-01
  attributes:
    Receiver: ELRS 2.4G V1.2
sources:
- type: official
  url: https://betafpv.com/products/elrs-micro-receiver
images: []
tags:
- elrs
- RC
- rx
---

# BETAFPV ELRS Micro Receiver

## 产品介绍

BETAFPV Micro receiver is based on the ExpressLRS project, an open-source RC link for RC applications. ExpressLRS aims to achieve the best possible link performance in both speeds, latency, and range. This makes ExpressLRS one of the fastest RC links available while still offering long-range performance.

###

A ton of ExpressLRS items are available now!

### ExpressLRS PWM Receivers

ExpressLRS now supports direct PWM output from receivers that have been specifically designed for this mode. BETAFPV ELRS Micro receiver features PWM output for the application of fixed-wing, helicopters, RC cars, boats and etc, and supports failsafe function, which can protect RC models from being out of control. Besides, the plug-and-play design makes it very easy and friendly to use.

Note: To work with PWM receiver, please make sure the TX and RX firmware is ELRS V2.0.0.

### BETAFPV ExpressLRS Receivers

Choosing a suitable receiver to fly quadcopter or other RC models is very important. BETAFPV ExpressLRS Receivers including ELRS Lite, Nano, Micro, and the newest SuperD, greatly fulfill pilots' requirements for FPV flying.

### Specification

- Item: BETAFPV ELRS Micro Receiver

- Weight: 4.5g (with antenna)

- Antenna: U.FL + T antenna (recommend 80mm Dipole T Antenna)

- PWM channel: 5 channels

- Serial output protocol: PWM or CRSF

- Size: 19mm*32mm*9mm (without antenna)

- MCU: ESP8285/SX1280/SX1281

- Telemetry power: 12.5dbm/17mW

- Frequency bands: 2.4GHz ISM

- Input voltage: 5V~9V DC @ "+" pad

- Default firmware version: ExpressLRS v2.0

- Adapted RC Model Type: Multirotors, Fixed-wing aircraft, Helicopters, RC Cars, RC Boats and etc.

###

### Diagram

Below is the diagram for ELRS Micro receiver.

Note: Now the firmware version of the micro receiver manufactured by our company is ELRS 3.3.0. ELRS Innovative team has officially released version 3.3.0, which is not compatible with the 2.x version. Significantly, the TX module and receiver have to be in the same ELRS version, otherwise, the frequency cannot match successfully.

Note: The Micro receiver also supports flash CRSF output firmware, in this case CH2 corresponds to TX and CH3 corresponds to RX.

Please click here to know the way to flash firmware for Micro receiver.

Click to download the firmware of the ELRS Micro Receiver(V3.3.0 Version).

### Know More About ExpressLRS

ExpressLRS is an open-source RC link for RC applications. Everyone could find this project on Github or join the discussion in Facebook Group.

ExpressLRS is based on Semtech Lora SX127x or SX1280 hardware for RX and TX respectively. it aims to achieve the best possible link performance in both speeds, latency, and range. At 900 MHz a maximum of 200 Hz packet rate is supported. At 2.4 GHz a blistering 500Hz is currently supported with a custom OpenTX build. This makes ExpressLRS one of the fastest RC links available while still offering long-range performance.

More and more vendors start to support the ExpressLRS radio protocol in different parts, like radio transmitter with ELRS in stock, drone with built-in ELRS receiver, ELRS TX module for JR bay, or Nano bay. BETAFPV team take part in this project and provide a series of ExpressLRS components.

### Binding Procedure

The Micro receiver comes with officially major release V2.0.0 protocol and has not been set for a Binding Phrase. So please make sure the RF TX module works on officially major release V2.0.0 protocol and no Binding Phrase has been set beforehand.

- Enter binding mode by plugging in and unplugging the Micro receiver three times;

- Make sure the LED is on double flashing, this indicates the Micro receiver is in bind mode;

- Make sure the RF TX module or radio transmitter also enters the binding mode, which sends out a binding pulse;

- When the LED light is solid, it indicates that the devices are successfully bound.

Note: once the devices have been successfully bound, the receiver will store the binding information. There would be no need for re-bind on the later use as the devices would be connected automatically.

Note: If you reflash the firmware of the Micro receiver with your own Binding Phrase, please make sure the RF TX module has the same Binding Phrase to perform an auto bind.

### Failsafe and PWM Output

When the connection or signal is lost between the radio transmitter and receiver, the failsafe function will adjust all the channels to the failsafe values set by the users, maximum keep safety and prevent from flying away. It's necessary to set up failsafe values properly if you are not using a flight controller, such as RC fixed-wing.

- Power on the Micro receiver and wait for 20 seconds without binding.

- Once the indicator is flashing quickly, the receiver's WiFi has been activated.

- Connect WiFi via computer or mobile phone.

- WiFi Name: ExpressLRS RX

- WiFi PWD: expresslrs

- Open the website address: http://10.0.0.1, and set your own failsafe values.

Note: Failsafe values are absolute and do not use the "invert" flag.

Micro receiver LED status indication is shown below.

### FAQ

Recommend ExpressLRS Recovery Dongle for unbricking the receiver.

### Package

- 1 * ELRS Micro Receiver

- 1 * BETAFPV 80mm T antenna

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

https://betafpv.com/products/elrs-micro-receiver
