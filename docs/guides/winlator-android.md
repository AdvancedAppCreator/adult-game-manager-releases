---
title: Windows games with Winlator
last_updated: 2026-10-08
---

# Windows games with Winlator

AGM can manage and launch supported Windows game folders through
[Winlator Secure](https://github.com/AdvancedAppCreator/winlator-app).

## Setup

1. Install AGM and Winlator Secure from their official GitHub releases.
2. Complete Winlator Secure's first-launch runtime setup and review its privacy
   and provenance documentation.
3. Add or install a Windows game from local files through AGM.
4. Let AGM create or register the compatible Winlator entry.
5. Adjust container settings only when the game requires them.

AGM can analyze supported Unity 2019-2022 LTS texture metadata without reading
streamed texture payloads or modifying game files. When Winlator advertises
the capability, AGM can configure its container-private texture-limit overlay.

## Keep upgrades recoverable

Do not manually remove the old game folder during an AGM-managed replacement.
Wait until the new copy launches and the launcher registration is confirmed.
If AGM reports a pending recovery, retain both folders and follow the
on-screen resolution flow rather than deleting one manually.
