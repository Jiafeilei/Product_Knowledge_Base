---
product_id: I2e5EUDCqgrUys0UoE
brand: BETAFPV
model: ELRS Lite Receiver
variant: All Variants
source_url: https://betafpv.com/products/elrs-lite-receiver
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
- sku_code: I2e5EUDCqgrUys0UoE-01
  attributes:
    Receiver: ELRS 2.4G
    Antenna: Flat Antenna V1.2
- sku_code: I2e5EUDCqgrUys0UoE-02
  attributes:
    Receiver: ELRS 2.4G
    Antenna: Tower Antenna
sources:
- type: official
  url: https://betafpv.com/products/elrs-lite-receiver
images: []
tags:
- elrs
- RC
- rx
---

# BETAFPV ELRS Lite Receiver

## 产品介绍

Building on the open-source ExpressLRS framework – renowned for delivering ultra-low latency, blistering speeds, and exceptional range – the upgraded Lite Receiver flat antenna V1.2 now features an extra-thin 3mm board, 0.46g ultra-lightweight design and enlarged soldering pads. Optimized impedance matching elevates signal reliability and sensitivity, enabling 300m range at 25mW transmitter power and up to 1000m at 50mW, pushing the boundaries of long-range potential in micro-sized receivers.

A ton of ExpressLRS items are available now!

### Specifications

- Weight: 0.46g (Flat Antenna V1.2), 0.47g (Tower Antenna)

- Size: 11mm*10mm*3mm (Flat), 10mm*10mm*6mm (Tower)

- MCU: ESP8285

- Telemetry power: 17mW

- Frequency bands: 2.4GHz ISM

- Input voltage: 5V

- Antenna: Integrated SMD ceramic antenna

### Diagram

Flat antenna 2.4G V1.2:

Tower antenna:

### Enhanced Signal Reliability & Sensitivity

The flat antenna V1.2’s optimized impedance matching unlocks a transformative leap in signal reliability and sensitivity. Where the original flat antenna V1.1 achieved 500-600m at 50mW transmitter power/500Hz, the V1.2 now delivers a robust 1000m under identical conditions – alongside superior signal consistency. This precision-tuned design minimizes packet loss during high-speed maneuvers and enhances low-power efficiency, ensuring crisp responsiveness at 25mW (300m range) and unwavering stability at max output.

Watch our flight test video to see the V1.2’s 1,000m range in action.

### Lightweight Design, Simplified Installation

Responding to community feedback, the flat antenna V1.2 now features enlarged soldering pads designed to simplify installation and reduce errors – a critical upgrade for novices and seasoned builders alike. Combined with a 13.2% weight reduction (now just 0.46g), the updated design retains its compact footprint while shedding unnecessary mass, freeing up crucial weight budgets for performance-focused builds.

### BETAFPV ExpressLRS Receivers

Selecting the right receiver is crucial for optimal quadcopter and RC model performance. BETAFPV's comprehensive ExpressLRS lineup - featuring the ELRS Lite, Nano, Micro, and our newest SuperD receivers - delivers tailored solutions to meet every pilot's FPV requirements.

### Nano RX vs. Lite RX

The Nano Receiver (2.4G version) is the first receiver with power amplifier (PA+LNA), delivering 100mW telemetry output and better sensitivity for longer range. In contrast, the Lite Receiver doesn't have a PA/LNA, so its telemetry power is limited to the SX1280 RF chip's native 17mW output.

Another key difference is the antenna: the Nano Receiver comes with a standard external Dipole T antenna, while the Lite Receiver uses a SMD ceramic antenna, which typically offers shorter range.

For best performance, we highly recommend the Nano Receiver if your build has enough space. However, for racing and 65-85mm whoop drones, the Lite Receiver remains the better choice.

### Flat Antenna vs. Tower Antenna

The new Lite Receiver flat antenna V1.2 features an extra-thin 3mm board and 0.46g lightweight design, ideal for drones with space constraints. Its low-profile flat antenna can withstand crashes, delivering durability compared to protruding tower antennas.

