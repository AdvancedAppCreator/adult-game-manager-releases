---
title: Troubleshooting / FAQ
last_updated: 2026-05-29
---

# Troubleshooting / FAQ

Common Adult Game Manager problems usually come from stale catalogs, Android file permissions, or old private config.

## The app opens GitHub README instead of a polished help site

That is expected until GitHub Pages is enabled for this repository. The full MkDocs help source is in `docs/`, and the README links to the same help pages.

## A game is unmatched

Sync catalogs, then refresh from catalog. If it is still unmatched, use manual search, paste the source page URL, or mark it as not in catalog.

## A match opens the wrong site

Edit the match and choose the correct source entry. Adult Game Manager stores source-aware matches, so the selected source controls the page URL.

## Catalog results look old

Run catalog sync again. If sync fails, save diagnostics and check the log for catalog URL or network errors.

## Update check still shows an old version

Check loaded config summaries in diagnostics logs. An old private config may override version feeds. AGM should report how many version feeds are active without printing private tokens.

## Diagnostics upload menu is missing

Upload actions only appear when diagnostics upload is configured. You can still use local diagnostics save and copy diagnostics summary.

## Does the app download games?

No. It tracks local apps/games, searches catalogs, opens source pages, and helps install local files you choose.
