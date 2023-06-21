# MineKhan-Modded-TESTING
This is a fork from a minecraft simulator (see [bottom](https://github.com/roamingBug666/MineKhan-Modded-TESTING/edit/main/README.md#the-original-code))

## To-Do

### **General**
 - [ ] Make adjacent glass blocks/panes merge inner borders
 - [ ] Make lapis ore drop multiple lapis (random between 4 and 8)
 - [x] For now it drops itself and can be crafted for 6 lapis
 - [ ] Make block damage only activate when on direct collision, not on the blocks around
 - [ ] Make magma only hurt when not crouching, and remove drowning
 - [x] Enable spectator shortcut "L" in survival when cheats are enabled
 - [ ] Make 3rd person not look like a grass and
 - [ ] STOP THE BOBBING cuz it looks terrible
 - [x] Change release pointer for screenshot to a more accessible key
 - [ ] Implement mob drops
 - [ ] Add the popups to hotbar items too
 - [ ] Implement swords
 - [ ] Implement axes
 - [ ] Implement shovels
 - [x] Add goldPickaxe to breakTypes
 - [ ] Migrate all sounds to local file for offlineivity, independency, and resources
 - [ ] Make the textures originate from a texture atlas
 - [ ] Make ores spawn in veins
 - [x] 
 - [x] Make skeletons spawn naturally
 - [x] Make spiders spawn naturally
 - [ ] Include height for creeper explosions (mining underground, above they reking your base)
 - [ ] Make creepers spawn naturally (when previous is done)
 - [x] Add hidden command to toggle cheats (cheats true/false)
 - [ ] Add chest mechanics (for multiple chests)
 - [ ] Creation menu:
   * [x] Add cheats switch
   * [ ] Make it work
   * [ ] Add bonus chest option
   * [ ] Make it work
 - [ ] Make mobs 2 blocks tall (no arms/legs yet)
 - [ ] Make endermen 3 blocks tall and a better aggro mechanism
 - [ ] Make mobs actually hurt the player, and spawn them only in >7 light level blocks
 - [ ] Make wheat drop wheat item
 - [ ] Add bread (crafted from 3 wheat)
 - [ ] Make creepers explode properly
 - [ ] Add explosion particles and effects
 - [ ] Make exploding TNT ignite (and launch) other TNT inside radius instead of destroying it too
 - [ ] Make mobs take block damage like the player (lava, magma, cacti, wither roses, etc.)
 - [ ] Pare mobs's jump heights down to 1,25 (jump over blocks with more ease but not over fences)
 - [ ] Implement at least rudimentary mob pathfinding
 - [ ] Up fences's hitbox heights to 1,5
 - [ ] Limit what forms can different blocks take (fences, slabs, stairs) to shorten the enter cycle and to actually not have pickaxe stairs
 - [ ] Have the ability to climb down ladders as well (`SHIFT`)
 - [ ] Add blocks:
   * [ ] Sea life blocks like coral (blocks, fans, coral)
   * [ ] Sea blocks like prismarine (stone, dark, bricks) and sea lanterns
   * [ ] Chests that can store stuff (and are saved in the saveString)
   * [ ] Candles
   * [ ] Clay, and bricks
   * [ ] Smow, snow blocks, snow grass, powdered snow, and powdered snow in a bucket
   * [ ] Amethyst
   * [ ] Terracotta (all colors)
   * [ ] Bamboo (plant, block, door, trapdoor)
   * [ ] Kelp
   * [ ] Sugarcane
   * [ ] Sea pickle
   * [ ] Froglights (yellow, green, purple)
   * [ ] Endstone
 - [ ] Make furnaces, looms, etc. actually rotate
 - [ ] Make leaves despawn when not close to wood
 - [ ] Make some items/blocks not appear on the creative inventory (like SW logs)
### **Crafting**
 - [x] Make the rest of the door crafting recipes and foolproof
 - [x] Make the trapdoor crafting recipes and foolproof
 - [X] Make the blocks to ingots/items crafting recipes
 - [x] Foolproof the flint n steel crafting recipe
 - [x] Make the crafting table crafting recipes and foolproof
 - [x] Foolproof the stick crafting recipe
 - [ ] Make the furnace crafting recipe
 - [x] netheritePickaxe (Experimental - diamond pick, two iron picks, and two sticks to craft)
### **Overworld**
 - [ ] Add clouds
 - [ ] Dungeons with spawners that work and loot chest/s
 - [ ] Better gradients and depth to rivers/lakes/oceans
 - [ ] Implement biomes:
   * [ ] Mesa
   * [ ] Decent mountains
   * [ ] Ocean biome
   * [ ] Roofed forest
   * [ ] Bamboo forest
### **Nether**
 - [ ] Add nether mobs
   * [ ] Blazes (um flying fireshooting cubes seem like something i dont want to add yet tho)
   * [ ] Endermen
   * [ ] Nether skeletons
   * [ ] Magma cubes (implement the splitting into smaller cubes)
   * [ ] Ghasts
   * [ ] Maybe piglins, brutes, hoglins, zoglins, etc.

### **End**
 - [ ] Add it (flatter noise for the top and a steeper noise for the underside)
 - [ ] Add the pillars
 - [ ] Add a ton of endermen

## Bugs:
 - [ ] Side torches drop themselves instead of a regular torch
 - [ ] Even when there is a stack in the inventory, new items always appear on the hotbar
 - [ ] Water sides are visible on chunk borders (from the outside of the water)
 - [ ] If you catch your fall with a ladder, you die anyway when you hop down (no way to climb down)
 - [ ] Same when you switch into creative or spectator, fly down, hover, then land down on survival mode
 - [ ] At high speeds you can phase through blocks, especially when you're falling, and then you're falling forever on the other side of bedrock

# The original code
 - [Hacker1234's MineKhan-modded](https://github.com/Hacker1254/MineKhan-Modded)
 - [Thingmaker's MineKhan](https://thingmaker.us.eu.org/)
 - [Willard's MineKhan](https://willard.fun/minekhan/)
