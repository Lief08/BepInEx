![](https://staticdelivery.nexusmods.com/mods/3667/images/394/394-1701937869-2137190105.png)

| [Description](#description) | [Installing](#installing) | [Contact Author](#contact-author) | [Other Info](#config-and-other-info) | [Config](#config) | [Source](#source) | [Changelog](#changelog) | [Screenshots](#screenshots) |
|---|---|---|---|---|---|---|---|

## Description
Ever sailed past a visible coastline, but it didn't appear on your world map? That's because the default radius around the player that is uncovered on the world map is smaller than your view distance! This mod allows you to increase that explore radius, either by a static or skill based amount.

The custom skill can be enabled/disabled via the mod's config file, generated after the mod is loaded at least once (see Config & Other Info below).

## Installing

### Manual Install

Extract the Advize_CartographySkill.dll file into your BepinEx/plugins folder.
Directory structure should look like this:
```
BepInEx ->
    plugins ->
        Advize_CartographySkill.dll
```
#### In multiplayer environments:
Configuration settings will sync between connected clients using ServerSync. Install the mod on the server (if dedicated) to ensure its configuration file remains authoritative.

## Contact Author
You can reach me on the Nexus to provide bug reports or feedback https://www.nexusmods.com/valheim/mods/394

For further mod or mod dev support, I can be found at the following Discord server:

[![](https://i.imgur.com/HZMpQip.png)](https://discord.gg/89bBsvK5KC)

## Config and Other Info:
The mod is configurable. A config file will be generated after first loading the mod and can be found in ﻿BepInEx/config/advize.CartographySkill.cfg

The config can be edited out of game with a text editor, or modified in game using the Configuration Manager mod.

Note: In multiplayer environments, configuration settings will sync between connected clients using ServerSync. Install the mod on the server (if dedicated) to ensure its configuration file remains authoritative.

Localization Support: A file named Advize_CartographySkill.json will be generated in the config\CartographySkill directory after the game is first launched while [General]EnableLocalization is set to true. In it you will find the ability to change the skill name and description text. I will be improving upon this later.

By default, one should be able to reach cartography level 100 before exploring an entire world; but it will not add xp for parts you've already discovered (yet). If you need to increase the level higher and you've discovered your whole world, you'll need to uncover parts of the map in a new world.

Future Plans:

Interface with / include cartography table related features.
Implementing features by popular request.

## Config
### Default Config File:
```
Please see Nexus mod page for the default configuration.
```
## Source
Github Repo: [Advize_ValheimMods](https://github.com/AdvizeGH/Advize_ValheimMods)

## Screenshots

Skill in Skills Window

![](https://staticdelivery.nexusmods.com/mods/3667/images/394/394-1615440013-1118542910.png)

Config Options

![](https://staticdelivery.nexusmods.com/mods/3667/images/394/394-1701939052-1235984861.png)