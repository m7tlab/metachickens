---
description: A detailed, chronological record of all changes made to a project, often including technical information.
---

# Changelog

## [Unreleased]

### Added

- **Implemented spawner crafting** for all mobs.
  - Crafted using a **spawn egg** of a specific mob and eight **iron bars** in a crafting grid.
- **Added spawner harvesting** with a **silk touch** pickaxe.
  - Breaking a spawner with a silk touch enchanted pickaxe now drops the spawner item, which retains its mob type.
- **Introduced DNA Bottles**.
  - Right-clicking any living mob with a **glass bottle** now gives you a **DNA Bottle** containing that mob's genetic data.
  - Right-clicking a baby chicken with a DNA Bottle will consume the bottle and create a **Metachicken** with the corresponding mob's DNA.
- **Adjusted chicken egg-laying behavior**.
  - Metachickens now lay **spawn eggs** of the mob whose DNA they carry, replacing the standard egg drops.
- **Added an element of risk** to the metachicken creation process.
  - The process has a **30% chance** to instantly kill the baby chicken.
- **Added a safeguard** to prevent **player DNA** from being used.
  - If a player's DNA is collected, it will default to **zombie DNA** instead.
