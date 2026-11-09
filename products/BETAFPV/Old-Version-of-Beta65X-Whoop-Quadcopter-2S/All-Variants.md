---
product_id: VnAQLfJvjK0N8QVzct
brand: BETAFPV
model: Old Version of Beta65X Whoop Quadcopter (2S)
variant: All Variants
source_url: https://betafpv.com/products/oldversion-beta65x-whoop-quadcopter-2s
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Brushless Quad
collected_by: workbuddy
confidence: 0.6
specifications: {}
skus:
- sku_code: VnAQLfJvjK0N8QVzct-01
  attributes:
    Rx Version: Frsky FCC Version
- sku_code: VnAQLfJvjK0N8QVzct-02
  attributes:
    Rx Version: Frsky LBT Version
- sku_code: VnAQLfJvjK0N8QVzct-03
  attributes:
    Rx Version: DSMX
- sku_code: VnAQLfJvjK0N8QVzct-04
  attributes:
    Rx Version: Flysky
- sku_code: VnAQLfJvjK0N8QVzct-05
  attributes:
    Rx Version: Futaba
- sku_code: VnAQLfJvjK0N8QVzct-06
  attributes:
    Rx Version: PNP
sources:
- type: official
  url: https://betafpv.com/products/oldversion-beta65x-whoop-quadcopter-2s
images: []
tags:
- Discontinued
---

# BETAFPV Old Version of Beta65X Whoop Quadcopter (2S)

## 产品介绍

Beta65X series is out of stock now, but you can try the new pusher style X-series drone - Beta85X V2.

This is a new era for Whoop drones. 2S Whoop drone has the power to fly real acro, like a larger quad, but is still small enough, safe enough, and quiet enough to fly anywhere. Beta75X and Beta65X. X is for "eXtreme".

BETA65X Speed Test by Daniel Sugano

Detailed review about Beta65X by Daniel Sugano.

A detailed review of the Beta75X drone by Nate Payne on YT.

Another overview and flight video by  Brenden Guffin.

For more video about these 2S Whoop drone, please check here:

More Overview Videos

Have any questions about 2S Whoop drone, please join our group on Facebook:

2S POWER-WHOOP GROUP

Join the online discussion about 2S Whoop drones at RCGroups.com:

Beta65X   Beta75X

The big brother Beta75X is available too. Get a Beta75X here.

### Bullet Point

- Beta65X start a new era of 2S whoop drones. With a big improvement in power, you could fly real acro, like a larger quad, but is still small enough, safe enough, and quiet enough to fly anywhere.

- With the high performance STM32F405 processor FC boards and tuned Betaflight Ominibus 3.5.0 firmware, everyone could fly the Beta65X drone like a racing professor.

- Durable and light enough frame is customed for the Beta65X. A total weight of 26g give pilots a good balance of weight and nice punch on 2S battery.

- Whole drone no soldering or tinkering necessary. Customed lightest 0802 12000KV motors with cable connectors. Just plug and play.

- 2pcs 1S 300mAh Lipo HV batteries are recommended in default. So pilot could also use their whoop batteries.

### Specification

- Weight: 26g (without battery)

- Motors: 0802 12000KV with connector

- Props: 31mm 4-blades props, 1.0mm shaft hole

- Camera: Z02 AIO Camera 35 degree

- Receiver Option: Frsky XM / DSMX / Futaba S-FHSS / Flysky

- Batteries: 300mah 1S Lipo HV Batteries

FC SPECIFICATIONS

Find more details about this 2S F4 FC board  in another page.

- CPU: STM32F405

- Six-Axis: MPU6000

- Size: 26mm x 26mm, whoop mounting pattern

- Firmware version: Betaflight OMNIBUSF4SD (OBSD) 3.5.0

- OSD: Built-in BetaFlight OSD (STM32 controls OSD chip over SPI in DMA mode)

- Smart Audio port is available for radio control VTX

ESC SPECIFICATIONS

Find more details about this 2S ESC board in another page.

- Support BLheli/BLHELI_S suite Pass-through ready

- Support PPM, Oneshot125, Oneshot42, Multishot, Dshot150, Dshot300, Dshot600

- Input voltage: 2S-3S lipo

- Cotinue current: 12A

- Peak current: 18A

- Firmware: BLHELI_S

- Processor: SILABS EFM8BB21F16G

Z02 AIO Camera VTX

Find more details about this AIO Z02 camera VTX in another page. On the Beta65X, it is the customed version with VTX board and camera board split.

- Output power: 0mW, 25mW and 200mW (Adjustable)

- Smart Audio function is included for radio control

- Antenna: Dipole ANT

- Frequency: 5.8GHz 6 bands 48 channels, with Raceband: 5362~5945MHz

- TV System: NTSC

- Field of view: 100-120 degrees with 1/4 lens

### Props Out

The Beta65X drone also comes with "props out" in default. Why we need "props out" direction?

Default Betaflight props direction, quadcopter dips and "washes out" in hard corners. With reversed props or "props out", no more dipping even in hardest cornering.

Know more about "Props Out".

### Power Cable

There is only one choices for the Beta65X battery -- PH 2.0 option for you. The two 260mAh Lipo HV 1S batteries can be inserted into the slot in design, as seen below.

### Customized Z02

The AIO camera VTX on the Beta665X is a customized version of Z02. The VTX board and camera board are split and 35 degree camera mount for more fast flying. At the same time, it have all the other function of the Z02 camera, like output power switchable between 0mW, 25mW and 200mW. Smart audio is available for VTX remote control in default.

How to change the frequncy or output power via remont control, please check the manual Smart Audio.

Download the STL file for the camera mount.

How to fix your Z02 camera if the image is blurred or the lens is loose after crashes?

### FAQ

1. Update About the LED at the rear for Beta65X

The FC board is now upgraded to V1.2. It can support programable LED like WS2812 etc. But there's NO rear LED holder for Beta65X by default.

2. I am interested in connecting an HD camera and DVR, but I don't want to overload the circuit of 5V.

The 5V regulator on the FC board could handle 2A of load. So you could use it for HD camera or DVR board. More details, please check the FC board page.

3. Does this drone have current sensor?

This drone does NOT have a real current sensor. We use the virtual current meter in Betaflight. When properly calibrated, it can be accurate enough to be useful. Here is the pre-calibrated value out of the box.

set current_meter = VIRTUAL
set ibatv_scale = 90
set ibatv_offset = 29

4. How to connect the receiver to the 2S brushless FC?

Please don't forget to plug the battery when you try to connect the connector to the 2S brushless FC. Find out more details in our support page.

5. Cli Dump for different versions of the 2S Whoop are provided in our support page.

6.  For some reason whenever i turn off and turn back on the quad vtx resets to 25mw even if i save the setting.

The button and SmartAudio cannot be used at the same time. You can either change the vtx setting by button or SmartAudio.

If you only use the button, you can find SmartAudio on the Ports page and set it to Disabled.
If you only use the SmartAudio, you can find more details here to know how to do this.

7. ETA of my 2S whoop drones.

We know that you guys can't wait to get this little monster and want to know about the ETA. Check out the shipping information here.

8. How to set up smart audio vtx control? (Multirotor Guide gives you the most straightforward explanation)

### Package

- 1 * Beta65X BNF 2S Whoop Quadcopter

- 1 * Spare 31mm 4-blades props (2CW+2CCW)

- 2 * 300mAh 1S Lipo batteries (Not for PNP version)

- 1 * Spare Canopy

## 技术参数

（来源页未提供规格表）

## 官方资料

https://betafpv.com/products/oldversion-beta65x-whoop-quadcopter-2s
