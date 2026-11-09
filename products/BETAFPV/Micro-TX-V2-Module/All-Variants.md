---
product_id: wycwVnodsWdsp5waF8
brand: BETAFPV
model: Micro TX V2 Module
variant: All Variants
source_url: https://betafpv.com/products/micro-tx-v2-module
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Module
collected_by: workbuddy
confidence: 0.6
specifications:
  Max RF Power: 2W
  Frequency Band: 900MHz
  Fan: 2507 12000RPM
  RF Chip: SX1276
  External Power Supply: Supported 5-25V
skus:
- sku_code: wycwVnodsWdsp5waF8-01
  attributes:
    Output power: 2W
    Frequency: ELRS 915MHz
- sku_code: wycwVnodsWdsp5waF8-02
  attributes:
    Output power: 2W
    Frequency: ELRS 868MHz
sources:
- type: official
  url: https://betafpv.com/products/micro-tx-v2-module
images: []
tags:
- elrs
- module
- tx
---

# BETAFPV Micro TX V2 Module

## 产品介绍

The Micro TX V2 Module boasts a Max 2W RF output of up to 200Hz packet rate, and an efficient cooling system with an integrated TCXO, enlarged airflow vents, and a high-speed 2507 Axial Fan. It's designed for superior link stability and anti-interference capabilities. Flashing your firmware with ease using the 5D button and OLED display. It's an ideal choice for pilots seeking a reliable signal under long-range flight.

### Bullet Point

- With the 2000mW Max RF Power, enjoy stronger signals, and longer transmission distances.

- Featuring a built-in TCXO, CNC aluminum alloy heat sink, enlarged airflow vents, and a high-speed 2507 Axial Fan, the upgraded cooling system ensures stable link performance.

- Say goodbye to multiple steps of PID switches to flash the firmware, enjoying a fluent flashing experience easily with one 5D button and an OLED display.

- Backpack function aims to allow wireless communication between ExpressLRS, and other FPV-related devices for command and control, or for querying config.

### Specification

- Item: BETAFPV Micro TX V2 Module | ELRS 915/868MHz

- Weight: 54.8g

- Color: Black

- Antenna Connector: SMA-KE

- RF Power: 10mW/25mW/50mW/100mW/250mW/500mW/1000mW/2000mW

- Packet Rate: 25Hz/50Hz/100Hz/100Hz Full/200Hz/D50

- Frequency Band: 915MHz FCC/868MHz EU

- Backpack: Support

- Input Voltage: 7V~13V DC

- Rated Current: 10V,1A@2000mW,200Hz, 1:128

- USB Port: Type-C

- Fan Voltage: 5V

- Default Firmware Version: ExpressLRS V3.4.3

- Target Name: BETAFPV Micro 900MHz TX V2

The Micro TX V2 Module is an upgrade from the ELRS Micro TX Module. Below is a comparison of key specifications.

### Diagram

BETAFPV Micro TX V2 module is compatible with the radio transmitter which has the micro module bay (AKA JR/SLIM module bay, e.g. Frsky Taranis X9D, TBS Mambo). Below is the diagram.

Note: Please assemble the antenna before powering on. Otherwise, the TX module's PA chip will be permanently damaged.

### 2W RF Power

The Micro TX V2 Module boasts a powerful 2000mW transmission power. Featuring a built-in TCXO (temperature-compensated crystal oscillator). it can withstand extreme temperatures with no fear of heat and cold, continuously outputting accurate frequency for eliminating signal interference, achieving a reliable long-range flight. Experience stronger signals, longer transmission distances, and an expanded radio transmitter range. With these options, pilots can explore and connect with greater freedom in wireless communication.

Note: For optimal safety and performance when operating at 2W high power, please use the XT30 connector with an external power supply configured for 2-4S. This setup supports voltages ranging from 5V to 25V.

Using it together with the ELRS Receivers ensures a super stable yet strong radio link for pilots to fly in any environment that requires extremely stable signals and low latency, including FPV racing, long-range flight, and cinematic shooting. It gives pilots an aggressive but stable flight experience.

### Cooling System Iteration

Engineered for precision and performance, this Micro TX V2 Module boasts a robust, CNC aluminum alloy heat sink design. Its cooling system includes enlarged airflow vents and an optimized fan layout, both internally and externally. Powered by a high-speed 2507 Axial Fan, it masterfully channels heat away, even under the most demanding power outputs. This ensures not only stable link performance but also the ultimate in temperature control, making drones easily cope with high loads and soar stably.

### Moxon Antenna V2

BETAFPV Moxon Antenna V2 has been very popular with pilots since its release. By taking the features of Moxon and adding some new ones, the coaxial cable of Moxon V2 is soldered to the antenna, decreasing the signal transmission loss for better performance. Besides, the soldered joint is protected by an injection molding cover, making it a whole unit and very easy to install.

### OLED and Button

