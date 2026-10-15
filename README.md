# Brick releases

Android builds of Brick, a focus app that blocks apps and sites until you scan your own QR code or NFC tag.
Each release is built by CI from the private source repo. The app checks this page for updates.

## Install

1. On the phone, download [brick.apk](https://github.com/altrao/brick-releases/releases/latest/download/brick.apk).
2. Open it and allow your browser or Files app to install apps when Android asks.
3. Open Brick and follow **Settings → Permissions**.

## Updates

Brick checks for a new release when you open it. Tap **Update** on Home (or in Settings) to install it.
The first time, Android asks you to let Brick install apps. After Brick has updated itself once, later updates install without a prompt.

Android only installs an update signed with the same key as the Brick you have, so a tampered APK can't replace it.
