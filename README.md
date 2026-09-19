# Missionect releases

Official Missionect desktop installers. Application source code is maintained separately.

- [Download Missionect](https://www.missionect.com/download)
- [Latest release](https://github.com/hyw950/missionect-releases/releases/latest)

## macOS

For Apple Silicon Macs (M1 or later), macOS 11.0 or later.
Open the DMG, then drag Missionect into Applications.
The macOS installer is Developer ID signed and notarized by Apple.

Each release includes a SHA-256 checksum file. In Terminal, run `shasum -a 256 -c Missionect-1.0.0+1-macos-arm64.dmg.sha256` in the folder containing both downloaded files.

## Release metadata

`latest.json` provides versioned download URLs, file sizes, minimum OS requirements, and checksums for the website.
Publish and verify release assets before updating this manifest. Never replace the files of a published version; publish a new version instead.
