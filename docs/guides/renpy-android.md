---
title: Ren'Py games on Android
last_updated: 2026-10-08
---

# Ren'Py games on Android

AGM can keep compatible Ren'Py games visible in the same library as installed
Android games while JoiPlay handles execution.

## A safer workflow

1. Keep the original archive until the game launches and your saves are
   confirmed.
2. Install the current JoiPlay app and required Ren'Py plugin from their
   official source.
3. Use AGM's local install flow to select the archive you already possess.
4. Review whether AGM proposes a new install or replacement before confirming.
5. Match the installed game to a catalog entry if automatic matching cannot
   prove the identity.
6. Before upgrades or save edits, keep AGM's generated backup and any
   game-specific save export.

## Patches

AGM only applies a selected Ren'Py patch archive when it can prove that the
patch belongs to exactly one installed game. Game identity and version
compatibility are separate checks; an unproven version is refused rather than
guessed. Replaced files receive a verified rollback point.

## Limits

Not every desktop Ren'Py game is compatible with Android or JoiPlay. Custom
native modules, unusual launchers, and engine modifications can still require
game-specific support.
