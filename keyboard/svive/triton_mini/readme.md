the agk 12 qk is comparable to  the isy igk 5000 bk or svive triton mini.

to flash this firmware, use sonix flasher (https://github.com/SonixQMK/sonix-flasher) set device to SN32F24x and qmk offset to 0x00. there is no jumploader required.


BEFORE FLASHING ENTER BOOTLOADER ON HFD

to do this, either enter other layer and press esc, or press reboot to bootloader hfd inside sonix, or short ground and boot pins on the board.


to flash qmk, click flash qmk and select compiled .bin file. to flash normaly, click revert to stock firmware and select compiled .bin file.
