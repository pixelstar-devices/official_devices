```
Devuce: Redmi Note 10 5G/Poco M3 Pro 5G
Device code name: camellia/camellian
Device maintainer: Noah
```

# Method:

How to flash ROM:
Make sure your either on MIUI 13+
Anything below causes it not to boot.

1. Download the boot.img and ROM
the boot.img is recovery
2. Install ROM's recovery using :
fastboot flash boot boot.img
3. Boot into it using power + volume up button
In pixelstar adb sideload must be enabled in the apply update section.
4. On your PC with the downloaded ROM, type in the terminal: adb sideload ROM.zip
5. Flash #latest_fw (optional)
6. Wipe data/factory reset
7. Reboot and enjoy

# Downloads:

* ROM: [Download](https://sourceforge.net/projects/pixelstar/files/camellia/Releases/PixelStar-Tiramisu-camellia-13.0-20230924-0939-OFFICIAL.zip/download)
* Recovery: [Download](https://sourceforge.net/projects/pixelstar/files/camellia/Releases/boot.img/download)
* Firmware: [Download](https://xiaomifirmwareupdater.com/firmware/camellian/)

## Note:

* Always clean flash/wipe data if you are coming from any other ROM or if you are coming from stock.
* Check the changelog before flashing.
* Flashing latest_fw is recommended.
