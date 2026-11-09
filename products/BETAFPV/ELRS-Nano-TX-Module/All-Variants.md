---
product_id: lpyKaQPegR3GKgKtQe
brand: BETAFPV
model: ELRS Nano TX Module
variant: All Variants
source_url: https://betafpv.com/products/elrs-nano-tx-module
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Module
collected_by: workbuddy
confidence: 0.6
specifications:
  Blue: 100mW
  Purple: 250mW
  Red: 500mW
skus:
- sku_code: lpyKaQPegR3GKgKtQe-01
  attributes:
    Style: ELRS 2.4G
- sku_code: lpyKaQPegR3GKgKtQe-02
  attributes:
    Style: ELRS 915MHz
- sku_code: lpyKaQPegR3GKgKtQe-03
  attributes:
    Style: ELRS 868MHz
- sku_code: lpyKaQPegR3GKgKtQe-04
  attributes:
    Style: ELRS 2.4G (Japan MIC Version)
sources:
- type: official
  url: https://betafpv.com/products/elrs-nano-tx-module
images: []
tags:
- Discontinued
- sale
- tx
---

# BETAFPV ELRS Nano TX Module

## 产品介绍

BETAFPV Nano RF TX module is based on the ExpressLRS project, an open-source RC link for RC applications. ExpressLRS aims to achieve the best possible link performance in both speeds, latency, and range. This makes ExpressLRS one of the fastest RC links available while still offering long-range performance.

A ton of ExpressLRS items are available now!

### Specification

- Packet refresh rate: 25Hz/50Hz/100Hz/200Hz (915MHz/868MHz)
25Hz/50Hz/150Hz/250Hz/500Hz (2.4GHz)

- RF output power: 100mW/250mW/500mW

- RF output power: 0.3mW/Mhz 20mW MAX (Japan MIC version)

- Frequency bands (Nano RF Module 2.4G version): 2.4GHz ISM

- Frequency bands (Nano RF Module 915MHz/868MHz version): 915MHz FCC/868MHz EU

- Input voltage: 5V~12V

- USB port: Type-C

### Diagram

BETAFPV Nano RF module is compatible with the radio transmitter which has the nano module bay (AKA lite module bay, e.g. Frsky Taranis X-Lite, Frsky Taranis X9D Lite, TBS Tango 2).

Note: Please assemble the antenna before power on. Otherwise, the PA chip in the Nano TX module will be damaged permanently.

### Upgrade the Firmware

The stock firmware of the Nano receiver and TX module manufactured by our company is ELRS 3.3.0.;
ELRS Innovative team officially released the first major version V1.0.0 on 17th July. It has some updates :

- 2.4G Nano TX Module supports 500Hz refresh rate;

- Short press the button on the Nano module 3 times to get into the binding status.

High recommend upgrading the TX modules and receivers' to the first major version V3.3.0. Also, pilots could check this Github page for the newest released version if possible.

Note:

1. TX module and receiver have to be in the same ELRS version, otherwise, the binding will fail.

2. TX module does NOT support upgrade via WiFi. Please use the ExpressLRS Configurator to upgrade the firmware.

Now Nano TX module from Jan 2022 supports upgrade via WIFI. For orders before Jan 2022, please contact us at email support@betafpv.com if you have any questions or problems.

User manual of How to Flash Firmware of ELRS RX/TX.

Note: Now the firmware version of it manufactured by our company is ELRS 3.3.0. Click to download the firmware of the ELRS Nano TX Module(V3.3.0 Version).

### Know More About ExpressLRS

ExpressLRS is an open-source RC link for RC applications. Everyone could find this project on Github or join the discussion in Facebook Group.

ExpressLRS is based on Semtech Lora SX127x or SX1280 hardware for RX and TX respectively. it aims to achieve the best possible link performance in both speeds, latency, and range. At 900 MHz a maximum of 200 Hz packet rate is supported. At 2.4 GHz a blistering 500Hz is currently supported with a custom OpenTX build. This makes ExpressLRS one of the fastest RC links available while still offering long-range performance.

More and more vendors start to support the ExpressLRS radio protocol in different parts, like radio transmitter with ELRS in stock, drone with built-in ELRS receiver, ELRS TX module for JR bay, or Nano bay. BETAFPV team take part in this project and provide a series of ExpressLRS components.

### Basic Configuration

ExpressLRS uses the Crossfire serial protocol (AKA CRSF protocol) to communicate between the radio transmitter and the Nano TX module. So make sure your radio transmitter supports the CRSF serial protocol. We use the radio transmitter with the OpenTX system to show how to set up the CRSF protocol and LUA script. To set this up, in the OpenTX system, enter into model settings, and on the "MODEL SETUP" tab, turn off the "Internal RF". Next, enable "External RF" and select "CRSF" as the protocol.

ExpressLRS use the OpenTX LUA script to control the TX module, like bind or setup. With the LUA script, pilots could check, and set up some configurations of the Nano RF TX module. For more details, please check the Support Page.

- Save the ELRS.lua script files onto the radio transmitter's SD Card in the Scripts/Tools folder;

- Long press the "SYS" button (for RadioMaster T16 or similar radios) or the "Menu" button (for Frsky Taranis X9D or similar radios) to access the Tools Menu where you can find ELRS script ready to run with only one click;

- The below image show, the LUA script run successfully;

### Bind & Output Power

Nano TX module could enter binding status via ELRS. Lua script, as described in the "LUA Script" chapter. Besides, a short press button on the module could also enter binding status.

Note: The LED will NOT flash when entering binding status. The module will exit from binding status 5 seconds later auto. Short and consecutive press 3 times to bind.

Nano RF TX module could switch the output power via ELRS. Lua script, as described in the "LUA Script" chapter. Besides, long-press the button on the module could switch the output power.

The RF TX module output power and LED indication as shown below.

### FAQ

BETAFPV ELRS Nano TX module user manual download.

How to flash the firmware of ExpressLRS TX/RX.

ELRS Nano TX Module conforms to the technical standards regulated by the Ministry of Internal Affairs and Communications (MIC) of Japan. Please view the certificate here.

### Package

- 1 * BETAFPV ELRS Nano TX module

- 1 * BETAFPV Moxon antenna

- 1 * Nano TX module user manual

Note: The Moxon antenna black or white will be shipped randomly.

usechatgpt init success

## 技术参数

| LED Color | RF output power |
|---|---|
| Blue | 100mW |
| Purple | 250mW |
| Red | 500mW |

## 官方资料

https://betafpv.com/products/elrs-nano-tx-module
