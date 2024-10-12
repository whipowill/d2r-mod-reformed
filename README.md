# Diablo II Reformed

This is my custom mod for Diablo II Resurrected v2.4.3.  This is the version of the game I play on SSF Offline, and which represents the last true "classic" D2 version.

I'm putting a lot of effort into making this as good as I can get it, coming from Project Diablo 2.  I plan to spend quite a bit of time adventuring in Sanctuary.

Since I play on Linux, I can't use D2RMM bc it doesn't work on wine.  So, putting together this mod by myself takes me back to how we used to do things on D2LOD.

## Features

This mod includes the following changes:

- **Skip Intro** - skip the intro videos when you boot the game
- **Main Menu** - removed character models so you can focus on Santuary (like D2LOD)
- **Extra Stash** - stash has the max 7 tabs allowed by the game
- **Cain Location** - Deckard Cain now stands by the stash in Act V
- **Item Icons** - shortening names w/ icons since we don't have a loot filter
- **Light Beams** - certain items now flash a beam of light when they drop
    - Charms
    - Jewels
    - Runes
- **Drop Tweaks**
    - Runes are less punishing to find (experimental)
    - Countess
        - Always drops 3 runes
        - Can drop higher runes
- **Class Tweaks**
    - Druid
        - Lycanthropy lasts 1 minute per point
- **Stackable Items** - gems and runes are stackable to 48 and 12

### Todo

- Stackable Keys - uber keys?
- Jewel Fragments - new item from PD2
- Merc Auras - do I want this?  will it show on Merc screen?
- Splash Damage - do I want this?  does it break the game?
- Tier labels for unique and set items
- Light beams for unique and set items

## Install

- Download this zipfile and extract it
- Make a ``mods/`` folder in your D2R directory
- Place ``reformed.mpq`` inside the ``mods/reformed/`` folder
- Change your game shortcut to launch with ``-enablerespec -txt -mod reformed``

Note that you can only play with one mod at a time and you must relaunch the game for your changes to take effect.

## Credits

- [HighTechLowIQ](https://github.com/HighTechLowIQ/ModdingDiablo2Resurrected) - original stash mod
- [Givemhell](https://www.nexusmods.com/diablo2resurrected/mods/102?tab=files&file_id=507) - original item icons
- [olegbl](https://www.nexusmods.com/diablo2resurrected/mods/176?tab=description) - original stackable gem icons

## Tools

- [Hexed.it](https://hexed.it/) - for editing binary files
- [CascView](https://www.hiveworkshop.com/threads/ladiks-casc-viewer.331540/) - for extracting data directory
- [D2RLFB](https://github.com/whipowill/php-d2r-lfb) - my PHP app to change item names
- [CharacterMap](https://en.wikipedia.org/wiki/GNOME_Character_Map) - Linux app for viewing font characters

## External Links

- [Blizzard](https://diablo2.blizzard.com/en-us/) - official website