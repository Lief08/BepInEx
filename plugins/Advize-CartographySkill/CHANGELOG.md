### 3.0.0
- Split Spyglass and Cartography Skill into two separate mods.
- Modernized code base.
- Updated ServerSync to v1.17.
- Compiled against Valheim 0.217.31 & BepInEx 5.4.2202.

### 2.1.2
- Updated ServerSync to v1.13 for Valheim 0.211.11.

### 2.1.1
- Updated ServerSync to v1.11 for Valheim 0.211.7 crossplay support.
- Added localization support for skill name and skill description.
	- To see new strings in localization file, delete Advize_CartographySkill.json and allow it to regenerate.

### 2.1.0
- Adopted ServerSync in place of Authoritative Config.
- Changed [Controls] in config to be of type KeyboardShortcut instead of string.
	- It's recommended you delete and regenerate your config file.
- Compiled against BepInEx 5.4.17 and Valheim 0.206.5.

### 2.0.3
- Added more null reference error prevention.

### 2.0.2
- Corrected cartography skill icon.

### 2.0.1
- Added extra null reference error prevention.

### 2.0.0
- Updated for Hearth and Home.
- Removed SkillInjector dependency.
- Both cartography skill and spyglass item can now be enabled/disabled individually.
- Localization support added for spyglass name and description.

### 1.5.0
- Dropped MCE support in favor of AuthoritativeConfig.
- Embedded assets within .dll file.

### 1.4.0
- Changed skill hover description in skill window.
- Added MCE support for server admins.

### 1.3.7
- Consolidated Nexus and Thunderstore branches.

### 1.3.6
- Fixed README.

### 1.3.5
- Minor code cleanup.
- Added debug message.
- Packaged for Thunderstore.io release.

### 1.3.4
- Updated spyglass icon to match 3D model.
- Added fix for error when generating a fresh world.
- Changed debug messages to accommodate new code flow. Code refactoring.

### 1.3.3
- Fixed conflict with Valheim+ and potential conflicts with all other mods who adjust field of view.
	- From this day forward, when you are zooming in with the spyglass, YOU ZOOM IN WITH THE SPYGLASS.

### 1.3.2
- No more Better Archery conflicts, all spyglass zoom levels now work!
- Spyglass can be spawned via console using prefab name advize_item_spyglass.
- Fixed a fov calculation error.
- Added Nexus mod ID for update checks.
- Added debug messages for when debug messages are enabled.
- Console command 'cartxpsync' added for Map Sync Mod users.
- Other fixes.
	
### 1.3.1
- Correctly bumped mod version number.
	
### 1.3.0
- Replaced Spyglass model.
- Spyglass will no longer zoom in or out while the inventory is open.
	
### 1.2.0
- Added spyglass control options to mod config.
- Spyglass now renders during character select screen.
	
### 1.1.1
- Added spyglass related config settings.
	- Zoom distance and field of view reduction are now configurable.
	- Spyglass item can be disabled entirely.
	
### 1.1.0
- Added craftable Spyglass item with custom mesh, textures, and unique logic.
	
### 1.0.3
- Minor update. Final code cleanup before new (if any) features are added. No need to update if you have 1.0.2.

### 1.0.2
- Disabled debug messages by default, but added config setting to toggle.
	- This improves performance when traveling quickly or entering "exploremap" into the console.

### 1.0.1
- New icon.
- View radius will now decrease if skill level is lowered without having to reload world.
- Fortified logic to prevent unexpected behaviour.

### 1.0.0
- Created Mod.