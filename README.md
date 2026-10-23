# Minecraft 26.3 friends guide

Everything you need to play on our Java Edition survival server is on this page. The server runs the gameplay datapacks and plugins, so **you do not need to install any mods or datapacks**. The resource pack below is optional and makes your game look like the host's.

## Get started

Darren will privately send you a **Tailscale invitation** and the **server address**. The invitation shares only the server PC, not Darren's other devices. [How Tailscale sharing works](https://tailscale.com/docs/features/sharing)

![Three illustrated steps: install and sign in to Tailscale, accept Darren's invitation, then add the private address with port 25565 in Minecraft](images/connect-with-tailscale.svg)

1. [Install Tailscale](https://tailscale.com/download) on the computer you play on, then **sign in**.
2. Open Darren's invitation link and select **Accept**. Keep Tailscale **connected**.
3. Launch **Minecraft: Java Edition 26.3**. Open **Multiplayer → Add Server**. Enter Darren's private Tailscale address **with `:25565` at the end** (for example, `100.x.y.z:25565`), then join. The server PC and game server must be on.

**Optional matching visuals:** Download the [Friends Survival resource pack](https://github.com/gypsymagic236/minecraft-26.3-friends-pack/releases/latest/download/Friends-Survival-26.3.zip). In Minecraft, open **Options → Resource Packs → Open Pack Folder**, put the ZIP there **without extracting it**, and move it into the active column.

The welcome guide appears every time you join; type `/trigger mcguide` to see it again.

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

| [VeinMiner](https://modrinth.com/project/OhduvhIc) | [Excavating](https://modrinth.com/project/pKiI1vdn) |
| :---: | :---: |
| <a href="https://modrinth.com/project/OhduvhIc"><img src="https://cdn.modrinth.com/data/OhduvhIc/images/f4c0ad7fa3b8b579753c1f757e80151798717c68.gif" alt="VeinMiner breaking a connected ore vein" width="250"></a> | <a href="https://modrinth.com/project/pKiI1vdn"><img src="https://cdn.modrinth.com/data/pKiI1vdn/images/f1f300f8855d1a8f469dd418a193089d723c2453.gif" alt="Excavating enchant mining a larger area" width="250"></a> |

### Travel and waypoints

| Feature | What to do |
| --- | --- |
| Waypoint markers | `/trigger waypoint` opens personal and global markers |
| Rename a waypoint | Stand within 4 blocks and type `/wpname <new name>`; free to rename |
| Crafted Waystones | Craft and place a Waystone, then use it to travel to another in the **same dimension** |
| Set and use your one home | `/trigger sethome` and `/trigger homes` |
| Return to a previous location | `/trigger back`; after a final death it returns to the death location |

Waystones are public by default, free to use after crafting, unlimited per player, and anyone can break a placed one. The recipe uses **1 [Lodestone](https://minecraft.wiki/w/Lodestone), 1 [Eye of Ender](https://minecraft.wiki/w/Eye_of_Ender), 2 [Amethyst Shards](https://minecraft.wiki/w/Amethyst_Shard), and 3 matching base blocks**. Other travel commands are instant and have no cooldown.

**Base blocks:** [Andesite](https://minecraft.wiki/w/Andesite), [Sandstone](https://minecraft.wiki/w/Sandstone), [Nether Bricks](https://minecraft.wiki/w/Nether_Bricks), [Mossy Stone Bricks](https://minecraft.wiki/w/Mossy_Stone_Bricks), [Cobbled Deepslate](https://minecraft.wiki/w/Cobbled_Deepslate), [Copper Block](https://minecraft.wiki/w/Copper_block), [Prismarine Bricks](https://minecraft.wiki/w/Prismarine_bricks), [Tuff](https://minecraft.wiki/w/Tuff), [Red Sandstone](https://minecraft.wiki/w/Red_Sandstone), or [Quartz Block](https://minecraft.wiki/w/Blocks_of_quartz).

| [Better Waypoints](https://modrinth.com/datapack/better-waypoints) | [Waystones](https://modrinth.com/project/UKUcgltR) |
| :---: | :---: |
| <a href="https://modrinth.com/datapack/better-waypoints"><img src="https://i.ytimg.com/vi/mzh78_l_LIQ/hqdefault.jpg" alt="Better Waypoints video preview" width="250"></a> | <a href="https://modrinth.com/project/UKUcgltR"><img src="https://cdn.modrinth.com/data/cached_images/c39228a4b7442b35dfce064f78c56fc180500d28.gif" alt="Waystones crafting recipes" width="250"></a> |

The Better Waypoints video shows its full feature set; this server uses its markers, while crafted Waystones handle travel.

### Playing together

| Feature | What to do |
| --- | --- |
| Request player teleport | `/tpa <playername>`; the other player uses `/tpaccept` or `/tpadeny` |
| Revive a friend | **Sneak near** a glowing, downed player for 2 seconds; you have 45 seconds before they die |

### Help and displays

| Feature | What to do |
| --- | --- |
| Player guide | `/trigger mcguide` |
| Toggle the coordinates HUD | `/trigger ch_toggle`; `/trigger ch_help` shows its options |

## Things that happen automatically

- [Multiplayer Sleep](https://vanillatweaks.net/picker/datapacks/) lets one player skip the night; a sleep message appears in chat after five seconds.
- [Health Indicator](https://modrinth.com/datapack/health-indicator) shows health below player names. [Durability Ping](https://vanillatweaks.net/picker/datapacks/) warns about low durability on held gear and armor with an action-bar message and sound.
- [Villager Death Messages](https://vanillatweaks.net/picker/datapacks/) announces villager deaths with coordinates; [Wandering Trader Announcements](https://vanillatweaks.net/picker/datapacks/) reports nearby arrivals; [AFK Display](https://vanillatweaks.net/picker/datapacks/) grays out idle players.
- [Spawn Animations](https://modrinth.com/datapack/spawn-animations) makes mobs emerge with sounds. [Simple Revive](https://modrinth.com/datapack/player-revive) lets downed players crawl.
- [Clumps](https://modrinth.com/datapack/ly-clumps) combines nearby experience orbs to reduce lag. Instant XP pickup is off so Mending works normally.

| [Health Indicator](https://modrinth.com/datapack/health-indicator) | [Simple Revive](https://modrinth.com/datapack/player-revive) | [Spawn Animations](https://modrinth.com/datapack/spawn-animations) |
| :---: | :---: | :---: |
| <a href="https://modrinth.com/datapack/health-indicator" target="_blank" rel="noopener noreferrer"><img src="https://cdn.modrinth.com/data/hxaUKE37/images/a851f319889e4eccdf8884fce0a294bcb54bfeaa.jpeg" alt="Health points displayed below a player's name" width="220"></a> | <a href="https://modrinth.com/datapack/player-revive" target="_blank" rel="noopener noreferrer"><img src="https://cdn.modrinth.com/data/x1IFRoPF/images/51eb0408f273fb17ebb25a49832bd0025a5be0c6_350.webp" alt="Downed player lying low and able to crawl" width="220"></a> | <a href="https://modrinth.com/datapack/spawn-animations" target="_blank" rel="noopener noreferrer"><img src="https://i.imgur.com/X8A0UY9.gif" alt="A Stray digging out of the ground as it spawns" width="220"></a> |

## Server datapacks and plugins

These are installed on the server. **Do not put them in your Minecraft resource-packs folder.** The list reflects the latest local audit of the server files; the host may update it later.

| Area | Installed features |
| --- | --- |
| Travel and finding places | Back, Better Waypoints (markers only), Coordinates HUD, Custom Nether Portals, Elevators, Homes, Nether Portal Coords, Spawn, crafted Waystones; SimpleTPA handles player requests |
| Mining, building, and farming | Armor Statues, Armored Elytra, Cauldron Concrete, Cauldron Mud, Chunk Loaders, Fast Leaf Decay, Glass Always Drops, More Effective Tools, Painting Picker, Redstone Rotation Wrench, Silk Touch Budding Amethyst, Timber, Villager Workstation Highlights, Wood Stripper, XP Bottling |
| Drops and recipes | Double Shulker Shells, Dragon Drops, Ender Chest Always Drops, Husks Drop Sand, Kill Empty Boats, Unlock All Recipes |
| Status and convenience | AFK Display, Clumps, Durability Ping, Health Indicator, Multiplayer Sleep, Real Time Clock, Silence Mobs, Simple Revive, Spawn Animations, Spawning Spheres, Track Raw Statistics, Track Statistics, Villager Death Messages, Wandering Trader Announcements |
| Server guide | Welcome Guide (the join message and `/trigger mcguide`) |

The server plugins are **NeatSort**, **SmartStash**, **VeinMiner**, **Excavating Enchant**, **SimpleTPA**, and the waypoint renaming helper. All sorting is manual. The table above covers the main commands and controls; other packs mainly change recipes, drops, displays, or automatic behavior.

### Vanilla Tweaks datapacks

The server uses **38 [Vanilla Tweaks datapacks](https://vanillatweaks.net/picker/datapacks/)** from the list above. Examples include **Back and Homes** for travel; **Timber, Armor Statues, and Fast Leaf Decay** for building; **Double Shulker Shells and Dragon Drops** for loot; and **Multiplayer Sleep, AFK Display, and Coordinates HUD** for convenience. Vanilla Tweaks explains each pack in its picker.

## Credits and updates

The downloadable visual pack is customized from [Vanilla Tweaks](https://vanillatweaks.net/). It is free. See [their terms](https://vanillatweaks.net/terms/) and the `credits.txt` inside the ZIP. Server features come from [Vanilla Tweaks datapacks](https://vanillatweaks.net/picker/datapacks/) and the linked projects: [NeatSort](https://modrinth.com/project/ZgbYoHqH), [SmartStash](https://modrinth.com/project/XYbeLI5P), [VeinMiner](https://modrinth.com/project/OhduvhIc), [Excavating Enchant](https://modrinth.com/project/pKiI1vdn), [SimpleTPA](https://modrinth.com/plugin/simple-tpa-vexo), [Better Waypoints](https://modrinth.com/datapack/better-waypoints), [Waystones](https://modrinth.com/project/UKUcgltR), [Simple Revive](https://modrinth.com/project/x1IFRoPF), [Spawn Animations](https://modrinth.com/project/zrzYrlm0), [Health Indicator](https://modrinth.com/project/hxaUKE37), and [Clumps](https://modrinth.com/datapack/ly-clumps).

When the host posts an updated pack, download the latest release and replace the old ZIP in your resource-packs folder. Your world saves and server datapacks stay on the server.
