# APSIS Keyboard

![ApsisKeyboard version 1](https://i.imgur.com/ *addsoon)

Apsis Aphelion/Perihelin is 6×4+5 keys column-staggered split keyboard greatly inspired by Sofle wich is based on Lily58, Corne and Helix keyboards.

More details about the keyboard and build guides can be found here: [future Keyboard Build Log and Guide](https://w9two.com)

* Keyboard Maintainer: [Lorn Jackson](https://w9two.com) 
* Hardware Supported: SofleKeyboard PCB, ProMicro  
* Hardware Availability: [PCB & Case Data](https://github.com/w9two/ApsisKeyboard)

## Firmware Revisions
- `apsis/rev1` is used for v1

Make example for this keyboard (after setting up your build environment):

    make apsis/rev1:default
    

Flashing example for this keyboard:

    make apsis/rev1:default:flash

Press reset button on he keyboard when asked.

Disconnect the first half, connect the second one and repeat the process.

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix
* **Physical reset button**: Briefly press the button near the TRRS connector. Quickly double-tap if you are using Pro Micro.
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
