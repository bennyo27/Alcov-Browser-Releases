# Alcov Desktop releases

Public downloads and update metadata for Alcov, the desktop browser with agents built in.

Application source stays private; this repository holds release artifacts only.

- Download the latest build from the [releases page](https://github.com/bennyo27/Alcov-Browser-Releases/releases/latest).
- `latest.yml` (Windows) and `latest-linux.yml` (Linux) are the `electron-updater` feeds for automatic in-app updates via **Settings → Updates**.

## Windows (x64 NSIS Installer)
Download `Alcov-*-win-x64.exe` and double-click to install (creates Desktop and Start Menu shortcuts, includes bundled Chromium, Node, and Pi runtime). Builds are currently unsigned — if Windows SmartScreen prompts on first launch, click **More info → Run anyway**.

## Linux (x64 AppImage)
Download `Alcov-*-linux-x86_64.AppImage`, mark it executable (`chmod +x Alcov-*-linux-x86_64.AppImage`), and run it. Builds are currently unsigned.
