# Jwizzle's Addons List for TurtleWoW 1.17.0
This is Jwizzle's comprehensive Addon repository for TurtleWoW Vanilla Plus. I created this Repository to consolidate the addons I use and provide a list for others to download Addons for TurtleWoW. NOTE: Not every Addon is compatible with other Addons.

*The repository will be updated every few months to the newest build of the addons*

Here, you may also find the [sources](https://github.com/NoM0Re/Addons/blob/main/README.md#most-useful-wow-addons-for-patch-335a-wotlk) so you can download them directly if you prefer. Best of luck Turtles and happy questing.

## Table of Contents
- AtlasLoot TW Edition
- Auctionator
- AutoDB2
- Dhask's FlightMap
- LevelRange[Turtle]
- Looking For Turtles - LFT
- Magnify
- Mail
- Missing TradeSkills List
- SortBags
- TradeSkillsData[Vanilla]
- TradeSkillsData[Turtle]
- TurtleSnacks
- unitscanTurtle
- WIM
- TurtleCount
- PfQuest
- PfQuest[TurtleWoW DB]
- PfUI
- PfUI[Elite Overlay]
- ShaguNotify
- ShaguScore
- ShaguDPS

## Installing WoW Addons
1. Download an Addon
2. Unzip downloaded Addon (if required)
3. Find in your World of Warcraft folder, the /Interface/Addons folder
4. Drag and drop folder(s) into the addon folder (folder name should match .toc file inside; remove "-master" if needed).
5. Restart the Game

## Patching a Vanilla Client
By default, you may notice that in Vanilla WoW, Auto-loot is enabled by holding shift when right-clicking a mob. To reverse this and auto-loot by default rather than by shift-clicking, you will need to patch your client which you can do manually by changing the bytes of the `WoW.exe` file, or by using a simple pre-made patcher. I recommend using the tool described in this [TurtleWoW Forum Post](https://forum.turtle-wow.org/viewtopic.php?f=29&t=2331&sid=7e91376af1c056172eb82b92e1ca18cb) By patching your client using this tool, you may also apply the following enhancements:

- **apply 4GB Patch**
  - Makes the game use up to 4GB of virtual memory instead of the designated 2GB.
  - (same functionality as the 4GB Patch from NTCore)

- **disable Cache generation**
  - Basically hinders the game from creating a WDB folder and its cache files within.
  - (simply changes the folder name to a "blank" name, and since Windows can't create such folders the folder and the files within don't get generated at all)

- **increased Sound Channels**
  - Raises the limit of the maximum useable Sound Channels from 12 to 256.
  - (ever wondered why some sound effects won't play when you're for e.g. in a crowded area, because all useable sound channels are occupied at that moment.)

- **improved Field of View**
  - Increases the FoV value from the original ~1.57 to ~1.925 which is used in WotLK.
  - (same value as in the improved-fov.exe from Torta's Github)

- **AutoLoot w/o shift**
  - It basically reverses its functionality, so you loot automatically without holding [shift] (or your designated key) and loot normally while holding it.

*Full Credit to Subannix on the TurtleWoW Forum for this*
     
# Addon List

### Atlasloot TW Edition
Loot tables for Dungeons and Raids

[Download](https://github.com/Lexiebean/AtlasLoot)

![Screenshot](/Images/atlasloot.webp)

