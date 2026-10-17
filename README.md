# Lumora

**A fast, smooth video player for Android** — local files and your home network, in one app.

### ⬇️ [Download the latest APK](https://github.com/unreal-ahsan/Lumora/releases/latest)

## Features

- Plays almost any format: MKV, MP4, AVI, MOV, WebM, TS, HEVC/H.265, AV1, VP9 and more.
- Hardware decoding with automatic software fallback.
- **Network streaming from SMB (Windows / NAS shares), FTP and WebDAV.**
  - Connect to a server with just its address: Lumora lists every shared folder for you.
    No need to type a share name.
  - Smooth playback of high-bitrate video over Wi-Fi with fast seeking.
- Subtitles: embedded, external, and auto-loaded from the same folder (also on network shares).
- Gestures for seeking, volume and brightness; playback speed; picture-in-picture.
- Material You design with light and dark themes.

## Which APK should I download?

| File | For |
|---|---|
| `Lumora-…-arm64-v8a.apk` | Almost all modern phones (recommended) |
| `Lumora-…-armeabi-v7a.apk` | Older 32-bit phones |
| `Lumora-…-universal.apk` | Works on every device (larger download) |
| `Lumora-…-x86_64.apk` / `x86.apk` | Emulators and Intel/AMD Android devices |

Not sure? Pick **universal**.

## Connecting to a network share (SMB)

1. Open the **Network** tab and tap **+**.
2. Choose **SMB**, enter the computer's IP address (for example `192.168.1.10`) and your
   Windows/NAS username and password (or tick *Anonymous/Guest*).
3. Leave **Path** as `/` to see all shared folders, or enter `/ShareName` (or
   `/ShareName/Folder`) to open a specific place directly.

## License

Lumora is free to download and use, but it is **not open source**. See [LICENSE.md](LICENSE.md).
Redistribution and any use for training or evaluating AI / machine-learning models are
prohibited.

Lumora is built on open-source software, including mpvEx (Apache-2.0), mpv and FFmpeg
(LGPL-2.1+). See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
