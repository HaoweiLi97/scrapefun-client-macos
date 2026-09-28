# ScrapeFun Client for macOS

[简体中文](./README.md) · **English**

[Product overview](https://github.com/HaoweiLi97/ScrapeFun/blob/main/README.en.md) · [Stable downloads](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/latest) · [All releases](https://github.com/HaoweiLi97/scrapefun-client-macos/releases) · [Online documentation](https://scrapefun.com/?lang=en#/docs)

> Updated: 2026-09-28. Versions and assets below are the stable releases checked on this date. Follow the corresponding Release for later changes.

macOS desktop client for connecting to an existing ScrapeFun Server, browsing and playing movie and TV resources, and reading comics. You do not need to install Server on the same Mac as Client.

## Downloads and environment

| Item | Current stable release |
| --- | --- |
| Version | [0.0.4](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/tag/v0.0.4) |
| Architecture | Apple Silicon / arm64 |
| Manual installation | `.dmg` |
| Update assets | `.zip`, `.blockmap`, `latest-mac.yml` |

Download the DMG from the [stable download page](https://github.com/HaoweiLi97/scrapefun-client-macos/releases/latest). This release does not provide an Intel installer. Check the specific release and package for system requirements and signing status.

## Installation

1. Open the DMG and drag `ScrapeFun Client.app` into Applications.
2. Launch the client from Applications.
3. If macOS blocks launch, first verify the source, architecture, and first-launch instructions for that release.

ZIP, blockmap, and YAML files support update distribution. Prefer the DMG for a first manual installation.

## Connect to Server

Enter the Server address, such as `http://192.168.1.10:8096`, and sign in with a Server account. For connections from another device, Server must allow the appropriate network access. `localhost` refers only to the current Mac.

## Updates and configuration

Use the client's update mechanism, or download a newer DMG and install over the current version. Updates under the same user normally retain connection settings; do not delete the user configuration directory. Updating Client does not upgrade Server. Back up server libraries and business data separately.

## Troubleshooting

Include your macOS version, Mac architecture, Client and Server versions, and reproduction steps. For installation errors, include the system message; for playback errors, add logs with sensitive details removed and media codec information.

## Support and licensing

This repository provides platform installation instructions and official release assets. Submit usage questions and feature requests to the [main repository Issues](https://github.com/HaoweiLi97/ScrapeFun/issues). For accounts, activation, or private logs, contact `scrapefun@outlook.com`. Report security issues privately according to the [security instructions](./SECURITY.en.md).

See the new [commercial license statement](./LICENSE.en.txt) and full [software license agreement](./EULA.en.md). Ordinary personal, household, and internal organizational use is allowed. Pro requires a valid entitlement. Software redistribution, resale, customer delivery, and paid hosting require separate written authorization. The statement does not retroactively change existing licenses; existing assets follow their supplied licenses, and third-party components retain their own licenses.

[Releases and compatibility](https://github.com/HaoweiLi97/ScrapeFun/blob/main/RELEASE_POLICY.en.md) · [Third-party components](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.en.md) · [Support](./SUPPORT.en.md)
