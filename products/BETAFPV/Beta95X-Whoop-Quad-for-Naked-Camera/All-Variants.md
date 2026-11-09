---
product_id: jAJHG33mrKkZRlQnby
brand: BETAFPV
model: Beta95X Whoop Quad for Naked Camera
variant: All Variants
source_url: https://betafpv.com/products/beta95x-whoop-quadcopter-for-naked-camera
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless Quad
collected_by: workbuddy
confidence: 0.6
specifications: {}
skus:
- sku_code: jAJHG33mrKkZRlQnby-01
  attributes:
    Rx Version: TBS Crossfire
- sku_code: jAJHG33mrKkZRlQnby-02
  attributes:
    Rx Version: Frsky FCC
- sku_code: jAJHG33mrKkZRlQnby-03
  attributes:
    Rx Version: Frsky LBT
- sku_code: jAJHG33mrKkZRlQnby-04
  attributes:
    Rx Version: DSMX
- sku_code: jAJHG33mrKkZRlQnby-05
  attributes:
    Rx Version: Futaba
- sku_code: jAJHG33mrKkZRlQnby-06
  attributes:
    Rx Version: PNP
sources:
- type: official
  url: https://betafpv.com/products/beta95x-whoop-quadcopter-for-naked-camera
images: []
tags:
- Discontinued
---

# BETAFPV Beta95X Whoop Quad for Naked Camera

## 产品介绍

We are sorry to announce that the Beta95X for Naked Camera series is discontinued and will not be available for sales anymore. We recommend you buy its great alternative Beta95X V3 Whoop Quadcopter and Beta95X V3 HD Digital VTX.

Based on the Beta95X whoop platform, we designed a BEC board for Naked Camera, which can be used on the Beta95X for video shooting. The wheelbase is only 100mm and weighs about 86.4g without GoPro and battery. With 2.5" 3-blades propellers, 1106 motors and 16A BLHeli_32 ESC, it could do all the acrobatic motions smoothly, like dive and power loop. We also provide the Beta85X for Naked Camera too.

We BETAFPV have authorized BeverlyHillsAerials would be the exclusive distributor of Beta95X (For Naked Camera Version) in the USA territory, the dealer support and pricing would be provided by BeverlyHillsAerials

Please note that the naked camera and the battery are not including. Click here to link to the Beta95X (HD Digital VTX).

### Bullet Point

- This kit is the optimal choice for FPV filming, weighs about 85.2g without GoPro HERO and battery.

- Install with customized EOS2 V2 camera and A01 VTX，you can enjoy the real-time FPV feds and low RF interference on the flight.

- The pad is available for pilots to control the GoPro recording via the radio transmitter.

- Built with the high-performance STM32F051K66 processor FC boards and tuned BETAFPVF405(BEFH), faster input signals with lower latency and higher update rates are reachable, give you much more power.

- Equipped with an adjustable camera mount of 0-50° for FPV film shooting. This will be the best choice for building the smallest cinewhoop drone that can carry a naked GoPro HERO6.

### Specification

- Item: Beta95X for Naked Camera

- Weight: 85.2g (without GoPro HERO6 or battery)

- Wheelbase: 100mm

- F405 Flight Controller & 16A BLHeli_32 ESC V2.0

- Frame: Beta95X Frame

- Motors: 1106 4500KV with connector

- Props: Gemfan 2540 3-Blades Props

- Receiver Option: Frsky XM+ / TBS Crossfire

- Battery: 4S 450mAh Battery (Not including)

- Camera: Betafpv EOS V2 Camera

- Flight time: 4min - 5min with 450mAh 4s 75C battery (smooth flight in a windless environment)

### 95X Cinewhoop with GoPro

In recent months, more and more pilots are interested in the super small, lightweight, and powerful Cinewhoop. Pilots like Richárd Papp and Tommy Tibajia started their cinewhoop project on our Beta85X and Beta95X with GoPro or Insta360 for FPV filming. If you wanna know more about cinewhoop, feel free to join us on Facebook.
>> NAKED Cinewhoop Community

Based on the 95X Whoop platform, we design a BEC board for this FPV community which is for the naked GoPro. This whoop drone can carry on the GoPro lite camera and keep in 106g without battery. With a pluggable connector, make it easier to plug in and out.

Meanwhile, we designed a camera holder for Naked Camera, so you can install the Naked Camera directly and it is also anti-shake. With the adjustable camera mount of 0-50°, it can be used for the different flying modes of insane flying or slowing flying.

### The idea of Naked Camera

Based on the discussion of the cinewhoop, we designed a BEC board and a fitting case for Naked GoPro HERO6/7 to make it as a whole Naked Camera. With a pluggable connector and a lightweight of 29g, easier to install on your cinewhoop for FPV filming.

So what is the special of the BEC board? It is integrated with the 5V@2A BEC, the stock GoPro buttons, LED and remote recording, solving the problem of the unstable power supply and redundant FPC connect way. The current BEC board fits for GoPro HERO6 and GoPro HERO7 Black.

### How to Setup Remote Record

The pilot could use the switch on the radio transmitter to start/stop record. Some more configuration needed.

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

###

### Parts of Naked Camera Series

We know some of the pilots might have a question about how to get the case for the naked camera or some might wanna grab the naked Camera directly. Here we provide some more choices for your better installation.

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

###
FAQ

-
STL File for Naked Camera Series

- How to assemble the case with the Naked Camera

-
Cli Dump of Beta95X for Naked Camera (Click here to find the details)

###

###

###

###

###

### Package

- 1 * Beta95X for Naked Camera

- 1 * BEC Board for Naked Camera

- 1 * Case for Naked Camera

- 1 * GH1.25 Power Cable (80mm 30AWG)

- 1 * Pack of Screws

*Please note that the naked camera and the battery are not including.

## 技术参数

（来源页未提供规格表）

## 官方资料

https://betafpv.com/products/beta95x-whoop-quadcopter-for-naked-camera
