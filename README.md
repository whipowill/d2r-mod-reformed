# Diablo II Reformed

![Diablo II Resurrected](https://i.imgur.com/LJvw35g.png)

This is a custom mod for Diablo II Resurrected v2.4.3 (released June 29, 2022).  This is the version of the game I play on SSF offline, which I think represents the last true "classic" D2 version.

This version of the game also supports TCP/IP games.

I'm putting a lot of effort into making this as good as I can get it, w/ a few ideas from Project Diablo 2.  I plan to spend quite a bit of time adventuring in Sanctuary.

STATUS: IN PROGRESS

## Features

I'm focusing on QOL features but trying to leave the game as classic as I can.

- **TCP/IP** - configured to use Bonesy's TCP/IP mod
- **Skip Intro** - skip the intro videos when you boot the game
- **Main Menu** - removed character models to show you scenes of Santuary
- **Extra Stash** - stash has the max 7 tabs allowed by the game
- **Cube Expansion** - cube is 2x as large for twice as much loot
- **Cain Location** - Deckard Cain now stands by the stash in Act V
- **Amazon Retouch** - restoring model to be closer to original game
- **Loot Filter** - shortening names w/ icons since we don't have a true loot filter
- **Potion Boost** - all temporary potions last 5 minutes (from 30 seconds)
- **Magic Quivers** - arrows and bolts can be magic and rare
- **Infinite Ammo** - quivers and throwing weapons replenish quantity
- **Splash Damage** - all melee weapons have splash damage (set at 100%)
- **Countess Counts** - always drops 3 runes, and can drop higher than before
- **Rune Drops** - high runes are much less punishing to find
- **Druid Fixes** - shapeshift lasts longer, vines and spirits never die
- **Merc Auras** - Blessed Aim in Act 1, ____ in Act 3, and ____ in Act 4 (unfinished)
- **Simple Upgrades** - 3x gem to upgrade gem, 2x rune to upgrade rune
- **Easy Respec** - cube a key to get a Token of Absolution
- **Stackable Gems** - cube a gem to convert to stackable form
- **Stackable Runes** - cube a rune to convert to stackable form
- **Safe Unsocket** - socketed item + key -> get the item and runes back
- **Corrupted Items** - unsocketed unique/set item + Worldstone Shard -> socketed item
- **Jewel Fragments** - cube unwanted jewels into stackable jewel fragments

### Todo

- Enable en masse gem upgrades by the stack
- Add new sprites for Jewel Fragment and Worldstone Shard (help needed)
- Make Jewel Fragment recipies actually work as if it were a Jewel

## Install

- Download this [zipfile](https://github.com/whipowill/d2r-mod-reformed/archive/master.zip) and extract it
- Make a ``mods/`` folder in your D2R directory
- Place ``reformed.mpq`` inside the ``mods/reformed/`` folder
- Change your game shortcut to launch with ``-enablerespec -txt -mod reformed``
- Download the icon font file (100mb) from [here](https://mega.nz/folder/2d5DQBQC#VQoZVQUwnf0JzgEr1qplYg)
- Place font in ``mods/reformed/reformed.mpq/data/hd/ui/fonts/``
- Copy my stash files from ``Saved Games/`` into your user D2R Saved Games folder
    - THIS ACTION WILL ERASE YOUR SHARED STASH!
- Launch the game and enjoy the chill vibes

### TCP/IP

- Rename your ``D2R.exe`` to ``D2R_OLD.exe``
- Download the TCP/IP mod [here](https://drive.google.com/uc?export=download&id=1QWmeInMTQvn-LUJsgZMyKchwvh58BNrK)
- Copy the new ``D2R.exe`` into your D2R directory

## Notes

When dealing w/ stackable gems and runes, convert them into their stackable form in the cube.  Due to a flaw in the game itself, you can't merge stacks of items to each other in the stash.  You have to take your stacked items from the stash, merge them in your inventory, and then move them back to the stash.

I made all stackable items (keys, gems, runes, fragments, shards) where if you cube the stack it will break off one from the stack for you.

To disable or tweak melee splash damage, open ``mods/reformed/reformed.mpq/data/global/excel/missiles.txt`` and look for row 688 column DH.  I have this set to ``32`` which means 25% of weapon damage gets splashed (pretty low).  Changing to ``64`` would mean 50% of weapon damage gets splashed.  Changing to ``0`` would mean the feature is disabled.

### Failures

I couldn't get these ideas work:

- Light beams on drop for unique and set items

## Keyboard Macros

This game is very clicky and you can quickly develop carpal tunnel syndrome.  To avoid this I wrote a [keyboard macro](https://github.com/whipowill/ahk-autoattack) that lets you hold down ``spacebar`` to move and attack.  This makes melee characters a lot easier to play.

When using this type ``/nopickup`` when you enter the game so you don't pickup everything on the ground.

## Credits

With a little help from my friends:

- [bonesy](https://www.d2rmodding.com/remodded) - TCP/IP mod
- [hightechlowiq](https://github.com/HighTechLowIQ/ModdingDiablo2Resurrected) - original stash mod
- [givemhell](https://www.nexusmods.com/diablo2resurrected/mods/102?tab=files&file_id=507) - original font item icons
- [olegbl](https://www.nexusmods.com/diablo2resurrected/mods/176?tab=description) - original stackable gem/rune icons
- [deadjack](https://www.nexusmods.com/diablo2resurrected/mods/8?tab=files) - original melee splash mod
- [yoloswag](https://www.nexusmods.com/diablo2resurrected/mods/45) - original Amazon retouch
- [olegbl](https://www.nexusmods.com/diablo2resurrected/mods/189?tab=files) - original expanded cube

## External Links

Links to places that might be helpful:

- [Blizzard](https://diablo2.blizzard.com/en-us/) - official website
- [The Arreat Summit](http://classic.battle.net/diablo2exp/) - official guide
- [Holy Grail Tracker](https://d2-holy-grail.herokuapp.com/) - track your items
- [Tankazon's Rune Wizard](https://fabd.github.io/diablo2/runewizard/index.html) - plan your runewords
- [D2 Planner](https://d2planner.github.io/skills/) - plan your skills
- [Reddit](https://www.reddit.com/r/diablo2/) - forum for all the D2 fans