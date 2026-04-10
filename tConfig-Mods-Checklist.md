# tConfig Mods Checklist

- Some mods have different names but are the same mod, like for Shockah, need to check those
- every single failing mod needs to be verified source code structure, extracted if obj, and rebuilt, and compared for duplicates
- need to double check fails included in the table
- Need to reorganize and fix files structures of failing
    - Note Blocks (fail) - Override folder?
    - oof, retribution of the something mode, weird install, and russian?
    - Portal Mod v1 (fails) - _picture folder?
    - Portal Mod v2 (fails)
    - tConfig Debugger - release 11? messed up file structure will have to sort out, there is a 0.35.2 version to compare too
    - The Story of Red Cloud 2018 Update - look at instructions and decide if this is broken
- Need to also compare extracted source code of older version objs to source code we have to determine if what source code was made to work on older versions, but ends up working on newer versions
- Need to go through the middle table from tConfig fandom

## Need to be looked at:
- https://tconfig.fandom.com/wiki/Wingzero007_Mod_Tests
- https://tconfig.fandom.com/wiki/Romulan_Paladin%27s_Dust_and_Sound_Catalog_Mod
- https://tconfig.fandom.com/wiki/Paradise_Lost/old
- https://www.dropbox.com/s/4czhchi9l45gq35/Terraria%20Mod%20Archive%20V5.zip?dl=0 
- https://forums.terraria.org/index.php?threads/xinput-gamepad-support-mod-pre-1-3.1260/

| Symbol | Meaning |
|--------|--------|
| ❌     | Not Done/Missing |
| ⚠️     | Unofficial Port/Workaround/Unnecessary |
| ?      | Unsure |
| ✅     | Complete/Official Support |

Marking something as 0.38 compatabile means that it outputs an obj when using ModPack Builder, this doesn't mean the mod completely and perfectly works. If there is an issue file an issue on this Github.

## Terraria 1.1 Mods with Source Code

**_Note:_** All "fails" and "obj issues" are source code files that have been tested with tConfig 0.38, they still need to be tested with other versions

