# Recapture releases

Downloads for **Recapture**, an instant-replay recorder for Windows (AMD and NVIDIA graphics cards).

## Install

1. Download `Recapture.exe` from the [latest release](https://github.com/muhammedx86/recapture-releases/releases/latest).
2. Put it in a folder of its own (for example `C:\Recapture`) and run it. Your settings are kept next to it.
3. In the app, install the Recapture service when asked (one Windows prompt). Recording then runs in the background.

## Updates

The app checks this page for a new version at start and once a day (Settings › Updates). When one is out it shows a
banner; nothing installs until you choose **Update**. The update is checked against its signature, Windows asks for
permission once, and the new version replaces the old one. Old versions and cached files are removed; your settings,
logs and clips stay.

Each release has two files:

- `Recapture.exe`: the app, the background service and the recording engine in one file.
- `update.json`: what the app reads to find the update (version, SHA-256, size, notes, signature).

The source code is not public. This repository holds only the releases.
