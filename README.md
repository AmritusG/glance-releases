# Glance — Releases

Native macOS DXV-first video player.

This repository hosts signed, notarized DMG releases of Glance.
The source code is private. Bug reports and feature requests are welcome via the [Issues tab](../../issues).

## Download

Current version: **Glance 0.19.2** — [Glance-v0.19.2.dmg](https://github.com/AmritusG/glance-releases/releases/download/v0.19.2/Glance-v0.19.2.dmg) ([SHA-256](https://github.com/AmritusG/glance-releases/releases/download/v0.19.2/Glance-v0.19.2.dmg.sha256), [release notes](https://github.com/AmritusG/glance-releases/releases/tag/v0.19.2))

All previous versions are available on the [Releases tab](../../releases).

Known issue in 0.19.2 (and 0.19.0–0.19.1): dropping a file can crash Glance when the app it was dragged from quits right after the drop (Finder drags are unaffected). See [the issue](../../issues/1).

## What it is

A fast macOS video player with native DXV1 / DXV3 and HAP (Hap1, Hap5, HapY, HapM, HapA) decoding, alongside the codecs macOS plays itself (H.264, HEVC, ProRes, Motion JPEG). Built for VJs and content creators who work with DXV files daily.

Since 0.19.0 Glance is built in Rust on a cross-platform core; settings and shortcuts are the same as before.

## Installing

1. Download the latest `.dmg`
2. Double-click to mount
3. Drag `Glance.app` into your Applications folder (replacing an older Glance keeps your settings)
4. First launch: macOS verifies the signature and notarization (~2 seconds), then opens

## Requirements

- macOS 14 (Sonoma) or later
- Apple Silicon or Intel Mac

## Reporting issues

Please open an [Issue](../../issues) with:

- macOS version (`sw_vers`)
- Glance version (visible in the About menu)
- Steps to reproduce
- Screenshot or screen recording if visual

## License

Glance binaries are distributed for personal and commercial use.
