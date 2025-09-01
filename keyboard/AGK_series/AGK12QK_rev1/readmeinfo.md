The AGK 12 QK is comparable to the ISY Igk 5000 BK or Svive Triton Mini.

To flash this firmware, use sonix flasher (https://github.com/SonixQMK/sonix-flasher) set device to SN32F24x and qmk offset to 0x00. there is no jumploader required.


# Bootloader

Enter the bootloader in 3 ways:

    Bootmagic reset: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard.
    Physical reset: Short the GND and BOOT pads on the PCB while connecting the keyboard. They are accessible if you remove the space keycap. See https://github.com/cederlys/svive-qmk for images and hints.
    Keycode in layout: Press the key mapped to QK_BOOT if it is available. In the default keymap, this is mapped to Fn+ESC.



to flash qmk, click flash qmk and select compiled .bin file. to flash normaly, click revert to stock firmware and select compiled .bin file.
