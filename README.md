# HamLogs.Si for Android

HamLogs.Si is a ham radio logbook that keeps your logs on your own device. This is the Android app. The same logbook also runs in any browser at **https://hamlogs.si**.

## Download

Get the latest APK from the [**Releases** page](https://github.com/coffeedev/hamlogs-si/releases/latest) (`HamLogs-Si-v….apk`).

## Install

1. Open the downloaded file on your phone. Android asks you to allow installing apps from this source (your browser or file manager): allow it.
2. If Google Play Protect says it doesn't know the app, choose **Install anyway**. The app isn't on the Play Store, so Play Protect has not seen it before.
3. Open **HamLogs.Si**, then register with your callsign, or restore a backup.

Android 7.0 or newer. A radio needs a USB cable with an OTG adapter.

## What it adds to the web app

- **Radio over USB**: reads frequency and mode from a QMX/QMX+, IC-7300 and other CI-V radios straight into the QSO form (Chrome on Android can't see some of these; the app can). It only reads from the radio.
- **Smoother uploads**: LoTW uploads read LoTW's reply directly, with no extra window.
- Everything else is the same as the web app: logbooks, contests and Cabrillo, search, dashboard, Club Log, eQSL, LoTW, backups and working offline.

## Check the file (optional)

Each release has a `.sha256` file. To compare it with your download:

- Windows: `certutil -hashfile HamLogs-Si-v2.0.58.apk SHA256`
- Linux/macOS: `sha256sum HamLogs-Si-v2.0.58.apk`

Every release is signed with the same key. Its certificate SHA-256 fingerprint is:

`C1:0C:7A:56:28:3D:B0:40:11:2E:E5:09:2E:D7:B3:1E:36:F9:E2:E1:FD:B5:6F:FD:A0:79:7E:60:2A:C2:12:1E`

(In Android: Settings, Apps, HamLogs.Si, or any app that shows signing certificates.) An update signed with a different key will not install over it.

## Updates

New versions are posted on the Releases page. Install the new APK over the old one; your logs stay on the device. The app tells you when a newer version is out.

## Your data

Your logs stay on your device. Only your callsign, grid and handle are sent to the server when you register. Online backups, if you turn them on, are encrypted on your device with your user key first. Keep your user key safe: it cannot be recovered.

## Problems

Open an [issue](https://github.com/coffeedev/hamlogs-si/issues) and say your phone model, Android version and app version (shown at the bottom of the Main tab).
