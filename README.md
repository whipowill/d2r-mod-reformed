# Diablo II Reformed

This is my custom mod for Diablo II Resurrected v2.4.3.  This is the version of the game I play on SSF Offline, and which represents the last true "classic" D2 version.

Since I play on Linux, I can't use D2RMM bc it doesn't work on wine.  Furthermore, putting together this mod myself takes me back to how we used to do things on D2LOD.

## Features

This mod includes the following changes:

- **Skip Intro** - skip the intro videos when you boot the game
- **Main Menu** - character selection screen just shows the world of Santuary (like D2LOD)
- **Extra Stash** - enjoy the max 7 stash tabs allowed by the game
- **Cain Location** - Deckard Cain now stands by the stash in Act V
- **Item Icons** - since we don't have loot filter, shortening names is best we can do
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

### Todo

- Add stacking gems
- Cube recipe changes
    - 2 items up

**Paused Ideas**

- Merc Auras - do I want this?  will it show on Merc screen?
- Splash Damage - do I want this?  does it break the game?

## Install

- Download this zipfile and extract it
- Make a ``mods/`` folder in your D2R directory
- Place ``reformed.mpq`` inside the ``mods/`` folder
- Change your game shortcut to launch with ``-enablerespec -txt -mod reformed``

Note that you can only play with one mod at a time and you must relaunch the game for your changes to take effect.

## Credits

- [HighTechLowIQ](https://github.com/HighTechLowIQ/ModdingDiablo2Resurrected) - original stash mod
- [Givemhell](https://www.nexusmods.com/diablo2resurrected/mods/102?tab=files&file_id=507) - original item icons
- [olegbl](https://www.nexusmods.com/diablo2resurrected/mods/176?tab=description) - original stackable gems

## Helpful Tools

- [Hexed.it](https://hexed.it/) - for editing binary files
- [CascView](https://www.hiveworkshop.com/threads/ladiks-casc-viewer.331540/) - for extracting data directory
- [D2RLFB](https://github.com/whipowill/php-d2r-lfb) - my PHP app to change item names
- [CharacterMap](https://en.wikipedia.org/wiki/GNOME_Character_Map) - Linux app for viewing font characters