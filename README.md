<p align="center">
  <img src="https://raw.githubusercontent.com/tiendunghk/whisker-releases/main/icon.svg" width="96" alt="Whisker" />
</p>

<h1 align="center">Whisker</h1>

<p align="center">Your Android app's logs, crashes and screen — in one window.</p>

This repository hosts the **installers** for Whisker. Grab the latest version from **[Releases](https://github.com/tiendunghk/whisker-releases/releases/latest)**.

| Platform | Download |
| --- | --- |
| macOS (Apple Silicon) | [Whisker_aarch64.dmg](https://github.com/tiendunghk/whisker-releases/releases/latest/download/Whisker_aarch64.dmg) |
| macOS (Intel) | [Whisker_x64.dmg](https://github.com/tiendunghk/whisker-releases/releases/latest/download/Whisker_x64.dmg) |
| Windows | [Whisker_x64-setup.exe](https://github.com/tiendunghk/whisker-releases/releases/latest/download/Whisker_x64-setup.exe) |
| Linux | [Whisker_amd64.AppImage](https://github.com/tiendunghk/whisker-releases/releases/latest/download/Whisker_amd64.AppImage) · `.deb` and `.rpm` on the release page |

## Requirements

- Android SDK platform-tools (`adb`) — e.g. `brew install android-platform-tools`
- A device or emulator with USB debugging enabled, Android 7.0+

## macOS: first launch

Whisker isn't notarized yet. The first time, right-click **Whisker.app → Open** and confirm, or run:

```bash
xattr -dr com.apple.quarantine /Applications/Whisker.app
```
