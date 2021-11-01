# DIABOLIST VR INSTALL GUIDE

- [1] [Introduction.](#introduction)

- [2] [Core Mod List Features.](#core-mod-list-features)

- [3] [Dev Details and Test Specs.](#dev-details-and-test-specs)

- [4] [Gameplay Preperation.](preperation)

    - [4a] [SkyrimVR Install.](#skyrimvr-install)

    - [4b] [Wabbajack Install.](#wabbajack-install)


# INTRODUCTION.
![Diabolist VR Wolf Right Final 2 0 D-R-R](https://user-images.githubusercontent.com/78007822/139607370-54db657a-af31-498c-acfb-b3474550df9a.jpg)
#
Diabolist VR pays homage to the hack-n-slash loot-hoarding ARPG of the late 90s, by adding 6 Diablo inspired mods, which includes a custom flame intro and music overhaul, authentic Diablo in-game font, the female Amazon character from Diablo 2 overhauled with spear throwing mechanics, the Horadric Crafting Cube, Imperius Solarion Spear and Tyrael Armor from Diablo 3, increased overall population with hundreds of unique monsters, a sprawling dungeon called Skyrim Underground, along with 65 additional Forgotten Dungeons.

The loot system is **very generous**, like the Diablo series always has been, so you will likely be tossing away or selling much, Nethers Follower Framework has an option to enable your followers to run to town and sell **ANY** gear you give them for the **FULL worth of the item** regardless of the funds available on merchants, using this feature is **Highly Recommended** as you continue gathering loot as DVR hosts merchants with 10x the default amount of septims as vanilla Skyrim gives when you goto the stores to sell manually, this won't be nearly enough for what you will find and want to sell. **All that being said**... making income in DVR will **NOT** be an issue regardless of selling gear, due to the treasure chests, bosses and dragons also providing plenty of septims.

**DVR uses a 5 tier loot system inspired by Diablo 4.**
 - Common 
 - Magical 
 - Rare
 - Legendary 
 - Mythic

This also **applies 10 different enchant variations on all tiers**, **EXCEPT** common.
#
## CORE MOD LIST FEATURES.

- Enemies will be stronger to start but not over-powering, Fine-Tuned difficulty settings flow in both directions for hard-mode or easy-mode, plus a few optional cheat mods are available for casual steam-rolling fun.

- Staying true to the original Skyrim content, there are no major storyline addons or game-changing town/city/quest overhauls, it's a large yet surprisingly straight-forward mod list, the Dragonborn storyline and Civil War are still the focal point and on par with vanilla.

- All nonsense weapon and armor enchantments from the Summermyst Enchantments mod have been removed, this makes for awesome enchantment combinations for all the items they apply too, you will likely need to crank difficulty as you level up and find Legendary & Mythic items, you will become quite powerful.

- Random Loot Boxes at several merchants across Skyrim, they are easy to find and they *can be* addictive.

- Transmuting lower quality items into a higher quality ones, or convert items of one type to another with the [Horadric Cube from Diablo II](https://www.nexusmods.com/skyrim/mods/22806/?tab=description) ⬅️**please read the authors nexus page linked here to see more details on how to do this.**

- This mod list is a loot hoarders dream ...and with that in mind, every new character you create starts with a ring that has 10,000 carry weight.

- VR controller functionality, physics, visuals, performance are all enhanced & improved through various tools, mods & .ini settings.

- **Focusing heavily on mod list optimization**, DVR uses low DynDOLOD settings along with Occlusion, with a surprisingly decent visual outcome, most players *should* have good performance with multiple HMDs on higher-end modern PCs.**

- The latest must-have popular VR Quality of Life mods have all been added and fully updated to my knowledge. (this includes the new SkyUI)

**Diabolist VR aims to be a simple to setup & play, high-fantasy, Diablo themed mod list, based on dungeon crawling, monster hunting and loot hoarding,** _I tried my best to create a nostalgic Diablo vibe while adventuring through the province of Skyrim._
#
## DEV DETAILS AND TEST SPECS.

### Developed and tested with this HMD and PC setup:

 - Oculus Rift S.
 - Win 10 ver. 1909 Fully Updated.
 - Ryzen 7 3800x AMD Processor.
 - 32 Gigs of G-Skill 14-34 Low Latency RAM.
 - Kingston NVMe M.2 1tb SSD.
 - Nvidia 3090 GPU.
#
The initial wabbajack setup file is 4.80 gb & the finished install folder size is 94 gb, for a total size of roughly 99 gb, it’s highly recommended that you install this on a NVMe M.2 SSD for optimal performance, although traditional SSD should be fine.

**I focused heavily on optimizing DVR** during development and testing via performance tools, mod settings, ini settings and using low DynDOLOD 3 @ 512k res with xLodGEN Occlusion.

Most users should experience good performance using multiple HMDs with a higher-end modern PC. 

Since I use a Rift S, the skyrimvr.ini / skyrimprefs.ini files will reflect that, so a few of these .ini settings need to be adjusted to suit your specific HMD. I will go over that and other recommended settings throughout this guide.
#

## GAMEPLAY PREPERATION.

### SkyrimVR Install:

It is **CRITICAL** to have a 100% fresh install of SkyrimVR available & ready to play with no other files added, It is also **CRITICAL** to **have your SkyrimVR game installed in a folder outside of  C:/Program Files  and  C:/Program Files (x86)**  just **ignore these 2 folders for the entire process of this install guide, due to possible admin rights restrictions.**

Steam does not easily allow for new install folders, simply follow 
[This Easy Guide](https://drive.google.com/drive/folders/1lOBFqblzA23AbXFz-usTejOKR5UFsPjA?usp=sharing) to change that.

First, start the default Steam version of SkyrimVR to have the game create the appropriate .ini file in the documents folder on your C drive, and also to adjust the game's vanilla settings.

I have provided screenshots of the recommended SkyrimVR settings, along with highly recommended mod settings for DVR, however, all mod options in MCM are relatively safe to experiment with.

Refer to these screenshots below once you first load the game, **(and after Diabolist VR is installed)**... as I will Not be explaining these settings in detail aside from the screenshot **‘NOTES’** i have added, most of this is self-explanatory and also based on your preference and PC performance.
#
![VR Performance](https://user-images.githubusercontent.com/78007822/139617500-49f12f18-8311-426e-a045-c1b5ae8cf814.png)
-
![VR Performance 2](https://user-images.githubusercontent.com/78007822/139617544-c8bfd44b-a2bf-411a-a283-05d8dc02ac70.png)
![VR Performance 3](https://user-images.githubusercontent.com/78007822/139618123-a1acb305-3ff7-4e7d-8f9b-c0968dd25e31.png)
-
![VR General Settings](https://user-images.githubusercontent.com/78007822/139700937-e01a3313-06cd-4111-8d8b-e30e5bb21495.png)
![VR General Settings 2](https://user-images.githubusercontent.com/78007822/139618717-47785cc5-81c8-43ac-9f0e-82e693936673.png)
#
## Wabbajack Install:

### A NEXUS PREMIUM ACCOUNT IS HIGHLY RECOMMENDED, OTHERWISE 600 MODS WILL HAVE TO BE DOWNLOADED MANUALLY.😵
#
- Download and install the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases). ⬅️️ **This 1st step is mandatory**

- Next, download [DiabolistVR](https://drive.google.com/file/d/1T8xmV9K4_5wMt4AC2rBia09qgBqL8JOu/view?usp=sharing).

- Make a folder on any SSD drive with space and **label it DVR.**

- **IMPORTANT REMINDER: -DO NOT- Install Anything Into Your C:/Program Files or C:/Program Files (x86) Folders, due to admin restrictions.**

- Open the Wabbajack file you downloaded to begin the install process, on the bottom right, select the DVR folder you created & the download section will automatically pick the mod folder for you inside of itself, or you can select a different folder to keep the downloaded zipped mods separate, it’s your choice.

- Click the big blue arrow, sit back & relax while it installs, if you’re curious you can watch the mod info that pops up to get an idea of what’s being installed, you are downloading over 500 mods so just be patient & let it finish, if it freezes, simply start the process over, to do this, open the Diabolist VR wabbajack file & click the arrow again without doing anything else & it will resume where it left off.

- After install is finished, close the Wabbajack window & proceed to the DVR folder, open the Game Files Folder, then drag & drop ALL of these files into your SkyrimVR root folder.

## ⚙️SKYRIMVR INI TWEAKER⚙️


