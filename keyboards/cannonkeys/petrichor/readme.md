# Petrichor PCB

Petrichor PCB from CannonKeys for the AKB Petrichor keyboard
(This firmware is used for both the hotswap and solderable variant)

* Keyboard Maintainer: [Andrew Kannan](https://github.com/awkannan)
* Hardware Supported: RP2040
* Hardware Availability: [CannonKeys](https://cannonkeys.com)


Make example for this keyboard (after setting up your build environment):

    make cannonkeys/petrichor:default
    
Flashing example for this keyboard:

    make cannonkeys/petrichor:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 4 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Hold the "BOOTSEL" button on the back of the PCB and briefly press the "REBOOT" button on the back of the PCB.
* **Top side reboot pads**: Bridge the reboot pads on the top of the PCB with a pair of tweezers twice in a row, quickly.
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