While both antennas share similar gain and return loss characteristics, the flat antenna V1.2’s optimized impedance matching achieves better signal reliability and sensitivity – extending operational range to 1,000m (versus the discontinued tower antenna’s 600m). This upgrade focuses entirely on perfecting the crash-resistant flat antenna design, delivering pilots unprecedented range and durability in the most compact form factor available.

### Know More About ExpressLRS

ExpressLRS is an open-source RC link for RC applications. Everyone could find this project on Github or join the discussion in Facebook Group.

ExpressLRS is based on Semtech Lora SX127x or SX1280 hardware for RX and TX respectively. it aims to achieve the best possible link performance in both speeds, latency, and range. At 900 MHz a maximum of 200 Hz packet rate is supported. At 2.4 GHz a blistering 500Hz is currently supported with a custom OpenTX build. This makes ExpressLRS one of the fastest RC links available while still offering long-range performance.

More and more vendors start to support the ExpressLRS radio protocol in different parts, like radio transmitter with ELRS in stock, drone with built-in ELRS receiver, ELRS TX module for JR bay, or Nano bay. BETAFPV team take part in this project and provide a series of ExpressLRS components.

Note: Now the firmware version of our Lite Receiver flat antenna V1.2 and tower antenna is ELRS 3.3.0; ELRS Innovative team has officially released version 3.3.0. If you want to flash ELRS official firmware, please download the latest ExpressLRS-Configurator or read our manual for flashing it. Significantly, the TX module and receiver have to be in the same ELRS version, otherwise, the frequency cannot match successfully.

Download the latest ExpressLRS-Configurator.

Manual for flashing ExpressLRS official firmware.

Click to download the firmware of the ELRS Lite Receiver (V3.3.0 Version).

### Configuration & Bind

ExpressLRS uses the Crossfire serial protocol (AKA CRSF protocol) to communicate between the receiver and the flight controller board. So make sure your flight controller board supports the CRSF serial protocol. Next, we use the flight controller with Betaflight firmware to show how to set up the CRSF protocol.

The connection between the ELRS Lite Receiver and the FC board is shown below.

Enable the corresponding UART (e.g. UART3 below) as a Serial Rx on Betaflight Configurator "Ports" tab.

On the "Configuration" tab, select "Serial-based receiver" on the "Receiver" panel, and select "CRSF" as the protocol. Telemetry is optional here and will reduce your stick update rate due to those transmit slots being used for telemetry.

The Lite Receiver comes with offically major release V3.0.0 protocol and no Binding Phrase inlcuded. Lite Receiver could enter binding status by power on/off three times.

- Plugin and unplug the Lite Receiver three times;

- Make sure the LED is doing a quick double blink, which indicates the receiver is in bind mode;

- Make sure the RF TX module or radio transmitter enter binding status, which sends out a binding pulse;

- If the receiver has a solid light, it's bound.

Note: Binding once and the receiver will store the binding information. Re-power and the connect successfully auto.

Note: If you reflash firmware of the receiver with your own Binding Phrase, please make sure the TX module has the same Binding Phrase. The RF TX module and the receiver will bind automatically in this situation.

### Recommended Part

- ExpressLRS Recovery Dongle

### File

BETAFPV ELRS Nano Receiver User Manual (Lite Receiver and Nano Receiver use the same manual)

### Package

- 1 * BETAFPV ELRS Lite Receiver (flat antenna V1.2 / tower antenna)

- 2 * Spare shrink tube

- 4 * 30awg silicon connection wires (1 black, 1 red, 1 white, 1 yellow)

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
| Model Type | FPV Drone, Fixed-wing aircraft | Fixed-wing aircraft, Helicopter, RC Cars, RC Boats | FPV Drone | FPV Drone, Whoop Drone |

## 官方资料

https://betafpv.com/products/elrs-lite-receiver
