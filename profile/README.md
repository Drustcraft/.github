# Drustcraft

![Drustcraft Banner](img/vareal.jpg)

[![Pull Requests Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![first-timers-only Friendly](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](http://www.firsttimersonly.com/)
[![Issues Open](https://img.shields.io/github/issues/drustcraft/engine?color=008080)](https://github.com/Drustcraft/engine/issues)
[![Discord](https://img.shields.io/discord/782787130334248973.svg?color=%237289da&label=discord)](http://drustcraft.gg/discord)
[![GitHub Good First Issues](https://img.shields.io/github/issues/drustcraft/engine/good%20first%20issue?label=Good%20First%20issues)](https://github.com/drustcraft/engine/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)
[![GitHub Help Wanted issues](https://img.shields.io/github/issues/drustcraft/engine/help%20wanted?label=%22Help%20Wanted%22%20issues)](https://github.com/drustcraft/engine/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)

[Drustcraft](https://www.drustcraft.com.au) is a [Minecraft](https://www.minecraft.net) community that not only enables players to play in a large open MMORPG, but also gives the tools to create their own towns, quests, shops, NPCs, participate in world events, dungeons and raids through story-telling, design and coding.

The ultimate goal of this project is to create a free-play, safe and open world for players to explore and expand on, directing the storyline towards their work. There is even options for organisations to join in and create their own townships, quests and engagements!

## What is the Drustcraft Engine?

The Drustcraft Engine is the code (predominately [Denizen Script](https://denizenscript.com)) that adds all the core features used in an Drustcraft Environment such as Builder tools, NPC jobs and regions. The Engine does recommend certain Minecraft Plugins to be installed such as Denizen, Citizens, WorldGuard and FastAsyncWorldEdit in order for all features to be enabled.

The Drustcraft Engine does not include any configuration or world settings/environments. That is up to the server administrator to configure and setup. Anyone can run the Drustcraft Engine on their own server. These servers are known as "**powered by the Drustcraft Engine**".

### Licensing

The Drustcraft Engine is available under the [GPL-3.0 license](https://github.com/Drustcraft/Drustcraft-Engine/blob/dev/LICENSE) which in summary allows you to use this code on your own server, even for commercial use, however:

- This software is provided as-is with no warranty of any kind. You cannot hold **Drustcraft (ABN 90 649 231 818)**, its employees or anyone who contributes to this software liabile for any damages resulting from the use of the software
- The GPL-3.0 license does not cover the use of the **Drustcraft Brand** or **Drustcraft Logo**. Drustcraft DOES NOT endorse your server/network. You may however use the text or logo "Powered by the Drustcraft Engine" in an unmodified way.
- You must link back to the original Drustcraft Github pages (https://github.com/drustcraft) or provide the original source code of the software.
- You are not required to release your modified version, or any part of it. You are free to make modifications and use them privately, without ever releasing them. **We do however encourge you release them for the Drustcraft community to use**.

## Installation

Drustcraft is made up of several parts including a [Website](https://github.com/Drustcraft/Drustcraft-Website), [API](https://github.com/Drustcraft/Drustcraft-API) and this Engine. The other components are not required in order for the Engine to operate on your Minecraft Server.

Ensure that you are running the recommended [Denizen](https://www.spigotmc.org/resources/denizen.21039/) and [PurPur](https://purpurmc.org) software for the specific release.

The following directories within the repository can then be installed into the following server directories:

| Repo Directory            | Server Directory     |
| :------------------------ | :------------------- |
| /Denizen/\*               | /plugins/Denizen/    |
| /dynmap/\* (optional)     | /plugins/dynmap/     |
| /ImageMaps/\* (optional)  | /plugins/ImageMaps/  |
| /ItemsAdder/\* (optional) | /plugins/ItemsAdder/ |
| /MythicMobs/\* (optional) | /plugins/MythicMobs/ |

## Links

- Website: [https://www.drustcraft.com.au](https://www.drustcraft.com.au)
- Download: [https://github.com/Drustcraft/Drustcraft-Engine/releases/latest](https://github.com/Drustcraft/engine/releases/latest)
- Discord: [http://drustcraft.gg/discord](http://drustcraft.gg/discord)

## Contributing

Contributions are **welcome** and will be fully **credited**.

We accept contributions via Pull Requests on [Github](https://github.com/Drustcraft/engine)

View the [contributing guidelines](https://github.com/Drustcraft/engine/blob/master/CONTRIBUTING.md) for more details.

If you are unsure, new to coding or need some help, feel free to reach out to us on [Discord](http://drustcraft.com.au/discord).

## Plugins

The following plugins are supported by the Drustcraft Engine and extend the engines functionality, however ARE NOT required for the Engine to function (it will operate in a reduced capacity with some features not available).

- [Citizens](https://www.spigotmc.org/resources/citizens.13811/) - _NPCs!_
- [Depenizen](https://github.com/DenizenScript/Depenizen/blob/master/README.md) - _Denizen &lt;-&gt; Other Plugins glue_
- [Dynmap](https://www.spigotmc.org/resources/dynmap.274/) - _World map rendering for the website_
- [Fast Async WorldEdit](https://www.spigotmc.org/resources/fast-async-worldedit.13932/) - _World Editing_
- [ItemsAdder\*](https://www.spigotmc.org/resources/✨itemsadder⭐emotes-mobs-items-armors-hud-gui-emojis-blocks-wings-hats-liquids.73355/) - Resource Packs
- [LuckPerms](http://luckperms.net) - _Permissions_
- [Multiverse-Core](https://www.spigotmc.org/resources/multiverse-core.390/) - _Manage worlds on a server_
- [MythicMobs](https://www.mythicmobs.net/index.php) - _Custom Mobs_
- [WorldGuard](https://dev.bukkit.org/projects/worldguard) - _Protects regions within worlds_
