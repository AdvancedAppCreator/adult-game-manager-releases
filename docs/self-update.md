---
title: Self-update
last_updated: 2026-05-29
---

# Self-update

Self-update checks configured version feeds for a newer Adult Game Manager APK.

## Where to find it

Main menu -> **Check for app update**.

## What it does

The app reads configured `version.json` feeds, compares the latest version/code with the installed app, and opens the APK download/install flow when an update is available.

## Current public feed

Public releases are hosted from the `AdvancedAppCreator/adult-game-manager-releases` GitHub release assets. Existing transition builds may also read an Azure bridge feed so older installs can migrate.

## If it says no version configured

Check whether an old or private `app_config.json` overrides update feed URLs. Recent AGM versions fall back to default feeds when blank legacy values are present.
