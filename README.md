Android Debug Bridge Plus is a command line that lets you use more ADB commands!

## Android Debug Bridge vs. Android ADB Plus

### Android ADB
ADB supports only some commands. Most commands start with `adb`.


### Android ADB ***+***
ADB Plus supports settings. It includes an error tracker, all commands starting with `android` (added ones start with `adbplus`), and more commands are added. It can also remove bloatware from the device.

## Something not possible in ADB

This only activates in ADB+, and not in ADB:
```
android app uninstall com.android.chrome
adbplus app open com.android.vending
```

## *IMPORTANT!!*
**I am not responsible for any damages to your Android.** Android ADB Plus may include destructive commands, for example `adbplus system resetsettings` or `adbplus sourcecode hack`. Use the `about-adb-plus important` command for more info.
