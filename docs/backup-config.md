---
title: Backup and config
last_updated: 2026-05-29
---

# Backup and config

Backup and config tools preserve your mappings and support advanced release/catalog settings.

## Where to find it

Menu -> **Backup & config ...**

## Backups

Export your app state before testing risky changes or moving to another device. Imports restore mapping state and personal tracking data included in the backup.

See [Export and import backup](backup/export-import.md) for the full workflow.

## Advanced app config

Advanced users can provide an `app_config.json` to override catalog, update, support, donation, and optional diagnostics-upload settings.

Adult Game Manager looks for drop-in config files in common Documents/Download locations and logs a safe summary when a config is loaded. It does not print upload tokens in logs.

See [App config](backup/app-config.md) for supported override types and safety notes.
