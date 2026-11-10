# Boomship for the desktop

Download Boomship for the desktop from **[boomship.ai/download](https://www.boomship.ai/download)**.

This repository holds only the published installers, under [Releases](https://github.com/geekynaman/boomship-desktop/releases). It contains no source code. Boomship's code is private.

| Build | File | Needs |
| --- | --- | --- |
| Mac with Apple silicon | `Boomship-<version>-mac-arm64.dmg` | macOS 13 Ventura or later |
| Mac with an Intel processor | `Boomship-<version>-mac-x64.dmg` | macOS 13 Ventura or later |
| Windows PC | `Boomship-<version>-win-x64.exe` | Windows 10 or 11, 64-bit |

Each release has `SHA256SUMS` and `latest.json`, so you can check that the file you downloaded is the one that was published.

## Not signed yet

The Mac builds are not notarized by Apple, and the Windows installer is not code-signed, so each system warns you the first time:

- **Mac:** macOS says it cannot check Boomship for malicious software. Open System Settings → Privacy & Security and click **Open Anyway**, once.
- **Windows:** SmartScreen may say it protected your PC. Click **More info**, then **Run anyway**.

There is no automatic update yet. Download a new version from boomship.ai/download.

## Security

The app is the Boomship workspace in its own window. It can't be run as a script runner or with a debugger attached, its sign-in session is encrypted with the system keychain, and it refuses to start if its code was changed. To report a security issue, email support@boomship.ai.
