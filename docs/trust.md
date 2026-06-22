---
title: Trust and verification
last_updated: 2026-06-22
---

# Trust and verification

Adult Game Manager is designed to be local-first and verifiable.

## Current release

| Item | Value |
| --- | --- |
| Version | v1.0.83 |
| APK | [AdultGameManager-1.0.83-release.apk](https://github.com/AdvancedAppCreator/adult-game-manager-releases/releases/download/app/AdultGameManager-1.0.83-release.apk) |
| APK SHA-256 | `5A5CACACDA5B8641336D6CA70FD26A209E6F01B663B5125A664BB88F01BA9EA5` |
| Source ZIP | [AdultGameManager-1.0.83-source.zip](https://github.com/AdvancedAppCreator/adult-game-manager-releases/releases/download/app/AdultGameManager-1.0.83-source.zip) |
| Source ZIP SHA-256 | `3171A64B1B170889A057050AE1C1037CD3F30F3AB917AECA8C45473F637E9FDC` |
| Source repository | [AdvancedAppCreator/adult-game-manager](https://github.com/AdvancedAppCreator/adult-game-manager) |
| Version metadata | [version.json](https://github.com/AdvancedAppCreator/adult-game-manager-releases/releases/download/app/version.json) |

VirusTotal hash lookup for the APK, if/when submitted:

`https://www.virustotal.com/gui/file/5A5CACACDA5B8641336D6CA70FD26A209E6F01B663B5125A664BB88F01BA9EA5`

## Source and license

The public source repository and source ZIP include:

- Apache-2.0 project license,
- privacy and permissions notes,
- third-party notices,
- release checksums,
- a GitHub Actions workflow for build/test/lint transparency.

Third-party components keep their original licenses. In particular, bundled UnRAR source has its own license and restrictions.

## Privacy basics

- No F95 login is required.
- No analytics SDK is included.
- No automatic game downloader is included.
- Catalog/update metadata is downloaded from public release URLs.
- Logs stay local unless the user explicitly saves/uploads them.
- Public defaults do not include private upload endpoints.

## Build transparency

The source ZIP can be inspected or built locally with JDK 17 and Android SDK API 34:

```powershell
.\gradlew.bat testDebugUnitTest lintDebug assembleRelease
```

Official release APKs are signed separately. Signing files are not part of the source distribution.
