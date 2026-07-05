# Steering ETS2 Controller

This repository hosts the compiled release files (Android APK & PC EXE) for the **Steering ETS2 Controller** project.

## Download the App

You can find the latest releases in the `releases/` directory:

- 📱 **Android App (APK):** [Download Latest APK](https://github.com/hmongcodequest/steering-ets2-controller/raw/main/releases/android/steering-ets2-v1.0.6.apk)
- 💻 **PC Server (EXE):** [Download Latest EXE](https://github.com/hmongcodequest/steering-ets2-controller/raw/main/releases/pc/VJoyServer-v1.0.7.exe)

## Folder Structure
- `releases/android/`: Contains the Android APK files.
- `releases/pc/`: Contains the PC Server executable and the `version.json` file used for the PC auto-updater.

## Auto-Update System
- **Android:** The Android application uses Firebase to check for updates. Make sure the `downloadUrl` in Firebase points to the raw link of the latest APK in this repository.
- **PC:** The PC application checks the `version.json` file in this repository to automatically detect and download new updates.

## Developed by
Developed by Keng.
