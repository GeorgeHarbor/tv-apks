# TV APKs

Release assets for Android TV and set-top box setup. APK binaries are stored in GitHub Releases, not in Git history.

## Spotify TV

- [Latest release](https://github.com/GeorgeHarbor/tv-apks/releases/latest)
- [Download spotify-tv.apk](https://github.com/GeorgeHarbor/tv-apks/releases/latest/download/spotify-tv.apk)
- [Version metadata](https://github.com/GeorgeHarbor/tv-apks/releases/latest/download/spotify-tv.json)
- [SHA-256 checksum](https://github.com/GeorgeHarbor/tv-apks/releases/latest/download/SHA256SUMS)

The initial APK is Spotify TV 1.85.2, package `com.spotify.tv.android`, versionCode 1850200, minimum Android API 21. It was supplied by the repository owner as `Spotify_TV-v1.85.2_build_1850200-Mod.apk`. The filename labels it as modified. This repository does not claim it is an official Spotify release or an independently audited build. Published metadata describes APK declarations, not an authenticity guarantee.

For setup automation, resolve the release metadata, download the APK and checksum, verify integrity and device compatibility, and install with `adb -s DEVICE_SERIAL install -r spotify-tv.apk`. Preserve existing data; stop on signing conflicts or downgrades instead of uninstalling or clearing data automatically. Do not replace an existing Spotify installation without checking its version and signing compatibility.
