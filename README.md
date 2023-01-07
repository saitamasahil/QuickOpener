# QuickOpener

![Header Image](https://raw.githubusercontent.com/saitamasahil/QuickOpener/main/banner.jpg)

An add-on for Pixel Launcher running on Android 13 QPR2. This add-on enables a quick launch feature on pixel launcher's searchbar.

### Compatibility
This module is expected to work on ROMs which are based on fairly unmodified Android source code.
- Android 13 QPR2 AOSP-based ROMs
> Note: For now there are no custom roms available on Android 13 QPR2 update. Android 13 QPR2 is in beta testing & available for Google Pixel Devices as stock rom. So, this module will only work if you have a Google Pixel Device running latest Android 13 QPR2 Beta or if you're using a port rom of latest beta.

## Building from source
The pre-made magisk module zip isn't available for download. You will have to make module yourself.

### For Ubuntu, Debian, and other Linux distributions
- Clone the repo using git.
```sh
git clone https://github.com/saitamasahil/QuickOpener
```
- Navigate to the **QuickOpener** folder.
```sh
cd QuickOpener
```
- Run autobuild.sh.
```sh
bash autobuild.sh
```
- The required zip package install command is in the script itself. However, if you encounter any errors, you can install **zip** manually. On Ubuntu or Debian, Use the following command to do so."
```sh
sudo apt install zip
```

### For Termux
- Open Termux, copy & paste this command
```sh
pkg upgrade || true
pkg install -y git
rm -rf QuickOpener
git clone https://github.com/saitamasahil/QuickOpener
cd QuickOpener
bash autobuild.sh
termux-setup-storage
mv Quick\ Opener* /sdcard
echo "Your magisk module is available in Internal Storage"
```
- Please make sure to grant storage permissions, if Termux asks you to do so, you will get Magisk module in your internal storage.
- Use [Termux From F-Droid](https://f-droid.org/en/packages/com.termux/) to perform these tasks.
- If you get this warning "It appears that directory '~/storage' already exists.
This script is going to rebuild its structure from
scratch, wiping all dangling files. The actual storage
content IS NOT going to be deleted" then just do press "y". It won't do any harm to your device.
- The required zip package install command is in the script itself. However, if you encounter any errors, you can install **zip** manually. Use the following command to do so."
```sh
pkg install zip
```

### Installation
- Flash in magisk
- Reboot device
- Check for the feature. If the feature doesn't appear then force stop launcher.

## Contact us
[![TeamFiles Telegram](https://img.shields.io/badge/Telegram-TeamFiles-%2326A5E4?logo=Telegram)](https://telegram.me/filesfederation)

[![Modules Repository](https://img.shields.io/badge/Telegram-Modules%20Repository-%2326A5E4?logo=Telegram)](https://telegram.me/modulesrepo)

[![Support Group](https://img.shields.io/badge/Telegram-Support%20Group-%2326A5E4?logo=Telegram)](https://telegram.me/fileschat)