The Intuitive Visualize Setting feature on the OLED, allows you to see and adjust your TX settings in real time and ensures that you're always in the know and in control. Personalize capabilities with the 5D Button feature, tailoring to your unique preferences and needs, and streamline your drone's operations, making it easier than ever to execute complex maneuvers and commands with just a touch.

There is a 5D button on the Micro TX V2 Module. Below is the basic operation of the button and OLED. Long Press: Unlock and enter the menu page, or apply current settings on the menu page. Up/Down: Move to the last/next row. Left/Right: Change the value of this row. Short Press: Enable binding status or WiFi upgrade status.

Note: When the RF TX module enters WIFI Upgrade status, the button will be invalid. Please re-power the RF TX module after the firmware update via WIFI.

### Streamline Steps, Abundant function

Say goodbye to multiple steps of PID switches to flash the firmware, enjoying a fluent flashing experience easily with one 5D button. Backpack function, some of the ExpressLRS TX modules include an additional ESP8285 chip, which lets us communicate wirelessly with other ESP8285-enabled devices using a protocol called espnow. We call this chip the "TX-Backpack". The TX-Backpack aims to allow wireless communication between ExpressLRS, and other FPV-related devices for command and control, or for querying config.

https://github.com/ExpressLRS/Backpack/wiki

### Combination with Most Radio TX

The Micro TX V2 Module supports the Micro module bay(AKA JR/SLIM module bay), which is compatible with most ELRS receivers and all OpenTX controllers and some no-OpenTX remote controls like T161Z, T16SZ, T18SZ, ET16, etc. on the market.

### ELRS Series

The ExpressLRS Series expands its lineup with the addition of the Micro TX V2 Module. To achieve exceptional link quality. BETAFPV takes the flying experience to new heights by introducing ELRS links that offer long-range capabilities, low latency, and high refresh rates in a radio control system.

### Basic Configuration

The Micro TX V2 Module defaults to receive signals in the Crossfire serial data protocol (CRSF), so the TX module interface of the remote control needs to support CRSF signal output. Taking the EdgeTX remote control system as an example, the following explains how to configure the remote control to output CRSF signals and control the TX module using Lua scripts.

CRSF Protocol: In the EdgeTX system, select "MODEL SEL" and enter the "SETUP" interface. In this interface, turn off Internal RF (set to "OFF"), turn on External RF, and set the mode to CRSF. Connect the module correctly and then the module will function properly.

Lua Script: Lua is a lightweight and compact script language. It can be used by being embedded in radio transmitters and easily reading and modifying the parameter set of the TX module. The directions for using Lua are as below.

- Download the elrsV3.lua on the BETAFPV official website or ExpressLRS configurator;

- Save the elrsV3.lua files onto the radio transmitter's SD Card in the Scripts/Tools folder;

- Press the "SYS" button or the "Menu" button on the EdgeTX system to access the "Tools" interface where you can choose "ExpressLRS" and run it；

- The below images show the Lua script if it runs successfully.

### Bind & External Power Supply

The Micro TX V2 Module comes with the official major release ExpressLRS V3.4.3 protocol and no Binding Phrase included. So please make sure the receiver works on the official major release ExpressLRS V3.0.0 protocol. And no Binding Phrase set.

- Put the receiver into binding mode and wait for the connection；

- Using the button and OLED, move to the Bind position and short-press the button. Then the RF module will enter binding status. Or you can enter binding mode by clicking 'Bind' in the Lua script. If the Indicator of the receiver and the module turned solid. It indicates that they bound successfully.

Note: If the TX module has been reflashed firmware with a Binding Phrase, then using the above binding method will not be bound to other devices. Please set the same binding phrase for the receiver to perform automatic binding.

The power consumption of the Micro TX V2 Module when using a transmission power of 500mW or above is relatively high, which will shorten the usage time of the radio controller.

-
Users can connect an external battery to the TX module through the XT30 port. The usage method is shown in the following figure.

Note: Please ensure the battery is fully charged before powering up the TX module to prevent reboot due to insufficient power supply, resulting in disconnection and loss of control.

### FAQ

- Click to download the User Manual for the Micro TX V2 Module.

- Click to download the Firmware for the Micro TX V2 Module.

### Package

- 1 * Micro TX V2 Module

- 1 * Moxon Antenna V2

- 1 * GH1.25-FUTABA Male Adapter Cable

- 1 * User Manual

- 1 * USB to Type-C Data Cable

- 1 * Service Card

## 技术参数

| Micro TX V2 | Micro TX |  |
|---|---|---|
| Max RF Power | 2W | 1W/500mW |
| Frequency Band | 900MHz | 900MHz/2.4GHz |
| Fan | 2507 12000RPM | 2510 8000RPM |
| RF Chip | SX1276 | SX128X/SX1276 |
| External Power Supply | Supported 5-25V | Supported 5-12V |

## 官方资料

https://betafpv.com/products/micro-tx-v2-module
