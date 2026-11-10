# LuxWash Android APK build

This fork contains the v5.0.4 source branch used to build the Android APK for the Bambu Lab A1 mini.

## Build

The GitHub Actions workflow at `.github/workflows/build-android-apk.yml` compiles the debug APK with JDK 17 and Android SDK 34. The APK is uploaded as a 30-day workflow artifact.

## Printer setup

Bambu LAN support is opt-in and experimental in the upstream application. In the app, enable **Settings → Printers → Experimental printer support**, then add **Bambu LAN → A1 Mini**. Configure the printer's IP address, access code and serial number. The printer and phone must be on the same local network; firmware/LAN-mode requirements may apply.

## Licensing

This project is based on Your One Slicer for Android and is licensed under AGPL-3.0. Preserve the upstream notices and make corresponding source code available when distributing modified builds.
