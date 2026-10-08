---
title: Adult Game Manager
last_updated: 2026-10-08
---

# Adult Game Manager

Adult Game Manager is a local-first Android library, update tracker, launcher
companion, installer, and save toolkit for installed APKs and extracted games.

[Download latest signed release](https://github.com/AdvancedAppCreator/adult-game-manager/releases/latest){ .md-button .md-button--primary }
[Report an issue](https://github.com/AdvancedAppCreator/adult-game-manager-releases/issues){ .md-button }
[Verify releases](verification.md){ .md-button }

## 40-second overview

[![Adult Game Manager overview](media/adult-game-manager-demo.gif)](media/adult-game-manager-demo.mp4)

![Main screen](screenshots/main-screen.png)

## What it does

| Area | Summary |
| --- | --- |
| Installed games | Lists installed APKs and AGM-managed extracted games in one place. |
| Catalog | Searches a game catalog by title, tags, status, engine, rating, and installed state. |
| Matching | Links local games to catalog entries and shows version/update state. |
| Launchers | Starts compatible games through JoiPlay, Winlator, and Kirikiroid2. |
| Install helpers | Plans installs and upgrades for local APKs and archives you select; it does not download games for you. |
| Save tools | Discovers supported Ren'Py and RPG Maker saves and creates backups before edits. |
| Backup/config | Exports/imports app state and supports advanced `app_config.json` overrides. |
| Diagnostics | Saves local logs and, when configured, uploads logs/screenshots only after you tap upload. |

## Start here

- [Getting started](getting-started.md) covers installation and first-run setup.
- [Install with Obtainium](install-obtainium.md) covers automatic GitHub release checks.
- [Launcher setup](launcher-setup.md) explains JoiPlay, Winlator Secure, and Kirikiroid2.
- [Main screen tour](main-screen.md) explains the installed-games list.
- [Catalog](catalog.md) explains source catalogs, filters, and opening game pages.
- [Matching games](mapping/auto-match.md) explains how installed games connect to catalog entries.
- [JoiPlay](joiplay.md) covers local JoiPlay imports and install helpers.
- [Why AGM?](why-agm.md) compares AGM with keeping separate manual launcher lists.
- [Practical guides](guides/renpy-android.md) cover common Android game-management workflows.
- [Diagnostics](diagnostics/logs.md) explains logs, local saves, and optional upload.
- [Trust and verification](verification.md) lists source, checksums, and privacy notes.

## Privacy basics

- No site login is required.
- No hosted account, ads, or analytics SDKs.
- No automatic game downloader.
- Diagnostics upload is opt-in and only appears when configured.