| Mod Name | Author | tConfig Version | Source Files | Builds | obj File | working obj file | Wiki Page |
|----------|--------|-----------------|--------------|--------|----------|------------------|-----------|
| Accessory Slots+ | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Achievements | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅  | ✅ | ✅ |
| Advanced Crafting Menu 2 | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| [Avalon](https://forums.terraria.org/index.php?threads/released-wip-terraria-avalon.378/) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | 0.38 | ✅ | ✅ | ✅ | ✅ | [fandom](https://avalonmod.fandom.com/wiki/Terraria_Avalon_Mod_Wiki), [wiki.gg](https://terrariamods.wiki.gg/wiki/Avalon) |
| [Avalon (1)](https://forums.terraria.org/index.php?threads/released-wip-terraria-avalon.378/) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | 0.38 | ✅ | ✅ | ✅ | ✅ | [fandom](https://avalonmod.fandom.com/wiki/Terraria_Avalon_Mod_Wiki), [wiki.gg](https://terrariamods.wiki.gg/wiki/Avalon) |
| [Avalon (fails)](https://forums.terraria.org/index.php?threads/released-wip-terraria-avalon.378/) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | ??? | ✅ | ❌ | ❌ | ❌ | [fandom](https://avalonmod.fandom.com/wiki/Terraria_Avalon_Mod_Wiki), [wiki.gg](https://terrariamods.wiki.gg/wiki/Avalon) |
| [Avalon (might be the first version) (fails)](https://forums.terraria.org/index.php?threads/released-wip-terraria-avalon.378/) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | ??? | ✅ | ❌ | ❌ | ❌ |
| Avalon Junkyard (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| [Avalon v16.6](https://forums.terraria.org/index.php?threads/released-wip-terraria-avalon.378/) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | 0.38 | ✅ | ✅ | ✅ | ✅ | [fandom](https://avalonmod.fandom.com/wiki/Terraria_Avalon_Mod_Wiki), [wiki.gg](https://terrariamods.wiki.gg/wiki/Avalon) |
| Avalon-Rewrite (obj issue) | ??? | ??? | ✅ | ✅ | ✅ | ❌ | [fandom](https://avalonmod.fandom.com/wiki/Terraria_Avalon_Mod_Wiki), [wiki.gg](https://terrariamods.wiki.gg/wiki/Avalon) |
| Awesome Christmas | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Awesome Christmas (fail) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| Base Mod | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Boss HP Bar | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Classy Magic 1.1.1 | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Defaults | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Epic Loot | [Surfpup](https://forums.terraria.org/index.php?members/surfpup.21475/) | 0.38 | ✅ | ❌ | ❌ | ✅ |
| Epic Loot 2 | [Surfpup](https://forums.terraria.org/index.php?members/surfpup.21475/) | 0.38 | ✅ | ❌ | ❌ | ✅ |
| Examples (obj issue) | ??? | ??? | ✅ | ✅ | ✅ | ❌ |
| Experience | ??? | ??? | ✅ | ✅ | ✅ | ✅ |
| Final Cheat Menu 2 | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Finaller Cheat Menu | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Flashkirby's Mounts and Stuff | Flashkirby | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Flashkirby's Weapons | Flashkirby | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Flashkirby's Weapons (1) | Flashkirby | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Flashlight + Fireworks | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Gamepad Mod | [Surfpup](https://forums.terraria.org/index.php?members/surfpup.21475/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Glue & Paint Gun | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| GodMode 3 | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Gold's Pickaxe Pack | Gold | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Gravity Gun (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| GRleam (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| Groxmod (requires BaseMod) (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| Health Interface | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Health Up! (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| HP Bars | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Industrail Revloution mod | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Item Manager | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Jensen's Moon Mod | Jensen | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Jewelcrafting Mod | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Kjulos Mod | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| Life Bars | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Magic Mirror Hotkey | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Minecarts | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Mystic Horizons | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Mystical Tomes | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Mystical Tomes (1) | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Never Enough Devices | MiraiMai | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Never Enough Magic | MiraiMai | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Never Enough Weaponry | MiraiMai | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Never-Ending Christmas | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Note Blocks (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| Nyan Cat (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| Obsidian Sword | ??? | ??? | ✅ | ✅ | ✅ | ❌ |
| Obsidian_Global | ??? | ??? | ✅ | ✅ | ✅ | ❌ |
| [Paradise Lost](https://tconfig.fandom.com/wiki/Paradise_Lost) | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Party Heads | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Poro's Dutvutanian Mod | Poro | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Poro's MWNN Mod | Poro | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Portal Gun | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Portal Mod v1 (fails) | [Surfpup](https://forums.terraria.org/index.php?members/surfpup.21475/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Portal Mod v2 (fails) | [Surfpup](https://forums.terraria.org/index.php?members/surfpup.21475/) |??? | ✅ | ❌ | ❌ | ❌ |
| [Project-1.1](https://github.com/MrPoloGit/Project-1.1) | [MrPoloGit](https://github.com/MrPoloGit) | 0.38 | ❌ | ✅ | ✅ | ✅ |
| PTS | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Recipe Book | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| RenzPack | Renz | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Roguelike | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| RomulanPaladin's Dust and Sound Catalog v0_1 | RomulanPaladin | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Russian Avalon Mashup (fails) | ??? | 0.38 | ✅ | ❌ | ❌ | ❌ | went through the induvidual mods need russians to read |
| San's Mod | San | 0.38 | ✅ | ❌ | ❌ | ❌ |
| Shake Off Buffs | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah Achievements | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah Boss HP Bar | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah Haunted Mine | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah HP Bar | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah Item Manager | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah Shop Info | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah World+ | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shockah's Quest Mod (fails) | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | ??? | ✅ | ❌ | ❌ | ❌ |
| Shop Info | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Shop Info (fails) | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | ??? | ✅ | ❌ | ❌ | ❌ |
| Silpm Mod 1.0.1 (fails) | Silpm | ??? | ✅ | ❌ | ❌ | ❌ |
| SonnyMod (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| Stacks Up! | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Supa Mushroom (obj issue) | ??? | ??? | ✅ | ✅ | ✅ | ❌ |
| SUPER SLIME (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| The Drone | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| The Kase mod 3.9 | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Thorium Content Pack | [DivermanSam](https://forums.terraria.org/index.php?members/divermansam.884/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| [tlcmod-1.1](https://github.com/MrPoloGit/tlcmod-1.1) | [MrPoloGit](https://github.com/MrPoloGit) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| True Invisibility | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| W1K - Monster Hunter Pack | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Wallpaperpack | Eikester | 0.38 | ✅ | ✅ | ✅ | ✅ |
| World+ (fails) | ??? | ??? | ✅ | ❌ | ❌ | ❌ |
| XBox Controller | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| Xbox Controller Mod | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY E O Y | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Holotiles Static Set | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Holowires | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Improved Mannequins | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Mystery Items Pack v1 | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Mystery Items Pack v2 | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Races Of Terraria | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Serverside Saving | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Step Up | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |
| YYY Yorais Wonderful World | ??? | 0.38 | ✅ | ✅ | ✅ | ✅ |

## obj files (will compare to the source files we have)

**_Note:_** All "fails" are obj files that have been tested with tConfig 0.38, they still need to be tested with other versions

| Mod Name | Author | tConfig Version | Source Files | Builds | obj File | working obj file | Wiki Page |
|----------|--------|-----------------|--------------|--------|----------|------------------|-----------|
| 2 Day Challenge 1 | ??? | 0.33.0 | ❌ | ❌ | ✅ | ❌ |  |
| Accessory Slots+  (v0.34.1) | ??? | 0.34.1 | ❌ | ❌ | ✅ | ❌ |  |
| Accessory Slots+  (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Accessory_Slots (fail) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Additional Weapons Mod (v0.28.8) | ??? | 0.28.0 | ❌ | ❌ | ✅ | ❌ |  |
| Adventure Dialogue (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Alternate Portal Mod (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Alternate Portal Mod | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Anti-Gravity_Mover (v0.22.8) | ??? | 0.22.8 | ❌ | ❌ | ✅ | ❌ |  |
| Avalon (v0.35.0) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Avalon (v0.35.3) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | 0.35.3 | ❌ | ❌ | ✅ | ❌ |  |
| Avalon v16.6 (fails) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Avalon v17.2 (fails) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Avalon v17.3 (fails) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Avalon v17.3.1 (fails) | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Avalon | [blahblahbal](https://forums.terraria.org/index.php?members/blahblahbal.17/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Awesome Christmas (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| BaseMod (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Binding of Terraria (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Binding of Terraria | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Boss HP Bar (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Boss_HP_Bar (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Builders_Pack (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Built-In (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Caelum Ignota  (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Capture The Flag (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Challenges (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Challenges | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| CharError (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Cheat Menu Modded (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Classy Vanity 1.1 (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Classy_Extras_v1.3a (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Classy_Magic_v1.3a (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Classy_Melee_v1.3a (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Classy_NPCs_v1.3a (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Classy_Tools_v1.3a (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Colored wires (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| CompilationMod (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Corruptor Mod (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Daggers (v0.27.1) | ??? | 0.27.1 | ❌ | ❌ | ✅ | ❌ |  |
| Dark Souls (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Dark Souls (v0.38 unsure if stable) v1 | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Dark Souls (v0.38 unsure if stable) v1 | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Dark_Souls_darksouls (1) (v0.35.3) | ??? | 0.35.3 | ❌ | ❌ | ✅ | ❌ |  |
| Dark_Souls_redcloudmsd (v0.35.3) | ??? | 0.35.3 | ❌ | ❌ | ✅ | ❌ |  |
| Defaults (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| DefaultsModified (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| DefaultsTest (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Dual Wielding (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Due West (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Durability (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Dust and Sound Catalog (v0.22.8) | ??? | 0.22.8 | ❌ | ❌ | ✅ | ❌ |  |
| Dying Soul (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Elemental Source (v0.28.7) | ??? | 0.28.7 | ❌ | ❌ | ✅ | ❌ |  |
| Enchantmentlocal (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Epic Loot (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Evil Modpack (v0.22.2) | ??? | 0.22.2 | ❌ | ❌ | ✅ | ❌ |  |
| Ex_Flail | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Examples - Prefixes (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Examples - Tiles (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Examples (fails) v1 | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Examples (fails) v2 | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Examples (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Fast Progression (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Final Cheat Menu 2 (v0.36) | ??? | 0.36 | ❌ | ❌ | ✅ | ❌ |  |
| Finaller Cheat Menu (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Flashkirby's Mounts and Stuff (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Flashkirby's Weapons (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Flashlight + Fireworks (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Furniture (v0.23.4) | Eikester | 0.23.4 | ❌ | ❌ | ✅ | ❌ |  |
| Furniture Examples - Test (v0.38 unsure if stable) | ??? | 0.38 |❌ | ❌ | ✅ | ✅ |  |
| Furniture Examples (v0.38 unsure if stable) | ??? | 0.38 |❌ | ❌ | ✅ | ✅ |  |
| Gamepad Mod (v0.29.1) | ??? | 0.38 | ❌ | ❌ | ✅ | ❌ |  |
| Gamepad Mod (v0.38 unsure if stable) | ??? | 0.38 |❌ | ❌ | ✅ | ✅ |  |
| Gamepad Support (v0.29.1) | ??? | 0.38 |❌ | ❌ | ✅ | ❌ |  |
| GameplayTest (v0.38 unsure if stable) | ??? | 0.38 |❌ | ❌ | ✅ | ✅ |  |
| GenTest (v0.38 unsure if stable) | ??? | 0.38 |❌ | ❌ | ✅ | ✅ |  |
| Glue & Paint Gun (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| GodMode 2 (v0.38 unsure if stable) | ??? | 0.38 |❌ | ❌ | ✅ | ✅ |  |
| GodMode 3 (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Grables_Recipe_Book (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Gravity Gun (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Green_Cats_Autosave_Players (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Groxmod (requires BaseMod) (v0.38 unsure if stable) | ??? | 0.38 |❌ | ❌ | ✅ | ✅ |  |
| Hardmode Plus (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Health Up! (v0.34.0) | ??? | 0.34.0 | ❌ | ❌ | ✅ | ❌ |  |
| Health Up! | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Infinity Chest | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Jensen's Moon Mod (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Jewelcrafting Mod (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Kurobari (v0.38 unstable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| LBP | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Magic Mirror Hotkey (v0.35.2) | ??? | 0.35.2 |❌ | ❌ | ✅ | ❌ |  |
| Meteor Brick Sample by wiring (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| MethodTest (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Metroid Mod (v0.34.0) | ??? | 0.34.0 |❌ | ❌ | ✅ | ❌ |  |
| Metroid Morph Ball | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| MiraiMais_Dual_Wielding (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Mirrors | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Monster_Hunter_Terra12345 (v0.22.8) | ??? | 0.22.8 |❌ | ❌ | ✅ | ❌ |  |
| More Chests | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Mystic Horizons (v0.35.0) | ??? | 0.35.0 |❌ | ❌ | ✅ | ❌ |  |
| Mystical Tomes (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Mystical Tomes (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Mystical_Tomes (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Nazi_Zombies_V2.7.2 (v0.22.8) | ??? | 0.22.8 |❌ | ❌ | ✅ | ❌ |  |
| Necro SP (v0.36) | ??? | 0.36 |❌ | ❌ | ✅ | ❌ |  |
| Necro SP | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Necro_SP_v1.91 (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Never Enough Accessories | MiraiMai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Never Enough Headgear (v0.34.1) | MiraiMai | 0.34.1 | ❌ | ❌ | ✅ | ❌ |  |
| Never Enough Headgear | MiraiMai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Never Enough Vanity | MiraiMai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| NoTileBreak (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| NoTilePlacement (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| NPCTest (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Nyan Cat (v0.35.0) | ??? | 0.35.0 |❌ | ❌ | ✅ | ❌ |  |
| Obsidian (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Obsidian Mod (No Rain) (0.24) | ??? | 0.38 | ❌ | ❌ | ✅ | ❌ |  |
| Obsidian Mod (No Rain) (0.36) | ??? | 0.38 | ❌ | ❌ | ✅ | ❌ |  |
| Obsidian Mod (v0.24) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Obsidian_Advancedweapons (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Obsidian_CustomBosses (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Obsidian_Global (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Obsidian_Ice (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Obsidian_ParallelWorld (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Obsidian_Pets (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Obsidian_Tools (v0.35.1) | ??? | 0.35.1 |❌ | ❌ | ✅ | ❌ |  |
| Old Avalon (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| OldPortal Mod (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Omnirs C, TaFF -- CW Yorai Mods (fails) | Omnir | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Omnirs Creatures, TaFF items (fails) | Omnir | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Omnirs Furniture (v0.28.8) | Omnir | 0.28.8 | ❌ | ❌ | ✅ | ❌ |  |
| Omnirs Melee Weapons (v0.28.8) | Omnir | 0.28.8 | ❌ | ❌ | ✅ | ❌ |  |
| Omnir's Nostalgia Pack (v0.28.8) | Omnir | 0.28.8 | ❌ | ❌ | ✅ | ❌ |  |
| Omnir's Nostalgia Pack Blasting (v0.38 unsure if stable) | Omnir | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Omnir's Nostalgia Pack Digging (v0.38 unsure if stable) | Omnir | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Omnir's Nostalgia Pack Low HP (v0.38 unsure if stable) | Omnir | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Omnir's Nostalgia Pack No Blast (v0.38 unsure if stable) | Omnir | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Omnirs_Creatures_TaFF_items_No_Blast (v0.23.1) | Omnir | 0.23.1 | ❌ | ❌ | ✅ | ❌ |  |
| Omnirs_Melee_Weapons (v0.23.1) | Omnir | 0.23.1 | ❌ | ❌ | ✅ | ❌ |  |
| Other_Worlds (v0.23.1) | ??? | 0.23.1 | ❌ | ❌ | ✅ | ❌ |  |
| PASE 002 | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Peaceful Mode | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Pickaxe_v1.3a (requires Universal Dye Pack) (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Plane (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Poro's Dutvutanian Mod (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Poro's MWNN Mod (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Portal Mod (v0.29.1) | ??? | 0.29.1 | ❌ | ❌ | ✅ | ❌ |  |
| Portal Mod (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Portal Mod (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| PTS (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| PVP (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| QuickDestroy (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Races The Redux (v0.35.3) | ??? | 0.35.3 | ❌ | ❌ | ✅ | ❌ |  |
| Randomized NPCs | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Reborn_Mod (v0.22.7) | ??? | 0.22.7 | ❌ | ❌ | ✅ | ❌ |  |
| Recipe Book (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Retribution of the Darkness (v0.35.0) | [Anton_ROTD](https://vk.com/rcreator) | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| RPG (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Shockah Achievements (v0.35.0) | Shockah | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Shockah Boss HP Bar (v0.35.0) | Shockah | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Shockah Haunted Mine (v0.35.0) | Shockah | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Shockah HP Bars (v0.35.0) | Shockah | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Shockah Item Manager (v0.35.0) | Shockah | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Shockah Shop Info (v0.35.0) | Shockah | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Shockah World+ (v0.35.0) | Shockah | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Sign Text | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| SillyNPCs | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| SimpleTransferExample (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Silpm Mod 1.0.1 (v0.23.3) | Silpm  | 0.23.3 | ❌ | ❌ | ✅ | ❌ |  |
| SonnyMod | Sonny | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Spigot | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Stacks Up! (v0.34.1) | ??? | 0.34.1 | ❌ | ❌ | ✅ | ❌ |  |
| Stats (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Steve | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| SwampPack (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| tConfig Debugger (v0.35.2) | ??? | 0.35.2 | ❌ | ❌ | ✅ | ❌ |  |
| Terrariastuck (BO4 hotfix) (v0.34.0) | Shockah | 0.34.0 | ❌ | ❌ | ✅ | ❌ |  |
| Terrariastuck | Shockah | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Three Stats (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Tile Performance (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| True Invisibility (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| TScript (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Unique Treasure (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Universal_Dye_Pack (fails) | ??? | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Vertigo Elemental (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K - Metroid Pack (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K - Misc Pack (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K - Touhou Pack (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K - Touhou Pack | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K - Warhammer Pack (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K - Warhammer Pack | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K CPR (v0.35.1) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.35.1 | ❌ | ❌ | ✅ | ❌ |  |
| W1K CPR (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K MM - 1.0.5 Balance (v0.28.1) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.28.1 | ❌ | ❌ | ✅ | ❌ |  |
| W1K MM - 1.0.5 Balance (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K MM - Difficulty Changer (v0.28.1) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.28.1 | ❌ | ❌ | ✅ | ❌ |  |
| W1K MM - Difficulty Changer (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K MM - Hunger System (v0.29.0) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.29.0 | ❌ | ❌ | ✅ | ❌ |  |
| W1K MM - Hunger System (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38| ❌ | ❌ | ✅ | ✅ |  |
| W1K MM - Liquids Modifier (v0.27.2) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.27.2 | ❌ | ❌ | ✅ | ❌ |  |
| W1K MM - Liquids Modifier (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| W1K MM - Position Saver (v0.38 unsure if stable) | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Wallpaperpack (v0.23.4) | Eikester | 0.23.4 | ❌ | ❌ | ✅ | ❌ |  |
| World of Falana (v0.35.1) | ??? | 0.35.1 | ❌ | ❌ | ✅ | ❌ |  |
| WorldGen Mod (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| WorldGen Plus (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| X-Boots (v0.38 unsure if stable) | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| Xbox Controller (v0.35.1) | ??? | 0.35.1 | ❌ | ❌ | ✅ | ❌ |  |
| Xbox Controller Mod (v0.35.0) | ??? | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| Yorais_Dual_Wielding (fails) | yorai | ??? | ❌ | ❌ | ✅ | ❌ |  |
| Yoraiz0rs Cheat Menu (v0.37) | ??? | 0.37 | ❌ | ❌ | ✅ | ❌ |  |
| YYY Bonfire Syndrome (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY DW TAO2 (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY Final Cheat Menu (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY HLR (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY Holotiles Static Set (v0.35.0) |
| YYY Holowires (v0.35.0) | yorai | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| YYY Holowires (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY Improved Mannequins (v0.35.0) | yorai | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| YYY Mystery Items Pack (1) (fails) | yorai | ??? | ❌ | ❌ | ✅ | ❌ |  |
| YYY Mystery Items Pack (v0.35.0) | yorai | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| YYY SAS (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY Serverside Saving (v0.35.0) | yorai | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| YYY Shields Complementary Pack (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY Step Up (v0.35.0) | yorai | 0.35.0 | ❌ | ❌ | ✅ | ❌ |  |
| YYY Visible Accessories (v0.38 unsure if stable) | yorai | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| YYY_Step_Up (fails) | yorai | ??? | ❌ | ❌ | ✅ | ❌ |  |
| ZZZ DRAGON PET | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |
| ZZZZ PROPER DARK SOULS | ??? | 0.38 | ❌ | ❌ | ✅ | ✅ |  |

## From tConfig Wiki
- https://tconfig.fandom.com/wiki/ModPacks

| Symbol | Meaning |
|--------|--------|
| ❌     | Not Done/Missing/Dead |
| ⚠️     | Unverified/No Download |
| ✅     | Downladable |

### 1.1+ Compatible Mods 2.0

| Mod Name | Author | tConfig Version | Source Files | Builds (on version) | obj File | working obj file | Link |
|----------|--------|-----------------|--------------|---------------------|----------|------------------|------|
| 13 Mods | [Shockah](https://forums.terraria.org/index.php?members/shockah.128/) | 0.38 | ❌ | ❌ | ❌ | ❌ | ❌ |
| 3 Mods | [SurfPup](https://forums.terraria.org/index.php?members/surfpup.21475/) | 0.38 | ❌ | ❌ | ❌ | ❌ | ❌ |
| 12 Mods | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.38 | ❌ | ❌ | ❌ | ❌ | ❌ |
| [The Kase Mod](https://forums.terraria.org/index.php?threads/tconfig-mod-the-kase-mod.28017/) | [Dragonpriest4](https://forums.terraria.org/index.php?members/dragonpriest4.12093/) | 0.36 | ✅ | ❌ | ❌ | ❌ | ✅ |
| [Industrial Revolution Mod](https://forums.terraria.org/index.php?threads/tconfig-mod-industrail-revolution-mod.38374/) | [Dragonpriest4](https://forums.terraria.org/index.php?members/dragonpriest4.12093/) | 0.36 | ✅ | ❌ | ❌ | ❌ | ✅ |

### 1.1+ Compatible Mods (NEED TO REGO AND CONFIRM WITH THE NEW TABLE FORMAT)

| Mod Name | Author | tConfig Version | Source Files | Builds (on version) | obj File | working obj file | Link |
|----------|--------|-----------------|--------------|---------------------|----------|------------------|------|
| [Green Cat's Xbox Controller Mod (needs more research)](https://forums.terraria.org/index.php?threads/xinput-gamepad-support-mod-pre-1-3.1260/) | [GreenCat77](https://forums.terraria.org/index.php?members/meowmaritus.5259/) | 0.35.3a | ❌ | ❌ | ❌ | ❌ |  |
| ChadPack - Food | Chadwick | 0.35.1a | ❌ | ❌ | ❌ | ❌ |  |
| W1K's Content Packs Remix | [W1K](https://forums.terraria.org/index.php?members/w1k.49/) | 0.35.1a |  ❌ |❌ | ❌ | ❌ |  |
| World of Falana | Wodzu93 | 0.35.1a | ❌ | ❌ | ❌ | ✅ |  |
| Jmod | Creeper_Man (Jensen) | 0.35.1 | ❌ | ❌ | ❌ | ❌ |  |
| Star Wars Modpack | FreyModder | 0.35.1 | ❌ | ❌ | ❌ | ❌ |  |
| Pixel Mark Crusaders' My Little Pony Pack | Pixel Mark Crusaders | 0.35.0 | ❌ | ❌ | ❌ | ❌ |  |
| ChadPack - Magic Mod | Chadwick | 0.34.1b | ❌ | ❌ | ❌ | ❌ |  |
| ChadPack - Nipponjin/Japanese Mod | Chadwick | 0.34.1b | ❌ | ❌ | ❌ | ❌ |  |
| Thorium Content Pack | DivermanSam | 0.34.0 | ❌ | ❌ | ❌ | ❌ |  |
| Buildaria-like mod | Duze | 0.33.0 | ❌ | ❌ | ❌ | ❌ |  |
| Super Metroid (and map) | Duze & ScooterBoot9697 | 0.33.0 | ❌ | ❌ | ❌ | ❌ |  |
| Ace's Final Fantasy Modification | Ace the Best | 0.31.1b | ❌ | ❌ | ❌ | ❌ |  |
| Retribution of the Darkness | Anton_ROTD | 0.31.1b | ❌ | ❌ | ❌ | ❌ |  |
| Bright Souls Mod v0.1.00 | LALZNOOBS | 0.31.1a | ❌ | ❌ | ❌ | ❌ |  |
| Recipe Book | grable | 0.30.4 | ❌ | ❌ | ❌ | ❌ |  |
| Space Mod | Deceitful Echo | 0.30.4 | ❌ | ❌ | ❌ | ❌ |  |
| Legend of Sapharan | Sapharan | 0.29.9 | ❌ | ❌ | ❌ | ❌ |  |
| Nyra's Mod Pack | Nyra Stiel | 0.29.6 | ❌ | ❌ | ❌ | ❌ |  |
| Daft Punk - Guy-Man's Helmet | Xargon | 0.29.3 | ❌ | ❌ | ❌ | ❌ |  |
| Doctor Who Mod | SonicR | 0.29.2 | ❌ | ❌ | ❌ | ❌ |  |
| Dark Souls Mod | Tim Hjersted | 0.29.1 | ❌ | ❌ | ❌ | ❌ |  |
| RussLeeIV's Mods | RussLeeIV | 0.29.1 | ❌ | ❌ | ❌ | ❌ |  |
| The Hellish Hardmode | Bullseye55 | 0.29.0 | ❌ | ❌ | ❌ | ❌ |  |
| Decorations and Wallpapers Pack | Eikester | 0.28.7 | ❌ | ❌ | ❌ | ❌ |  |
| Disassembly Mod | Eikester | 0.28.7 | ❌ | ❌ | ❌ | ❌ |  |
| Minecraft Hud Mod | Eikester | 0.28.7 | ❌ | ❌ | ❌ | ❌ |  |
| Terrariastuck | W1K | 0.28.7 | ❌ | ❌ | ❌ | ❌ |  |
| xR Zer0's Workshop | Wingzero007 | 0.28.7 | ❌ | ❌ | ❌ | ❌ |  |
| Droid15243's Modpacks | Droid15243 | 0.28.6 | ❌ | ❌ | ❌ | ❌ |  |
| Desert Pack | Eikester | 0.28.5 | ❌ | ❌ | ❌ | ❌ |  |
| Knight's Trenchcoats and Katanas | Knight9910 | 0.28.5 | ❌ | ❌ | ❌ | ❌ |  |
| Magia Machina | Revos | 0.28.5 | ❌ | ❌ | ❌ | ❌ |  |
| Bags of Holding | Lycos Hayes | 0.28.5 | ❌ | ❌ | ❌ | ❌ |  |
| Lycos Hayes' Vanity Flair Kit | Lycos Hayes | 0.28.5 | ❌ | ❌ | ❌ | ❌ |  |
| Tunnel King's Mods | Tunnel King | 0.28.5 | ❌ | ❌ | ❌ | ❌ |  |
| Drills and Tools | GiSS588 | 0.28.2 | ❌ | ❌ | ❌ | ❌ |  |
| Symple Terraria | Symple | 0.28.2 | ❌ | ❌ | ❌ | ❌ |  |
| Weapon/Accessory Modifier Pack | rangerofthewest | 0.28.2 | ❌ | ❌ | ❌ | ❌ |  |
| Alchemy Mod | [Deadwindshadow](https://steamcommunity.com/id/jimmyl) | 0.28.2 | ❌ | ❌ | ❌ | ❌ |  |
| SYNTAX'S MOD | SYNTAX | 0.28.1 | ❌ | ❌ | ❌ | ❌ |  |
| The Legend of Terraria | MiraiMai | 0.28.0 | ❌ | ❌ | ❌ | ❌ |  |
| Dynamic Difficulty Adjustment | Arkhalis | 0.27.2 | ❌ | ❌ | ❌ | ❌ |  |
| [Jewelcrafting Mod](https://www.dropbox.com/scl/fi/brt8sfl7nm04vmdq5sm4b/Jewelcrafting-Mod.zip?rlkey=mvc71qaqswka5qcmc5v6n2g9o&e=1) | [Deadwindshadow](https://steamcommunity.com/id/jimmyl) | 0.27.2 | ✅ | ❌ | ❌ | ✅ |  |
| Never Enough Devices! | MiraiMai | 0.27.2 | ❌ | ❌ | ❌ | ❌ |
| Never Enough Mods! | MiraiMai | 0.27.2 | ❌ | ❌ | ❌ | ❌ |
| Metroid Mod | scooterboot9697 | 0.27.2 | ❌ | ❌ | ❌ | ❌ |
| WW2 Weapons Pack | Shadow123 | 0.27.2 | ❌ | ❌ | ❌ | ❌ |
| Hesperides Temple | Excitement | 0.27.1 | ❌ | ❌ | ❌ | ❌ |
| Omnir's Modpacks | Omnir | 0.27.1 | ❌ | ❌ | ❌ | ❌ |
| Portal Mod (Temphix) | Temphix | 0.27.0 | ❌ | ❌ | ❌ | ❌ |
| Cobalt Mod | Blessed | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| Plexiglass | eliure | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| mbran's modpack | mbran139 | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| Mainslot-0 | MiraiMai | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| New Terraria Mod | Nawe^^ | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| [Rustlesser's ModPack 1.0.6](https://terraria.fandom.com/ru/wiki/Rustlesser%27s_ModPack) | [Rustlesser](https://terraria.fandom.com/ru/wiki/UserProfile:Rustlesser) | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| Sandbox Elemental | Solenix | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| Assassins Creed Modpack | X-Spider | 0.24.0 | ❌ | ❌ | ❌ | ❌ |
| The Portal Mod | [Surfpup](https://forums.terraria.org/index.php?members/surfpup.21475/) | 0.23.8 | ❌ | ❌ | ❌ | ❌ |
| tConfig Quest Mod | Wigglesniff | 0.23.8 | ❌ | ❌ | ❌ | ❌ |
| The True and Balanced Pack | Wingzero007 | 0.23.8 | ❌ | ❌ | ❌ | ❌ |
| Modern Warfare 3 Pack | warmaster949 | 0.23.7 | ❌ | ❌ | ❌ | ❌ |
| Tiles example pack (Surfpup) | [Surfpup](https://forums.terraria.org/index.php?members/surfpup.21475/) | 0.23.4b | ❌ | ❌ | ❌ | ❌ |
| Atomsk's Mods | AtomskShade | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Chest Colours | eliure | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Dark Souls Mod | Tim Hjersted | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Eggs! | Classikly | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Flag Mode | Light Sparkle | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| JMod | Joshua Searle | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Katanas+ | Fish Bowl | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Platinum Gear | Classikly | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Poison Mod | Party_Poison | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Sigia's Mod | Sigia | 0.23.3 | ❌ | ❌ | ❌ | ❌ |
| Silpa Mod | Silpa | 0.23.1 | ❌ | ❌ | ❌ | ❌ |
| Terraria Avalon | blahblahbal | 0.23.1 | ❌ | ❌ | ❌ | ❌ |
| Zoodle's Content Packs | Zoodletec | 0.33.0??? | ❌ | ❌ | ❌ | ❌ |
| Kjulo's DLC | Kjulo | 0.23.1 | ❌ | ❌ | ❌ | ❌ |
| Weird Weapon Mod | SpyStone | 0.23.1 | ❌ | ❌ | ❌ | ❌ |
| Other Worlds | Dogsonofawolf | 0.22.3 | ❌ | ❌ | ❌ | ❌ |
| Spells and Mysticism! | Mitchellex | 0.22.2 | ❌ | ❌ | ❌ | ❌ |
| Jordan's Modpack | Jordanlm98 | 0.21.7 | ❌ | ❌ | ❌ | ❌ |
| Dogsonofawolf's NPCs | Dogsonofawolf | 0.21.0 | ❌ | ❌ | ❌ | ❌ |
| Obsidian Mod | Obsidian | 0.19.6 | ❌ | ❌ | ❌ | ✅ |
| Sword Pack | Aerobit | 0.12.4 | ❌ | ❌ | ❌ | ❌ |
| Misc ModPack | FatObeseBird | ??? | ❌ | ❌ | ❌ | ❌ |
| Runescape Weapons | Robert | ??? | ❌ | ❌ | ❌ | ❌ |

### Terraria tConfig 1.0.6.1 Compatible Mods

| Mod Name | Author | tConfig Version | Source Files | Builds (on version) | obj File | working obj file | Link |
|----------|--------|-----------------|--------------|---------------------|----------|------------------|------|
| Death Pack | AlekakoC | 0.26.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Ice Pack | ??? | 0.26.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| [Rainbow Slime](https://www.mediafire.com/file/y45lwrbsj3r0l1k/SUPER+SLIME.rar) AKA SUPER SLIME | ??? | 0.26.2 | ✅ | ❌ |  ❌ | ❌ | ✅ |
| Kjulo's Dlc | Kjulo | 0.26.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Greater Healing Potion | Catlover341 | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| Amber Staff | Crimsonthorn | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| Day Orb | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| Kasudain's Arsenal | Kasudain | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| [Lawura's Builder Pack](https://tconfig.fandom.com/wiki/Lawura%27s_Builder_Pack) | Lawura | ??? | ❌ |  ❌ | ❌ | ❌ | ⚠️ |
| Weapon & Tools Overhaul | MrNewGuy | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| [Obsidian Sword](https://www.mediafire.com/file/kw51c2o7w5bqlpw/Obsidian+Sword.zip) | Serlan | ??? |  ✅ | ❌ | ❌ | ❌ | ✅ |
| [Supa Mushroom](https://www.mediafire.com/file/7d5yo2bemb0642a/Supa+Mushroom.zip) | ??? | ??? | ✅ | ❌ | ❌ | ❌ | ✅ |
| Dwarven Mod Pack | ShadowPhang | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| Barbershop | Slairne | 0.25.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| [Paradise Lost](https://tconfig.fandom.com/wiki/Paradise_Lost) | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ⚠️ |
| Goodie Box | ??? | 0.25.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Groovy Shirt | ??? | 0.25.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Lunar HP | ??? | 0.25.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Teleportation | ??? | 0.25.2 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Sagittarius Sword | ??? | 0.27.3 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Cosmic Crown | ??? | 0.27.3 | ❌ | ❌ | ❌ | ❌ | ❌ |
| [Portal Mod](https://www.mediafire.com/file/rgg67tqbsp664it/Portal%20Mod.zip) | Temphix | 0.27.0 | ✅ | ❌ | ❌ | ❌ | ✅ |
| Sword Pack | Offline | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| [Item Adventure Pack](https://tconfig.fandom.com/wiki/Bullseye55%27s_Item_Galaxy_Adventure!) | Bullseye55 | 0.26.4 | ❌ | ❌ | ❌ | ❌ | ⚠️ |
| VarietyPak | NeonJ | 0.26.4 | ❌ | ❌ | ❌ | ❌ | ❌ |
| Kjulos Mod (1.0 Beta) | Kjulo | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |
| SonnyMod | Sonny | ??? | ❌ | ❌ | ❌ | ❌ | ❌ |

### Category ModPack

- https://tconfig.fandom.com/wiki/Category:Modpack

| Mod Name | Author | tConfig Version | Source Files | Builds (on version) | obj File | working obj file | Link |
|----------|--------|-----------------|--------------|---------------------|----------|------------------|------|
| [Bullseye55's Item Galaxy Adventure!]((https://tconfig.fandom.com/wiki/Bullseye55%27s_Item_Galaxy_Adventure!)) | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ⚠️ |
| [HPack](https://tconfig.fandom.com/wiki/HPack) | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ⚠️ |
| [Lawura's Builder Pack](https://tconfig.fandom.com/wiki/Lawura%27s_Builder_Pack) | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ⚠️ |
| [Paradise Lost/old](https://tconfig.fandom.com/wiki/Paradise_Lost/old) | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ⚠️ |
| [Paradise Lost/old2](https://tconfig.fandom.com/wiki/Paradise_Lost/old2) | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ⚠️ |
| [Romulan Paladin's Dust and Sound Catalog Mod](https://tconfig.fandom.com/wiki/Romulan_Paladin%27s_Dust_and_Sound_Catalog_Mod) | Romulan Paladin | 0.22.8 | ✅ | ❌ | ✅ | ❌ | ⚠️ (embeded need to contact owner) |
| [Wingzero007 Mod Tests](https://tconfig.fandom.com/wiki/Wingzero007_Mod_Tests) | ??? | ??? | ❌ | ❌ | ❌ | ❌ | ⚠️ |

## Random (unconfirmed)
- Shockah's Mod
- W1K MM - 1.0.5 Balence