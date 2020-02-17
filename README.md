# gcc-arm-none-eabi-archive

TL;DR: Files are in [Releases](https://github.com/synthetos/gcc-arm-none-eabi-archive/releases)

This serves to archive the ARM GCC for bare-metal Cortex-M and Cortext-R, or as ARM calls it the [GNU Arm Embedded Toolchain](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm), built by them (when available) or us.

When we build it we use their source package and build instructions, changing as little as possible, to get the binaries for the build target only (IOW, we don't cross-compile for Windows from Raspberry Pi for the `armv7l` target).

# Download the files

The files are in the [Releases](https://github.com/synthetos/gcc-arm-none-eabi-archive/releases) area of this repo [GitHub -> synthetos/gcc-arm-none-eabi-archive](https://github.com/synthetos/gcc-arm-none-eabi-archive).

The original files can be found [here](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads) on ARM's web site. Note that in a few cases (currently `armv7l` target only) they don't provide pre-built binaries, and we've built them from the src download provided by ARM.

# Support, etc.

These files are provided AS-IS, and are simply copies of what are provided by ARM. This, in order to report a problem with the software, please report bugs though [their system](https://bugs.launchpad.net/gcc-arm-embedded/).

If you find a file missing, misnamed, or inaccurately described, then please [open an issue on this repo](https://github.com/synthetos/gcc-arm-none-eabi-archive/issues).



