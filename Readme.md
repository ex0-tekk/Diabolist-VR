# DIABOLIST VR INSTALL GUIDE

- [1] [Introduction.](#introduction)

- [2] [Mod List Features.](#mod-list-features)

- [3] [Dev Details and Test Specs.](#dev-details-and-test-specs)

- [4] [Gameplay Preperation.](#gameplay-preperation)

    - [4a] [SkyrimVR Install:](#skyrimvr-install)

    - [4b] [Wabbajack and DVR Install:](#wabbajack-and-dvr-install)
    
    - [4c] [SkyrimVR ini Tweaker:](#skyrimvr-ini-tweaker)
    
    - [4d] [CPU Threads:](#cpu-threads)
    
- [5] [MCM Recommended Settings.](#mcm-recommended-settings)
     
    - [5a] [Be Seated:](#be-seated)
    
    - [5b] [Claralux Lighting:](#claralux-lighting)
    
    - [5c] [DynDOLOD:](#dyndolod)
   
    - [5d] [Fine-Tuned Challange:](#fine-tuned-challange)
    
    - [5e] [Mihail Monster and SiC Difficulty Warning:](#mihail-monster-and-sic-difficulty-warning)


#
## INTRODUCTION.
![Diabolist VR Wolf Right Final 2 0 D-R-R](https://user-images.githubusercontent.com/78007822/139607370-54db657a-af31-498c-acfb-b3474550df9a.jpg)
-
Diabolist VR pays homage to the hack-n-slash loot-hoarding ARPG of the late 90s, by adding 6 Diablo inspired mods, which includes a custom flame intro and music overhaul, authentic Diablo in-game font, the female Amazon character from Diablo 2 overhauled with spear throwing mechanics, the Horadric Crafting Cube, Imperius Solarion Spear and Tyrael Armor from Diablo 3, increased overall population with hundreds of unique monsters, a sprawling dungeon called Skyrim Underground, along with 65 additional Forgotten Dungeons.

The loot system in DVR is **very generous**, just like the Diablo series is known for, so you will likely be tossing away or selling much, Nethers Follower Framework provides a dialogue option to make your followers run to town and sell **ANY** gear you give them regardless of the funds available on merchants, using this feature is **Highly Recommended** as you continue gathering loot, because when you goto the stores to sell manually, merchants will only have 10x the default amount of septims as vanilla Skyrim, but this won't be nearly enough for what you will find and want to sell. **All that being said**... making income in DVR will **NOT** be an issue regardless of selling gear, due to the treasure chests, bosses and dragons also providing plenty of septims.

**DVR uses a 5 tier loot system inspired by Diablo 4.**
 - Common 
 - Magical 
 - Rare
 - Legendary 
 - Mythic

This also **applies 10 different enchant variations on all tiers**, **EXCEPT** common.
#

## MOD LIST FEATURES.

- Enemies will be stronger to start but not over-powering, Fine-Tuned difficulty settings flow in both directions for hard-mode, easy-mode and everything in between, with a few _optional_ cheat mods available for casual steam-rolling fun.

- This mod list is a loot hoarders dream ...and with that in mind, every new character you create starts with a carry weight ring of 10,000.

- All nonsense weapon and armor enchantments from the Summermyst Enchantments mod have been removed, this makes for awesome enchantment combinations for all the items they apply too, you will likely need to crank difficulty as you level up and find Legendary & Mythic items, you will become quite powerful.

- Staying true to the original Skyrim content, there are no major storyline addons or game-changing town/city/quest overhauls, however, there are still plenty of noticable changes, it's a large yet surprisingly straight-forward mod list, the Dragonborn storyline and Civil War are still the focal point and on par with vanilla.

- Random Loot Boxes at several merchants across Skyrim, they are easy to find and they *can be* addictive.

- Transmuting lower quality items into a higher quality ones, or convert items of one type to another with the [Horadric Cube from Diablo II](https://www.nexusmods.com/skyrim/mods/22806/?tab=description) ⬅️**please read the authors nexus page linked here to see more details on how to do this.**

- The latest must-have popular VR Quality of Life mods have all been added and fully updated to my knowledge.

- VR controller functionality, physics, visuals, performance are all enhanced & improved through various tools, mods & .ini settings.

**Diabolist VR aims to be a simple to setup & play, high-fantasy, Diablo themed mod list, based on dungeon crawling, monster hunting and loot hoarding,** I tried my best to create a nostalgic Diablo vibe while adventuring through the province of Skyrim.
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
The initial wabbajack setup file is 4.80 gb & the finished install folder size is 94 gb, for a total size of roughly 99 gb, it’s **Highly Recommended** that you install this on a NVMe M.2 SSD for optimal performance, although traditional SSD _should_ be fine.

**I focused heavily on optimizing DVR** during development and testing via performance tools, mod settings, ini settings and using low DynDOLOD 3 @ 512k res with xLodGen Occlusion, most players *should* have good performance with multiple HMDs on higher-end modern PCs. 

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

![VR Performance](https://user-images.githubusercontent.com/78007822/139745143-a3161f8d-8d2e-47ee-9644-e4aec59ac37a.png)
-
![VR Performance 2](https://user-images.githubusercontent.com/78007822/139745160-74e1f1c6-192e-4812-becd-06e4bccbaa50.png)
![VR Performance 3](https://user-images.githubusercontent.com/78007822/139745169-a60d5e27-e4b4-4b04-b948-1c88354fcccd.png)
-
![VR General Settings Smaller](https://user-images.githubusercontent.com/78007822/139744742-34f38930-4fa2-4326-a0e2-4a6f051a9bc0.png)
![VR General Settings 2 Smaller](https://user-images.githubusercontent.com/78007822/139744851-985379d3-d4f7-469b-8e1c-30ededa387ae.png)
-
## Wabbajack and DVR Install:

### A NEXUS PREMIUM ACCOUNT IS HIGHLY RECOMMENDED, OTHERWISE 600 MODS WILL HAVE TO BE DOWNLOADED MANUALLY.😵

- Download and install the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases). ⬅️️ **This 1st step is mandatory**

- Next, download [DiabolistVR](https://drive.google.com/file/d/1T8xmV9K4_5wMt4AC2rBia09qgBqL8JOu/view?usp=sharing).

- Make a folder on any SSD drive with space and **label it DVR.**

- **IMPORTANT REMINDER: -DO NOT- Install Anything Into Your C:/Program Files or C:/Program Files (x86) Folders, due to admin restrictions.**

- Open the Wabbajack file you downloaded to begin the install process, on the bottom right, select the DVR folder you created & the download section will automatically pick the mod folder for you inside of itself, or you can select a different folder to keep the downloaded zipped mods separate, it’s your choice.

- Click the big blue arrow, sit back & relax while it installs, if you’re curious you can watch the mod info that pops up to get an idea of what’s being installed, you are downloading over 600 mods so just be patient & let it finish, if it freezes, simply start the process over, to do this, open the Diabolist VR wabbajack file & click the arrow again without doing anything else & it will resume where it left off.

- After install is finished, close the Wabbajack window & proceed to the DVR folder, open the Game Files Folder, then drag & drop ALL of these files into your SkyrimVR root folder.
#

## SkyrimVR ini Tweaker:

There are a few .ini settings you should be aware of, because we don’t all use the same PC / HMD, so it’s best to adjust these based on your HMD resolution and CPU threads.

### **NOTE**: **Windows 11 users can ONLY USE Mo2 2.4.2 or later**

**Look inside the DVR folder & open ModOrganizer.exe (2.4.2) 
Once it’s open, click on this icon.** 👉 ![Skyrim ini Tweaker Small](https://user-images.githubusercontent.com/78007822/139736342-91ff8313-2d95-460a-b9ab-b8483e5fbc0b.png)
### This configuration window will pop up.⬇️
![SkyrimVR ini Tweaker Settings](https://user-images.githubusercontent.com/78007822/139736900-0332834d-5369-47de-add5-c8462af09bec.png)
-
Having personalized .ini tweaks will help overall visuals based on SuperSampling settings. 
**Example:** using 150% SS with SteamVR works out to 2016 x 2172 per eye on the Oculus Rift S, and this resolution is reflected with two .ini settings.

**iHudMenuTextureSize=2172    &    iProjectedMenuTextureSize=2172**

These 2 sets of numbers above will always equal the largest number of your headsets resolution & they _should_ be adjusted with this ini configuration tool to match your HMD, for best in-game menu texture size.
#

## CPU Threads:

iNumHWThreads & iNumThreads represents how many threads your CPU has, it’s set to 16 threads in the skyrimvr.ini so this will need to be changed to your own CPU threads if it is not 16, (or you can reset these two ini settings to Skyrim's default if you prefer) a good program to find out how many threads your processor is using, would be [CPUID](https://www.cpuid.com/softwares/cpu-z.html), if more help is needed with this, please post in the [DVR Discord](https://discord.gg/HuqU54gPcv)
### **You can close the SkyrimVR ini Tweaker now.**
#

# MCM RECOMMENDED SETTINGS:

### Load the game through SKSE & create a new character, once you spawn into the Realm of Lorkhan it is Highly Recommended to use these settings shown below for the best DVR experience, performance and overall compatibility... however, for different results, experiment with your own settings.
#
## Be Seated:
![Be Seated](https://user-images.githubusercontent.com/78007822/139783752-e59b4400-2e79-4a7b-bd4c-f95f4552de28.png)
-
## Claralux Lighting:
### NOTE: You MUST use Claralux at night, simply enable the TOGGLE LIGHT LEVEL TEST MODE option past 6pm to change options, then disable it to continue.⬇️
![Claralux Settings](https://user-images.githubusercontent.com/78007822/139784108-e8e86f7f-9cf8-41b5-a4a1-f4fb22316a8c.png)
![Claralux Settings 2](https://user-images.githubusercontent.com/78007822/139784116-74f26356-f533-4e88-9492-467941ea62bf.png)
-
## DynDOLOD:
### NOTE: Enable Large Ref Fix, DynDOLOD will auto-activate when you leave the Realm of Lorkhan.
![DynDOLOD Settings](https://user-images.githubusercontent.com/78007822/139785164-ab8ac947-0fcd-4ed3-920c-bc1aa5a8c266.png)
-
## Fine-Tuned Challange:
### NOTE: DVR uses Adept difficulty by default, this is CRITICAL to utilize the Fine-Tuned Challenge mod, because the dmg & spawn multiplier numbers will NOT take effect if ANY other vanilla difficulty setting is used. Experiment if you want, however, Fine-Tuned DEFAULT / ADEPT is a good start if you want a somewhat difficult challenge for dungeon crawling, as the [Synthesis patch also includes a base difficulty increase](https://github.com/Synthesis-Collective/SynNoMoreEasyEnemies), which these numbers directly affect.
![Fine-Tuned Challenge Settings](https://user-images.githubusercontent.com/78007822/139785982-11c9f46d-1439-4129-a33e-d783dc2c8b3b.png)
-
## Mihail Monster and SiC Difficulty Warning:
### NOTE: Mihails monsters hit harder, move faster and take more dmg than other monsters, adept is a good start, but adjust your Fine-Tuned difficulty settings based on your lvl and personal preferences. 
### Adept difficulty is also Highly Recommended for Skyrim Immersive Creatures, these settings can be accessed within the Immersive Creatures MCM options.
#
