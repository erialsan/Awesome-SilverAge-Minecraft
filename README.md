---
type: "guide"
title: "Awesome SilverAge Minecraft"
description: "A curated list of mods, tools, and resources for Minecraft 1.0–1.12.2."
tags: ["minecraft", "awesome-list", "1.7.10", "1.12.2"]
status: "draft"
sources: [{"resource": "https://github.com/erialsan/1.7.10-Essential-mods"}, {"resource": "https://cleanroommc.com/wiki/end-user-guide/preparing-your-modpack"}, {"resource": "https://github.com/sindresorhus/awesome/blob/main/awesome.md"}]
---

# Awesome SilverAge Minecraft [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of mods, tools, and resources for Minecraft's SilverAge (1.0–1.12.2).

Keep older Minecraft versions playable, maintainable, and enjoyable with community-maintained fixes, modern runtimes, rendering improvements, and development tools. Initial coverage focuses on **1.7.10** and **1.12.2**.

This is a resource list, **not an install-everything modpack**. Check each project's supported versions and dependencies, and back up worlds before changing your setup.

## Contents

- [Minecraft 1.7.10](#minecraft-1710)
  - [Runtime and Infrastructure](#runtime-and-infrastructure)
  - [Performance and Fixes](#performance-and-fixes)
  - [Interface and Recipes](#interface-and-recipes)
  - [Libraries](#libraries)
- [Minecraft 1.12.2](#minecraft-1122)
  - [Runtime and Rendering](#runtime-and-rendering)
  - [Optimization and Fixes](#optimization-and-fixes)
- [Communities and Documentation](#communities-and-documentation)
- [Development Tools](#development-tools)
- [Blogs](#blogs)
- [Compatibility Notes](#compatibility-notes)
- [Contributing](#contributing)
- [Knowledge Format](#knowledge-format)
- [License](#license)

## Minecraft 1.7.10

Based on [1.7.10 Essential Mods](<https://github.com/erialsan/1.7.10-Essential-mods>) and its [detailed guide](<https://github.com/erialsan/1.7.10-Essential-mods/blob/main/docs/index.html>). Individual notes record source caveats and dependencies.

### Runtime and Infrastructure

- [lwjgl3ify](<https://github.com/GTNewHorizons/lwjgl3ify>) - Run 1.7.10 with modern Java and LWJGL 3. [Notes](<mods/1.7.10/lwjgl3ify.md>).
- [UniMixins](<https://github.com/LegacyModdingMC/UniMixins>) - Consolidated Mixin bootstrapping for legacy mods. [Notes](<mods/1.7.10/unimixins.md>).
- [JarJar](<https://github.com/GTNewHorizons/JarJar>) - Jar-in-Jar plugin for RetroFuturaBootstrap. [Notes](<mods/1.7.10/jarjar.md>).
- [EndlessIDs](<https://github.com/GTMEGA/EndlessIDs>) - Expand ID limits for larger modded environments. [Notes](<mods/1.7.10/endlessids.md>).

### Performance and Fixes

- [Angelica](<https://github.com/GTNewHorizons/Angelica>) - Modern rendering improvements for 1.7.10. [Notes](<mods/1.7.10/angelica.md>).
- [ArchaicFix](<https://github.com/embeddedt/ArchaicFix>) - Improvements targeting memory usage, stutter, and other legacy issues. [Notes](<mods/1.7.10/archaicfix.md>).
- [BugTorch](<https://github.com/jss2a98aj/BugTorch>) - Collection of Minecraft bug fixes. [Notes](<mods/1.7.10/bugtorch.md>).
- [CoreTweaks](<https://github.com/GTNewHorizons/CoreTweaks>) - Startup improvements and crash-related fixes. [Notes](<mods/1.7.10/coretweaks.md>).
- [Hodgepodge](<https://github.com/GTNewHorizons/Hodgepodge>) - Fixes and optimizations for Minecraft and other mods. [Notes](<mods/1.7.10/hodgepodge.md>).

### Interface and Recipes

- [InventoryBogoSorter](<https://github.com/GTNewHorizons/InventoryBogoSorter>) - Inventory sorting and organization. [Notes](<mods/1.7.10/inventory-bogo-sorter.md>).
- [NotEnoughItems Unofficial](<https://github.com/GTNewHorizons/NotEnoughItems>) - GTNH-maintained item and recipe browser. [Notes](<mods/1.7.10/nei-unofficial.md>).

### Libraries

Install libraries when required by the mods you use, rather than as standalone optimizations.

- [ChunkAPI](<https://github.com/FalsePattern/ChunkAPI>) - API for custom chunk data. [Notes](<mods/1.7.10/chunkapi.md>).
- [GTNHLib](<https://github.com/GTNewHorizons/GTNHLib>) - Shared library used by GTNH-related mods. [Notes](<mods/1.7.10/gtnhlib.md>).
- [ModularUI2](<https://github.com/GTNewHorizons/ModularUI2>) - GUI framework for mod developers. [Notes](<mods/1.7.10/modularui2.md>).

## Minecraft 1.12.2

Includes Cleanroom-based modernization and Forge-oriented fixes. Check the supported loader and release series for each project.

### Runtime and Rendering

- [Cleanroom](<https://cleanroommc.com>) - Modernized runtime and loader ecosystem for 1.12.2. [Notes](<mods/1.12.2/cleanroom.md>).
- [Celeritas](<https://git.taumc.org/embeddedt/celeritas>) - Terrain rendering improvements. [Notes](<mods/1.12.2/celeritas.md>).
- [Demonica](<https://github.com/ndellagrotte/Demonica>) - Iris-derived shader support for Cleanroom and Celeritas. [Notes](<mods/1.12.2/demonica.md>).
- [Pulsar](<https://github.com/Sumire-Labs/Pulsar>) - Starlight/SuperNova-derived lighting engine for Cleanroom. [Notes](<mods/1.12.2/pulsar.md>).

### Optimization and Fixes

- [Chibi](<https://www.curseforge.com/minecraft/mc-mods/chibi>) - Memory optimizations and crash-related fixes; formerly LoliASM. [Notes](<mods/1.12.2/chibi.md>).
- [PaperFixes](<https://github.com/Elephant1214/PaperFixes>) - CraftBukkit, Spigot, and Paper fixes ported to a Forge mod. [Notes](<mods/1.12.2/paperfixes.md>).
- [StellarCore](<https://github.com/NovaEngineering-Source/StellarCore>) - Client/server performance improvements and mod compatibility fixes. [Notes](<mods/1.12.2/stellarcore.md>).
- [Universal Tweaks](<https://github.com/ACGaming/UniversalTweaks>) - Configurable collection of bug fixes and tweaks. [Notes](<mods/1.12.2/universal-tweaks.md>).
- [VintageFix](<https://github.com/embeddedt/VintageFix>) - Startup, resource-loading, and memory improvements. [Notes](<mods/1.12.2/vintagefix.md>).

## Communities and Documentation

- [GTNewHorizons on GitHub](<https://github.com/GTNewHorizons>) - Many maintained mod forks, libraries, and development tools. GTNH forks can have pack-specific changes and are not automatically drop-in replacements. [Notes](<resources/gtnh-github.md>).
- [GT New Horizons Wiki](<https://wiki.gtnewhorizons.com/wiki/Main_Page>) - Community documentation for installing, running, and playing the 1.7.10 GTNH modpack. [Notes](<resources/gtnh-wiki.md>).
- [CleanroomMC](<https://cleanroommc.com>) - Official entry point for the loader, community mods, downloads, and documentation. [Notes](<resources/cleanroom-site.md>).

## Development Tools

- [Legacy-Modding-Skills](<https://github.com/erialsan/Legacy-Modding-Skills>) - Agent Skills by erialsan for migrating 1.7.10/1.12.2 mod build environments using GTNH and CleanroomMC templates. [Notes](<resources/legacy-modding-skills.md>).

## Blogs

- [渡海工場事務所](<https://madoha-4862.hatenablog.jp/about>) - Japanese-language blog covering Angelica, rendering tests, and shaders for legacy Minecraft. [Notes](<resources/tokai-blog.md>).

## Compatibility Notes

- **Cleanroom is a runtime/loader, not an ordinary optimization mod.** Follow the [official migration guide](<https://cleanroommc.com/wiki/end-user-guide/preparing-your-modpack>) and the requirements for your chosen release.
- **Demonica requires Cleanroom 0.7.x and Celeritas.** Pulsar also has specific Cleanroom version requirements; see its [notes](<mods/1.12.2/pulsar.md>).
- **Do not combine Pulsar with other lighting engines or OptiFine.** Follow the upstream incompatibility list.
- **StellarCore, VintageFix, and Chibi have overlapping features.** Review the [configuration notes](<mods/1.12.2/stellarcore.md>) before combining them.
- Celeritas auto-builds are explicitly described as high-risk by their distributor; do not mistake them for tagged stable releases.
- Source review does **not** establish runtime compatibility. Launch, performance, and combined-installation tests have not been performed for this list.

## Contributing

Suggest resources you can recommend, not just everything available. Include the supported Minecraft version, official project link, a short description, and sources for dependency or compatibility claims. Distinguish upstream documentation from personal measurements and third-party guides.

For a new entry, add an OKF concept document, link it from this list and the [index](<index.md>), and record the change in the [log](<log.md>). Keep descriptions in English; label non-English resources. Document verified conditions rather than promising universal compatibility.

## Knowledge Format

This repository is an [Open Knowledge Format v0.2](<https://raw.githubusercontent.com/fabricioctelles/skills/main/skills/okf-open-knowledge-format/references/spec-v02.md>) bundle. Each mod or resource has a separate concept document with YAML metadata, citations, and ordinary Markdown links.

- [Index](<index.md>) - All concept documents.
- [Log](<log.md>) - Dated changes.

`status: draft` describes the review state of these documents, **not** the development status of the linked projects. Source-check dates do not imply installation or benchmark testing.

## License

[Unlicense](<LICENSE>). Linked projects, articles, and documentation retain their own licenses and terms.
