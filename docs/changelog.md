---
title: Changelog
last_updated: 2026-06-30
---

# Changelog

## v1.1.4

- JoiPlay cleanup review ("Probably unused folders") now scans the entire folder tree under the selected root and reports the highest-level folders whose contents are not referenced by any JoiPlay game, instead of only folders sitting next to known games.
- Folders with no games anywhere in their subtree — for example a stray `Swf` folder, even when nested a few levels deep — are now listed.
- Each JoiPlay game folder is treated as an in-use leaf, so files inside a game are never flagged.

## v1.1.3

- Save editor: the Ren'Py editor now reaches values nested inside plugin/character objects (for example CharacterQuestManager character stats), not just top-level `store.*` scalars.
- You can edit stats like relationship/corruption directly, and list items show a name hint. Patched values are re-signed with the save's security key so the game accepts them.

## v1.1.2

- Fixed installing a JoiPlay game failing with "path not found". Extracted games are now passed to JoiPlay by their real folder path, so they import and launch correctly.

## v1.1.1

- Catalog tag labels now sync independently of the legacy catalog, so labels stay complete even when the legacy catalog is frozen.

## v1.1.0

- Catalog v2: data-driven sources, namespaced tag labels, and off-thread catalog search for a faster, more responsive Catalog tab.

## v1.0.91

- Catalog tag labels are now complete for the current F95 catalog; numeric tag/prefix IDs are resolved before publishing `labels.json`.
- Catalog rows hide any unresolved numeric IDs instead of showing raw numbers.
- Added a searchable **Tags** dropdown to the Catalog tab; it lists only tags/prefixes present in loaded catalog entries.
- Catalog **Source** and **Platform** filters are now dropdowns instead of long chip rows.
- Installed-library filters for **Manually matched**, **Thread updated after install**, and **Has saves** are grouped under one Filters dropdown.
- Fixed a Tags dropdown crash caused by putting a lazy list inside a Compose popup.
- Restored fast catalog tag filtering with a cached search index and debounced query updates.

## v1.0.83

- Added manual installed-date controls for installed games.
- Installed dates can be set from the catalog/thread date when available, set with the native Android date picker, or cleared.
- Installed-date overrides expire when the installed evidence fingerprint changes, so a replaced game does not keep a stale manual date.
- Reorganized the game action menu so Launch, Open thread/source, Refresh/check update, Match/notes/status, and Edit are top-level actions.
- Multi-action groups now use clearer side submenus with separated panel styling.

## v1.0.62

- Android 10 storage permission fix: AGM now requests legacy external-storage permissions on Android 10 and below instead of assuming All files access exists.
- Added a persistent installed-library view type toggle in the main menu.
- Card view now uses the cover-first card layout while opening the same full action popup menu as list view.
- Card/list preference is saved across app restarts.

## v1.0.58

- Save editor update.
- Ren'Py and RPGM save editor filters now include a **Whole word** option, so searches like `1` do not also match `10` or `11`.
- Ren'Py and RPGM save edits can optionally overwrite a matching same-name save in a nearby `sync` folder, with a backup made before replacing the sync copy.
- JoiPlay upgrades now record the source archive/version marker, helping AGM avoid stale folder-name version detection after upgrade-in-place flows.
- JoiPlay matching uses additional internal metadata when available, including Ren'Py `build_info`/options and RPGM/HTML titles.

## v1.0.51

- Trust/transparency release.
- Public source ZIP is attached to the GitHub release.
- Added Apache-2.0 project licensing, privacy/permissions notes, third-party notices, checksums, and a GitHub Actions build workflow.
- Public defaults no longer include developer donation/payment links.
- Release signing material and private config are excluded from source.

## v1.0.50

- Open folder now uses Android's native implicit folder-view/default-app flow.
- The folder action no longer forces a specific file manager package.
- If no file manager can open folders, AGM shows a message instead of opening the Android "Use this folder" permission picker.

## v1.0.48

- UI and cleanup release.
- Tapping a game row now opens the grouped Game actions menu.
- The top list summary moved behind an info icon popup to keep the title bar cleaner.
- Main menu labels and save-tool grouping were clarified.
- Android receiver registration lint was fixed.
- Launcher monochrome icon metadata was added.
- Minor stale storage comments/checks were cleaned up.
- SDK target remains unchanged.

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
