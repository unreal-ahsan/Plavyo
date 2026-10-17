# Third-Party Notices

Lumora is built on open-source software. The components below are used under their own
licenses; the [Lumora License](LICENSE.md) does not change their terms. The app's
**Settings → About → Open source licenses** screen lists every bundled library and its license.

## mpvEx: Apache License 2.0

Lumora is derived from **mpvEx** (https://github.com/marlboro-advance/mpvEx),
Copyright © marlboro-advance and contributors, which is derived from **mpvKt**
(https://github.com/abdallahmehiz/mpvKt), Copyright © abdallahmehiz and contributors.
Both are licensed under the Apache License, Version 2.0; the full text is in
[LICENSE-APACHE-2.0.txt](LICENSE-APACHE-2.0.txt).

Changes made for Lumora by Ahsan Habib (2026):

- Renamed and rebranded the app as Lumora, with its own application ID (`app.lumora.player`).
- SMB: browse a server from its root (Path `/`), listing all shares through the srvsvc
  `NetrShareEnum` RPC; Path also accepts a share or a folder inside a share.
- SMB: reachability is checked against the SMB port over TCP instead of ICMP.
- SMB streaming: one reusable session per stream and pipelined 1 MB read-ahead, for smooth
  playback and faster seeking.
- Points the update checker and project links at the Lumora releases page.

## libmpv / mpv-android: LGPL-2.1-or-later

Lumora dynamically links libmpv through mpv-android (https://github.com/marlboro-advance/mpv-android),
licensed under the GNU Lesser General Public License v2.1 or later. Its source is available at
that repository; see https://www.gnu.org/licenses/lgpl-2.1.html for the license text.

## FFmpeg: LGPL-2.1-or-later

Bundled with libmpv. Source: https://ffmpeg.org. License: https://www.gnu.org/licenses/lgpl-2.1.html.

## Other libraries

Includes, among others: SMBJ (Apache-2.0), Apache Commons Net (Apache-2.0), sardine-android
(Apache-2.0), NanoHTTPD (BSD-3-Clause), MediaInfoLib (BSD-2-Clause), OkHttp (Apache-2.0),
AndroidX and Jetpack Compose (Apache-2.0), Kotlin and kotlinx libraries (Apache-2.0).
The full list with license texts is in the app.
