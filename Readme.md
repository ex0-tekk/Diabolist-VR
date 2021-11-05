# Diabolist VR Install Guide

- **[1] [Introduction](#introduction)**

- **[2] [Recommended Specs for DVR](#recommended-specs-for-dvr)**

- **[3] [Mod List Features](#mod-list-features)**

- **[4] [Gameplay Prep](#gameplay-prep)**

    - [4a] [Windows Paging File Size](#windows-paging-file-size)

    - [4b] [SkyrimVR Install](#skyrimvr-install)
    
    - [4c] [Wabbajack and DVR Install](#wabbajack-and-dvr-install)
    
    - [4d] [SkyrimVR ini Tweaker](#skyrimvr-ini-tweaker)
    
    - [4e] [CPU Threads](#cpu-threads)
    
- **[5] [Recommended MCM Settings](#recommended-mcm-settings)**

    - [5a] [Be Seated](#be-seated)
    
    - [5b] [Claralux Lighting](#claralux-lighting)
    
    - [5c] [DynDOLOD](#dyndolod)
    
    - [5d] [Fine-Tuned Challange](#fine-tuned-challange)
    
    - [5e] [Mihail Monster and SiC Difficulty](#mihail-monster-and-sic-difficulty)
    
    - [5f] [Nethers Follower Framework](#nethers-follower-framework)
    
    - [5g] [Imaginator ENB Emulator](#imaginator-enb-emulator)
    
    - [5h] [Immersive Creatures](#immersive-creatures)
      
    - [5i] [Nemesis PCEA](#nemesis-pcea)

    - [5j] [R.A.S.S Weather](#rass-weather)
      
    - [5k] [Sounds of Skyrim - Civilization and Wilds](#sounds-of-skyrim---civilization-and-wilds)  
    
    - [5l] [Storm Lightning](#storm-lightning)

    - [5m] [Strike Obstruction Timed Block](#strike-obstruction-timed-block)

    - [5n] [Timing is Everything](#timing-is-everything)

    - [5o] [True Hunter](#true-hunter)
    
    - [5p] [True Spear Combat](#true-spear-combat)
    
    - [5q] [Unread Books Glow](#unread-books-glow)

    - [5r] [Wonders of Weather](#wonders-of-weather)

    - [5s] [Ye Old MCM Menu](#ye-old-mcm-menu)

- **[6] [The Sharper Eye](#the-sharper-eye)**

- **[7] [Nvidia Settings](#nvidia-settings)**

- **[8] [SkyrimVR and SkyrimPrefs ini](#skyrimvr-and-skyrimprefs-ini)**

- **[9] [DO NOT SORT DVR WITH LOOT](#do-not-sort-dvr-with-loot)**

- **[10] [INSTALL IS COMPLETE](#install-is-complete)**


#
## INTRODUCTION
![Diabolist VR Wolf Right Final 2 0 D-R-R](https://user-images.githubusercontent.com/78007822/139607370-54db657a-af31-498c-acfb-b3474550df9a.jpg)
-
**Diabolist VR pays homage to the hack-n-slash loot-hoarding ARPG of the late 90s, by adding 6 Diablo inspired mods, which includes a custom flame intro and music overhaul, authentic Diablo in-game font, the female Amazon character from Diablo II with spear throwing mechanics, the Horadric Crafting Cube from Diablo II, the Imperius Solarion Spear and Tyrael Armor from Diablo III, increased overall population with hundreds of unique monsters, a sprawling dungeon called Skyrim Underground, along with 65 additional Forgotten Dungeons.**
#

## RECOMMENDED SPECS FOR DVR

**The initial wabbajack setup file is 4.80 gb & the finished install folder size is 93 gb, for a total size of roughly 98 gb, it’s HIGHLY RECOMMENDED that you install this on a NVMe M.2 SSD for optimal performance, although traditional SSD *should* be fine.**

**I FOCUSED HEAVILY ON OPTIMIZING DVR during development and testing via performance tools, mod settings, ini settings and using low DynDOLOD 3 @ 512k res with xLodGen Occlusion, most players *should* have good performance with multiple HMDs on higher-end modern PCs.**

**Since I use a Rift S, the skyrimvr.ini / skyrimprefs.ini files will reflect that, so a few of these .ini settings will need to be adjusted to suit your specific HMD and PC. I will go over that and other recommended settings throughout this guide.**

### DVR is developed and tested with this HMD and PC setup:

 - **Oculus Rift S**
 - **Win 10 ver. 1909 Fully Updated**
 - **Ryzen 7 3800x AMD Processor**
 - **32 Gigs of G-Skill 14-34 Low Latency RAM**
 - **Kingston NVMe M.2 1tb SSD**
 - **Nvidia 3090 GPU**
#

## MOD LIST FEATURES

### DVR uses a 5 tier loot system inspired by Diablo 4.
 - **Common.**
 - **Magical.**
 - **Rare.**
 - **Legendary.**
 - **Mythic.**
#### NOTE: There is also 10 different enchant variations on all tiers, EXCEPT common.
#
 - **The loot system in DVR is VERY GENEROUS, just like the Diablo series is known for, so you will often be upgrading, tossing away or selling items, Nethers Follower Framework provides a dialogue option to make your followers run to town and sell ANY gear you give them regardless of the funds available on merchants, using this feature is HIGHLY RECOMMENDED as you continue gathering loot, because when you sell items manually, merchants will only have 10x the amount of septims as vanilla Skyrim, this is nice, but this won't be nearly enough for what you will find and *want* to sell, all that being said... making income in DVR will NOT be an issue regardless of you or your followers selling items, due to the treasure chests, bosses and dragons also providing plenty of septims.**

- **Random Loot Boxes are placed at several merchants across Skyrim, they are easy to find and they *can be* addictive.**

- **Transmuting lower quality items into a higher quality ones, or convert items of one type into another with the [Horadric Cube from Diablo II](https://www.nexusmods.com/skyrim/mods/22806/?tab=description) please read the authors nexus page linked here to see more details on how to do this.**

- **This mod list is a loot hoarders dream, and with that in mind, every new character you create starts with a 10,000lb carry weight ring.**

- **Enemies will be stronger to start but not too over-powering, Fine-Tuned difficulty settings flow in both directions for hard-mode, easy-mode and everything in between, with a few *optional* cheat mods available for casual steam-rolling fun. Look for *QoL Enhancements, Difficulty Options, Cheats & Level Lists* on the left side of your MO2 window, you will find these cheat mods placed throughout this cateagory, right click them and 'visit on nexus' for more info.**

- **All nonsense weapon and armor enchantments from the Summermyst Enchantments mod have been removed, this makes for some amazing enchantment combinations, you will likely need to crank the difficulty up as you continue to level, before long you will become quite powerful by coming across Legendary & Mythic items.**

- **The latest must-have popular VR Quality of Life mods have all been added and fully updated to my knowledge.**

- **VR controller functionality, physics, visuals, performance are all enhanced & improved through various tools, mods & .ini settings.**
#
 - **NSFW WARNING: (18+) This mod list uses CBBE Physics with no under-armor coverage for females, it also features many enchanted bikini armor drops, this lack of female underwear can be changed in CBBE BodySlide tool from the MO2 dropdown menu if you want panties and bras in your playthrough, however, it might look a bit odd looting worn bikini gear from a female NPC, only to see larger dark lace underwear and bra replacing it, but please post in the Discord DVR Support Chat room for help with this CBBE recompile.**
#
- **Staying true to the original Skyrim content, there are no major storyline addons or game-changing town/city/quest overhauls, however, there are still plenty of noticable changes, it's a large yet surprisingly straight-forward mod list, the Dragonborn storyline and Civil War are still the focal point and on par with vanilla.**

- **Diabolist VR aims to be a *simple to setup*, high-fantasy, Diablo themed mod list, based on dungeon crawling, monster hunting and loot hoarding. I tried my best to create a nostalgic Diablo vibe while adventuring through the province of Skyrim.**
#

## GAMEPLAY PREP
### Windows Paging File Size
 - **It is HIGHLY RECOMMENDED to set your pagefile size to 20GB. (20,000mb)**
 - **This is the modded SkyrimVR standard if you have 16GB RAM.**
 - **Use this number for both the initial size and max size on 1 free SSD with enough space.**
 - **There is no need to apply this pagefile size setting to multiple hard drives.**
**Keeping your Windows drive (typically the C: Drive) set to SYSTEM MANAGED SIZE Is HIGHLY RECOMMENDED while using the pagefile setup with 1 free hard drive in this fashion & how to configure the Windows Paging File Size is explained [HERE.](https://www.howto-connect.com/tweak-paging-file-for-better-windows-10-performance/)**

![Virtual Memory](https://user-images.githubusercontent.com/78007822/139851096-1b8f5275-4070-48ed-b974-58e80fb25349.png)
-
### SkyrimVR Install
 - **It is CRITICAL to have a 100% fresh install of SkyrimVR available & ready to play with no other files added, It is also CRITICAL to have your SkyrimVR game installed in a folder outside of  C:/Program Files  and  C:/Program Files (x86)  ignore these 2 folders for the entire process of this install guide, due to possible admin rights restrictions.**
 
 - **Steam does not easily allow for new install folders, simply follow [This Easy Guide](https://drive.google.com/drive/folders/1lOBFqblzA23AbXFz-usTejOKR5UFsPjA?usp=sharing) to change that.**
 
 - **First, start the default Steam version of SkyrimVR to have the game create the appropriate .ini file in the documents folder on your C drive, and also to adjust the game's vanilla settings.**
 
 - **I have provided screenshots of the recommended SkyrimVR settings, along with highly recommended mod settings for DVR, however, all mod options in MCM are relatively safe to experiment with.**
#### Refer to these screenshots below once you first load the game and after Diabolist VR is installed ... as I will Not be explaining these settings in further detail aside from the screenshot ‘NOTES’ i have added, most of this is self-explanatory and also based on your preference and PC performance.

![VR Performance](https://user-images.githubusercontent.com/78007822/139745143-a3161f8d-8d2e-47ee-9644-e4aec59ac37a.png)
![VR Performance 2](https://user-images.githubusercontent.com/78007822/139745160-74e1f1c6-192e-4812-becd-06e4bccbaa50.png)
![VR Performance 3](https://user-images.githubusercontent.com/78007822/139745169-a60d5e27-e4b4-4b04-b948-1c88354fcccd.png)
![VR General Settings Smaller](https://user-images.githubusercontent.com/78007822/139744742-34f38930-4fa2-4326-a0e2-4a6f051a9bc0.png)
![VR General Settings 2 Smaller](https://user-images.githubusercontent.com/78007822/139744851-985379d3-d4f7-469b-8e1c-30ededa387ae.png)
-
## Wabbajack and DVR Install

### A NEXUS PREMIUM ACCOUNT IS HIGHLY RECOMMENDED, OTHERWISE ROUGHLY 600 MODS WILL HAVE TO BE DOWNLOADED MANUALLY.😵

- **Download and install the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases).** ⬅️️**This First Step Is Mandatory**

- **Next, download [DiabolistVR](https://drive.google.com/drive/folders/100GIvYYJOzKz9Tdvt_K7wzdvKiEDj8Kx?usp=sharing).**

- **Make a folder on any SSD drive with space and label it DVR.**

- **IMPORTANT REMINDER: -DO NOT- install ANYthing into your C:/Program Files or C:/Program Files (x86) folders, due to admin restrictions.**

- **Open the Wabbajack file you downloaded to begin the install process, on the bottom right, select the DVR folder you created & the download section will automatically pick the mod folder for you inside of itself, or you can select a different folder to keep the downloaded zipped mods separate, it’s your choice.**

- **Now click the big blue arrow, sit back & relax while it installs, if you’re curious, you can watch the mod info that pops up to get an idea of what’s being installed, you can also download this file ➡️ [Diabolist VR 2.0 Definitive Re-Release.wabbajack.manifest.json](https://drive.google.com/drive/folders/18DD_fVfsnnzwJPg5DvIKzJaWczmEnfUG?usp=sharing), then simply drag and drop it into the [Wabbajack Manifest Website](https://www.wabbajack.org/#/modlists/manifest) to see all the mods being installed, you are downloading roughly 600 mods so just be patient & let it finish, if it freezes, simply start the process over, to do this, open the Diabolist VR wabbajack file & click the arrow again without doing anything else & it will resume where it left off.**

- **After install is finished, close the Wabbajack window & proceed to the DVR folder, open the Game Files Folder, then drag & drop ALL of these files into your SkyrimVR root folder.**
#

## SkyrimVR ini Tweaker

**There are a few .ini settings you _should_ be aware of, because we don’t all use the same PC / HMD, so it’s best to adjust these based on your HMD resolution and CPU threads.**

### **NOTE**: **Windows 11 users can ONLY USE MO2 2.4.2 or later**

**Look inside the DVR folder & open ModOrganizer.exe (2.4.2)
Once it’s open, click on this icon. ➡️ ![Skyrim ini Tweaker Small](https://user-images.githubusercontent.com/78007822/139736342-91ff8313-2d95-460a-b9ab-b8483e5fbc0b.png)**
### This configuration window will pop up.⬇️
![SkyrimVR ini Tweaker Settings](https://user-images.githubusercontent.com/78007822/139736900-0332834d-5369-47de-add5-c8462af09bec.png)

**Having personalized .ini tweaks will help overall visuals based on SuperSampling settings.**

**Example: using 150% SS with SteamVR works out to 2016 x 2172 per eye on the Oculus Rift S, and this resolution is reflected with two .ini settings.**

**iHudMenuTextureSize = 2172 ... & ... iProjectedMenuTextureSize = 2172**

**These 2 sets of numbers above will always equal the largest number of your headsets resolution & they *should* be adjusted with this ini configuration tool to match your HMD, for best in-game menu texture size.**
#

## CPU Threads

**iNumHWThreads & iNumThreads represents how many threads your CPU has, it’s set to 16 threads in the skyrimvr.ini so this will need to be changed to your own CPU threads if it is not 16, (or you can reset these two ini settings to Skyrim's default if you prefer) a good program to find out how many threads your processor is using, would be [CPUID](https://www.cpuid.com/softwares/cpu-z.html), ⬅️️ click to install, if more help is needed with this, please post in the [DVR Discord](https://discord.gg/HuqU54gPcv)**
### **You can close the SkyrimVR ini Tweaker now.**
#

# RECOMMENDED MCM SETTINGS

#### Load the game through SKSE & create a new character, once you spawn into the Realm of Lorkhan it is HIGHLY RECOMMENDED to use these settings shown below for the best DVR experience, performance and overall compatibility... however, for different results, experiment with your own settings.
#

## Be Seated
![Be Seated](https://user-images.githubusercontent.com/78007822/139783752-e59b4400-2e79-4a7b-bd4c-f95f4552de28.png)

## Claralux Lighting
#### NOTE: You MUST use Claralux settings at night, simply enable the TOGGLE LIGHT LEVEL TEST MODE option past 6pm to change options, then DISABLE IT TO CONTINUE.
#### If you Fail to Disable this AFTER adjusting these options ⬇️ then your character will be frozen and unable to move when you return to your game.
![Claralux Settings](https://user-images.githubusercontent.com/78007822/139784108-e8e86f7f-9cf8-41b5-a4a1-f4fb22316a8c.png)
![Claralux Settings 2](https://user-images.githubusercontent.com/78007822/139784116-74f26356-f533-4e88-9492-467941ea62bf.png)
-
## DynDOLOD
#### NOTE: Enable Large Ref Fix, DynDOLOD will auto-activate when you leave the Realm of Lorkhan.
![DynDOLOD Settings](https://user-images.githubusercontent.com/78007822/139785164-ab8ac947-0fcd-4ed3-920c-bc1aa5a8c266.png)
-
## Fine-Tuned Challange
#### NOTE: DVR uses Adept difficulty by default, this is CRITICAL to utilize the Fine-Tuned Challenge mod, because the dmg & spawn multiplier numbers will NOT take effect if ANY other vanilla difficulty setting is used. Experiment if you want, however, Fine-Tuned DEFAULT / ADEPT is a good start if you want a *somewhat* difficult challenge for dungeon crawling, as the [Synthesis patch also includes a base difficulty increase](https://github.com/Synthesis-Collective/SynNoMoreEasyEnemies), which these numbers directly affect.

![Fine-Tuned Challenge Settings](https://user-images.githubusercontent.com/78007822/139785982-11c9f46d-1439-4129-a33e-d783dc2c8b3b.png)
-
## Mihail Monster and SiC Difficulty
#### NOTE: Mihails creations hit harder, move faster and take more damage than other monsters, they are based PURELY on Skyrim vanilla stats and mechanics, but they are created somewhat Over Powered, adept is a good start and then simply adjust your Fine-Tuned difficulty settings based on your lvl and personal preferences. 
#### Adept difficulty is also HIGHLY RECOMMENDED for Skyrim Immersive Creatures (SiC), these settings can be accessed within the Immersive Creatures MCM options.
#
## Nethers Follower Framework
#### NOTE: Difficulty Settings for Followers GIVING DAMAGE can be adjusted in the Nethers Follower Framework mod settings inside MCM. Please read this very helpful [PDF Guide](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=153383&game_id=1704) from the author of this mod, if needed, as NFF has a slew of options to get acquainted with. 
#### Also included is [Ashien's Cursed Rings](https://www.nexusmods.com/skyrim/mods/64530) <--click & read the mod page for the rings location, this mod will help your followers effectively TAKE DAMAGE at higher levels.
![NFF](https://user-images.githubusercontent.com/78007822/139795556-8f090a9c-5fd6-473e-98be-26f89e807455.png)
-
## Imaginator ENB Emulator
![Imaginator Settings](https://user-images.githubusercontent.com/78007822/139812380-f525b3de-92a9-4744-9a97-5c750cd55ee5.png)
-
#### NOTE: It is CRITICAL to have Sunlight and Sky at -2, ⬇️ these settings remove excess surface and snow glare.
![Imaginator Settings 2](https://user-images.githubusercontent.com/78007822/139812436-f2dbf65d-a753-4d06-9a47-24266703d9c4.png)
![Imaginator Settings 3](https://user-images.githubusercontent.com/78007822/139812485-4348a4ec-36c8-4aef-b240-b98293cadbf9.png)
#### NOTE: These 4 tintor colors set to 1 will help remove the excess blue/green tint within Skyrim. ⬆️
#
## Immersive Creatures
#### NOTE: If you want to minimize Non-Adult animal spawns (Wolf Pups 🐺) drop the additional animal spawn chance to 1%, in the Additional Spawns options.
![Immersive Creatures No Wolf Pups](https://user-images.githubusercontent.com/78007822/139816694-d626fe76-e6fc-4afe-a077-e1e9121f45bf.png)
-
## Nemesis PCEA
#### NOTE: These animations are HIGHLY RECOMMENDED for the Player and NPC.
![Nemesis PCEA Settings](https://user-images.githubusercontent.com/78007822/139820342-a119bb60-493e-4131-a2ed-7da9499fc004.png)
-
## R.A.S.S Weather
![R A S S Settings](https://user-images.githubusercontent.com/78007822/139821113-f1368d48-a4d5-41e7-a46f-d0e900d8eaf3.png)
#### NOTE: Camera Visual Effects DISABLED is HIGHLY RECOMMENDED for better VR visuals ⬆️ and overall performance.
#
## Sounds of Skyrim - Civilization and Wilds
#### NOTE: These are the recommended DISABLED sounds for an overall better audio experience.
![SoS Civ Settings](https://user-images.githubusercontent.com/78007822/139822593-bc3a4b2a-7dd6-42ea-88ec-209f88bbfc12.png)
![SoS Wilds Settings](https://user-images.githubusercontent.com/78007822/139822728-0301c97a-eb06-42ce-b04a-f9ebf54131ad.png)
-
## Storm Lightning
#### NOTE: Use Realistic or Ultra Realistic for best VR results.
![Storm Lightning Settings](https://user-images.githubusercontent.com/78007822/139826224-4534dba6-0899-43b7-984a-a42c791d9d43.png)
-
## Strike Obstruction Timed Block
#### NOTE: It is HIGHLY RECOMMENDED to DISABLE player parry mechanics, these animations are not triggered in VR.
![Strike Obstruction Timed Block Settings](https://user-images.githubusercontent.com/78007822/139826990-c155d19e-b1ca-42a6-92b1-4f5c3e749f7d.png)
-
## Timing is Everything
#### NOTE: It is HIGHLY RECOMMENDED to click ‘LOAD PRESET’ and ENABLE the Lexy FISSES settings.
![Timing is Everything Settings](https://user-images.githubusercontent.com/78007822/139827581-999b3eb6-4e8e-4f70-be62-7b269bd88fe3.png)
-
## True Hunter
#### NOTE: This mod reduces or increases all animal clutter, Higher % = potential performance impact.
![True Hunter Settings](https://user-images.githubusercontent.com/78007822/139829124-a1184205-3602-4d99-8026-5531a5eba26c.png)
-
## True Spear Combat
#### NOTE: This mod is ONLY used for NPC spear throwing, it is HIGHLY RECOMMENED to DISABLE ALL player options, including the random scripting, as seen in this screenshot.
![True Spear Combat](https://user-images.githubusercontent.com/78007822/139837809-576f44f6-5945-423a-8b81-50eeefcf4946.png)
-
## Unread Books Glow
#### NOTE: In general, plain books glow is not suggested, but it's great for book collecting.
![Unread Books Glow](https://user-images.githubusercontent.com/78007822/139838085-27dec7d9-bed1-49e9-9e42-9665622dcc9c.png)
-
## Wonders of Weather
#### NOTE: These settings increase overall rain performance & fantasy visuals.
![WoW Settings](https://user-images.githubusercontent.com/78007822/139839212-26e1ba6f-9108-4146-b1fb-21bea4cb44ef.png)
-
## Ye Old MCM Menu
#### NOTE: Use this mod to backup all mod menu configs you have set... but first, use the BACKUP MOD SELECTION option and choose the mods you want saved, this is very helpful for loading all of your mod settings for multiple playthroughs.
![Ye'Old MCM Menu](https://user-images.githubusercontent.com/78007822/139839346-e83e7665-90b1-462a-bd14-24252eb0c2f5.png)
-
# The Sharper Eye
#### NOTE: With SteamVR, I recommend using [The Sharper Eye](https://www.nexusmods.com/skyrimspecialedition/mods/46999/) mod with or without TAA, this mod needs to be downloaded manually and placed inside your root SkyrimVR folder, please click the link provided above and read the mod page for more info.
![The Sharper Eye](https://user-images.githubusercontent.com/78007822/139843882-792e6293-f0b9-4c05-8564-62e06bfce179.png)
-
# NVIDIA Settings
#### NOTE: The SkyrimVR specific nVidia settings I have provided are for better visual clarity for the Rift S, but they likely work fine with a range of other HMDs, do some research online and feel free to experiment with your own settings if these are not sufficient for your GPU.
![SkyrimVR nVidia settings](https://user-images.githubusercontent.com/78007822/139841627-35baa896-32a9-48ba-a864-b1973264ac6f.png)
-
# SkyrimVR and SkyrimPrefs ini
#### NOTE: If your game feels ‘Off’ or ‘Not Quite Right’ after installing and playing, or if you just want to reset your current Diabolist VR .ini [skyrimprefs.ini & skyrimvr.ini](https://drive.google.com/drive/folders/1HZ2Tgr3YjiP1zxBMwpN3OusSq4kTHT5n?usp=sharing) ⬅️️ click this link to get both current files and then overwrite them inside your ‘DVR\profiles\Diabolist VR’ folder, also make sure to replace these files inside your ‘C:\Documents\My Games\Skyrim VR’ folder.

# DO NOT SORT DVR WITH LOOT
#### NOTE: DVR has been manually sorted from top to bottom & using loot WILL destroy the correct plugin order, if you add more mods, you will NEED to know where to place those new plugins, However, If you mess up the plugins, you can simply click the circular icon on the Mod Organizer window to restore the original plugin order based on the most recent date.
![No LOOT Sorting](https://user-images.githubusercontent.com/78007822/139843104-bfc25312-5f4c-4fed-9919-fb064dbef888.png)
-
# INSTALL IS COMPLETE 
 - ### You’re Ready to Play! 
 - ### Please post on [DVR Discord](https://discord.com/invite/HuqU54gPcv) if you need modlist support. 
# Thanks for downloading Diabolist VR! 
### ...but most importantly...
# Have fun monster hunting & loot hoarding!
![Diabolist VR Wolf Right Final 2 0 D-R-R-Small](https://user-images.githubusercontent.com/78007822/139849187-bad8a216-0a47-47d6-a9ab-3611595678cd.jpg)
-
#### - Latest DVR Guide Update, 11/04/2021
