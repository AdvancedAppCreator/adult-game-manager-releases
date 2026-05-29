---
title: Permissions
last_updated: 2026-05-29
---

# Permissions

Adult Game Manager asks Android for permissions only when a feature needs access to local apps, files, or app installation.

## Installed apps

The app needs to see installed applications so it can list APK games and compare them with catalog entries. Android may show this as an installed-apps visibility permission depending on the device and Android version.

## Files and folders

File access is used for local APKs, JoiPlay archives, `.joiback` backups, exported backups, saved diagnostics, screenshots, and optional drop-in config files.

Use the Android picker when possible. If a device requires broader storage access for a workflow, grant it only if you are comfortable with that access.

## Installing APKs

If you use **Install APK**, Android may ask you to allow installs from the browser, file manager, or Adult Game Manager. This is an Android system prompt. Adult Game Manager does not bypass Android's installer.

## Diagnostics upload

Diagnostics upload is not automatic. Upload actions only appear when upload settings are configured, and uploads happen only after you tap the upload action.
