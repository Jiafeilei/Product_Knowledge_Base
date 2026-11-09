---
product_id: OB16e44iG2SERKQDaB
brand: BETAFPV
model: SMO 360 Camera
variant: All Variants
source_url: https://betafpv.com/products/smo-360-camera
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Camera
collected_by: workbuddy
confidence: 0.6
specifications: {}
skus:
- sku_code: OB16e44iG2SERKQDaB-01
  attributes:
    Version: Default
sources:
- type: official
  url: https://betafpv.com/products/smo-360-camera
images: []
tags:
- Discontinued
---

# BETAFPV SMO 360 Camera

## 产品介绍

Meet the SMO 360 Camera - A high-quality ultralight action panoramic camera designed for your FPV Drones! Developed by BETAFPV using Insta360 technology, SMO 360 camera only weighs 55g and is perfectly fit for FPV drones. The distance between the 2 lenses is 40mm, giving more room to the drone height. Meanwhile, with the FlowState stabilization function, pilots can shoot panoramic video and get an ultra-smooth and stable video, which makes the SMO 360 camera the best choice for pilots in search of high-quality 360 videos with FPV drones!

Therefore, to better enjoy the SMO 360 camera, we highly recommend buying the Pavo 360 drone designed for this camera.

### Bullet Point

- SMO 360 Camera is perfectly suitable for the Pavo360 FPV Quadcopter, Pilots can capture airborne 360 views and hide the drone entirely from sight.

- SMO 360 camera is an ultralight panoramic camera that is specially designed for FPV drones. Developed by BETAFPV using Insta360 technology, it only weighs 55g and can be easily mounted on a variety of FPV drones.

- With SMO 360 camera's 5.7K 360-degree shots and FlowState stabilization function, pilots can shoot 5.7K 360-degree video with greater detail, smoother stabilization, and better dynamic range.

- Support using the radio transmitter to control SMO 360 camera on power on/off and start/stop recording remotely, making it more convenient to operate.

- The power supply range is 6V-27V, supporting 2-6S Lipo batteries. With the 4-pin pluggable connector, pilots can easily connect the SMO 360 with your flight controller for power supply and recording.

### Specification

- Item: SMO 360 Camera

- Weight: 55g

- Size: 40mm×49.6mm×52mm

- Power supply range: 6V-27V (2S-6S Li-Po battery)

- Lens aperture: F2.0

- 35mm equivalent focal length: 7.2mm

- Video resolution: 5760x2880@24/25/30fps, 3840x1920@30/50fps, 3008x1504@100fps

- Video format: insv (export through App or Studio)

- Video code: H.265

- Video mode: Standard, HDR, Timelapse

- Video maximum bit rate: 100Mbps

- Bluetooth: BLE4.0

- Wi-Fi: 5G (standard range approx. 10m)

- Micro SD card: UHS-I V30 speed class and above recommended, exFAT format (maximum storage capacity is 1TB)

- Operating environment: -20°C to 40°C (-4°F to 104°F)

- Recommend Accessories: SMO 4K Camera Cable Pigtail

### Designed For Pavo360 FPV Drone

SMO 360 is an ultralight action camera that is designed for mounting on the Pavo360 FPV drone. Weighing at just 55 grams, and it can be easily mounted and carried on Pavo360. Meanwhile, its "pusher-style" inverted frame maintains a low center of gravity and makes the drone easier to maneuver.

Note: Although the Pavo360 equips with landing gear that is designed for protecting the SMO 360 camera lens, further protection is necessary. Strongly recommend buying lens guard together.

### FPV Stabilization

SMO 360 is backed up with Insta360’s FlowState stabilization, which ensures the video is stable throughout the flight, no matter what maneuvers you attempt. This makes SMO 360 the perfect camera for capturing 360 videos while flying an FPV drone.

### Longer Distance Between 2 Lenses

