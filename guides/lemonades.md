 ```
Device name: Oneplus 9r 
Device codename: Lemonades
Device maintainer: Tanuj Dhama
```

# Method:

flashing-for-beginners:

How to install Custom rom [Beginners Friendly]

1. You must on latest OxygenOS depends on your region.
2. Install locally the same OTA zip to flash it both slot A/B.
3. Unlock your bootloader.
4. Go to Fastboot Mode, then flash  Recovery in CMD "Note you must be in latest google platform-tools".
5. In the path where is the recovery.img and rom package zip:
Type in cmd
fastboot devices
fastboot flash recovery recovery.img
6. In fast boot click volume down twice to select recovery mode, then select by clicking power button.
7. In  Recovery do a "Factory Reset/FormatData", then go back.
8. Flash the rom zip package zip via Update via ADB.
9. Click Update via ADB in recovery,
Open cmd where the rom zip file is present,
Type this in cmd:
adb devices
adb sideload <rom.zip>
Then wait until it finish the,
1/2
2/2
10. Go back to recovery then do a factory reset/format data, then reboot and enjoy!

If you want to root:
Go to recovery
Update via adb, then sideload the Magisk-v24.0.zip

If you want to preserve your root in the next OTA updates.
Use the same thing you used to preserve like in OxygenOS.

Done very simple as that.

# Downloads:

* ROM: [Download](https://sourceforge.net/projects/pixelstar/files/lemonades/Releases/)
* Recovery: [Download](https://t.me/lemonadescustombuilds/1310)
* Firmware: [Download](https://github.com/Wishmasterflo/Firmware_flasher)

## Note:

* Always clean flash/wipe data if you are coming from any other ROM or if you are coming from stock.
* Check the changelog before flashing.
