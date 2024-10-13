# Diablo II Reformed

This is a custom mod for Diablo II Resurrected v2.4.3.  This is the version of the game I play on SSF offline, which I think represents the last true "classic" D2 version.

It's also the version that I'm hearing rumors is close to being able to support TCP/IP games.

I'm putting a lot of effort into making this as good as I can get it, w/ a few ideas from Project Diablo 2.  I plan to spend quite a bit of time adventuring in Sanctuary.

Since I play on Linux, I can't use D2RMM bc it doesn't work on Wine.  So, putting together this mod by myself takes me back to how we used to do things on D2LOD.

## Features

I'm focusing on QOL features and leaving the game as classic as I can.

- **Skip Intro** - skip the intro videos when you boot the game
- **Main Menu** - removed character models to show you scenes of Santuary (like D2LOD)
- **Extra Stash** - stash has the max 7 tabs allowed by the game
- **Cain Location** - Deckard Cain now stands by the stash in Act V
- **Loot Filter** - shortening names w/ icons since we don't have a true loot filter
- **Stackable Items**
    - Keys to 24 (from 12)
    - Scrolls to 48 (from 20)
    - Gems to 48 (from 1)
    - Runes to 12 (from 1)
- **Cube Recipies**
    - 3x gem -> higher gem
    - 2x rune -> higher rune
- **Light Beams**
    - Charms
    - Jewels
    - Runes
- **Drop Rates**
    - Runes (experimental & subject to change)
        - Low Runes 60%
        - Mid Runes 30%
        - High Runes 10%
    - Countess
        - Always drops 3 runes
        - Can drop higher runes per difficulty
- **Class Tweaks**
    - Druid
        - Lycanthropy lasts 1 minute per point (from 20 seconds)
- **Weapons Changes**
    - Quivers
        - Replenishing
        - Magic and Rare possible
- **Merc Auras**
    - Act 1 - Blessed Aim
        - Fire
        - Cold
    - Act 2 (no changes)
        - Normal
            - Combat - Prayer
            - Defense - Defiance
            - Offense - Blessed Aim
        - Nightmare
            - Combat - Thorns
            - Defense - Holy Freeze
            - Offense - Might
        - Hell
            - Combat - Prayer
            - Defense - Defiance
            - Offense - Blessed Aim
    - Act 3 - Meditation

    - Act 5 (no change, still thinking about it)

When dealing w/ stackable gems and runes, convert them into their stackable form in the Cube.  Due to a flaw in the game itself, you can't merge stacks of items to each other in the stash.  You have to take your stacked items from the stash, merge them in your inventory, and then move them back to the stash.

### Todo

- Add margin spacing to loot drop frames
- Enable socket recipies on unique/set/rare/magic items
- Jewel Fragments - idea from PD2, would have to change recipies
- Merc Auras - do I want this?  will aura show on Merc screen?
- Splash Damage - do I want this?  does it break the game?
- Tier labels for unique and set items

### Not Doable

These are ideas I had but couldn't get to work.

- Light beams for unique and set items

## Thoughts

I'm a D2 purist who rejected D2R as being an unworthy version of the game.  After sitting out for 3 years, I've finally taken the plunge to try and see if I can make D2R work for me.

The decision to take TCP/IP out of D2R was a crime against humanity.  Whoever made that decision at Blizzard is going to spend an eternity in Hell.  Also, whoever butchered the Amazon -- eternity in Hell.

Rumors are that modders will get v2.4 of the game to work on TCP/IP.

One of the biggest mistakes made in D2R was allowing close up view of your characters.  The blurry vision of the characters in LOD gave you room to use your imagination as to who they were and what they looked like.

Making the main menu focus entirely on close up view of your characters was a mistake bc those menu screens are meant to focus on Santuary itself.  Scenes of the horror of the world you are about to jump in and save.

But let me talk about the poisitives.

## Install

- Download this [zipfile](https://github.com/whipowill/d2r-mod-reformed/archive/master.zip) and extract it
- Make a ``mods/`` folder in your D2R directory
- Place ``reformed.mpq`` inside the ``mods/reformed/`` folder
- Change your game shortcut to launch with ``-enablerespec -txt -mod reformed``
- Download the icon font file (100mb) from [here](https://mega.nz/folder/2d5DQBQC#VQoZVQUwnf0JzgEr1qplYg)
- Place font in ``mods/reformed/reformed.mpq/data/hd/ui/fonts/``
- Launch the game

## Keyboard Macros

This game is very clicky and you can quickly develop carpal tunnel syndrome.  To avoid this I wrote a [keyboard macro](https://github.com/whipowill/ahk-autoattack) that lets you hold down ``spacebar`` to move and attack.  This makes melee characters a lot easier to play.

When using this type ``/nopickup`` when you enter the game so you don't pickup everything on the ground.

## Credits

A little help from my friends.

- [HighTechLowIQ](https://github.com/HighTechLowIQ/ModdingDiablo2Resurrected) - original stash mod
- [Givemhell](https://www.nexusmods.com/diablo2resurrected/mods/102?tab=files&file_id=507) - original font item icons
- [olegbl](https://www.nexusmods.com/diablo2resurrected/mods/176?tab=description) - original stackable gem/rune icons

## Tools

- [Hexed.it](https://hexed.it/) - for editing binary files
- [D2Excel](https://hexed.it/) - for editing TXT files
- [CascView](https://www.hiveworkshop.com/threads/ladiks-casc-viewer.331540/) - for extracting data directory
- [D2RLFB](https://github.com/whipowill/php-d2r-lfb) - my PHP app to manage "loot filter" item names
- [CharacterMap](https://en.wikipedia.org/wiki/GNOME_Character_Map) - Linux app for viewing font characters

## External Links

- [Blizzard](https://diablo2.blizzard.com/en-us/) - official website
- [The Arreat Summit](http://classic.battle.net/diablo2exp/) - official guide
- [Holy Grail Tracker](https://d2-holy-grail.herokuapp.com/) - track your items
- [Tankazon's Rune Wizard](https://fabd.github.io/diablo2/runewizard/index.html) - see what runewords you can make
- [D2 Planner](https://d2planner.github.io/skills/) - plan your skill allocations
- [Reddit](https://www.reddit.com/r/diablo2/) - forum for all the D2 fans