---
type: "mod"
title: "Roughly Enough IDs (REID)"
description: "Extends block, item, biome, potion, and enchantment ID limits using a newer chunk format."
resource: "https://modrinth.com/mod/reid"
tags: ["minecraft", "1.12.2", "id extensions"]
status: "draft"
sources: [{"resource": "https://modrinth.com/mod/reid"}, {"resource": "https://api.modrinth.com/v2/project/reid"}]
generated: {"by": "process:ai-assistant", "at": "2026-11-15T16:30:10+09:00"}
---

# Roughly Enough IDs (REID)

A fork of JustEnoughIDs that extends block, item, biome, potion, and enchantment ID limits on Minecraft 1.12.2. It uses a 1.13-style chunk format with blockstate palettes and integer biome arrays, and adds compatibility for additional mods.

- Target: Minecraft 1.12.2 / Forge
- Category: ID extensions
- Installation side: both client and server
- Distribution: [Modrinth](<https://modrinth.com/mod/reid>)
- Development: [RoughlyEnoughIDs](<https://github.com/TerraFirmaCraft-The-Final-Frontier/RoughlyEnoughIDs>)

## Installation notes

**Removing REID will break worlds saved with it.** Back up worlds before installing, migrating, or changing the mod setup. The project also warns that biome-editing tools such as World Painter may not work with REID worlds.

The project documents a MixinBooter requirement starting with REID 2.0.8. Follow the dependency requirements of the selected release and loader environment. Compatibility with individual mods is version-specific; do not assume support for every build or a safe downgrade to an older world format.

## Sources

- [Modrinth project description](<https://modrinth.com/mod/reid>)
- [Modrinth project metadata and description API](<https://api.modrinth.com/v2/project/reid>)

Sources reviewed: 2026-11-15. This entry is based on documentation; startup, performance, and compatibility have not been tested for this list.

## Related

- [EndlessIDs for Minecraft 1.7.10](<../1.7.10/endlessids.md>)
- [Back to the list](<../../README.md>)
