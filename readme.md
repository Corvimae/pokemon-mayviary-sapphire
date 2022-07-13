# Pokémon Mayviary Sapphire

I asked my Discord to replace as many trainers in Alpha Sapphire as they wanted, and they sure did something with it, huh.

This is absolutely unbalanced. It's similar to [Emerald Kaizo](https://www.pokecommunity.com/showthread.php?t=395830), though almost certainly not as difficult. Things will seem arbitrary and not make sense. It is a disaster, please enjoy it.

## Installing
1. Download [Lunar IPS](https://fusoya.eludevisibility.org/lips/index.html) if you don't already have it.
2. Download the latest release from [Releases](https://github.com/Corvimae/pokemon-mayviary-sapphire/releases) and unzip it.
3. Unpack your Alpha Sapphire ROM using the [.Net 3DS Toolkit](https://gbatemp.net/threads/release-net-3ds-toolkit-extract-and-repack-3ds-roms-and-cias.444427/) (or another tool if you prefer). **You must dump your own cartridge or digital copy using custom firmware. I cannot tell you where to acquire a ROM.**
    ```
    > ToolkitConsole.exe AlphaSapphire.3ds AS
    ```
4. Double-click on each of the IPS files in the unzipped folder, and apply each patch to the associated file using the table below:
    Patch        | File
    -------------|---------------
    trdata.ips   | RomFS/a/0/3/6
    trclass.ips  | RomFS/a/0/3/7
    trpoke.ips   | RomFS/a/0/3/8
    gametext.ips | RomFS/a/0/8/1
5. Repack the ROM.
    ```
    > ToolkitConsole.exe AS MayviaryAS.cia
    ```

You need Luma3DS or an emulator to run this mod.

## Rules

### Rules for all trainers
- Your team must not exceed the level of the original trainer's highest leveled Pokemon by more than 50%, rounded up. (e.g. Roxanne's Lv. 12 and 14 would allow you to have Lv. 21 Pokemon)	
- You can rename the trainer.	
- You must attempt to maintain some sort of team consistency for repeated trainers. A claim on a repeated trainer is a claim on all of their encounters.
- Trainers that use a Mega Evolution must still use one.
- No Legendaries or Mythicals.

### Rules for boss trainers (gym leaders, Elite 4, Archie, etc.)
- You may add up to 3 additional Pokemon to your trainer.	
- You may give the leader up to two additional HEALING OR BATTLE ITEMS.	
- You may set the AI level to 255.
- Brendan/May are considered a boss, except for Brendan/May 1. You must keep starter consistency, but you can go Hop I Don't Know What I'm Doing Disaster Mode if you like.	
- Tate and Liza are separate claims. I believe you can give them each up to 6? It works in Emerald I know.		
- Gym leaders and Elite 4 members need a theme!	
- Aqua members must primarily use Dark and Water types.	
- Repeated trainers may have one Legendary or Mythical on their final Any% encounter.  (Elite 4 may have one in round 2)
- You may add one Mega if the trainer does not use one and it is after the 4th badge.	
- No limit on held items.	

### Rules for miscelaneous trainers
- You may set the AI level to 135.
- If the trainer is a gym trainer or Team Aqua member, you may give then one item.
- You may change the trainer class of the trainer unless they are a Aqua Grunt.
- If you claimed a gym leader, you have first call on that gym's trainers if you want them.
- No Mega Evolutions.
- You may use one held item.

## Notes
- Due to limitations of the engine, trainer IVs are always the same and can only be 0, 8, 16, or 24. EVs are always 0.
Text file 22 - Trainer Names