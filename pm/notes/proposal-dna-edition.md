# **Proposal: DNA Edition Feature**

This proposal outlines a new feature that introduces the ability to modify the DNA bottles, allowing players to create mobs with enhanced attributes, potion effects, and unique behaviors. This builds on the existing core mechanics by adding a layer of depth and customization, making the process of creating Metachickens more strategic and rewarding.

## **Core Concepts**

The new system centers around a new item and a custom crafting mechanic.

### **The Genetic Sequencer**

A new multi-block structure or a single block, called the **Genetic Sequencer**, will be added. This block serves as the dedicated station for all DNA modification. This provides a more immersive and distinct feel for this advanced process.

### **DNA Modifier Items**

A new category of items, **DNA Modifiers**, will be introduced. These are consumable items that, when used in the Genetic Sequencer, apply specific attributes to a DNA bottle. They could be crafted using a variety of rare materials to ensure they are a progression goal for players.

* **Example Crafting Recipe:**  
  * DNA Modifier (Speed): Requires sugar, a blaze rod, and a fermented spider eye.  
  * DNA Modifier (Resistance): Requires a diamond block, a bedrock fragment, and an iron block.

## **Modifiable Attributes and Effects**

The DNA Modifier items can be categorized based on the type of enhancement they provide. When a DNA Modifier is applied to a DNA bottle, the bottle's name, lore, and NBT data are updated to reflect the new attributes.

### **Health and Durability**

* **Extra Health:** Increases the maximum health of the resulting mob. Needs Glistering Melon Slice DNA study.
* **Fire Resistance:** Makes the mob immune to fire damage. Needs Magma Cube DNA study.
* **Defense/Armor:** Adds an armor attribute to the mob, reducing incoming damage.

### **Offensive Capabilities**

* **Increased Damage:** Boosts the base attack damage of the mob.  
* **Knockback:** Adds a knockback attribute to the mob's attacks.  
* **Critical Strike:** Gives the mob a chance to deal critical damage.

### **Mobility and Movement**

* **Jump Height:** Increases the mob's jump height. Needs Rabbit DNA study.
* **Speed:** Boosts the mob's movement speed. Needs sugar cane DNA study.
* **Water Breathing:** Allows the mob to breathe underwater indefinitely. Needs Pufferfish DNA study.
* **Dolphins Grace:** Allows the mob to glide through water. Needs Dolphin DNA study.
* **Levitation:** Makes the mob levitate in the air. Needs Shulker DNA study.
* **Slow Falling:** Makes the mob fall slowly. Needs Phantom DNA study.

### **Potion Effects and Special Properties**

* **Invisibility:** The mob becomes invisible after a short duration. Needs spider DNA study.
* **Regeneration:** The mob regenerates health over time. Needs Axolotl DNA study or Ghast DNA study.
* **Strength:** Applies a strength potion effect to the mob. Needs Blaze DNA study.
* **Night Vision:** Grants the mob permanent night vision. Needs Golden carrot DNA study.

## **Gameplay and Balancing**

* **Tiered Modifiers:** To maintain balance, modifiers could be tiered (e.g., Minor, Major, Potent). Applying a Major Speed modifier would be more effective than a Minor one but would require rarer materials.  
* **Stacking and Limitations:** There should be a configurable limit on how many modifiers can be applied to a single DNA bottle. Applying too many could also increase the "failure rate" risk when creating a Metachicken, making it more likely for the chicken to die.  
* **Configuration:** The entire system should be highly configurable. A new section in the config.yml would allow server administrators to adjust crafting recipes, modifier effects, stacking limits, and risk percentages to fit their server's difficulty.

## **User Experience**

* **Visual Cues:** A modified DNA bottle will have an enhanced texture, an enchanted glint, or custom lore text (e.g., "Modified with \+5 Health and Fire Resistance") to show its new properties.  
* **Mob Feedback:** The resulting Metachicken will also have a visible effect (e.g., particle effects for a speed boost) and the custom attributes will be applied to the mob it spawns.

This feature would significantly enhance the player's journey, making genetic engineering a core and rewarding part of the Metachickens experience.
