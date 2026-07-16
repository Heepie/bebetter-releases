# beBetter Releases

This repository hosts the official public release artifacts for the beBetter
desktop application. The application source code is maintained separately in a
private repository.

## Download

Download the latest published version from the
[Releases](https://github.com/Heepie/bebetter-releases/releases) page.

For macOS, use the signed and notarized DMG for the initial installation.
After installing a version that supports in-app updates, future releases can be
downloaded and installed from the application's update button.

## Release artifacts

Published releases may contain:

- `beBetter-<version>-arm64.dmg` for manual macOS installation
- `beBetter-<version>-arm64-mac.zip` for in-app updates
- `latest-mac.yml` and related metadata used by the updater

Release binaries are attached to GitHub Releases rather than committed to the
Git history. This repository only tracks public release notes and metadata.

## Security

Only download artifacts from published releases in this repository. Official
macOS builds are signed with the beBetter Developer ID certificate and
notarized by Apple.
