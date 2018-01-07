# gpioutil

A command-line utility for using GPIO devices on Digilent Zynq boards.

This gpio utility uses [libgpio](https://github.com/mitchellorsucci/libgpio) and [libuio](https://github.com/mitchellorsucci/libuio) and expects that the gpio hardware (AXI GPIO) is set up as a generic uio device in the device tree.

Usage and device-info can be printed from the command line by typing `gpioutil -h` or `gpioutil --help` for usage and help.
Similarly, `gpioutil -d` or `gpioutil --device` will print information to the console about the type of AXI GPIO devices that are present on the system and set up as uio devices.




