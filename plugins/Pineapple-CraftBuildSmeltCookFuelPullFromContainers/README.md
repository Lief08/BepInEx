<h1>Introduction</h1>
My name is DrPine.  I am uploading some of mods that are only over at NexusMods so that everyone can use them in the Thunderstore Mod Manager with ease.  Below is the description from Nexus Mods.



Developed by aedenthorn

## Description

This mod allows you to pull resources from all containers in range when:

- Crafting an item
- Upgrading an item
- Building a construction piece
- Adding fuel or ore to a smelter
- Adding wood to a kiln
- Adding fuel to a fire, standing torch, or sconce
- Cooking food in a cooking station
- Doing whatever it is you do with windmills

It also provides several modifier keys for advanced behaviour:

- A modifier key (**left shift** by default) that, when held, pulls until full for ore and fuel.
- A modifier key (**left ctrl** by default) that, when held, pulls the resources into the player inventory instead of building/crafting.
- A modifier key to turn off the mod's behaviour entirely (**left alt** by default) when held down. This behaviour can also be reversed in the config to only allow this mod to perform its function when the key is held down by setting **SwitchPrevent** to **true**.

## Features

Crafting stations and build menu will show an item's creatability based on resources available in all nearby containers rather than just player
inventory.

Resource requirement numbers will now also show the total amount available in nearby chests. You can customize this in the
config file.

Resources that the player's inventory doesn't have enough of will flash yellow (customizable) instead of red.

When building a container, there will now be particle effect lines between the container and crafting stations in range, thanks to bakaspaceman who wrote this code!

## Prevent Lists

There are two prevent lists in the config:

- **FuelDisallowTypes** - specifies types of consumables like wood and coal that are disallowed (does not apply to kilns, as kilns considered wood an ore)
- **OreDisallowTypes** - specifies types of ore (anything that is transformed into something else) that are disallowed.

Both lists should be comma separated with no spaces, e.g. RoundLog,FineWood.

Item names are available [here](https://www.reddit.com/r/valheim/comments/lig8ml/spawn_item_command_list/).

## Container Types

The config contains toggles for each type of chest as well as ship and wagon containers to ignore completely.

## Config

A config file **BepInEx/config/aedenthorn.CraftFromContainers.cfg** is created after running the game once with this mod).

You can adjust the config values by editing this file using a text editor or in-game using the [Config Manager](https://valheim.thunderstore.io/package/cjayride/ConfigurationManager/).

## Installation

- Automated

  - Suggested to use the [R2ModMan](https://thunderstore.io/package/ebkr/r2modman/) Mod Manager

- Manual

  - Copy the ExtendedPlayerInventory.dll to your /Valheim/BepInEx/plugins directory

If you want to complain or ask for help or help me test my mods, you can visit [my Discord server](https://discord.gg/bs6zHuj).

[Click here for a list of all my mods for Valheim.](https://www.nexusmods.com/valheim/articles/104)

## Source Code

[https://github.com/aedenthorn/ValheimMods](https://github.com/aedenthorn/ValheimMods)

## Change Log

v3.5.1

- Rebuild for update

v3.5.0

- Fix for update

v3.4.0

- Fix for 0.217.14

v3.3.1

- Balista reload fix

v3.3.0

- Added ballista reloading

v3.2.1

- Tooltip fix

v3.2.0

- Fix for new update

v3.1.2

- NRE fix

v3.1.1

- NRE fix

v3.1.0

- Performance fix

v3.0.2

- Small performance tweaks

v3.0.1

- Added private area check

v3.0.0

- Fix for mistlands update

v2.3.0

- Original reupload from NexusMods
