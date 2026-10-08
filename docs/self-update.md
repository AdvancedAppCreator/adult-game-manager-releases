---
title: Self-update
last_updated: 2026-10-08
---

# Self-update

Self-update checks configured version feeds for a newer Adult Game Manager APK.

## Where to find it

Main menu -> **Check for app update**.

## What it does

The app reads configured `version.json` feeds, compares the latest version/code with the installed app, and opens the APK download/install flow when an update is available.

## Current public feed

Signed public releases are hosted from the
[`AdvancedAppCreator/adult-game-manager`](https://github.com/AdvancedAppCreator/adult-game-manager/releases)
GitHub release assets.

You can also use [Obtainium](install-obtainium.md) to monitor the same public
GitHub releases independently of AGM's built-in update check.

## If it says no version configured

Check whether an old or private `app_config.json` overrides update feed URLs. Recent AGM versions fall back to default feeds when blank legacy values are present.
