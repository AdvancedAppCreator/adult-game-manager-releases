---
title: App config
last_updated: 2026-05-29
---

# App config

`app_config.json` is an advanced override file for release, catalog, support, donation, and optional diagnostics-upload settings.

## Where to put it

Adult Game Manager looks for drop-in config files in common Documents and Download locations using the app's Adult Game Manager folder names.

## What it can override

- Catalog and source index URLs.
- Version/update feed URLs.
- Fallback APK URL.
- Help, issues, support, and donation links.
- Optional diagnostics upload settings.
- Optional feature flags.

## Safety

The app logs only a safe config summary. It must not print upload authorization tokens or private query strings in diagnostics logs.

## Troubleshooting

If a config is loaded, logs should include a private config summary showing counts and booleans, not secrets. Blank legacy fields should fall back to AGM defaults where supported.
