# slipperypenguin Keymap for the KBD75 PCB

## Additional Notes
75% Keymap for KBD75 with default ANSI layout + default layer switching for Windows and Mac "modes" + custom Fn layers for each mode. Handy flash guide [here](https://github.com/dvdizon/kbd75-qmk-guide/blob/master/README.md)

### Windows Mode
![Edulpn Keymap for the KBD75 PCB Windows Mode](https://imgur.com/doI46vP.png)

### Mac Mode
![Edulpn Keymap for the KBD75 PCB Mac Mode](https://i.imgur.com/t7oTjjc.png)

## Build
To build the default keymap, simply run `make kbd75/rev2:slipperypenguin`.

- - -

# Steps
1. Compile the keymap
  1. `cd qmk_firmware`
  2. `$ make kbdfans/kbd75/rev2:slipperypenguin`
  3. hex file created in root project folder
2. Open up QMK_TOOLBOX
3. Set keyboard to "Bootloader" mode with `FN + ESC` (while in Mac layer)
4. Make sure the dfu keyboard is recognized by QMK Toolbox
5. point to the local hex file to flash and flash.
6. DO NOT UNPLUG WHILE FLASHING
