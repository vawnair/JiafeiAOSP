# JiafeiAOSP
JiafeiAOSP is an Android Open Source Project based ROM.

## prerequisites

Get [adb](https://developer.android.com/studio/releases/platform-tools).

## Installation

Get [twrp](https://twrp.me) for your device

Boot into twrp 
```bash
adb reboot bootloader/fastboot
fastboot boot twrp.img
```

Navigate into Advanced => ADB Sideload, Wipe Dalvik and Cache, Then swipe to start sideload.

On your computer's console/command line, type:
```bash
adb sideload JiafeiAOSP.zip
```

Reboot to apply changes, now tada! 
You're good to go.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU](https://choosealicense.com/licenses/gpl-3.0/)
