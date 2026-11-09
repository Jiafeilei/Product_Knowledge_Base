---
product_id: 5hglR8Qoq60XR6EerK
brand: BETAFPV
model: Pavo Series COB LED Strip
variant: All Variants
source_url: https://betafpv.com/products/pavo-series-cob-led-strip
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: LED Light
collected_by: workbuddy
confidence: 0.6
specifications:
  resource PINIO 1 A08: //Set the LED_STRIP pin (i.e., serial port A08) as PINIO function
  set pinio_box = 40,255,255,255: //Configure the parameters of the PINIO function
  save: //Save configuration
skus:
- sku_code: 5hglR8Qoq60XR6EerK-01
  attributes:
    Color: Green
    Length: 560mm
- sku_code: 5hglR8Qoq60XR6EerK-02
  attributes:
    Color: Green
    Length: 750mm
- sku_code: 5hglR8Qoq60XR6EerK-03
  attributes:
    Color: Ice Blue
    Length: 560mm
- sku_code: 5hglR8Qoq60XR6EerK-04
  attributes:
    Color: Ice Blue
    Length: 750mm
- sku_code: 5hglR8Qoq60XR6EerK-05
  attributes:
    Color: White
    Length: 560mm
- sku_code: 5hglR8Qoq60XR6EerK-06
  attributes:
    Color: White
    Length: 750mm
- sku_code: 5hglR8Qoq60XR6EerK-07
  attributes:
    Color: Red
    Length: 560mm
- sku_code: 5hglR8Qoq60XR6EerK-08
  attributes:
    Color: Red
    Length: 750mm
sources:
- type: official
  url: https://betafpv.com/products/pavo-series-cob-led-strip
images: []
tags:
- Discontinued
- led strip
---

# BETAFPV Pavo Series COB LED Strip

## 产品介绍

The Pavo Series COB LED Strip is a 5V-powered LED strip measuring 560/750mm*4 mm. It provides increased visibility and facilitates easy observation of the drone's flight by the pilots during nighttime or poorly lit conditions, which also enhances operational safety, It can be securely mounted on the frame whoop duct, adding unique lighting effects and a visually captivating appearance. Choose from a single color option of ice blue, white, green, or red, or even mix multiple colors to personalize and elevate your flying experience while ensuring safety.

### Specification

- Item: Pavo Series COB LED Strip

- Color: Ice Blue, White, Green, Red

- Length: 560mm/750mm

- Width: 4mm

- Supply Voltage: 5V

- Current: 450mA~600mA(560mm), 500mA~800mA(750mm)

- Control Signal: High and Low Logic Levels

- Applicable Drone: Pavo Pico, Pavo20, Pavo25 V2, Meteor85(560mm), Pavo35(750mm)

###

### Configuration

The Pavo Series COB LED Strip configuration instructions are as follows:

- Connect the flight controller to the Betaflight Configurator and switch to the CLI configuration interface.

- Enter "resource" in the CLI configuration interface to export the serial port configuration of the flight controller.

- Select the available port on the flight controller as the control port to control the COB LED Strip. The following takes the LED_STRIP port as an example to configure the PINIO function of the flight controller:

- Set the mapping relationship between the radio transmitter and the flight controller's PINIO function. In Betaflight Configuration, assign the PINIO function (USER1 in the diagram below) to the switch on the remote controller (taking AUX3 as an example).

Note: The appearance of the Ice Blue COB LED Strip is light yellow, while the Green strip is white, and the white strip is yellow.

### Package

- Item: Pavo Series COB LED Strip

- 1 * Pavo Series COB LED Strip

- 1 * 3-Pin Cable

## 技术参数

| resource LED_STRIP 1 NONE | //Release the serial port function of the LED_STRIP pin |
|---|---|
| resource PINIO 1 A08 | //Set the LED_STRIP pin (i.e., serial port A08) as PINIO function |
| set pinio_box = 40,255,255,255 | //Configure the parameters of the PINIO function |
| save | //Save configuration |

## 官方资料

https://betafpv.com/products/pavo-series-cob-led-strip
