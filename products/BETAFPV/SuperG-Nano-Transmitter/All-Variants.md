---
product_id: Wao6KCKUnSBucT53dH
brand: BETAFPV
model: SuperG Nano Transmitter
variant: All Variants
source_url: https://betafpv.com/products/superg-nano-transmitter
source_platform: brand
collected_at: '2026-11-09T18:36:24+08:00'
status: unverified
category: Module
collected_by: workbuddy
confidence: 0.6
specifications:
  Max RF Power: Dual-1000mW
  RF Chip: Dual SX128x
  Antenna Mode: Gemini
  Cooling System: Supported
  Backpack: Supported
  External Power Supply: Supported 7-13V
skus:
- sku_code: Wao6KCKUnSBucT53dH-01
  attributes:
    Color: Black
- sku_code: Wao6KCKUnSBucT53dH-02
  attributes:
    Color: Red
- sku_code: Wao6KCKUnSBucT53dH-03
  attributes:
    Color: Grey
sources:
- type: official
  url: https://betafpv.com/products/superg-nano-transmitter
images: []
tags:
- elrs
- module
- tx
---

# BETAFPV SuperG Nano Transmitter

## 产品介绍

Based on ELRS V3.3 and collaborated with ELRS developer team, the First Ever Gemini Dual-Frequency Diversity Transmitter comes out! At present, SuperG Nano Transmitter can be fully activated to achieve the best link quality ever combined with diversity rx such as SuperD receiver or SuperP receiver. With dual 1W transmit power, it excels in anti-interference performance and stability, making it the ideal solution for demanding applications like FPV racing, long-range flight, and professional photography.

###
Bullet Point

- Introducing the pioneering Gemini Dual-Frequency Diversity Transmitter, propelling ELRS into the era of dual-frequency capabilities.

- Dual 1W transmit power experienced amplified signal strength, expanded transmission distances, and a substantial increase in remote control range.

- In conjunction with existing true diversity receivers, activating the Gemini mode ensures unwavering signal stability even in the most intricate radio environments.

- Meticulously crafted from CNC aluminum alloy, the transmitter casing facilitates efficient thermal conductivity, complemented by an intelligently designed Heatsink system for optimal heat dissipation.

- Featuring 2 customizable buttons and 1 USB port, the transmitter accommodates external power sources, enabling steadfast long-range expeditions.

### Specification

- Item: BETAFPV SuperG Nano Transmitter Module | ELRS 2.4G

- Weight: 44.8g

- Color: Black, Red, Grey

- Antenna Connector: 2* RP-SMA

- RF Power: 25mw/50mW/100mW/250mW/500mW/1000mW

- Packet Rate: 50Hz/100Hz/150Hz/250Hz/333Hz/500Hz/D250/D500/F500/F1000

- Frequency Band: 2.4GHz ISM

- Backpack: support

- Input Voltage: 7V~13V DC

- Rated Current: 8V,1000mA@1000mW, 1:128, Gemini mode

- USB Port: Type-C

- Fan Voltage: 5V

- Default Firmware Version: ExpressLRS V3.3.0

- Target Name: BETAFPV SuperG Nano 2.4GHz TX

### Diagram

Below is the diagram for the SuperG Nano Transmitter.

Note: Please assemble the antenna before powering on. Otherwise, the PA chip in the SuperG Nano Transmitter will be damaged permanently.

The following is the comparison information of the 3 products SuperG Nano Transmitter, ELRS Nano TX Module and ELRS Micro TX Module. It shows the advancing updates and specifications more than ever.

### Know More About Diversity&Gemini

- Antenna Diversity mode, two antennas. Switch the two antennas regularly to read the RSSI value of the signal and determine which antenna to use to receive data.

- True Diversity mode, where both antennas receive data at the same frequency, and the antenna that receives the correct data first is used.

- Gemini mode, where two antennas simultaneously receive telemetry data with a frequency difference of 40MHz. They also transmit data simultaneously but at different frequencies. This means that you can receive the same data packets on different frequencies and antennas. This mode provides stable flight even in complex radio environments.

Among them, Gemini is the most advanced function yet of ExpressLRS - Gemini mode currently! It owns the most stable mode for receiving signals and offers higher resistance to interference and stability, making it suitable for various applications.

