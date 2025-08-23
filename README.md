# Metachickens Plugin

The **Metachickens Plugin** is a Minecraft plugin designed to enhance gameplay by introducing genetic modifications and unique mechanics involving chickens and mob spawners. This plugin provides new crafting recipes, interaction mechanics, and random effects to make your Minecraft world more dynamic and fun.

## Features

- **DNA Bottles**: Collect DNA from mobs by right-clicking with a glass bottle, used for genetic modifications.
- **Genetically Modified Chickens**: Inject DNA into baby chickens to create "Metachickens" with random damage or death risks.
- **Dynamic Spawn Eggs**: DNA-modified chickens lay spawn eggs of the injected entity type instead of regular eggs.
- **Spawner Recipes**: Craft spawners using 8 iron bars and a spawn egg of the desired mob.
- **Silk Touch Spawners**: Harvest spawners with Silk Touch while retaining the entity type.

## Installing

Currently, the only way to install the plugin is to [build it from source](CONTRIBUTING.md#build-from-source).

## Configuration

No additional configuration is required! The plugin works out of the box.

## Compatibility

- **Minecraft Version**: 1.20 or higher
- **API**: Built using the Bukkit/Spigot API.

## How to Use

### Collecting DNA

1. Right-click a mob with a glass bottle to collect its DNA.
2. DNA bottles display the type of DNA collected.

### Creating Metachickens

1. Right-click a baby chicken with a DNA bottle.
2. The chicken becomes a "Metachicken" with the injected DNA:
   - It lays spawn eggs of the injected mob.
   - It has a small chance of dying or taking damage during modification.

### Crafting Spawners

1. Gather 8 iron bars and the spawn egg of the mob you want to spawn.
2. Use the crafting table to create the spawner using the following recipe:  

```
III
IEI
III
```
- `I`: Iron Bars  
- `E`: Spawn Egg

### Harvesting Spawners

1. Use a Silk Touch-enchanted tool to break a spawner.
2. The spawner will drop as an item that retains the entity type.

## Contribution

We welcome contributions!  
Feel free to fork the project, submit pull requests, or report issues on our [GitHub repository](https://github.com/beduality/metachickens).

---

[Contribute](CONTRIBUTING.md) | [License](LICENSE)
