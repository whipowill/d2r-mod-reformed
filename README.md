# Diablo II Reformed

This is a custom mod for Diablo II Resurrected v2.4.3 (June 29, 2022).  This is the version of the game I play on SSF offline, which I think represents the last true "classic" D2 version.

It's also the version I'm hearing rumors could support TCP/IP games.  Whoever at Blizzard made the decision to strip TCP/IP from the game -- after it was already in there -- is going to Hell.

I'm putting a lot of effort into making this as good as I can get it, w/ a few ideas from Project Diablo 2.  I plan to spend quite a bit of time adventuring in Sanctuary.

STATUS: In progress, not a final product.

## Features

I'm focusing on QOL features and trying to leave the game as classic as I can.

- **Skip Intro** - skip the intro videos when you boot the game
- **Main Menu** - removed character models to show you scenes of Santuary (like D2LOD)
- **Extra Stash** - stash has the max 7 tabs allowed by the game
- **Cain Location** - Deckard Cain now stands by the stash in Act V
- **Loot Filter** - shortening names w/ icons since we don't have a true loot filter
- **Stackable Items** - gems and runes are now stackable (when converted in cube)
- **Cube Recipies** - 3x gem and 2x rune cube to upgrade
- **Light Beams** - charms, jewels, and runes show beams of light
- **Infinite Ammo** - quivers can be magic, quivers and throwing weapons replenish
- **Splash Damage** - all melee weapons have splash damage (tuned low at 25%)
- **Drop Rates**
    - Runes (experimental & subject to change)
        - Low 60%
        - Mid 30%
        - High 10%
    - Countess
        - Always drops 3 runes
        - Can drop higher runes than vanilla
- **Class Tweaks**
    - Druid
        - Lycanthropy lasts 1 minute per point (from 20 seconds)
- **Merc Auras**
    - Act 1
        - Fire - Blessed Aim
        - Ice - Blessed Aim
    - Act 2 (no changes)
    - Act 3 (no changes YET)
    - Act 5 (no changes YET)


### Todo

- Add replenishing quant on unique and set items
- Enable mass gem upgrades by the stack
- Enable socket recipies on unique/set/rare/magic items (faux corruption mod)
- Jewel Fragments from PD2, would have to change recipies

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

## Notes

When dealing w/ stackable gems and runes, convert them into their stackable form in the Cube.  Due to a flaw in the game itself, you can't merge stacks of items to each other in the stash.  You have to take your stacked items from the stash, merge them in your inventory, and then move them back to the stash.

To disable or tweak melee splash damage, open ``mods/reformed/reformed.mpq/data/global/excel/missiles.txt`` and look for row 688 column DH.  I have this set to ``32`` which means 25% of weapon damage gets splashed (pretty low).  Changing to ``64`` would mean 50% of weapon damage gets splashed.  Changing to ``0`` would mean the feature is disabled.

Replenishing ammo runs at different time frames depending on the item.  Arrows and bolts will replenish at about 1 per 3 seconds.  Javalins seem to replenish at about 1 per 6 seconds.  If it works how it did in D2LOD, if you run your item down to 0 quantity it will disappear and you lose the item.

### Failures

I couldn't get these ideas work:

- Light beams for unique and set items

## Keyboard Macros

This game is very clicky and you can quickly develop carpal tunnel syndrome.  To avoid this I wrote a [keyboard macro](https://github.com/whipowill/ahk-autoattack) that lets you hold down ``spacebar`` to move and attack.  This makes melee characters a lot easier to play.

When using this type ``/nopickup`` when you enter the game so you don't pickup everything on the ground.

## Credits

With a little help from my friends:

- [hightechlowiq](https://github.com/HighTechLowIQ/ModdingDiablo2Resurrected) - original stash mod
- [givemhell](https://www.nexusmods.com/diablo2resurrected/mods/102?tab=files&file_id=507) - original font item icons
- [olegbl](https://www.nexusmods.com/diablo2resurrected/mods/176?tab=description) - original stackable gem/rune icons
- [deadjack](https://www.nexusmods.com/diablo2resurrected/mods/8?tab=files) - original melee splash mod

## External Links

Links to places that might be helpful:

- [Blizzard](https://diablo2.blizzard.com/en-us/) - official website
- [The Arreat Summit](http://classic.battle.net/diablo2exp/) - official guide
- [Holy Grail Tracker](https://d2-holy-grail.herokuapp.com/) - track your items
- [Tankazon's Rune Wizard](https://fabd.github.io/diablo2/runewizard/index.html) - plan your runewords
- [D2 Planner](https://d2planner.github.io/skills/) - plan your skills
- [Reddit](https://www.reddit.com/r/diablo2/) - forum for all the D2 fans