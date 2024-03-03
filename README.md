# Save me a piece of that corne

## Description

- corne from beekeeb
- hotswap choc sockets
- kailh sunset orange switches
  The default zmk firmware this was shipped with is a basic layout provided by beekeeb and can be found [here](https://github.com/beekeeb/zmk-config-corne-with-niceview/tree/main).

## Flashing

Pushing a commit will trigger the github action to build and flash the firmware to the keyboard.
Once the action is complete, it is ready to be downloaded and flashed to the keyboard.
The firmware file will be in the artifacts section of the action. Click on the latest action and then click on the `build` job. The firmware file will be in the `Artifacts` section at the bottom of the page.
To flash the firmware to the keyboard, do this each side at a time:

- double press the reset button on one of the sides
- then connect the keyboard to the computer
- the keyboard will show up as a folder in the file explorer
- drag the corresponding side's firmware file to the keyboard folder

## Configuration

Uses ZMK firmware. Docs can be found [here](https://zmkfirmware.dev/docs/)

To view combos and special settings in a gui, use the [zmk-configurator](https://nickcoutsos.github.io/keymap-editor/).
Sign in with your github account and select the repository and branch you want to edit.

### Layers

I have 4 layers set up on this keyboard:

- Base
- Lower
- Raise
- Hyper (Lower + Raise)

Base layer is just letters.
Lower is numbers and arrow keys.
Raise is symbols.
Hyper (Lower then Raise) is used on mac to control karabiner-elements.
