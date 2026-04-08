# PinGo - Downloads

Collaborative shopping list app for Windows and Android.

## Latest Release - v1.0.0

### Windows
[Download ToDoo Setup 1.0.0.exe](https://github.com/timoCasti/PinGo-ToDoo-Release/releases/download/v1.0.0/ToDoo-Setup-1.0.0.exe) (378 MB)

**Requirements:** Windows 10/11

### Android
[Download ToDoo 1.0.0.aab](https://github.com/timoCasti/PinGo-ToDoo-Release/releases/download/v1.0.0/ToDoo-1.0.0.aab) (52.7 MB)

**Requirements:** Android 5.0+

**Note:** The `.aab` file is the Android App Bundle format. For direct installation on your device, you may need to convert it to APK or sideload it. For distribution, use Google Play Store.

## Installation

### Windows
1. Download the .exe file
2. Run the installer
3. Follow the setup wizard

### Android

**Option 1: Google Play Store (Recommended)**
- Upload the `.aab` file to Google Play Console for distribution

**Option 2: Direct Installation**
- The `.aab` format cannot be directly installed on devices
- If you need an `.apk` for direct installation, build using:
  ```
  cd android && ./gradlew assembleRelease
  ```
- Then install the generated `.apk` file by enabling "Install from unknown sources"

## Features
- Collaborative shopping lists
- Real-time sync with Supabase
- Works offline with local database
- Cross-platform: Windows, Android, Web
