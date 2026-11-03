<div align="center">
  <img src="./docs/images/client-icon.png" alt="ScrapeFun Client" width="80" />
  <h1>ScrapeFun Client for macOS</h1>
  <p><a href="./README.md">简体中文</a> · <strong>English</strong></p>
  <p><a href="https://scrapefun.com/?lang=en">Website</a> · <a href="https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.5.0">Download</a> · <a href="https://github.com/HaoweiLi97/scrapefun-client-macos/releases">All releases</a> · <a href="https://scrapefun.com/?lang=en#/docs">Documentation</a></p>
</div>

> Updated: 2026-11-03. Versions and assets below are the stable releases checked on this date. Follow the corresponding Release for later changes.

macOS desktop client for connecting to an existing ScrapeFun Server, browsing and playing movie and TV resources, and reading comics. You do not need to install Server on the same Mac as Client.

## Downloads and environment

| Item | Current stable release |
| --- | --- |
| Version | [0.5.0](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.5.0) |
| System | macOS 26.5 or later |
| Architecture | Apple Silicon / arm64 |
| Manual installation | `.dmg` |
| Trust status | Ad-hoc integrity signature; not Apple Developer ID signed or notarized |

Download the DMG from the [0.5.0 download page](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.5.0). This release does not provide an Intel installer. Check the specific release and package for system requirements and signing status.

## Installation

1. Open the DMG and drag `ScrapeFun Client.app` into Applications.
2. Launch the client from Applications.
3. If macOS blocks first launch, verify the download source before using the command documented for this release:

   ```bash
   xattr -dr com.apple.quarantine "/Applications/ScrapeFun Client.app"
   ```

   This removes the download quarantine flag; it does not add Apple signing or notarization.

0.5.0 provides a DMG and checksum files only. Install it manually; this package is not distributed through in-app automatic updates.

## Connect to Server

Enter the Server address, such as `http://192.168.1.10:8096`, and sign in with a Server account. For connections from another device, Server must allow the appropriate network access. `localhost` refers only to the current Mac.

## Updates and configuration

For 0.5.0, download the version-specific DMG, quit the client, and replace the existing app. Updates under the same user normally retain connection settings; do not delete the user configuration directory. Updating Client does not upgrade Server. Back up server libraries and business data separately.

<details>
<summary>Troubleshooting</summary>

Include your macOS version, Mac architecture, Client and Server versions, and reproduction steps. For installation errors, include the system message; for playback errors, add logs with sensitive details removed and media codec information.

</details>

## Support and licensing

This repository provides platform installation instructions and official release assets. Submit usage questions and feature requests to the [main repository Issues](https://github.com/HaoweiLi97/ScrapeFun/issues). For accounts, activation, or private logs, contact `scrapefun@outlook.com`. Report security issues privately according to the [security instructions](./SECURITY.en.md).

See the new [commercial license statement](./LICENSE.en.txt) and full [software license agreement](./EULA.en.md). Ordinary personal, household, and internal organizational use is allowed. Pro requires a valid entitlement. Software redistribution, resale, customer delivery, and paid hosting require separate written authorization. The statement does not retroactively change existing licenses; existing assets follow their supplied licenses, and third-party components retain their own licenses.

[Releases and compatibility](https://github.com/HaoweiLi97/ScrapeFun/blob/main/RELEASE_POLICY.en.md) · [Third-party components](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.en.md) · [Support](./SUPPORT.en.md)
