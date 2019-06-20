# The Default Planck Layout, with some tweaks

## Build Firmware
syntax:
`make <my_keyboard>:<my_keymap>`

example:
`make planck/rev6:slipperypenguin/rev6`

- - -
## Steps
1. Compile the keymap
  1. `cd qmk_firmware`
  2. `$ make planck/rev6:slipperypenguin/rev6`
  3. hex file created in root project folder
2. Open up QMK_TOOLBOX
3. Set keyboard to "Bootloader" mode with `LOWER + RAISE + Q`
4. Make sure the dfu keyboard is recognized by QMK Toolbox
5. point to the local hex file to flash and flash.
6. DO NOT UNPLUG WHILE FLASHING
