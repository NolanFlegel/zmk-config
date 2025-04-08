## ZMK config for 6x3 Cornish-Zen split keyboard

[ZMK](https://zmk.dev/)
[Corne-ish Zen](https://lowprokb.ca/pages/corne-ish-zen-support)

## Current Layout

## Flashing Firmware

To locate your firmware files...

Navigate to the "Actions" tab, Select the desired workflow run in the centre area of the page.
After clicking the desired workflow run, locate the "Artifacts" section at the bottom of the page. This section contains the results of the build, in a file called "firmware.zip".
Download the firmware zip archive and extract the two .uf2 files. They are named according to which side they need to be flashed to.
Flash the firmware to your keyboard by double-clicking the reset button to put the it in bootloader mode. A window should pop up showing the contents of the storage on the keyboard. Drag and drop the correct .uf2 file into the window. When the upload is complete the window will close and the keyboard will exit bootloader mode.
If only the keymap file has changed, then only flash the left side firmware to the left side.
If the conf file was changed, flash both sides their respective files.

The keyboard is now ready to use.