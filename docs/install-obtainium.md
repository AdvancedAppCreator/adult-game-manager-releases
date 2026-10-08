---
title: Install with Obtainium
last_updated: 2026-10-08
---

# Install with Obtainium

[Obtainium](https://github.com/ImranR98/Obtainium) can monitor AGM's public
GitHub releases and notify you when a new signed APK is available.

## Add AGM

1. Install Obtainium from its official project.
2. In Obtainium, choose **Add App**.
3. Enter:
   `https://github.com/AdvancedAppCreator/adult-game-manager`
4. Let Obtainium detect GitHub as the source.
5. If an APK filter is requested, use `.apk`.
6. Add the app and review the detected release before installing.

## Verify the source

The source must be the `AdvancedAppCreator/adult-game-manager` repository.
Official releases include checksums, a detached checksum signature, an Android
signing-certificate fingerprint, and a source archive.

Obtainium is an independent project. AGM does not control Obtainium and does
not receive account or usage information from it.

## Existing installs

Android only accepts an update when the package name and signing certificate
match the installed app. If Android reports a signature conflict, do not
uninstall until you have backed up any AGM state you want to retain.

You can also use AGM's [built-in self-update](self-update.md).
