# Docs maintenance rules

These rules keep the Adult Game Manager help site in sync with the shipping app.

## Hard rules

1. Any UI change requires a docs change in the same release. If you add, rename, remove, or change the behavior of any menu item, dialog, screen, or row icon, update the matching page under `docs/`.
2. Each menu item or feature has exactly one canonical page. Use the navigation map in `mkdocs.yml` to find it.
3. Update `docs/changelog.md` with one line per user-visible change, linking to the affected docs page.
4. Bump the `last_updated:` front matter at the top of every page you touch to today's date.
5. Screenshots live in `docs/screenshots/`. Reference from top-level pages with `screenshots/name.png` and from nested pages with `../screenshots/name.png`.
6. GitHub Pages is published by `.github/workflows/docs.yml` after Pages is enabled for the repository.

## Page conventions

- Open with a one-sentence summary of what the feature does.
- Include a "Where to find it" section for menu items.
- Prefer exact menu names from the app.
- Keep wording source-neutral unless a feature is specifically about F95Zone or JoiPlay.

## Feature map

| Feature | Page |
| --- | --- |
| First-run welcome and F95 Updater migration | `docs/getting-started.md` |
| Installed games list, status colors, search, multi-select | `docs/main-screen.md` |
| Manual matching dialog | `docs/mapping/manual-search.md` |
| Paste page URL | `docs/mapping/paste-url.md` |
| "Not in catalog" flag | `docs/mapping/not-in-catalog.md` |
| Catalog sync and source catalogs | `docs/catalog/sync.md` |
| Refresh installed games from catalog | `docs/catalog/refresh.md` |
| Catalog filters | `docs/catalog/browse-filter.md` |
| Review unmapped games | `docs/catalog/review-unmapped.md` |
| Auto-hide non-games | `docs/catalog/auto-hide.md` |
| JoiPlay install/import/settings/delete | `docs/joiplay/*.md` |
| APK install helper | `docs/installs/install-apk.md` |
| Backup import/export and auto-backups | `docs/backup/*.md` |
| Drop-in `app_config.json` | `docs/backup/app-config.md` |
| Logs, diagnostics, optional upload, screenshots | `docs/diagnostics/logs.md` |
| App self-update | `docs/self-update.md` |
