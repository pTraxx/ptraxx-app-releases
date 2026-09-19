# ptraxx-app-releases
19 September 2026

# pTraxx || App Downloads

Official release builds of **pTraxx**, the digital out-of-home (DOOH) signage player and content platform by [Traxx Technology](https://traxxtech.africa).

> This repository hosts installers only.

## Download (latest)

| Platform | File | Link |
|---|---|---|
| Windows 10/11 (64-bit) | `ptraxx-setup.exe` | [Download](https://github.com/pTraxx/ptraxx-app-releases/releases/download/v1.0.4/ptraxx.exe) |
| Android | `ptraxx.apk` | [Download](https://github.com/pTraxx/ptraxx-app-releases/releases/download/v1.0.4/ptraxx.apk) |

Older versions and release notes: [Releases](https://github.com/pTraxx/ptraxx-app-releases/releases)

## Install

### Windows
1. Run `ptraxx-setup.exe`.
2. If you see **"Windows protected your PC"**, click **More info → Run anyway**.
3. Follow the installer. Tick **Start at login** for unattended screens.

Updating: run the new installer. It upgrades in place; your settings are kept.

### Android
1. Open `ptraxx.apk` on the device.
2. When prompted, allow **Install unknown apps** for your browser or file manager.
3. Tap **Install**.

Updating: install the new APK over the existing app. No need to uninstall.

## Verify your download

Each release lists a SHA-256 checksum per file. To compare:

```powershell
# Windows (PowerShell)
Get-FileHash .\ptraxx-setup.exe -Algorithm SHA256
```
```bash
# macOS / Linux
shasum -a 256 ptraxx.apk
```

Only install files downloaded from this repository or the official pTraxx website.

## Requirements

| Platform | Minimum |
|---|---|
| Windows | Windows 10 or 11, 64-bit |
| Android | Android <X.0> or later |

## Support

- Website: <https://digital.oohtraxx.com
- Email: hello@oohtraxx.com

Report issues through the contacts above rather than GitHub Issues.

---

© Traxx Technology. All rights reserved.
