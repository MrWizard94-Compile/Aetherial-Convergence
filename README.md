# Aetherial Convergence

> Technology and magic are two sides of the same coin. A tightly-curated, anti-bloat pack where heavy KubeJS scripting forces Create, Botania, Ars Nouveau, Mekanism, and AE2 to depend on each other.

**Minecraft 1.20.1 · Forge 47.x · CurseForge-format modpack**

## Overview

| Spec | Detail |
|------|--------|
| Title | Aetherial Convergence |
| Version | Minecraft 1.20.1 |
| Loader | Forge 47.x |
| Primary focus | Tightly-integrated tech + magic (anti-bloat) |
| Difficulty | Scaling threat; gatekept dimensions |
| Pack version | 0.1.0 (foundation) |

Endgame goal: craft the **Aetherial Star** (custom item) requiring both Mekanism fusion power and Tier-4 Ars Nouveau rituals — stabilizing worldgen and granting flight rings + unbreakable tools.

## Repository layout

| Path | Purpose |
|------|---------|
| `manifest/manifest.json` | CurseForge manifest (Forge 1.20.1). `files[]` resolved at packaging time. |
| `overrides/config/` | Pack configs (committed) |
| `overrides/mods/` | Local mod jars (gitignored; `.gitkeep` tracked) |
| `docs/CONCEPT.md` | Original design vision (incl. 6-step gameplay guide) |
| `docs/MODLIST.md` | Curated mod roster + Forge 1.20.1 availability notes |

## Status

🌱 **Foundation scaffolded.** Structure, manifest, and curated roster in place. Mod `files[]` not yet resolved to CurseForge IDs — see `docs/MODLIST.md`. The custom Aetherial Star recipe + cross-mod gating are KubeJS work under `overrides/kubejs/`.

## Building / CurseForge export

1. Drop mod jars into `overrides/mods/` to test in a local Forge 1.20.1 instance.
2. Resolve each mod's `projectID` / `fileID` into `manifest/manifest.json` `files[]`.
3. Zip `manifest.json` + `overrides/` per the CurseForge modpack spec; publish via the CurseForge author dashboard.

## Related

- [JanusPrime orchestration](https://github.com/MrWizard94-Compile/JanusPrime)
- Sibling concept packs: Aethelgard, Aetheria, Chronicles of the Shattered Cosmos, Omniverse Odyssey
