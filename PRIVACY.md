# Plavyo Privacy Policy

_Last updated: 17 October 2026_

Plavyo is a video player that runs entirely on your device. It has no accounts, no ads, no
analytics and no tracking, and its developer does not run any server that receives your data.

## What stays on your device

- **Your videos and playback history.** Plavyo reads media files to play them. Watch history,
  resume positions and settings are stored only in the app's private storage.
- **Saved network connections.** Server addresses, usernames and passwords you enter for SMB,
  FTP or WebDAV are stored only in the app's private database on your phone. They are sent only
  to the server you configured, when you connect to it.

- **Private folder.** Videos you hide are moved into a hidden folder on your own storage. The
  list of their original locations and your PIN (stored only as a one-way hash, never the PIN
  itself) are kept in the app's private storage on your phone and are never sent anywhere.

## Network activity

- **Streaming:** Plavyo connects directly from your phone to the servers or links you choose.
- **Network scan:** when you tap **Scan**, Plavyo checks the devices on your local network for
  file sharing (SMB and FTP ports) and asks them for their names. This traffic never leaves your
  local network, and the results are not stored or sent anywhere.
- **Update check:** Plavyo asks GitHub (api.github.com) whether a newer version is available.
  GitHub receives a normal web request (including your IP address) under
  [GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## Permissions

- **Media / storage access:** to find and play videos and subtitles on your device.
- **Internet / network:** for streaming, network shares, the network scan and the update check.
- **Notifications:** to show playback controls while a video plays in the background.

## Crash reports

If Plavyo crashes, it can show you the error log. Nothing is sent automatically; you decide
whether to share it.

## Deleting your data

Clear the app's data in Android **Settings → Apps → Plavyo → Storage**, or uninstall the app.
This removes everything Plavyo stored.

## Children

Plavyo does not collect personal information from anyone, including children.

## Contact

Questions about privacy: open an issue at https://github.com/unreal-ahsan/Plavyo/issues
