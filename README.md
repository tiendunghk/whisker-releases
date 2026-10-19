<p align="center">
  <img src="https://raw.githubusercontent.com/tiendunghk/whisker-releases/main/icon.svg" width="96" alt="Whisker" />
</p>

<h1 align="center">Whisker</h1>

<p align="center">Your Android app's logs, crashes and screen — in one window.</p>

This repository hosts the **installers** for Whisker. Grab the latest version from **[Releases](https://github.com/tiendunghk/whisker-releases/releases/latest)**.

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `Whisker_<version>_aarch64.dmg` |
| macOS (Intel) | `Whisker_<version>_x64.dmg` |
| Windows | `Whisker_<version>_x64-setup.exe` (or `.msi`) |
| Linux | `Whisker_<version>_amd64.AppImage`, `.deb` or `.rpm` |

Whisker updates itself: installed apps offer new versions from this page automatically.

## Requirements

- Android SDK platform-tools (`adb`) — e.g. `brew install android-platform-tools`
- A device or emulator with USB debugging enabled, Android 7.0+

## macOS: first launch

Whisker isn't notarized yet. The first time, right-click **Whisker.app → Open** and confirm, or run:

```bash
xattr -dr com.apple.quarantine /Applications/Whisker.app
```
