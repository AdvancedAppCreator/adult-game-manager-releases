---
title: Trust and verification
last_updated: 2026-06-11
---

# Trust and verification

Adult Game Manager is designed to be local-first and verifiable.

## Current release

| Item | Value |
| --- | --- |
| Version | v1.0.51 |
| APK | [AdultGameManager-1.0.51-release.apk](https://github.com/AdvancedAppCreator/adult-game-manager-releases/releases/download/app/AdultGameManager-1.0.51-release.apk) |
| APK SHA-256 | `36868D35B2B60CA53F0F74D5243A6523D7E9043727509A5E4A93496545AEF58A` |
| Source ZIP | [AdultGameManager-1.0.51-source.zip](https://github.com/AdvancedAppCreator/adult-game-manager-releases/releases/download/app/AdultGameManager-1.0.51-source.zip) |
| Source ZIP SHA-256 | `C4265FC47ABDE276BBA53E0D4E31E7E43EBF955DDED922D9B0F2B097F69AD102` |
| Source repository | [AdvancedAppCreator/adult-game-manager](https://github.com/AdvancedAppCreator/adult-game-manager) |
| Version metadata | [version.json](https://github.com/AdvancedAppCreator/adult-game-manager-releases/releases/download/app/version.json) |

VirusTotal hash lookup for the APK, if/when submitted:

`https://www.virustotal.com/gui/file/36868D35B2B60CA53F0F74D5243A6523D7E9043727509A5E4A93496545AEF58A`

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

