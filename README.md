# Icuity for macOS

A native training calendar for Intervals.icu. This repository hosts public app downloads and issue reports. Application source code is maintained privately.

## Download

Get the DMG from [Releases](https://github.com/psca/icuity-releases/releases), open it, and drag Icuity into Applications.

Requires macOS 26 or later. Supports Apple Silicon and Intel Macs.

## Homebrew

```sh
brew tap psca/tap
brew install --cask psca/tap/icuity
```

If Homebrew asks you to trust the custom cask, run `brew trust --cask psca/tap/icuity` and retry.

## Public testing preview

The current preview is ad-hoc signed, not Developer ID signed or notarized by Apple. macOS may block its first launch. If you trust the download, attempt to open it, then use System Settings > Privacy & Security > Open Anyway if offered. Homebrew does not bypass Gatekeeper.

Report bugs using this repository's Issues. Do not include API keys or private fitness data in public reports.

Icuity is an independent application and is not an official Intervals.icu product.
