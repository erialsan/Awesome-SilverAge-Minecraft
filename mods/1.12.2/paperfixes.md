---
type: "mod"
title: "PaperFixes"
description: "Ports bug fixes and performance improvements from CraftBukkit / Spigot / Paper to a Forge mod."
resource: "https://github.com/Elephant1214/PaperFixes"
tags: ["minecraft", "1.12.2", "optimization and fixes"]
status: "draft"
sources: [{"resource": "https://github.com/Elephant1214/PaperFixes/blob/HEAD/README.md"}]
generated: {"by": "process:ai-assistant", "at": "2026-11-15T07:00:51+00:00"}
---

# PaperFixes

Ports bug fixes and performance improvements from CraftBukkit / Spigot / Paper to a Forge mod.

- Target: Minecraft 1.12.2
- Category: optimization and fixes
- Distribution and development: [Official project](<https://github.com/Elephant1214/PaperFixes>)

## Installation notes

This is not a loader for Bukkit plugins. improvedTickLoop may conflict with other tick-loop changes. A conflict with older VintageFix versions' mixin.bugfix.slow_tps_catchup is documented, but that setting was later removed; do not interpret this as a conflict across all versions.

## Sources

- [Reference 1](<https://github.com/Elephant1214/PaperFixes/blob/HEAD/README.md>)

Sources reviewed: 2026-11-15. This entry is based on documentation; startup, performance, and compatibility have not been tested for this list.

## Related

- [VintageFix](<vintagefix.md>)
- [Back to the list](<../../README.md>)
