---
title: Probably unused folders
last_updated: 2026-06-30
---

# Probably unused folders

Probably unused folders helps find JoiPlay game folders that are no longer referenced by your JoiPlay backup.

## Where to find it

Menu -> **JoiPlay ... -> Probably unused JoiPlay folders**.

## What it does

Adult Game Manager reads a JoiPlay backup (`.joiback`) to learn which folders your installed JoiPlay games use, then scans the folder you select. It walks the whole tree and lists the highest-level folders whose contents are not used by any game in the backup — so an unused folder is reported even when it is nested several levels down. Game folders themselves are shown as in use, and their internal files are never flagged.

## Be careful

This is a cleanup aid, not proof that a folder is safe to delete. Check folder contents before removing anything.
