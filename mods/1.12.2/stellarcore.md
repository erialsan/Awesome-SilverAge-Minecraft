---
type: "mod"
title: "StellarCore"
description: "A collection of client and server performance improvements and mod compatibility fixes."
resource: "https://github.com/NovaEngineering-Source/StellarCore"
tags: ["minecraft", "1.12.2", "optimization and fixes"]
status: "draft"
sources: [{"resource": "https://github.com/NovaEngineering-Source/StellarCore/blob/master/README.md"}, {"resource": "https://cleanroommc.com/wiki/end-user-guide/preparing-your-modpack"}]
generated: {"by": "process:ai-assistant", "at": "2026-11-15T07:00:51+00:00"}
---

# StellarCore

A collection of client and server performance improvements and mod compatibility fixes.

- Target: Minecraft 1.12.2
- Category: optimization and fixes
- Distribution and development: [Official project](<https://github.com/NovaEngineering-Source/StellarCore>)

## Installation notes

The standard Forge README requires MixinBooter 8.0+ and ConfigAnyTime 2.0+. On Cleanroom, also consult the official guide. Features overlap with VintageFix and the Chibi / LoliASM family; see the configuration notes below.

### Configuration overlap with VintageFix

StellarCore's README instructs users to disable the following VintageFix settings when using the corresponding features.

| StellarCore feature | VintageFix setting to disable |
| --- | --- |
| ParallelModelLoader / StitcherCache | `vintagefix.mixin.dynamic_resources` |
| ParallelTextureLoad | `vintagefix.mixin.textures` |
| ResourceExistStateCache | `vintagefix.mixin.resourcepacks` |

The same README's CensoredASM / LoliASM notes instruct users to disable StellarCore's `general.performance.vanilla.BakedQuadVertexDataCanonicalization` and `general.performance.forge.UnpackedBakedQuadVertexDataCanonicalization` when using LoliVertexDataPool. Recheck configuration names and behavior for your Chibi version.

## Sources

- [Reference 1](<https://github.com/NovaEngineering-Source/StellarCore/blob/master/README.md>)
- [Reference 2](<https://cleanroommc.com/wiki/end-user-guide/preparing-your-modpack>)

Sources reviewed: 2026-11-15. This entry is based on documentation; startup, performance, and compatibility have not been tested for this list.

## Related

- [VintageFix](<vintagefix.md>)
- [Chibi](<chibi.md>)
- [Back to the list](<../../README.md>)
