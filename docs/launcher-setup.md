---
title: Launcher setup
last_updated: 2026-10-08
---

# Launcher setup

AGM keeps the library and catalog state while compatible launcher/runtime apps
execute extracted games.

## Choose the runtime for the game

| Game type | Compatible runtime |
| --- | --- |
| Ren'Py, RPG Maker, HTML, and other JoiPlay-supported games | [JoiPlay](joiplay.md) and its required plugins |
| Windows x86/x64 games | [Winlator Secure](https://github.com/AdvancedAppCreator/winlator-app) |
| KiriKiri/Kirikiri Z games | [Kirikiroid2 Community Fork](https://github.com/AdvancedAppCreator/kirikiroid2) |
| Android APK games | Android itself |

The compatibility of an individual game still depends on its engine, files,
plugins, and the selected runtime.

## Recommended order

1. Install AGM from its [latest signed release](https://github.com/AdvancedAppCreator/adult-game-manager/releases/latest).
2. Install only the runtime needed for your games.
3. Grant storage or package permissions only when Android and the selected
   workflow require them.
4. In AGM, select local game files or folders that you already possess.
5. Review AGM's proposed install, replacement, or launch action before
   confirming it.

## Project boundaries

AGM does not bundle JoiPlay, Wine, Winlator, or game files. Winlator Secure and
Kirikiroid2 Community Fork are separately published projects with their own
licenses, release notes, privacy disclosures, and support boundaries.

Do not report fork-specific problems to the original upstream projects.