SuperG Nano Transmitter features Gemini mode. In a testing video by developer Jye Smith, it is shown that with a refresh rate of 1000Hz, the LQ value fluctuates between 90-100 when the true diversity receiver is in operation. However, after switching to Gemini mode, the LQ value stabilizes at 99-100. This demonstrates that ELRS goes to great lengths to ensure link stability.

### Combination with Diversity RX

Gemini mode is built upon the hardware foundation of true diversity receivers and requires a dual RF output high-frequency module. When used with Super series products, the advantages of Gemini mode can be fully utilized. And The effects of using the transmitter and receiver in various modes are as follows:

Using it together with True Diversity Receiver ensures a super stable yet strong radio link for pilots to fly in any environment that require extremely stable signals and low latency. Including long-range flights, multiplayer flights, and FPV racing. It gives pilots a robust and aggressive flight experience.

### Dual 1W Output Power

The SuperG Nano Transmitter with Dual-active Antennas@Dual Frequencies, each boasting a powerful 1W transmission power. Experience stronger signals, longer transmission distances, and enhanced remote control range.

### Cooling System Iteration

The casing part is made of CNC aluminum alloy with an anodized surface for durability. It efficiently dissipates heat, thanks to its optimized internal airflow and high-speed fan with copper heat fins. Fly with confidence and enjoy reliable performance every time.

### Combination with Most Radio TX

The SuperG Nano Transmitter could be configured via LUA script. EdgeTX and OpenTX radio transmitter that supports CRSF could be used easily. It available for popular Nano interface TX when used with Micro-Nano Module Adapter including Radiomaster TX16, Boxer, Zorro. Jumper T16, T20, T Pro. Frsky QX7, X9, X Lite.

Note: LiteRadio 3 Pro Radio Transmitter cannot support dual transmitter power above 100mW due to power supply issues.

### Express Yourself in Vibrant Colors

SuperG Nano Transmitter is a cutting-edge device that offers a distinct and personalized flair, with a range of three vibrant color options including red, grey, and black. The combination of its sleek design, superior functionality, and colorful choices perfectly caters to those who seek elevate style and performance.

### ELRS Series

The ExpressLRS Series expands its lineup with the addition of SuperG Nano Transmitter. To achieve exceptional link quality, pair the Gemini TX with Super series diversity receivers. BETAFPV takes the flying experience to new heights by introducing ELRS links that offer long-range capabilities, low latency, and high refresh rates in a radio control system.

### Basic Configuration

SuperG Nano Transmitter is designed to receive signals using the Crossfire Serial Data Protocol (CRSF). Therefore, the interface of the transmitter's high-frequency module needs to support CRSF signal output. Taking the EdgeTX transmitter system as an example, we will explain how to configure the transmitter to output CRSF signals and control the transmitter using Lua scripts.

In the EdgeTX system, navigate to MODEL SEL and enter the SETUP menu. Disable Internal RF (set to OFF), enable External RF, and set the Output Mode to CRSF, as shown in the picture below.

Lua scripting is a lightweight and compact scripting language that can be embedded in the transmitter for convenient access to and modification of the transmitter's configuration.

- Download the elrsV3.lua script from the BETAFPV Support Center or ExpressLRS Configurator.

- Copy the official Lua script, elrsV3.lua, to the SD card of the transmitter, under the path Scripts/Tools.

- On the EdgeTX system, long-press the SYS button or MENU button to access the SD-HC CARD menu.

- In this menu, select the elrsV3.Lua script and run it.

- If the Lua script runs successfully, the interface will appear as shown in the illustration below.

### Custom Buttons

SuperG Nano Transmitter reserves 2 buttons that can be customized by users. Here are the specific steps to operate:

- Enable the transmitter's WiFi or power it on and wait for 60 seconds to enter WiFi mode using LUA programming.

- The RGB indicator light will slowly flash in green, indicating that the transmitter has automatically enabled WiFi (WiFi name: ExpressLRS TX, WiFi password: expresslrs).

- Connect your smartphone or computer to the WiFi network and open a web browser. Enter http://10.0.0.1 to access the custom button settings page.

- In the corresponding button's Action column, select the desired custom function. Then, choose the button type and the number of presses or duration in the Press and Count columns. Click SAVE to complete the settings.

###

Currently, there are 6 available functions that can be assigned to shortcut buttons. There are 2 ways to use the buttons: long-press and short-press. The duration of a long press can be customized, while the number of presses for a short press can also be customized.

The following are the 6 functions that can be set:

