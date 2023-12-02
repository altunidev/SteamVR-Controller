# Hardware considerations

## Research and Development hardware

### Tracking

For making the BeatSaber sabers beat.

- Existing SteamVR trackers (i.e. HTC Vive Tracker 2.0, 3.0, Tundra Tracker, or eteeTracker)
- Custom Solution
    - [Tundra Tracker IO Expansion Board](https://tundra-labs.com/products/tundra-tracker-io-expansion-board)
    - [Tundra Tracker Developer Board](https://tundra-labs.com/products/tundra-tracker-developer-board)
    - Frankenstein modded [HTC Vive Controller (2018)](https://www.vive.com/us/accessory/controller2018/) ([Amazon link](https://www.amazon.com/HTC-Vive-Controller-pc/dp/B07QV3VLYJ), may find deals for about 50% off)
        > Another idea is to simply take an existing HTC Vive or Vive Pro controller, disassembling it, and re-wiring all triggers to work in a different form factor. But it's [$200](https://www.amazon.com/dp/B07QV3VLYJ) though... (Only looking at the 2018 Vive 2.0 Wand controllers as those are Base Station 2.0 and 1.0 compatible instead of just 1.0. My R&D setup is 2.0 stations only.)

## Controller Components

### Processor
The thinker-box.

- Arduino Pro Micro
- ESP32
- ESP8266
- nRF52840 (credit sctanf)
- nRF52832 (credit sctanf)
- TL448K6D-VR (Tundra Labs integrated processor)
    - Very extensive for many use-cases
    - Already designed for SteamVR pairing
    - ~$52 per unit, very expensive for simply just the microcontroller
    - Datasheet: https://cdn.shopify.com/s/files/1/0560/9455/6369/files/TL448K6D-VR_Datasheet_v1p1.pdf
        - Local PDF copy: [TL448K6D-VR_Datasheet_v1p1.pdf](assets/TL448K6D-VR_Datasheet_v1p1.pdf)
        > Only keeping on repo for the sake of documentation and data backups. Please reach out if there are concerns.


### Buttons
Useful for many activities, like button pushing!

- [Gulikit buttons](https://gulikit.com/productinfo/854180.html)
    - no capacitive touch sensing

### Joystick
Keep virtually active so you don't need to be physically active.

- [GuliKit Electromagnetic Joystick Module for Steam Deck](https://gulikit.com/productinfo/1026071.html)
    - capacitive touch sensing available
    - bulky form factor
- [Gulikit Switch Joycon joystick](https://gulikit.com/productinfo/945307.html)
    - no capacitive touch sensing
- [Zerone 3D Joystick Axis Analog Sensor Replacement Module](https://www.amazon.com/Joystick-Wireless-Controller-Replacement-Console/dp/B07SW2YJ8Z/)
    - no capacitive touch sensing
    - potentiometer sensor (no hall effect, prone to wear)
    - affordable option
    - Consider firmware-based stick drift calibration fixes: https://www.youtube.com/watch?v=L2uyeBfFYp8 (credit MuffinTastic)

### Power Management
A fancy way of saying "battery system".

- Standard AA batteries (hot swappable)
- Custom rechargable solution (make considerations with knowledge of current SlimeVR BMS hardware)
    - Li-Ion Pouch Cells
    - Charging boards

### Wire Harness
How things connect to each other.

- Fully modular wire-connected system (using either JST or DuPont connectors)
- Fully integrated soldered solution
- Some hybrid of the two
