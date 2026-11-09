---
product_id: oYfar0kJ7Mx9HfnoeA
brand: BETAFPV
model: Beta85X Whoop Quad for Naked Camera
variant: All Variants
source_url: https://betafpv.com/products/beta85x-whoop-quadcopter-for-naked-camera
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless Quad
collected_by: workbuddy
confidence: 0.6
specifications: {}
skus:
- sku_code: oYfar0kJ7Mx9HfnoeA-01
  attributes:
    Rx Version: TBS Crossfire
- sku_code: oYfar0kJ7Mx9HfnoeA-02
  attributes:
    Rx Version: Frsky FCC
- sku_code: oYfar0kJ7Mx9HfnoeA-03
  attributes:
    Rx Version: Frsky LBT
- sku_code: oYfar0kJ7Mx9HfnoeA-04
  attributes:
    Rx Version: DSMX
- sku_code: oYfar0kJ7Mx9HfnoeA-05
  attributes:
    Rx Version: Futaba
- sku_code: oYfar0kJ7Mx9HfnoeA-06
  attributes:
    Rx Version: PNP
sources:
- type: official
  url: https://betafpv.com/products/beta85x-whoop-quadcopter-for-naked-camera
images: []
tags:
- Discontinued
---

# BETAFPV Beta85X Whoop Quad for Naked Camera

## 产品介绍

Beta85X Whoop Quad for Naked Camera series is discontinued now, but you can try the new pusher style X-series drone - Beta85X V2.
Beta85X is packed with a BEC board, case and adjustable mount for the naked camera, so you can easily build a cinewhoop with the naked camera and greatly minimize the weight. It flies GREAT on a 450mah 4s battery. You can get a quick and stable flight for about 4 minutes. It's the best choice for those who are interested in building cinewhoop for FPV filming. We also provide the Beta95X for Naked Camera too.

Please note that the naked camera and the battery are not including. Click the link here to get the Beta85X FPV.

### Bullet Point

- Beta85X comes with a BEC board, which specially designed for GoPro HERO6. Integrated GoPro stock buttons and LED.

- Install customized EOS2 V2 camera and A01 VTX，you can enjoy the real-time FPV feds and low RF interference on flight.

- Pad is available for pilot to control the GoPro recording via the radio transmitter.

- With the pluggable connector, which is easier to connect with your flight controller for power supply and recording.

- Equipped with an adjustable camera mount of 0-50° for FPV film shooting. This will be the best choice for building the smallest cinewhoop drone that can carry a naked GoPro HERO6.

### Specification

- Item: Beta85X for Naked Camera

- Weight: 67.77g (without GoPro HERO or battery)

- F4 AIO Brushless FC 12A V2 (BLHeli_S)

- Frame: Beta85X Frame V2

- Motors: 1105 5000KV Brushless motor

-
Props: 2" 4-Blades Props

- Receiver Option: Frsky XM+ / TBS Crossfire

- Camera: Betafpv EOS V2 Camera

- Recommended battery: 450mAh 4s 75C battery (Not including)

### 85X Cinewhoop with GoPro

In recent months, more and more pilots are interested in the super small, lightweight and powerful cinewhoop. Pilots like Richárd Papp and Tommy Tibajia started their cinewhoop project. Based on the stable and insane power system of Beta85X, Tommy built his Umma85 and keep sharing all his ideas in the group. If you wanna know more about cinewhoop, feel free to join us on Facebook.
>> NAKED Cinewhoop Community

For providing a great combo for FPV community, we design a BEC board which is for the naked GoPro HERO6 perfectly. With the carbon fiber case and pluggable connector, it is easier to plug in and out. Meanwhile, we designed the adjustable camera mount of 0-50°, it can be used for the different flying modes of insane flying or slowing flying.

###

### The idea of Naked Camera

Based on the discussion of the cinewhoop, we designed a BEC board and a fitting case for Naked GoPro HERO6/7 to make it as a whole GoPro Lite camera. With a pluggable connector and a lightweight of 29g, easier to install on your cinewhoop for FPV filming.

So what is the special of the BEC board? It is integrated with the 5V@2A BEC, the stock GoPro buttons, LED and remote recording, solving the problem of the unstable power supply and redundant FPC connect way. The current BEC board fits for GoPro HERO6 and GoPro HERO7 Black.

### How to Setup Remote Record

Pilot could use the switch on radio transmitter to start/stop record. Some more configuration needed.

For example, if you use F4 FC V2.0 in the drone, like the 95X whoop drone, the connection diagram is shown below. The yellow cable (FC B12 pin pad) is just for the remote record.

We use the Pinio function in Betaflight to control record. First, setup the Pinio function of the B12 pin in the FC board.

resource FLASH_CS 1 NONE
resource PINIO 1 B12
set pinio_box = 40,255,255,255
save

Next, map one of the switch channels in your radio transmitter to this Pinio (aka USER1). As shown below, we map the AUX4 channel in the radio transmitter to USER1 Pinio. The cursor in the orange zone means button released and white zone means pressed. So keep the cursor in the orange zone in default.

Third, check if the Pinio function works. Change the switch and make the cursor move from the orange zone to the white zone, and finally back to the orange zone. Now you could check the LED status to know if the record starts. Use the same process to stop recording.

If you use the 12A F4 AIO FC board, like the 85X whoop drone, you will use the LED_STRIP pin (aka A08 pin pad) for the Pinio function.

resource LED_STRIP 1 NONE
resource PINIO 1 A08
set pinio_box = 40,255,255,255
save

Know more about the Betaflight Pinio function.

###

### Parts of Naked Camera Series

We know some of the pilots might have a question about how to get the case for the naked camera or some might wanna grab the Naked Camera directly. Here we provide some more choices for your better installation.

- Beta95X for Naked Camera

- Beta85X for Naked Camera

- BEC Board for Naked Camera

- Case for Naked Camera

- Customized Naked Camera

### How to Disassemble GoPro HERO6/8 Black

Special thanks to JONAH BLAESER who provided the method of disassembling GoPro HERO6/8 Black. If you are interested, please check the link to know the specific steps to make your own naked GoPro.

GoPro HERO6 Black Disassembly Guide

We also provided the method of disassembling GoPro HERO8 Black. If you are interested, please check the link.

GoPro HERO8 Black Disassembly Guide

Note: Do this at your own risk. You will lose your GoPro’s warranty and you may end up bricking the camera if something goes wrong. This guide is not authorized by GoPro and your camera is not guaranteed to work afterward. BETAFPV will not be held responsible for this action.

### FAQ

- How to assemble the case with the GoPro camera

-
STL File for Customized Naked Camera

-
CLI Dump of Beta85X (Click here to find the details)

###

###

###

### Package

- 1 * Beta85X for Naked Camera

- 1 * BEC Board for Naked Camera

- 1 * Case for Naked Camera

- 1 * GH1.25 Power Cable (80mm 30AWG)

- 1 * Pack of Screws

*Please note that the Naked camera and the battery are not including.

## 技术参数

（来源页未提供规格表）

## 官方资料

https://betafpv.com/products/beta85x-whoop-quadcopter-for-naked-camera