Developed by BETAFPV using Insta360 technology, SMO 360 camera only weighs 55g and is perfectly fit for Pavo360 FPV drones. The distance between the 2 lenses is 40mm, giving more room to the drone height while the ONE R panoramic camera is 34mm. Meanwhile, The SMO 360 camera supports remote control of the camera's power on/off and start/stop of the video recording through the controller like SMO 4K Camera.

### Power Supply & TX Configuration

The camera comes with a 6V to 27V power connector that supports 2S to 6S LiPo FPV batteries. In the accessory kit, the red wire in the connecting wires is the power supply wire and needs to be soldered to the battery positive pad (VBat+); the black wire is the ground wire and needs to be soldered to the battery negative pad (GND); the white SH1.0 terminal should be plugged into the power socket of the camera. The power supply can be achieved after completing the above steps.

The SMO 360 camera supports remote control of the camera's power on/off and start/stop of the video recording through the controller. The yellow wire controls turning the video recording on/off and the blue wire controls turning the camera on/off.

Note: The remote recording and remote power cable are not soldered on FC board in the factory. Please solder it well before using these two functions.

Configure the PINIO function of TX1 pin through the following Betaflight commands.

resource SERIAL_TX 1 NONE //Turn off the serial port function of TX1 spindle
resource PINIO 2 A09 //Configure the TX1 pin (A09 pin) as the No. 2 PINIO
function
set pinio_box = 40,41,255,255 //Set PINIO function interval
save //Save configuration

The following diagram configures the PINIO function mapping relationship between the remote control and the flight control. In Betaflight Configuration, the PINIO function No. 2 (ie USER2 in the figure below) corresponds to the AUX5 channel of the remote control.

To activate or deactivate functions on the camera, you will need to move the switch from inactive (white area) to the active state (yellow area) and then back to the inactive state (white area).

Note: Your flight controller and radio controller switch configuration must match the setup of your equipment. Make sure you know what you are doing before configuring. If you do not use remote control function, cut or insulate the yellow and green wires separately and do not connect to any location.

### Mounting Instruction

The SMO 360 Camera is designed for Pavo360 quadcopter. Pilots can remove the top plate cover and directly install it on the drone. Meanwhile, we specially offer this SMO 4K Camera Cable Pigtail for pilots who want to modify more drones to carry an SMO 360 camera. The cable pigtail provides SMO 360 power input perfectly, no need for any more modification.

###

### FAQ

1. For more detailed info and instructions, kindly check the User Manual to download.

2. The SMO 360 comes without lens guard. We recommend buying lens guard together so it will protect your lens from scratches as well.

3. What exactly did BETAFPV & Insta360 collaboration contribute to the development of SMO 360?

SMO 360 is developed by BETAFPV using Insta360 technology. BETAFPV used Insta360’s image processing technology and modified the camera for mounting on an FPV. Insta360 integrated the Insta360 mobile app and desktop software with SMO 360, complete with Insta360’s proprietary FlowState stabilization algorithm and image stitching algorithm.

4. Is SMO 360 modified from Insta360 ONE R 360 Edition? What are the significant changes? Is it a new product line from ONE R?

SMO 360 is based on Insta360’s image processing and FlowState stabilization technology. The camera is stripped back to include just two fisheye lenses and a processing core, powered by an FPV battery. However, SMO 360 and ONE R 360 Edition are different products.
While SMO 360 is an ultralight action cam designed for mounting on an FPV, ONE R 360 Edition is an adaptive action camera designed for creative photographers and action sport lovers.

5. Who is the product for?

The SMO 360 was specially designed for FPV photographers. For years, DIY demons in the FPV community have been re-engineering old action cameras and making them more lightweight for FPVs. Now SMO 360 offers an out-of-the-box solution for FPV pilots who want to step up their FPV content without the hassle.

6. Who is responsible for repairing the camera in case of service?

If you encounter any issues please contact our technical support: support@betafpv.com

### Package

-
1 * SMO 360 Camera

-
2 * Power cord with SH1.0 terminal

-
1 * User Manual chg2

###

## 技术参数

（来源页未提供规格表）

## 官方资料

https://betafpv.com/products/smo-360-camera
