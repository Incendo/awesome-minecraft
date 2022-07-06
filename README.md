# Awesome Minecraft [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome frameworks, libraries and software relating to Minecraft. All software listed must be open sourced
and available for free.

Feel free to suggest more projects. Only suggest projects you'd recommend to a friend that you don't dislike.

# Contents

- [Libraries and Frameworks](#libraries-and-frameworks)
  - [Commands](#commands)
  - [Configuration](#configuration)
  - [Inventories](#inventories)
  - [Messages](#messages)
  - [Protocol](#protocol)
  - [Utilities](#utilities)
- [Mods](#mods)
  - [Other](#other-mods)
  - [Platforms](#platforms)
  - [Performance](#performance-mods)
- [Plugins](#plugins)
  - [Anti-Cheating](#anti-cheating)
  - [Building](#building)
  - [Maps](#maps)
  - [Other](#other)
    - [Bukkit](#bukkit)
    - [Sponge](#sponge)
    - [Velocity](#velocity)
  - [Permissions](#permissions)
  - [Region Management](#region-and-world-management)
- [Resources](#resources)
  - [Performance](#performance)
- [Software](#software)
  - [Tools](#tools)
  - [Proxy Software](#proxy-software)
  - [Server Software](#server-software)

# Libraries and Frameworks

## Commands
_Libraries that aid in the creation of Minecraft commands._

- [ACF](https://github.com/aikar/commands) - Annotation based Java Command Dispatch Framework.
- [Brigadier](https://github.com/Mojang/brigadier) - Brigadier is a command parser & dispatcher, designed and developed for Minecraft: Java Edition.
- [Chimera](https://github.com/Pante/chimera) - Command framework that does compile-time annotation processing and code generation for Bukkit plugins.
- [Cloud](https://github.com/Incendo/Cloud) - Command framework & dispatcher for the JVM with support for builders, annotations and a Kotlin DSL.
- [CommandAPI](https://github.com/JorelAli/CommandAPI) - A Bukkit-only API for the command UI introduced in Minecraft 1.13.
- [Commodore](https://github.com/lucko/commodore) - Utility for using Minecraft's 1.13 'brigadier' library in Bukkit plugins.
- [LiteCommands](https://github.com/Rollczi/LiteCommands) - Annotation based Command framework for Velocity, Bukkit, Paper, BungeeCord and your other implementations.

## Configuration
_Libraries that make it easier to work with configuration files._

- [Configurate](https://github.com/SpongePowered/Configurate/) - A simple configuration library for Java applications providing a node structure, a variety of formats, and tools for transformation.

## Inventories
_Libraries for creating Minecraft GUIs using inventories._

- [interfaces](https://github.com/Incendo/interfaces) - A Java user-interface library with support for Minecraft.
- [IF](https://github.com/stefvanschie/IF) - An inventory framework for managing GUIs.
- [InventoryGui](https://github.com/Phoenix616/InventoryGui) - A library for Bukkit plugins to create GUIs with inventories.
- [Canvas](https://github.com/IPVP-MC/canvas) - Canvas is a java library built for Bukkit to manage custom inventory based menus.

## Messages
_Libraries that make it easier to work with messages, text, etc._

- [adventure](https://github.com/KyoriPowered/adventure) - A serverside user interface library for Minecraft: Java Edition.
- [adventure-text-minimessage](https://github.com/KyoriPowered/adventure-text-minimessage) - Simple library that implements an easy to use textual format to send rich json messages.
- [MineDown](https://github.com/Phoenix616/MineDown) - A MarkDown inspired markup library for Minecraft chat components.
- [PlaceholderAPI](https://github.com/PlaceholderAPI/PlaceholderAPI) - PlaceholderAPI is a plugin for Spigot servers that allows server owners to display information from various plugins with a uniform format.

## Protocol
_Libraries for interacting with the minecraft protocol._

- [MCProtocolLib](https://github.com/Steveice10/MCProtocolLib) - MCProtocolLib is a simple library for communicating with a Minecraft client/server. It aims to allow people to make custom bots, clients, or servers for Minecraft easily.
- [PacketWrapper](https://github.com/dmulloy2/PacketWrapper) - Packet wrapper classes for ProtocolLib.
- [ProtocolLib](https://github.com/dmulloy2/ProtocolLib/) - Provides read and write access to the Minecraft protocol with Bukkit.

## Utilities
_Utilities that don't particularly belong in any other category._

- [adventure-nbt](https://github.com/KyoriPowered/adventure/tree/master/nbt) - Library for working with NBT.
- [Anvil](https://github.com/AnvilPowered/Anvil) - A cross-platform database API / ORM / entity framework with useful services for minecraft plugins
- [BKCommonLib](https://github.com/bergerhealer/BKCommonLib) - An extensive library used in bergerhealer's plugins.
- [helper](https://github.com/lucko/helper) - A collection of utilities and extended APIs to support the rapid and easy development of Bukkit plugins.
- [Item-NBT-API](https://github.com/tr7zw/Item-NBT-API) - Add custom NBT tags to Items/Tiles/Entities without NMS.
- [mineflayer](https://github.com/PrismarineJS/mineflayer) - Create Minecraft bots with a powerful, stable, and high level JavaScript API.
- [SchematicJS](https://github.com/EngineHub/SchematicJS/) - JavaScript library for working with Minecraft schematics.
- [SchematicWebViewer](https://github.com/EngineHub/SchematicWebViewer/) - Renders Minecraft schematics into a web canvas.
- [SquirrelID](https://github.com/EngineHub/SquirrelID/) - Library for working with Mojang profiles
- [Vault](https://github.com/MilkBowl/Vault) - Vault of common APIs for Bukkit Plugins.

# Mods

## Other Mods
_Other mods._

- [ReplayMod](https://github.com/ReplayMod/ReplayMod) - A Minecraft mod to record game sessions and replay them afterwards from any perspective.

## Platforms
_Modding platforms._

- [Fabric](https://github.com/FabricMC/fabric) - Next generation, highly modular and open Minecraft modding API.
- [MinecraftForge](https://github.com/MinecraftForge/MinecraftForge) - Modifications to the Minecraft base files to assist in compatibility between mods.

## Performance Mods
_Mods meant to increase game performance._

- [Krypton](https://github.com/astei/krypton) - A Fabric mod that optimizes the Minecraft networking stack and entity tracker.
- [lazy-dfu](https://github.com/astei/lazydfu) - Makes Minecraft DataFixerUpper initializatiion lazy.
- [lithium-fabric](https://github.com/jellysquid3/lithium-fabric) - A Fabric mod designed to improve the general performance of Minecraft without breaking things.
- [phosphor-fabric](https://github.com/jellysquid3/phosphor-fabric) - A Fabric mod designed to dramatically improve the performance of Minecraft's lighting engine while fixing many bugs.
- [sodium-fabric](https://github.com/jellysquid3/sodium-fabric) - A Fabric mod designed to improve frame rates and reduce micro-stutter.

# Plugins

## Anti-Cheating

- [NoCheatPlus](https://github.com/Updated-NoCheatPlus/NoCheatPlus) - NoCheatPlus attempts to enforce "vanilla Minecraft" mechanics, as well as preventing players from abusing weaknesses in Minecraft or its protocol, making your server more safe.

## Building
_Plugins that make building easier._

- [Builders-Utilities](https://github.com/Arcaniax-Development/Builders-Utilities) - A collection of a lot of tiny features that help with building.
- [Light-Cleaner](https://github.com/bergerhealer/Light-Cleaner) - Regenerates light levels in chunks or entire worlds to clean up dark spots. Continuation of NoLagg Lighting.
- [WorldEdit](https://github.com/enginehub/worldedit) - Minecraft map editor and mod.

## Maps
_Map viewers._

- [BlueMap](https://github.com/BlueMap-Minecraft/BlueMap) - A Minecraft mapping tool that creates 3D models of your Minecraft worlds and displays them in a web viewer.
- [dynmap](https://github.com/webbukkit/dynmap) - A set of Minecraft mods that provide a real time web-based map system for various Minecraft server implementations.
- [Minecraft-Overviewer](https://github.com/overviewer/Minecraft-Overviewer) - Render high-resolution maps of a Minecraft world with a Leaflet powered interface.

## Other
_Plugins that don't particularly fit in with any existing category._

- [DataSync](https://github.com/AnvilPowered/DataSync) - A minecraft plugin to synchronize and backup player data to a database
- [NuVotifier](https://github.com/nuvotifier/NuVotifier) - A fork of Votifier, with more robust code and vote forwarding.
- [OnTime](https://github.com/AnvilPowered/OnTime) - A cross-platform player time management plugin.
- [Plan](https://github.com/plan-player-analytics/Plan) - Player Analytics plugin for Minecraft Server platforms.
- [spark](https://github.com/lucko/spark) - A performance profiling plugin based on sk89q's WarmRoast profiler.

### Bukkit

- [Citizens](https://github.com/CitizensDev/Citizens2) - Plugin and API for creating service side NPCs.
- [CraftBook](https://enginehub.org/craftbook/) - Plugin that adds many new fun mechanics to the game with extreme levels of customisability.
- [EssentialsX](https://github.com/EssentialsX/Essentials) - Plugin suite providing essential commands and features, updated for the latest Minecraft versions.
- [ProtocolSupport](https://github.com/ProtocolSupport/ProtocolSupport) - Support older Minecraft versions.
- [ViaVersion](https://github.com/ViaVersion/ViaVersion) - Allows the connection of newer clients to older server versions for Minecraft servers.

### Sponge

- [Nucleus](https://github.com/NucleusPowered/Nucleus) - The Ultimate Essentials Plugin for Sponge.

### Velocity

- [Catalyst](https://github.com/AnvilPowered/Catalyst) - An essentials plugin for Minecraft proxies that will provide your server with a strong baseline; giving you all the useful commands you need.

## Permissions
_Plugins for user permission management._

- [BungeePerms](https://github.com/weaondara/BungeePerms) - Alternative permissions plugin for Minecraft servers.
- [LuckPerms](https://github.com/lucko/luckperms) - A permissions plugin for Minecraft servers.

## Region and World Management
_Plugins for managing and generating world regions._

- [BentoBox](https://github.com/BentoBoxWorld/BentoBox) - Expandable Minecraft server plugin for island-type games like SkyBlock or AcidIsland.
- [Chunky](https://github.com/pop4959/Chunky) - Plugin for pre-generating chunks.
- [GriefPrevention](https://github.com/TechFortress/GriefPrevention/) - Prevents all forms of grief - build/break, theft, spam, spawn camping, and more without a database.
- [Hyperverse](https://github.com/Incendo/Hyperverse) - A lightweight world mangement plugin for Bukkit.
- [Multiverse-Core](https://github.com/Multiverse/Multiverse-Core) - The original Bukkit Multi-World Plugin.
- [PlotSquared](https://github.com/IntellectualSites/PlotSquared) - Plot world generator and management plugin with support for schematics.
- [Prism-Bukkit](https://github.com/AddstarMC/Prism-Bukkit) - Prism is a rollback/grief management tool for Bukkit.
- [WorldGuard](https://github.com/enginehub/worldguard) - WorldGuard lets you and players guard areas of land against griefers and undesirables, as well as tweak and disable various gameplay features of Minecraft.

# Resources

## Blogs
_Blogs related to Minecraft._

- [Me4502](https://madelinemiller.dev/blog/category/minecraft/) - Me4502's blog with frequent posts relating to Minecraft development and server ownership.

## Support
_Support Resources for Minecraft._

- [HelpChat](https://helpch.at) - [Discord](https://helpch.at/discord): home of PlaceholderAPI and several other plugins, along with general minecraft and programming support.
- [M.O.S.S.](https://discord.gg/PHpuzZS): home to a ton of open source, minecraft related projects (including factions, essentials, pex, and more).
- [PaperMC](https://papermc.io) - [Discord](https://discord.gg/papermc), [Forums](https://papermc.io/forums/): official home of the paper project, where you can download paper, and receive support.
- [Syscraft](https://syscraft.org) - [Subreddit](https://old.reddit.com/r/syscraft/), [Discord community](https://discord.gg/Dx6SSkx), and online resources for everyone involved in making Minecraft servers, from development to hosting to running servers.

## Performance
_Resources for Minecraft performance tuning._

- [Aikar's Flags](https://aikar.co/2018/07/02/tuning-the-jvm-g1gc-garbage-collector-flags-for-minecraft/) - G1GC Garbage Collector Flags for Minecraft.
- [Krusic22's Flags](https://krusic22.com/2020/03/25/higher-performance-crafting-using-jdk11-and-zgc/) - Optimized JDK11+ & ZGC flags for Minecraft servers.
- [StartMC](https://startmc.sh/) - Aikars flags script generator.

## Protocol
- [wiki.vg](https://wiki.vg) - Wiki.vg has documented the whole minecraft protocol for java and bedrock edition.

# Software

## Proxy Software
_Minecraft server proxy software._

- [Geyser](https://github.com/GeyserMC/Geyser) - A bridge/proxy allowing you to connect to Minecraft: Java Edition servers with Minecraft: Bedrock edition.
- [Velocity](https://github.com/velocitypowered/velocity) - A Minecraft server proxy with unparalleled server support, scalability, and flexibility.
- [Waterfall](https://github.com/papermc/waterfall) - BungeeCord fork that aims to improve performance and stability.

## Server Software
_Minecraft server software._

- [Nukkit](https://github.com/CloudburstMC/Nukkit) - Server software for Minecraft: Bedrock Edition.
- [Paper](https://github.com/papermc/paper) - High performance Spigot fork that aims to fix gameplay and mechanics inconsistencies.
- [Sponge](https://github.com/SpongePowered/Sponge) - A community-driven open source Minecraft: Java Edition modding platform.

## Tools
_Miscellaneous tools._

- [Blockbench](https://github.com/JannisX11/blockbench) - Blockbench is a free, modern model editor for boxy models and pixel art textures.
- [MultiMC](https://multimc.org/) - MultiMC is a custom launcher for Minecraft that allows you to easily manage multiple installations of Minecraft at once.
- [pakkit](https://github.com/Heath123/pakkit) - A packet monitor for Minecraft written in Electron.
