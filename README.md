# One Take Composer — App Store source

Corresponding source for **version 1.0.0, build 49**, the temporary App Store edition without Surge.

## Download

[Download the full source archive](https://github.com/vanyashuvalov/one-take-composer-appstore-source/releases/tag/v1.0.0-build49) from the release assets. The ZIP contains the complete application source, Xcode project, Swift package, bundled resources, LAME/Plaits sources, notices, and build scripts. The automatically generated GitHub source snapshots contain only this index; use the explicitly named `OneTakeComposer-1.0.0-49-no-surge-source.zip` asset for the app.

SHA-256: `8b67cf014d739848efeffcab257a4bf84a378e7c9e050b41d5d7b7a89ed72715`

The archive includes `SOURCE-MANIFEST.json` with hashes for all 1,332 source/resource files.

## Build and modify

Extract the archive and read `README.md` and `docs/NO-SURGE-RELEASE.md`. Use Xcode 26.3 or a compatible newer toolchain on macOS. The app targets iOS 17+ and arm64. The included LAME encoder is built from source; the guide explains how to modify it and relink the app. Use your own Apple signing team to install a rebuilt version. No publisher credentials or signing keys are included.

## Licenses

First-party code retains its GPL-3.0-or-later grant. LAME retains its LGPL terms, and Plaits/stmlib retain their MIT notices. See `LICENSE`, `LICENSE-NOTICE.txt`, and component/resource notices inside the archive for the applicable terms; the code license does not replace separate asset notices.

This repository distributes the build 49 source archive. It contains no development-repository history and no Surge implementation, binary, or factory bank.
