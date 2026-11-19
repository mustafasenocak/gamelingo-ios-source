# Game Lingo — iPhone client source

The complete corresponding source for **Game Lingo 1.1.0 (32)** is distributed as the immutable build-28 source archive plus the build-32 source update below. Download both; the update contains every changed or new file, including the complete build-32 SHA-256 manifest. No files were removed.

1. [Download the base source (build 28)](https://github.com/mustafasenocak/gamelingo-ios-source/releases/download/v1.1.0/GameLingo-1.1.0-28-source.zip).
2. [Download the source update (build 32)](GameLingo-1.1.0-32-source-update.zip).
3. Extract both into the same directory, base first, and allow the update to replace matching files:

```sh
unzip GameLingo-1.1.0-28-source.zip -d GameLingo-source
unzip -o GameLingo-1.1.0-32-source-update.zip -d GameLingo-source
```

Read the resulting `README.md` for exact build instructions. The resulting `SOURCE-MANIFEST.json` describes the complete build-32 source. This overlay was checked byte-for-byte against the standalone complete build-32 source archive (SHA-256 `3ca72bd9c88a83638bf55605576af88ca308c2692b2e94ac35bce7443c1d9e2c`).

Base archive SHA-256: `09caabe921e4deb203b2412c9b1351d4d63eba4a1d26d53f66ada0b84536bf64`  
Source update SHA-256: `ed17be2676bfe7c14e871eba592cd0818743220bc945f23237eee8bcd98994bf`

Build 32 adds server-verified Premium access for the TV receiver, pairing protocol v2, and setup guidance. The same subscription covers the phone and compatible TV. The source includes the Flutter iPhone client, native PS5 bridge, patched Remote Play engine, third-party sources and notices, exact build inputs and build instructions. GitHub's automatically generated source archives contain this distribution index and update only; use both named downloads above.

## License and scope

The iPhone client is available under GNU AGPL-3.0-or-later with the included OpenSSL and application-store additional permissions. Read `LICENSE-iOS` and third-party notices inside the package. Source access is free and does not require Premium.

The source excludes the backend, admin application, signing credentials, API keys, user data and PSN registrations. Third-party files retain their own licenses. Game Lingo is not sponsored by Sony or PlayStation.

Version 1.1.0 supports translation while the iPhone app is visible. Publishing source does not mean Apple has approved the corresponding update. [Build-28 release and source](https://github.com/mustafasenocak/gamelingo-ios-source/releases/tag/v1.1.0) remain available unchanged.
