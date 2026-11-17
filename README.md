# Smooth Particles — unofficial 1.21.1 Fabric port

This project adapts Smooth Particles for Minecraft 1.21.1 on Fabric. It keeps the original `smoothparticles` mod ID and the upstream particle implementation and assets. Do not install it together with another Smooth Particles build.

## What it does

Smooth Particles adds block-placement particles, using small pieces of the placed block's texture. The upstream mod describes these particles as stone pebbles and wood splinters. It is client-side and can be used on multiplayer servers without installing it server-side.

## Requirements

- Minecraft 1.21.1
- Fabric Loader 0.16.10 or newer
- Fabric API
- MidnightLib
- Java 21 or newer

## Attribution and licensing

Original project: [Modrinth](https://modrinth.com/mod/smooth-particles) and [CurseForge](https://www.curseforge.com/minecraft/mc-mods/smooth-particles). The upstream project credits FatCactis and GGcarrothead. The linked successor source repository is [watermelone1/SmoothParticles](https://github.com/watermelone1/SmoothParticles).

The Modrinth and CurseForge project pages identify the mod as MIT-licensed, while the linked successor source repository includes a CC0-1.0 license. This port retains that source repository's CC0-1.0 notice and original assets. The mismatch is disclosed here rather than silently changing the source notice.

This is an unofficial compatibility port and is not endorsed by the original authors. The Minecraft 1.21.1 metadata and dependency declarations were adapted for this port; the original Java implementation and assets are retained.

## Verification

The Minecraft 1.21.1 source compiled and `remapJar` completed successfully with Java 21 and Gradle 8.8. The packaged metadata and icon were checked. No Minecraft client was launched, so in-game particle behavior and mixin application are not yet verified.

AI disclosure: Generative AI assisted with the Minecraft 1.21.1 compatibility metadata and dependency updates. No new AI-generated textures, models, or artwork are included.
