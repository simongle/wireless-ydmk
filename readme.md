# Split Wireless YDMK

## Usage
- Use only the USB-C Ports on the back of the keyboard.  The Mini USB ports are not connected to anything anymore.
- The left half of the board is the master side.  When using it wired, the left side should be plugged in.
    - The right USB-C port is only for charging the right half. 

- To use in wireless mode:
    - Select one of the 5 channels with `fn + alt + 1` (1,2,3,4,5 available)
    - Clear an existing paired client with `fn + alt + 6`  (if an existing client needs to be removed)
    - Pair with your device
    - You can pair 5 devices, one on each channel. You can switch between them with `fn + alt + {number}` (1,2,3,4,5)

    If the halves are not communicating, (happens after sitting a while, when a battery dies), press both the reset buttons on the back at the same time.


## Changing the Keymap
- For any info not explained below, see the ZMK documentation

- Fork or Download this repo
- Make any changes you want to the `zdmk.keymap` file. (see: [ZMK: Keymap Editing](https://zmk.dev/docs/features/keymaps))
- Push your changes.
- See [ZMk: Downloading Firmware](https://zmk.dev/docs/user-setup#download-the-archive)
- Connect the left half of the keyboard to your PC
- 'double-tap' the reset button on the back
- You should now be able to drag and drop the firmware file that you downloaded for the left half to the keyboard as if it was a flash drive.
- You may need to repeat for the right half as well.  (using the right firmware)