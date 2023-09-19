# Bluetooth-Microphone
## Abstract
The Bluetooth Microphone Device for Enhanced Wireless Communication project aimed at developing a cutting-edge wireless microphone system that utilizes Bluetooth technology to enable seamless and high-quality audio communication. The primary objective of this project is to design a versatile, user-friendly, and reliable microphone device, eliminating the constraints of wired connections and facilitating efficient communication across various applications. The proposed Bluetooth microphone device will be equipped with advanced features, including low-latency audio transmission, noise cancellation, and robust connectivity. It will be compatible with a wide range of devices, such as smartphones, tablets, laptops, and Bluetooth-enabled professional audio equipment. This will make it suitable for diverse use cases, such as public speaking, live performances, virtual meetings, and mobile vlogging.

## Product Specifications
* Bluetooth Technology: The device will integrate the latest Bluetooth protocols, ensuring stable and secure connections over short distances. It will support Bluetooth versions with low energy consumption to optimize battery life.
* High-Quality Audio Processing: The microphone will feature state-of-the-art audio processing algorithms to deliver crisp, clear, and noise-free sound reproduction. Adaptive noise cancellation will enable users to communicate effectively even in noisy environments.
* High-fidelity wireless audio with support for 24-bit/96 kHz audio formats.
* Advanced Audio Processing Wireless Connectivity: Voice processing such as Wide-Band (WB) speech, Acoustic Echo Cancellation (AEC) and Noise Reduction (NR).
* Bluetooth 5.0 certified dual mode audio module that offers high-quality wireless audio.
* User-Friendly: The device will be designed with a user-friendly interface, allowing quick pairing and intuitive controls muting functions.
* Rechargeable Battery: Battery can be recharged using micro-USB cable with mobile phone adapters.
* Long Battery Life: Emphasis will be placed on power efficiency to maximize the device’s battery life, making it suitable for extended use without frequent recharging. (Battery Capacity = 3200mAh)
* Compact and Ergonomic Design: The microphone will boast a sleek and lightweight design, making it portable and comfortable to use for prolonged periods.

## Selection of components
* BM83SM1
* Microphone – 4 mmx1.5mm, electret condenser, noise cancelling, solder pads, 1 V-DC
* LED – Green
* Switch
* Resistors 1kΩ
* Capacitors 0.1uF

## About BM83SM1 Chipset
The BM83SM1 is a Bluetooth module manufactured by Microchip Technology Inc. The BM83SM1 is part of the BM83 series of Bluetooth audio modules, which are designed for implementing Bluetooth audio solutions in various applications. The BM83SM1 module is typically used in applications like wireless speakers, headphones, and other audio devices where Bluetooth connectivity is required for audio streaming and control.
These modules are pre-certified to comply with various international standards, making it easier for manufacturers to integrate them into their products without the need for additional Bluetooth certifications.

## Pinout Diagram
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/e4363269-d9c1-4cc1-9e1f-042af7f1ef8d)

## Pinout Description
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/2d4752c5-51dd-4c6e-b092-6fbe69b2a655)
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/470048b3-70e5-4ad2-872d-8b80890885ed)


## Specification

### Power Management Unit
The on-chip PMU integrates the battery (lithium-ion and lithium-polymer) charger, and voltage regulator. A power switch is used to switch over the power source between the battery (BAT IN) and an adapter (ADAP IN).
The battery charger supports various modes with features listed below:
– Charging control using current sensor
– User-programmable current regulation
– High accuracy voltage regulation
– Constant current and constant voltage modes
– Stop charging and re-charging modes
### Audio Codecs
It supports both SBC and AAC Bluetooth audio codecs.
16-bit/24-bit I2S Digital Audio: – 8 kHz, 16 kHz, 44.1 kHz and 48 kHz sampling frequency for SBC and AAC.
16-bit Audio Stereo Analog-to-Digital Converter (ADC) with SNR 90 dB.
SBC and AAC are the two common codecs that you’ll find support for on most Bluetooth earphones. They’re also called lossy codecs because they significantly compress the data, with the goal being stability and speed over audio quality.
### Bluetooth 5.0 certified dual mode audio module that offers high-quality wireless audio.
### High-fidelity wireless audio with support for 24-bit/96 kHz audio formats.
### Two Modes of Operation
It can be operated in two modes either in embedded mode or in host mode. Host mode requires an external MCU to control the BM83SM1 module but in host mode it takes control of every peripheral device itself and controls everything as master device. In host mode, it does not require an external MCU.
Here we are oprating in Embedded Mode
### Voice processing such as Wide-Band (WB) speech, Acoustic Echo Cancellation
(AEC) and Noise Reduction (NR).
Here in this module we can adjust the voice band processing through firmware.
### Automatic Call answering option while connected with mobile phones
### Programmable Using Firmware via USB, UART or Over-The-Air

## How to programme
Download the software Here
https://www.microchip.com/en-us/product/bm83#Software

Connect the pins of the bottom PCB as below
* BM83’s 16 GND to USB’s Ground Brown Cable
* BM83’s 22 ADAP IN to USB’s 5V Red Cable
* BM83’s 36 DM to USB’s Data Minus White Cable
* BM83’s 37 DP to USB’s Data Plus Green Cable
Now connect to your PC, which you are using to program the module. Using the isUpdate tool which you can download from microchip.com, can upoload the firmware to the module.

![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/64d559af-b6cf-456a-872c-68b56cda941d)



## Reference
https://www.alldatasheet.com/datasheet-pdf/pdf/1176944/MICROCHIP/BM83.html
https://www.microchip.com/en-us/product/bm83#Software
https://www.mouser.com/datasheet/2/670/cmr_4015_44_sp-3011537.pdf

## Schematics
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/4b2c8879-a5f2-4669-aeb7-c2d236d4e2e6)



## PCB
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/83ec5907-0308-4c67-85a7-b08b0c99eedb)
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/b72ca2f7-68a2-48e9-b5e9-7f7a0c35d259)


## Enclosure
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/98695260-8f25-44d9-a43f-9800e4b1347f)

But due to printing cost, I have avoided some aesthetic curves and cut in the enclosure.
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/f74de2f3-94f2-4c12-b493-a24a9492666c)


## Product
![image](https://github.com/malanban/Bluetooth-Microphone/assets/131769448/242220ce-d7d9-4076-aa0b-28bc0dc4f6b4)

