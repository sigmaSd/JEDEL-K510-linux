# JEDEL-K510-linux
Workaround for the brightness key in JEDEL k510 keyboard

## How TO
Make sure your keyboard is plugged in, than execute the script, thats it.

This works as a daemon so keep it running.

You'll have to reexecute it each reboot and each time u plug in your keyboard.

### Dependencies
- libinput
- [rg](https://github.com/BurntSushi/ripgrep) (min 0.10.0)
- [fd](https://github.com/sharkdp/fd)
- unbuffer (expect)
- showkey

### Issues
Caps lock key turns off brightness
