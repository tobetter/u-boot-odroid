u-boot-odroid
=============

This package contains the binaries of u-boot in order to boot ODROID hardware designed with Samsung's SoC Exynos4. It must boot with the feature TrustZone is enabled, and this is also required to sign the binaries with specific security key.  Since these process is secured, u-boot is not able to modified or distributed by anyone uncertified. Prebuilt binaries are only able to be distributed.

There are four files in the package, will be installed into /boot directory and burned into your boot device such as SDCARD or eMMC.
    * BL1.bin
    * BL2.bin
    * TZSW.bin
    * u-boot.bin
