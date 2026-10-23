# Minecraft 26.3 friends guide

Everything you need to play on our Java Edition survival server is on this page. The server runs the gameplay datapacks and plugins, so **you do not need to install any mods or datapacks**. The resource pack below is optional and makes your game look like the host's.

## Get started

1. Launch **Minecraft: Java Edition 26.3**.
2. Ask the host for the current server address and add it under **Multiplayer → Add Server**. The address is shared privately and is not published here.
3. For matching visuals, download [Friends Survival resource pack](https://github.com/gypsymagic236/minecraft-26.3-friends-pack/releases/latest/download/Friends-Survival-26.3.zip). In Minecraft, open **Options → Resource Packs → Open Pack Folder**, put the ZIP there **without extracting it**, and move it into the active column.
4. Join the server. The welcome guide appears every time you join; type `/trigger mcguide` to see it again.

The resource pack changes visuals on your own computer; gameplay features below run on the server.

## Controls and commands

Type commands in Minecraft chat (press **T**). **Sneak** means your normal sneak key, usually **Left Shift** unless you changed it.

### Inventory and chests

| Feature | What to do |
| --- | --- |
| Sort your inventory | `/neatsort inv` — manual only; leaves your hotbar alone |
| Sort an open chest | **Shift + left-click** an empty chest slot |
| Put matching items into an open chest | **Shift + right-click** an empty chest slot |
| Pull everything from an open chest | **Left-click outside** its slots |
| Put away items into an open chest | **Right-click outside** its slots to push as much as will fit |

### Mining and building

| Feature | What to do |
| --- | --- |
| VeinMiner | **Sneak while mining ore**; up to 32 connected ore blocks; each block uses tool durability |
| Excavating | **Sneak with an Excavating-enchanted pickaxe or shovel** to mine a 3 × 3 × 3 area; each block uses durability |
| Timber | Break a tree with an axe **while standing** to fell it; leaves clear and saplings drop as items |

### Travel and waypoints

| Feature | What to do |
| --- | --- |
| Waypoint markers | `/trigger waypoint` opens personal and global markers |
| Rename a waypoint | Stand within 4 blocks and type `/wpname <new name>`; free to rename |
| Crafted Waystones | Craft and place a Waystone, then use it to travel to another in the **same dimension** |
| Set and use your one home | `/trigger sethome` and `/trigger homes` |
| Return to a previous location | `/trigger back`; after a final death it returns to the death location |

Waystones are public by default, free to use after crafting, unlimited per player, and anyone can break a placed one. The recipe uses **1 Lodestone, 1 Eye of Ender, 2 Amethyst Shards, and 3 matching base blocks**. Other travel commands are instant and have no cooldown.

### Playing together

| Feature | What to do |
| --- | --- |
| Request player teleport | Type `/trigger tpa set `, press **Tab** to see player IDs, then enter the chosen ID |
| Revive a friend | **Sneak near** a glowing, downed player for 2 seconds; you have 45 seconds before they die |

### Help and displays

| Feature | What to do |
| --- | --- |
| Player guide | `/trigger mcguide` |
| Toggle the coordinates HUD | `/trigger ch_toggle`; `/trigger ch_help` shows its options |

## Things that happen automatically

- One player sleeping skips the night. A sleep message appears in chat after five seconds.
- Health appears below player names. Low durability gives an action-bar warning and sound for held gear and armor.
- Villager deaths are announced with coordinates; nearby wandering traders are announced; idle players appear gray.
- Mobs have spawn animations and sounds. Players can crawl while downed.
- Survival difficulty is **Normal**, PvP is off, and items drop on death.

## See it in action

| [VeinMiner](https://modrinth.com/project/OhduvhIc) | [Excavating](https://modrinth.com/project/pKiI1vdn) | [Spawn Animations](https://modrinth.com/datapack/spawn-animations) |
| :---: | :---: | :---: |
| <a href="https://modrinth.com/project/OhduvhIc"><img src="https://cdn.modrinth.com/data/OhduvhIc/images/f4c0ad7fa3b8b579753c1f757e80151798717c68.gif" alt="VeinMiner breaking a connected ore vein" width="250"></a> | <a href="https://modrinth.com/project/pKiI1vdn"><img src="https://cdn.modrinth.com/data/pKiI1vdn/images/f1f300f8855d1a8f469dd418a193089d723c2453.gif" alt="Excavating enchant mining a larger area" width="250"></a> | <a href="https://modrinth.com/datapack/spawn-animations"><img src="https://i.imgur.com/X8A0UY9.gif" alt="A Stray digging out of the ground as it spawns" width="250"></a> |

## Server datapacks and plugins

These are installed on the server. **Do not put them in your Minecraft resource-packs folder.** The list reflects the latest local audit of the server files; the host may update it later.

| Area | Installed features |
| --- | --- |
| Travel and finding places | Back, Better Waypoints (markers only), Coordinates HUD, Custom Nether Portals, Elevators, Homes, Nether Portal Coords, Spawn, TPA, crafted Waystones |
| Mining, building, and farming | Armor Statues, Armored Elytra, Cauldron Concrete, Cauldron Mud, Chunk Loaders, Fast Leaf Decay, Glass Always Drops, More Effective Tools, Painting Picker, Redstone Rotation Wrench, Silk Touch Budding Amethyst, Timber, Villager Workstation Highlights, Wood Stripper, XP Bottling |
| Drops and recipes | Double Shulker Shells, Dragon Drops, Ender Chest Always Drops, Husks Drop Sand, Kill Empty Boats, Unlock All Recipes |
| Status and convenience | AFK Display, Durability Ping, Health Indicator, Multiplayer Sleep, Real Time Clock, Silence Mobs, Simple Revive, Spawn Animations, Spawning Spheres, Track Raw Statistics, Track Statistics, Villager Death Messages, Wandering Trader Announcements |
| Server guide | Welcome Guide (the join message and `/trigger mcguide`) |

The four server plugins are **NeatSort**, **SmartStash**, **VeinMiner**, and **Excavating Enchant**. All sorting is manual. The table above covers the main commands and controls; other packs mainly change recipes, drops, displays, or automatic behavior.

## Credits and updates

The downloadable visual pack is customized from [Vanilla Tweaks](https://vanillatweaks.net/). It is free. See [their terms](https://vanillatweaks.net/terms/) and the `credits.txt` inside the ZIP. Server features come from [Vanilla Tweaks datapacks](https://vanillatweaks.net/picker/datapacks/) and the linked projects: [NeatSort](https://modrinth.com/project/ZgbYoHqH), [SmartStash](https://modrinth.com/project/XYbeLI5P), [VeinMiner](https://modrinth.com/project/OhduvhIc), [Excavating Enchant](https://modrinth.com/project/pKiI1vdn), [Better Waypoints](https://modrinth.com/datapack/better-waypoints), [Waystones](https://modrinth.com/project/UKUcgltR), [Simple Revive](https://modrinth.com/project/x1IFRoPF), [Spawn Animations](https://modrinth.com/project/zrzYrlm0), and [Health Indicator](https://modrinth.com/project/hxaUKE37).

When the host posts an updated pack, download the latest release and replace the old ZIP in your resource-packs folder. Your world saves and server datapacks stay on the server.
