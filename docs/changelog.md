---
title: Changelog
last_updated: 2026-06-06
---

# Changelog

## v1.0.44

- Public-readiness fixes from code audit.
- RPGM save inspection is capped for large saves and shows a warning instead of trying to flatten unlimited values.
- RPGM save writes now use temp-file verification before replacing the live save.
- RPGM backups can be restored in-app.
- Support links ignore legacy F95 Updater thread overrides.
- JoiPlay summaries and sorting use scanned total sizes consistently.
- Android-only size sorts are hidden unless the Android source filter is active.
- Backup export is renamed for Adult Game Manager.
- Ren'Py large integer edits are supported.

## v1.0.42

- Fixed an RPGM save-edit crash/OOM on large saves.
- RPGM write verification now reads only the edited value path instead of flattening the full save tree.
- Backup, re-encode, re-read, and value verification safety checks remain in place.

## v1.0.39

- Improved landscape dialogs across Adult Game Manager.
- Save editors, compare views, file/folder pickers, save-location reports, association pickers, JoiPlay settings/browser, and catalog details now use side-by-side layouts where appropriate.
- Fixed the in-app support link so About/Share opens the public F95Zone thread.
- This release is especially useful on tablets, foldables, Samsung DeX, and phones used in landscape orientation.

## v1.0

- Public launch release of Adult Game Manager.
- In-app Documentation opens the live Adult Game Manager help site.
- Public GitHub update feed and latest APK assets are live.
- Multi-source catalog support is enabled for F95Zone and AdultGameWorld.
- The public F95Zone thread is now the main support/discussion thread.

## v0.2.13

- In-app Documentation now opens the working GitHub help landing page while GitHub Pages is pending repository enablement.
- Expanded Adult Game Manager help from a starter README into a full MkDocs help tree covering permissions, matching, catalog sync, installs, backups, diagnostics, self-update, support, and FAQ.

## v0.2.11

- Public help site created for Adult Game Manager.
- Help screenshots were refreshed from the in-app walkthrough capture.
- Diagnostics help now documents local save, optional upload, and screenshot capture behavior.

## v0.2.x

- Adult Game Manager moved app/catalog/update assets to the public `adult-game-manager-releases` repository.
- Runtime config supports catalog URLs, multiple update feeds, support/issues/donation links, and optional diagnostics upload.
