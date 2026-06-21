# Aetherial Convergence — Mod Roster

Curated from `docs/CONCEPT.md`. Availability is for **Minecraft 1.20.1 / Forge**.
Legend: ✅ available · ⚠ caveat · ❌ not on this version (substitute noted).

## Core Roster (from the concept table)

| Category | Mod | Role | 1.20.1 Forge |
|----------|-----|------|--------------|
| Technology | Create | Kinetic engineering (early–mid) | ✅ |
| Technology | Mekanism | Endgame ore processing + power | ✅ |
| Magic | Ars Nouveau | Spellcraft + magical automation | ✅ |
| Magic | Botania | Flora-based resource generation | ✅ |
| Exploration | Terralith | Vanilla-friendly Overworld overhaul | ✅ |
| Exploration | L_Ender's Cataclysm | Boss encounters + dungeons | ✅ |
| Logistics | Applied Energistics 2 | Digital storage + autocraft | ✅ |
| QoL | Sophisticated Backpacks | Portable upgradeable storage | ✅ |
| Combat | Better Combat | Melee animation overhaul | ✅ |
| Worldgen | Deeper and Darker | Deep Dark → explorable dimension | ✅ |
| Farming | Farmer's Delight | Cooking + food progression | ✅ |

## ⚠ Loader corrections (concept named Fabric mods)

The concept lists **Sodium & Iris** for performance/shaders. Those are **Fabric** mods and will **not** run on Forge 1.20.1. Use the Forge equivalents:

| Concept (Fabric) | Forge 1.20.1 replacement | Status |
|------------------|--------------------------|--------|
| Sodium | **Embeddium** | ✅ |
| Iris | **Oculus** | ✅ |

## Integration & QoL adds (recommended)

| Mod | Role | 1.20.1 Forge |
|-----|------|--------------|
| KubeJS | Cross-mod recipe gating + custom Aetherial Star | ✅ |
| Jade | Look-at tooltips | ✅ |
| JEI or REI | Recipe viewer | ✅ |
| FerriteCore / ModernFix | Memory + load optimization | ✅ |
| Citadel | (dep if Alex's mods are added) | ✅ |

## Notes

- Concept progression (6 steps): Survival → Create kinetic → Ars/Botania → AE2 (Botania crystals) → dimensional expeditions (Cataclysm cores → Mekanism casings) → **The Convergence** (Aetherial Star).
- The Deep Dark gatekeeping ("don't enter without an iron farm + storage net + Tier-2 spells") should be enforced via **KubeJS** difficulty/recipe scripts, not just documentation.
