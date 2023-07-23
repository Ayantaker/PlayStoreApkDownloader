# PlayStoreApkDownloader
Automation script to download and export play store APKs using a phone or emulator
Useful if you want to get bunch of play store APKs out for any purposes.

## How to use
- Point `APK_PACKAGE_NAME_LIST` variable in the script to the list with apk package names (ex : com.facebook.katana) in new lines
- Connect phone or emulator via adb
- Run the script. The script also caches the apks at `CACHE_DIR`. Helps if you are running it for lots of apks and you need to rerun the script.
