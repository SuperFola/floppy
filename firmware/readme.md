# Floppy

*The Floppy is an open source split keyboard based on the Sweep.*

* Keyboard Maintainer: [SuperFola](https://github.com/SuperFola)
* Hardware Supported: *Floppy + Liatris*
* Hardware Availability: [*Floppy Repository*](https://github.com/SuperFola/floppy)

Make example for this keyboard (after setting up your build environment):

    make floppy:default

Flashing example for this keyboard:

    make floppy:default:avrdude-split-right

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Entering the bootloader:

<!-- * **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard -->
* **Physical reset button**: Briefly press the small button on the inner side of the PCB - you may have pads you must short instead
<!-- * **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available -->
