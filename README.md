# Minecraft 26.3 friends guide

## Get started

> [!TIP]
> **Just joining? This is the only section you need.** You do not need to install mods or datapacks.

![Three illustrated steps: install and sign in to Tailscale, accept Darren's invitation, then add the private address with port 25565 in Minecraft](images/connect-with-tailscale.svg)

1. [Install Tailscale](https://tailscale.com/download) on the computer you play on, then **sign in**.
2. Ask Darren for a **Tailscale invitation** and the **server address**.
3. Open Darren's invitation link and select **Accept**. Keep Tailscale **connected**.
4. Launch **Minecraft: Java Edition 26.3**. Open **Multiplayer → Add Server**.
5. Enter Darren's private Tailscale address **with `:25565` at the end** (for example, `100.x.y.z:25565`), then join.

**Recommended resource pack:** For matching quality of life + visuals, download the [Friends Survival resource pack](https://github.com/gypsymagic236/minecraft-26.3-friends-pack/releases/latest/download/Friends-Survival-26.3.zip). 
In Minecraft, open **Options → Resource Packs → Open Pack Folder**, put the ZIP there **without extracting it**, and move it into the active column.

> [!TIP]
> **You're ready to play. You can stop reading here.** Everything below is an optional reference for mods, commands, and server features.

---

## More Details

**Jump to:** [Mansion Island seed guide](MANSION-ISLAND.md) · [Commands](#controls-and-commands) · [Automatic features](#things-that-happen-automatically) · [Installed packs](#server-datapacks-and-plugins)

### Controls and commands

Type commands in Minecraft chat (press **T**). **Sneak** means your normal sneak key, usually **Left Shift** unless you changed it.

#### Inventory and chests

| Feature | What to do |
| --- | --- |
| Sort your inventory | **Shift + left-click** an empty inventory slot, or **left-click outside** the inventory with an empty cursor; leaves your hotbar alone |
| Sort an open chest | **Shift + left-click** an empty chest slot |
| Put matching items into an open chest | **Shift + right-click** an empty chest slot |

#### Mining and building

| Feature | What to do |
| --- | --- |
| VeinMiner | **Sneak while mining ore**; up to 32 connected ore blocks; each block uses tool durability |
| Excavating | **Sneak with an Excavating-enchanted pickaxe or shovel** to mine a 3 × 3 × 3 area; each block uses durability |
| Timber | Break a tree with an axe **while standing** to fell it; leaves clear and saplings drop as items |

| [VeinMiner](https://modrinth.com/project/OhduvhIc) | [Excavating](https://modrinth.com/project/pKiI1vdn) |
| :---: | :---: |
| <a href="https://modrinth.com/project/OhduvhIc" target="_blank" rel="noopener noreferrer"><img src="https://cdn.modrinth.com/data/OhduvhIc/images/f4c0ad7fa3b8b579753c1f757e80151798717c68.gif" alt="VeinMiner breaking a connected ore vein" width="340"></a> | <a href="https://modrinth.com/project/pKiI1vdn" target="_blank" rel="noopener noreferrer"><img src="https://cdn.modrinth.com/data/pKiI1vdn/images/f1f300f8855d1a8f469dd418a193089d723c2453.gif" alt="Excavating enchant mining a larger area" width="340"></a> |

#### Travel and waypoints

| Feature | What to do |
| --- | --- |
| Waypoint markers | `/trigger waypoint` opens shared markers by default; choose **Place Waypoint** to add one for everyone. Personal markers remain available from the menu. |
| Rename a waypoint | Stand within 4 blocks and type `/wpname <new name>`; free to rename |
| Travel to a waypoint | Select a personal or global marker in `/trigger waypoint`; travel is free, including across dimensions |
| Set and use your one home | `/trigger sethome` and `/trigger homes` |
| Return to a previous location | `/trigger back`; after a final death it returns to the death location |

Travel commands are instant and have no cooldown. New waypoint markers are shared by default.

| [Better Waypoints](https://modrinth.com/datapack/better-waypoints) |
| :---: |
| <a href="https://modrinth.com/datapack/better-waypoints" target="_blank" rel="noopener noreferrer"><img src="https://i.ytimg.com/vi/mzh78_l_LIQ/hqdefault.jpg" alt="Better Waypoints preview" width="340"></a> |

#### Playing together

| Feature | What to do |
| --- | --- |
| Request player teleport | `/tpa <playername>`; the other player uses `/tpaccept` or `/tpadeny` |
| Revive a friend | **Sneak near** a glowing, downed player for 2 seconds; you have 45 seconds before they die |

#### Help and displays

| Feature | What to do |
| --- | --- |
| Player guide | `/trigger mcguide` |
| Toggle the coordinates HUD | `/trigger ch_toggle`; `/trigger ch_help` shows its options |

### Things that happen automatically

- **Sleep:** [Multiplayer Sleep](https://vanillatweaks.net/picker/datapacks/) lets one player skip the night; a sleep message appears in chat after five seconds.
- **Status:** [Health Indicator](https://modrinth.com/datapack/health-indicator) shows health below player names. [Durability Ping](https://vanillatweaks.net/picker/datapacks/) warns about low durability on held gear and armor with an action-bar message and sound.
- **Alerts:** [Villager Death Messages](https://vanillatweaks.net/picker/datapacks/) announces villager deaths with coordinates; [Wandering Trader Announcements](https://vanillatweaks.net/picker/datapacks/) reports nearby arrivals; [AFK Display](https://vanillatweaks.net/picker/datapacks/) grays out idle players.
- **Animations and revives:** [Spawn Animations](https://modrinth.com/datapack/spawn-animations) makes mobs emerge with sounds. [Simple Revive](https://modrinth.com/datapack/player-revive) lets downed players crawl.
- **After a final death:** [Graves](https://vanillatweaks.net/picker/datapacks/) saves your dropped items in a grave where you died; see the Vanilla Tweaks quick guide below to retrieve them.
- **Experience:** [Clumps](https://modrinth.com/datapack/ly-clumps) combines nearby XP orbs to reduce lag. Instant pickup is off so Mending works normally.

| [Health Indicator](https://modrinth.com/datapack/health-indicator) | [Simple Revive](https://modrinth.com/datapack/player-revive) | [Spawn Animations](https://modrinth.com/datapack/spawn-animations) |
| :---: | :---: | :---: |
| <a href="https://modrinth.com/datapack/health-indicator" target="_blank" rel="noopener noreferrer"><img src="https://cdn.modrinth.com/data/hxaUKE37/images/a851f319889e4eccdf8884fce0a294bcb54bfeaa.jpeg" alt="Health points displayed below a player's name" width="220"></a> | <a href="https://modrinth.com/datapack/player-revive" target="_blank" rel="noopener noreferrer"><img src="images/simple-revive-downed.png" alt="A glowing, downed player lying on the ground with the revive timer visible" width="220"></a> | <a href="https://modrinth.com/datapack/spawn-animations" target="_blank" rel="noopener noreferrer"><img src="https://i.imgur.com/X8A0UY9.gif" alt="A Stray digging out of the ground as it spawns" width="220"></a> |

### Server datapacks and plugins

These features run on the server. **Do not put them in your Minecraft resource-packs folder.**

| Area | Installed features |
| --- | --- |
| Travel and finding places | Back, Better Waypoints (free travel), Coordinates HUD, Custom Nether Portals, Elevators, Homes, Nether Portal Coords, Spawn; SimpleTPA handles player requests |
| Mining, building, and farming | Armor Statues, Armored Elytra, Cauldron Concrete, Cauldron Mud, Chunk Loaders, Fast Leaf Decay, Glass Always Drops, More Effective Tools, Painting Picker, Redstone Rotation Wrench, Silk Touch Budding Amethyst, Timber, Villager Workstation Highlights, Wood Stripper, XP Bottling |
| Drops and recipes | Double Shulker Shells, Dragon Drops, Ender Chest Always Drops, Husks Drop Sand, Kill Empty Boats, Unlock All Recipes |
| Status and convenience | AFK Display, Clumps, Durability Ping, Graves, Health Indicator, Multiplayer Sleep, Real Time Clock, Silence Mobs, Simple Revive, Spawn Animations, Spawning Spheres, Track Raw Statistics, Track Statistics, Villager Death Messages, Wandering Trader Announcements |
| Server guide | Welcome Guide (the join message and `/trigger mcguide`) |

The server plugins are **NeatSort**, **SmartStash**, **InventorySortShortcut**, **VeinMiner**, **Excavating Enchant**, **SimpleTPA**, **NeverEnoughRecipes** (with AbyssalLib), and the waypoint renaming helper. All sorting is manual. The table above covers the main commands and controls; other packs mainly change recipes, drops, displays, or automatic behavior.

#### Vanilla Tweaks quick guide

The server has **39 [Vanilla Tweaks datapacks](https://vanillatweaks.net/picker/datapacks/)**. Most work automatically; these need a special action:

- **Elevators:** Drop an Ender Pearl onto wool to make an elevator. Jump to the matching-color elevator above; crouch to go below.
- **XP Bottling:** Right-click an enchanting table with an empty glass bottle in hand. Smelt the XP bottle in a furnace to reclaim the experience.
- **Chunk Loaders:** Drop a Copper Ingot onto a Lodestone to keep its chunk loaded while the server runs. Break the Lodestone to get the ingot back. This pack is customized from [Vanilla Tweaks](https://vanillatweaks.net/picker/datapacks/).
- **Graves:** Left- or right-click your grave to retrieve your items and XP; `/trigger graves` lists your graves.
- **Armor Statues:** Type `/trigger as_help` for the armor-stand controls.

### Credits and updates

The optional visual pack is customized from [Vanilla Tweaks](https://vanillatweaks.net/). See [their terms](https://vanillatweaks.net/terms/) and the `credits.txt` inside the ZIP. Server features also use [Vanilla Tweaks datapacks](https://vanillatweaks.net/picker/datapacks/) and these projects:

- **Progression and travel:** [Better Waypoints](https://modrinth.com/datapack/better-waypoints), [SimpleTPA](https://modrinth.com/plugin/simple-tpa-vexo).
- **Inventory and mining:** [NeatSort](https://modrinth.com/project/ZgbYoHqH), [SmartStash](https://modrinth.com/project/XYbeLI5P), [VeinMiner](https://modrinth.com/project/OhduvhIc), [Excavating Enchant](https://modrinth.com/project/pKiI1vdn).
- **Other conveniences:** [Simple Revive](https://modrinth.com/project/x1IFRoPF), [Spawn Animations](https://modrinth.com/project/zrzYrlm0), [Health Indicator](https://modrinth.com/project/hxaUKE37), [Clumps](https://modrinth.com/datapack/ly-clumps).

When the host posts an updated pack, download the latest release and replace the old ZIP in your resource-packs folder. Your world saves and server datapacks stay on the server.
