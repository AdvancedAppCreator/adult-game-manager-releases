---
title: Sources and sync
last_updated: 2026-05-29
---

# Sources and sync

Catalog sync downloads the configured source index and source catalog files so Adult Game Manager can search and match games locally.

## Where to find it

Use **Catalog** tools or refresh actions from the main menu.

## What it does

The app fetches a catalog index, then loads enabled source catalogs such as F95Zone and AdultGameWorld. Each entry keeps source ID, title, source URL, version text, tags, platforms, rating, and other source-specific metadata.

## When to sync

- After installing a new AGM version.
- Before reviewing unmapped games.
- If catalog search results look stale.
- After changing catalog URLs in `app_config.json`.

## Troubleshooting

If sync fails, check network connectivity, then use [Diagnostics and logs](../diagnostics/logs.md) to save a local log.
