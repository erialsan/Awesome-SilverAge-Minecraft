---
type: "resource"
title: "CleanroomGradle"
description: "A Gradle plugin for Cleanroom loader development and Cleanroom-targeted Minecraft 1.12.2 mods."
resource: "https://github.com/CleanroomMC/CleanroomGradle"
tags: ["minecraft", "development", "gradle", "1.12.2", "cleanroom"]
status: "draft"
sources: [{"resource": "https://github.com/CleanroomMC/CleanroomGradle/blob/HEAD/README.md"}]
---

# CleanroomGradle

[CleanroomGradle](<https://github.com/CleanroomMC/CleanroomGradle>) is a Gradle plugin for developing the Cleanroom loader and Cleanroom-targeted mods. Its userdev workflow sets up a Minecraft 1.12.2 mod workspace through a selected Cleanroom dependency.

The project documents development runs, dependency deobfuscation, reobfuscated artifacts, Mixin refmap generation, and shared toolchain caches. Loader, userdev, and standalone vanilla workflows have different configuration and tasks.

## Usage Notes

This is build tooling, not an in-game optimization mod. Follow the official README for the selected plugin and Cleanroom versions; do not assume its configuration is interchangeable with RetroFuturaGradle or legacy ForgeGradle.

Named vanilla environments can target other Minecraft versions. That feature does not imply Cleanroom mod-loader support for those versions. Choose the intended environment explicitly and verify both build output and development launches when migrating.

## Sources

- [Official README](<https://github.com/CleanroomMC/CleanroomGradle/blob/HEAD/README.md>).

Source checked: 2026-11-15. No build migration or development launch has been tested for this list.

## Related

- [Cleanroom project notes](<../mods/1.12.2/cleanroom.md>).
- [Cleanroom official website](<cleanroom-site.md>).
- [Legacy-Modding-Skills](<legacy-modding-skills.md>).
- [Back to the list](<../README.md>).
