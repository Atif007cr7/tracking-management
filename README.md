# FocusMate (beta)

FocusMate shows where your screen time goes. A 3D companion sits on the edge of your screen (in the MacBook notch, or floating over your Android apps), cheers you on when you focus, nudges you when you drift, and tracks your subscriptions with renewal countdowns.

> **Beta.** Sign-in is open to invited testers only while Google reviews the app. Want to try it? Email **codewithatif@gmail.com** with the Google address you will sign in with.

## Download

| Platform | Status | Download |
|---|---|---|
| macOS 12 or later (Apple silicon & Intel) | ✅ Beta | [Latest release](https://github.com/Atif007cr7/tracking-management/releases/latest) |
| Windows | 🚧 In progress | — |
| Android 8 or later | ✅ Beta | [Latest release](https://github.com/Atif007cr7/tracking-management/releases/latest) |

## Install on macOS

1. Download `FocusMate-<version>-macos.dmg` from the [latest release](https://github.com/Atif007cr7/tracking-management/releases/latest).
2. Open the DMG and drag **FocusMate** into **Applications**.
3. The beta is not notarized by Apple yet, so the first launch needs one extra step:
   open **FocusMate** from Applications; when macOS says it can't verify the developer, go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.
4. Sign in with Google. FocusMate lives in the menu bar (hourglass icon) and has no Dock icon.

## Install on Android

1. On your phone, download `FocusMate-<version>-android.apk` from the [latest release](https://github.com/Atif007cr7/tracking-management/releases/latest).
2. Open it. Android asks to allow installs from your browser or Files app; allow it, then tap **Install**. If Play Protect warns about an unknown app, choose **Install anyway**. This beta is not on the Play Store.
3. Open **FocusMate** and sign in with Google.
4. Grant the two permissions FocusMate asks for:
   - **Usage access**: lets FocusMate read Android's own screen-time log.
   - **Display over other apps**: lets your companion float over other apps. You can turn it off any time in FocusMate's settings.

To check the download, compare its SHA-256 with `SHA256SUMS.txt` attached to the release:

```sh
shasum -a 256 FocusMate-*
```

## What it does

- **Tracks your time**: which app is in front, for how long, with idle and screen-lock detection.
- **Productivity score**: apps are grouped as productive, neutral or distracting.
- **3D companion**: speech bubbles for deep focus, long distractions, breaks and goals. Pick your character in the dashboard.
- **Dynamic Island** (Mac): drag the companion to the top of a MacBook screen and it lives around the notch.
- **Floating companion** (Android): drag it to either edge; tap it to see the app you are on, tap again to open FocusMate.
- **Subscriptions**: optional, read-only Gmail access finds receipts from Netflix, Prime, Claude, Spotify and more, then counts down to each renewal.
- **Dashboard**: daily chart, focus mix and every app over the last 7 or 30 days.

## Privacy

- Your activity history stays on your device.
- Gmail access is optional and read-only. Only receipts from known subscription services are read, and they are read on your device.
- Signing out removes FocusMate's access to your Google account and deletes the subscription data it found.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