The pictures below show the functionality of the transmitter in its factory default settings. (The left button is Button1 and the right button is Button2).

Note: This transmitter hardware does not support button RGB lights.

### Bind & External Power Supply

The SuperG Nano Transmitter utilizes the default firmware, which employs the ExpressLRS V3.3.0 official protocol without a Binding Phrase. Consequently, the binding receiver should also be equipped with firmware V3.0.0 or higher and have no Binding Phrase set. For optimal performance, it is recommended to position the transmitter's two antennas as far apart as possible.

- Put the receiver in a bound state and wait for connection.

- Click the "Bind" in the Lua script or the set custom button to enter the binding mode.

- If the Indicator has turned solid, it indicates that the device has been bound successfully.

Note: If the firmware of the TX is reflashed and the Binding Phrase is configured, you cannot enter the Binding state through the above method. Please set the RX to the same frequency Binding Phrase, and the TX and RX can be connected automatically.

When the dual transmit power exceeds 500mW, the SuperG Nano Transmitter exhibits relatively high power consumption, leading to a reduced battery life. To prolong the transmitter's usage time, it is advisable to utilize an external battery as a power source.

- The power consumption of the transmitter is not only related to the transmit power but also to the telemetry ratio. When using high power of 500mW and above, the return ratio can be set higher to reduce power consumption and extend use time.

- For example, in Gemini mode, the power consumption of setting the return ratio to 1:128 is 1000mA, while the power consumption of setting the return ratio to 1:2 is only half of 1:128.

Note: When the voltage of the radio transmitter battery or external battery is lower than 7V (2S) or 10.5V (3S), please use the Gemini mode of 500mW and 1W carefully, otherwise the transmitter will enter the restart state due to insufficient power supply, resulting in disconnection out of control.

### FAQ

When establishing a link, it is not possible to enter the LUA script.

- The ELRS LUA script version is outdated and requires an upgrade to elrsV3.lua.

- The baud rate of the radio transmitter is set below 400K, and it should be adjusted to a value above that.

- If there is no option to modify the baud rate, it is necessary to update the radio transmitter firmware, ensuring that EdgeTX is at version V2.7.0 or newer.

If your radio transmitter is unable to use the F1000 Packet rate or prompts "Baud rate is too low".

- Reason: F1000 requires a baud rate higher than 400K, and the radio transmitter's baud rate is 400K by default.

- Solution: First update the baud rate (greater than 400K) setting in the Hardware from the Model Setup menu or System menu, then restart the radio transmitter to ensure the baud rate setting has been applied. Then change the Packet rate.

When the F1000 is turned on, the Packet rate between the radio transmitter and the SuperG Nano Transmitter is less than 1000.

- Reason: EdgeTX version problem

- Solution: The EdgeTX version needs to be upgraded to 2.8.0 or above. And the LiteRadio 3 Pro Radio Transmitter defaults to EdgeTX 2.8.0 and does not have this problem.

The SuperG Nano Transmitter's default firmware is ELRS V3.3.0, and users need to update the receiver to V3.0.0 or above to bind the frequency.

- Download the Instruction Manual for the SuperG Nano Transmitter

- Download the firmware for the SuperG Nano Transmitter

- Download the Backpack firmware for the SuperG Nano Transmitter

- Download the STL File for the SuperG Nano TX Insulated shell

-
Click to learn more about the ELRS Lua Scripts

### Package

- 1 * SuperG Nano Transmitter (Black/Red/Grey)

- 2 * 2.4G Glue Stick Antenna

- 1 * USB to Type-C Data Cable

- 1 * Type-C Male to XT30U Male Power Cable

- 1 * GH1.25 Male to FUTABA Male Signal Cable

- 1 * Micro-Nano Module Adapter (Standard Version)

- 1 * Double Side EVA Foam Tape

- 1 * Instruction Manual

- 1 * Service Card

## 技术参数

| SuperG Nano TX | Nano TX | Micro TX |  |
|---|---|---|---|
| Max RF Power | Dual-1000mW | 500mW | 500mW/1000mW |
| RF Chip | Dual SX128x | Single SX128x | Single SX128x |
| Antenna Mode | Gemini | Single | Single |
| Cooling System | Supported | Unsupported | Supported |
| Backpack | Supported | Unsupported | Supported |
| External Power Supply | Supported 7-13V | Unsupported | Supported 5-12V |

## 官方资料

https://betafpv.com/products/superg-nano-transmitter
