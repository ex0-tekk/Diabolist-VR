# Diabolist VR Install Guide

- **[1] [Introduction](#introduction)**

- **[2] [Recommended Specs for DVR](#recommended-specs-for-dvr)**

- **[3] [Mod List Features](#mod-list-features)**

- **[4] [Gameplay Prep](#gameplay-prep)**

    - [4a] [Windows Firewall Settings](#windows-firewall-settings)

    - [4b] [Windows Paging File Size](#windows-paging-file-size)

    - [4c] [SkyrimVR Install](#skyrimvr-install)
    
    - [4d] [Wabbajack and DVR Install](#wabbajack-and-dvr-install)
    
    - [4e] [SkyrimVR ini Tweaker](#skyrimvr-ini-tweaker)
    
    - [4f] [CPU Threads](#cpu-threads)
    
- **[5] [Recommended and Critical MCM Settings](#recommended-and-critical-mcm-settings)**

    - [5a] [Be Seated](#be-seated)
    
    - [5b] [Claralux Lighting](#claralux-lighting)
    
    - [5c] [DynDOLOD](#dyndolod)
    
    - [5d] [Fine-Tuned Challange](#fine-tuned-challange)
    
    - [5e] [RLE - SiC - Mihail Monsters](#rle---sic---mihail-monsters)

    - [5f] [Nethers Follower Framework](#nethers-follower-framework)
    
    - [5g] [Imaginator ENB Emulator](#imaginator-enb-emulator)
    
    - [5h] [Immersive Creatures](#immersive-creatures)
      
    - [5i] [Nemesis PCEA](#nemesis-pcea)

    - [5j] [R.A.S.S Weather](#rass-weather)
      
    - [5k] [Sounds of Skyrim - Civilization and Wilds](#sounds-of-skyrim---civilization-and-wilds)  
    
    - [5l] [Storm Lightning](#storm-lightning)

    - [5m] [Strike Obstruction Timed Block](#strike-obstruction-timed-block)

    - [5n] [Timing is Everything](#timing-is-everything)

    - [50] [Unread Books Glow](#unread-books-glow)

    - [5p] [VRIK](#vrik)
     
    - [5q] [Wonders of Weather](#wonders-of-weather)

- **[6] [The Sharper Eye](#the-sharper-eye)**

- **[7] [TAA On or Off](#taa-on-or-off)**

- **[8] [Nvidia Settings](#nvidia-settings)**

- **[9] [SkyrimVR and SkyrimPrefs ini](#skyrimvr-and-skyrimprefs-ini)**

- **[10] [DO NOT SORT DVR WITH LOOT](#do-not-sort-dvr-with-loot)**

- **[11] [INSTALL IS COMPLETE](#install-is-complete)**


#
[1]
## INTRODUCTION
![DVR Logo Final New 800x](https://user-images.githubusercontent.com/78007822/145327653-ebdda405-f8bd-44bd-ac60-cbffd9637bda.png)

### Diabolist VR is a high fantasy theme-based mod list that pays homage to the hack-n-slash loot-hoarding ARPG of the late 90s by adding 7 Diablo inspired mods and so much more, this includes:
 
 - **A custom flame Diablo intro.**
 - **Solarion Spear intro replacer.**
 - **Authentic in-game Diablo font.**
 - **Intro and in-game music overhaul.**
 - **A town portal spell called Voidgate.**
 - **A classicly generous 3 tier loot system.**
 - **The Horadric Crafting Cube from Diablo II.**
 - **The female Amazon from Diablo II visually improved over the LE version.**
 - **The Imperius Solarion Spear and Tyrael Armor from Diablo III, these can only be crafted.**
 - **Hundreds of unique monsters with increased population, with more aggro range and combat abilities.**
 - **A sprawling multi-dungeon system called Skyrim Underground, along with 65 additional Forgotten Dungeons.**
#
[2]
## RECOMMENDED SPECS FOR DVR

**This modlist was developed ON and FOR a modern higher-end PC.**

**It has a total size of roughly 100 GB once it's fully installed, it’s HIGHLY RECOMMENDED that you install this on a NVMe M.2 SSD for optimal performance, although traditional SSD *should* be fine.**

**I FOCUSED HEAVILY ON OPTIMIZING DVR during development and testing via performance tools, mod settings, ini settings and using low DynDOLOD 3 @ 512k res with xLodGen Occlusion, most players *should* have good performance with multiple HMDs on higher-end modern PCs.**

**Since I use a Rift S, the skyrimvr.ini files will reflect that, so a few of these .ini settings will need to be adjusted to suit your specific HMD and PC. I will go over that and other recommended settings throughout this guide.**

### DVR is developed and tested with this HMD and PC setup:

 - **Oculus Rift S**
 - **Win 10 ver.20H2 Fully Updated**
 - **Ryzen 7 3800x AMD Processor**
 - **32 Gigs of G-Skill 14-34 Low Latency RAM**
 - **Kingston NVMe M.2 1tb SSD**
 - **Nvidia 3090 GPU**
#
[3]
## MOD LIST FEATURES
### To save space on the in-game loot card, DVR now uses a 3 tier STAR Halgaris RPG loot system. 
### % = Drop Rate.
#
 - **No Star = No enchant (Vanilla) = 15%** - NOTE: _Some_ hard-coded vanilla gear and quest items still have 1 or more enchants with No Star.
 - **1 Star = 1 Enchant = 67%**
 - **2 Stars = 2 Enchants = 15%**
 - **3 Stars = 3 enchants = 3%**
#### NOTE: There is 10 randomly enchanted item variations on all tiers, EXCEPT No Star, No Enchant (Vanilla).
#
 - **The loot system in DVR is VERY GENEROUS, just like the Diablo series is known for, so you will often be upgrading, tossing away or selling items, Nethers Follower Framework provides a dialogue option to make your followers run to town and sell ANY gear you give them regardless of where you are or the funds available on merchants, using this feature is HIGHLY RECOMMENDED as you continue gathering loot if you don't always want to travel and sell. Making income in DVR should not be an issue regardless of you and your followers selling items, due to the boss chests and dragons providing plenty of gold, additionally, in an attempt to balance bartering and trade, I have added an increase in overall cost for buying items and subsequently less income for selling all items, along with other barter tweaks such as, increased merchant gold, increased ferry and horse carriage costs, sleeping at the inn costs more, etc.**

- **Loot Boxes are placed at merchants across 7 different cities, they are easy to find and they *can be* addictive, but loot keys are not cheap.**

- **This mod list is a loot hoarders dream, and with that in mind, every new character you create starts with a 10,000lb carry weight ring.**

- **Transmuting lower quality items into a higher quality ones, or convert items of one type into another with the [Horadric Cube from Diablo II](https://www.nexusmods.com/skyrim/mods/22806/?tab=description) please read the authors nexus page linked here to see more details on how to do this.**

- **Voidgate is a spell every player starts with in DVR, you simply access it from your magic menu and cast a dual portal to step into, for example: you're dungeon crawling and you want to goto town to sell or buy... ok, so you cast the spell and a blue swirling portal opens, now you open your map and goto your desired location (DVR lets you teleport out from ANY dungeon via your map), once you're finished, you simply cast the spell again and a 2nd portal opens, walk into the swirling portal, this returns you back to the spot where you were previously adventuring.**

- **Fine-Tuned Challenge mod difficulty settings replace the traditional Skyrim difficulty settings, they flow in both directions for hard-mode, easy-mode, and everything in between... with a few *optional* cheat mods available for casual steam-rolling fun. Look for *QoL Enhancements, Difficulty Options, Cheats & Level Lists* on the left side of your MO2 window, you will find these cheat mods placed throughout this category, right click them and 'visit on nexus' for more info.**

- **All nonsense weapon and armor enchantments from the Summermyst Enchantments mod have been removed, this makes for some amazing enchantment combinations, you will likely need to crank the difficulty up as you continue to level, before long you will become quite powerful by coming across 2 star & 3 star items, and by also enchanting your own gear.**

- **The latest must-have popular VR Quality of Life mods have all been added and fully updated to my knowledge, this now includes the newly released [Physical VR Dodge](https://www.nexusmods.com/skyrimspecialedition/mods/58605/), ⬅️️ click to see mod details.**

- **VR controller functionality, physics, visuals, performance and LOD are all enhanced & improved through various tools, mods & .ini settings.**
#
 - **MILD NSFW WARNING: (18+) This mod list uses CBBE Physics with no under-armor coverage for females, it also features bikini armor for you to craft, this lack of female underwear can be changed in CBBE BodySlide tool from the MO2 dropdown menu if you want panties and bras in your playthrough, please post in the Discord DVR Support Chat room for help with this CBBE recompile if needed.**
#
- **DVR comes with a new game-changing mod called [The Paarthurnax Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/51711), aside from this there are no other storyline content overhauls, while being a large yet surprisingly straight-forward mod list, DVR still hosts plenty of noticable changes, but the Dragonborn storyline and Civil War are still the focal point and on par with vanilla.**

- **Diabolist VR aims to be performance friendly as a *simple to setup*, high-fantasy, Diablo themed mod list, based on dungeon crawling, monster hunting and loot hoarding. I tried my best to create a nostalgic Diablo vibe while adventuring through the province of Skyrim.**
#
[4]
## GAMEPLAY PREP
[4a]
### Windows Firewall Settings
 - **It is HIGHLY RECOMMENDED to BLOCK SkyrimVR.exe (Inbound & Outbound), within your windows firewall settings, to prevent random CTD produced by Bethesda server pings.**
 - **Open your windows search function and type in Firewall, then click on 'Windows Defender Firewall with Advanced Settings.**
 
![Firewall Settings 1](https://user-images.githubusercontent.com/78007822/140569744-80e05750-decc-48e4-976e-a84ac707259a.png)
 - ### **When the Windows firewall options pop up, follow these steps below:**
 - **1. Click Inbound Rules**
 - **2. Click New Rule**
 - **3. Click Program, then Next.**

![Firewall Settings 2](https://user-images.githubusercontent.com/78007822/140570706-82949ebb-a4eb-47a4-ae45-13f6f6031696.png)
 - ### **Now direct this window to your SkyrimVR root folder and select SkyrimVR.exe**
![Firewall Settings 3](https://user-images.githubusercontent.com/78007822/140577020-ba21dac5-6462-4fdc-b5bf-25893ec53587.png)
 - ### **Make SURE you select BLOCK, another window will pop up with Domain, Private and Public, make sure they are all selected.**
![Firewall Settings 4](https://user-images.githubusercontent.com/78007822/140572008-768a8955-f3a7-4cdc-8a3c-aa9dec013d86.png)

![Firewall Settings 5](https://user-images.githubusercontent.com/78007822/140572430-5546eb0d-5fea-4ed7-8b4c-a9242217ebb2.png)
 - ### **Just name this to whatever you want, or copy the screenshot provided, then click finish.**
![Firewall Settings 6](https://user-images.githubusercontent.com/78007822/140572798-048e221d-0f9e-43dd-a3af-9984fca91ac8.png)
## **NOTE: MAKE SURE YOU REPEAT THE EXACT SAME STEPS FOR OUTBOUND BLOCK.**
[4b]
### Windows Paging File Size
 - **It is HIGHLY RECOMMENDED to set your pagefile size to 20GB (20,000mb).**
 - **20GB is the modded SkyrimVR standard if you have 16GB RAM, I personally use 40GB for more overhead, but this is just my preference.**
 - **Use this number for both the initial size and max size on 1 free SSD with enough space.**
 - **There is no need to apply this pagefile size setting to multiple hard drives.**
**Keeping your Windows drive (typically the C: Drive) set to SYSTEM MANAGED SIZE Is HIGHLY RECOMMENDED while using the pagefile setup with 1 free hard drive in this fashion & how to configure the Windows Paging File Size is explained [HERE.](https://www.howto-connect.com/tweak-paging-file-for-better-windows-10-performance/)**

![Virtual Memory](https://user-images.githubusercontent.com/78007822/139851096-1b8f5275-4070-48ed-b974-58e80fb25349.png)
-
[4c]
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
[4d]
## Wabbajack and DVR Install

### A NEXUS PREMIUM ACCOUNT IS HIGHLY RECOMMENDED, OTHERWISE 500+ MODS WILL HAVE TO BE DOWNLOADED MANUALLY.😵

- **Download and install the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases).**

- **Next, download [DiabolistVR](https://drive.google.com/drive/folders/100GIvYYJOzKz9Tdvt_K7wzdvKiEDj8Kx?usp=sharing).**

- **Next, make a folder on the SSD drive you'll be using and label it DVR.**

- **IMPORTANT REMINDER: -DO NOT- install ANYthing into your C:/Program Files or C:/Program Files (x86) folders, due to admin restrictions.**

- **Download Diabolist VR from the Wabbajack VR section to begin the install process, once that initial download is done a new Wabbajack window will pop up, on the bottom right select the Install Location ( 3 Dots ... ) select the DVR folder you created, the download section will automatically pick the mod folder for you inside of itself, or you can select a different folder to keep the downloaded zipped mods separate, it’s your choice.**

- **Now click the big blue arrow, sit back & relax while it installs, if you’re curious, you can watch the mod info that pops up to get an idea of what’s being installed, you can also download this file ➡️ [Diabolist VR 2.8.4.wabbajack.manifest.json](https://drive.google.com/drive/folders/18DD_fVfsnnzwJPg5DvIKzJaWczmEnfUG?usp=sharing), then simply drag and drop it into the [Wabbajack Manifest Website](https://www.wabbajack.org/#/modlists/manifest) to see all the mods being installed, you are downloading 600 mods so just be patient & let it finish, if it freezes, simply start the process over, to do this, open the Diabolist VR wabbajack file & click the arrow again without doing anything else & it will resume where it left off.**

- **After install is finished, close the Wabbajack window & proceed to the DVR folder, open the Game Files Folder, then drag & drop ALL of these files into your SkyrimVR root folder, there *should* be only 1 overwrite notification for the Skyrim.ini file, this overwrite is correct, do it.**
#
[4e]
## SkyrimVR ini Tweaker

**There are a few .ini settings you *should* be aware of, because we don’t all use the same PC / HMD, so it’s best to adjust these based on your HMD resolution and CPU threads.**

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
[4f]
## CPU Threads

**iNumHWThreads & iNumThreads represents how many threads your CPU has, it’s set to 16 threads in the skyrimvr.ini so this will need to be changed to your own CPU threads if it is not 16, (or you can reset these two ini settings to Skyrim's default if you prefer) a good program to find out how many threads your processor is using, would be [CPUID](https://www.cpuid.com/softwares/cpu-z.html), ⬅️️ click to install, if more help is needed with this, please post in the [DVR Discord](https://discord.gg/HuqU54gPcv)**
### **You can close the SkyrimVR ini Tweaker now.**
#
[5]
# RECOMMENDED AND CRITICAL MCM SETTINGS

#### Load the game through SKSE & create a new character, once you spawn in, it is HIGHLY RECOMMENDED to use these MCM settings shown below for the best DVR experience, performance and overall compatibility... however, for different results, experiment with your own settings.
#
[5a]
## Be Seated
![Be Seated](https://user-images.githubusercontent.com/78007822/139783752-e59b4400-2e79-4a7b-bd4c-f95f4552de28.png)
-
[5b]
## Claralux Lighting
#### NOTE: You MUST use Claralux settings at night, simply enable the TOGGLE LIGHT LEVEL TEST MODE option past 6pm to change options, then DISABLE IT TO CONTINUE.
#### If you Fail to Disable this AFTER adjusting these options ⬇️ then your character will be frozen and unable to move when you return to your game.
![Claralux Settings](https://user-images.githubusercontent.com/78007822/139784108-e8e86f7f-9cf8-41b5-a4a1-f4fb22316a8c.png)
![Claralux Settings 2](https://user-images.githubusercontent.com/78007822/139784116-74f26356-f533-4e88-9492-467941ea62bf.png)
-
[5c]
## DynDOLOD
#### NOTE: Enable Large Ref Fix, DynDOLOD will auto-activate when you leave the Realm of Lorkhan.
![DynDOLOD Settings](https://user-images.githubusercontent.com/78007822/139785164-ab8ac947-0fcd-4ed3-920c-bc1aa5a8c266.png)
-
[5d]
## Fine-Tuned Challange
#### NOTE: DVR uses Adept difficulty by default, this is CRITICAL to utilize the Fine-Tuned Challenge mod, because the dmg & spawn multiplier numbers will not function as intended if any other vanilla difficulty setting is used, this mod simply REPLACES the vanilla difficulty settings with detailed % numbers. Experiment if you want, however, Fine-Tuned DEFAULT % with ADEPT set is a good start if you want a starter difficultly challenge for dungeon crawling, but for the best experience you would set the multipliers progressively higher, for example: 100%, 150%, 200%, 300%, then adjust the Dmg taken & inflicted sliders based on your preferences, personally, I use 200+ with those 4 sliders for a bigger challange along with -50% Dmg Inflicted and +50% Dmg Taken, because of all the powerful weapons and armor that drop right away.
![Fine-Tuned Challenge Settings](https://user-images.githubusercontent.com/78007822/139785982-11c9f46d-1439-4129-a33e-d783dc2c8b3b.png)
-
[5e]
## RLE - SiC - Mihail Monsters
#### NOTE: DVR uses several monster mods at its core: Rogue Like Encounters, (RLE) Skyrim Immersive Creatures (SiC), Scary Night Spawner, Creepy Zombies, and _some_ individual Mihail Monsters, additionally, Skyrim Underground has it's own set of monsters.
#### RLE provides 3 Combat modules to pick from and DVR uses the Clean Combat Module, which only alters the enemy combat styles, this module adds NO further difficulty, and it lets Fine-Tuned Challenge handle all base difficulty aspects.
### RLE Combat Features, Quoted From Nexus:
 - **RAID ADDS: Dragons (and many other creatures) now have mmo-style adds which spawn mid-fight, regular dragons get two or more dragonlings at 50% health, Alduin gets dragonlings at 50% and 2 or more Blackguards of Akatosh (black daedroths wielding daedric greatswords) at 25%.**

 - **DIRE ARROWS: Distributed throughout the world, morrowind-style, are creature types that use enchanted arrows... these may be crafted or collected to be used at will, their damage ratings are much higher than normal arrows, and many of them explode upon impact.**

 - **MULTI-FORM ENEMIES: There is a growing list of special enemies in the world that have more than one form. By this, I mean when their health reaches zero, they change into a weaker or stronger version of themself. Some examples are Troll Pillages, Earth-bound Sinners, Grand Flame Atronachs, and certain Wisp Mothers.**

 - **ROGUES: Distributed throughout the world are versions of intelligent enemies that can visibly stealth and perform poisonous backstab attacks.**

 - **CRITICAL HITS: Most non-humans now have a 1 in 10 chance to do critical damage with melee or ranged attacks.**

 - **BLOCK-RUNNING, QUICK-DRAW, & FASTER MOVEMENT WHILE AIMING: Most humanoid enemies will frequently be pretty decent at positioning themselves in a fight and have these custom perks to mirror that.**

 - **CLEAVES: Most creatures in the world, but very rarely humanoids, attack in arcs, hitting everything in those arcs. These were added to punish players who always group their party close together when fighting something large and tough. If a giant can hit everyone, for instance, with a single swing, it will, the same goes for most other creatures.**

 - **BLOOD LUST: All living creatures drop blood, hearts, spinal fluid, and flesh, consumed by mortals, they do nothing, but when consumed by the cursed (vampires and werewolves), they restore health, stamina, and magicka. Likewise... the cursed are now unable to recieve any benefits from non-meat based food as well as stamina, health, and magicka potions... hearts can be consumed for stamina and health without being in werewolf form in order to still contribute to the leveling process.**

 - **DRAGON COMBAT MODULE ADDITIONS: Dragons now have conjuration magic, disarming power words to combat weapon users, necromancy, and more breath weapons in the dlc areas. Common dragon-like creatures also have a large assortment of abilities.**

 - **NO KILLMOVES: This is for fighting to the very bitter end every single time, uninterrupted by killmove animations.**

 - **NUMIDIUM NORMAL WEAPON SOUNDS : This is for the god-weapons dropped by children of numidium bosses in dwemer dungeons as they might sound too loud and noisey for some.**

### NOTE: Adept difficulty is also HIGHLY RECOMMENDED for Skyrim Immersive Creatures (SiC), these settings can be accessed within the Immersive Creatures MCM options, then use Fine-Tuned from that point forward.
#
[5f]
## Nethers Follower Framework
#### NOTE: Difficulty Settings for Followers GIVING DAMAGE can be adjusted in the Nethers Follower Framework mod settings inside MCM. It is also possible to ADD custom Followers like Inigo and Lucien into the Framework so they can use the NFF rules, I have tested this feature extensively over months of playtime as I always take these followers with me on ALL playthrough adventures, and it works like a charm, Access their dialogue menu after recruiting them into your party and then simply choose the NFF Import option. Please read this very helpful [PDF Guide](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=153383&game_id=1704) from the author of this mod, if needed, as NFF has a slew of options to get acquainted with. 
#### Also included is [Ashien's Cursed Rings](https://www.nexusmods.com/skyrim/mods/64530) <--click & read the mod page for the rings location, this mod will help your followers effectively TAKE DAMAGE at higher levels.
![NFF](https://user-images.githubusercontent.com/78007822/139795556-8f090a9c-5fd6-473e-98be-26f89e807455.png)
-
[5g]
## Imaginator ENB Emulator
![Imaginator Settings](https://user-images.githubusercontent.com/78007822/139812380-f525b3de-92a9-4744-9a97-5c750cd55ee5.png)
-
#### NOTE: It is HIGHLY RECOMMENDED to have Sunlight at -1 or -2, ⬇️ this setting removes excess surface and snow glare, -2 Sky is just my own preference but not required to reduce glare.
![Imaginator Settings 2](https://user-images.githubusercontent.com/78007822/139812436-f2dbf65d-a753-4d06-9a47-24266703d9c4.png)
![Imaginator Settings 3](https://user-images.githubusercontent.com/78007822/139812485-4348a4ec-36c8-4aef-b240-b98293cadbf9.png)
#### NOTE: These 4 tintor colors set to 1 will help remove the excess blue/green tint within Skyrim. ⬆️
#
[5h]
## Immersive Creatures
#### NOTE: If you want to minimize Non-Adult animal spawns (Wolf Pups 🐺) drop the additional animal spawn chance to 1%, in the Additional Spawns options.
![Immersive Creatures No Wolf Pups](https://user-images.githubusercontent.com/78007822/139816694-d626fe76-e6fc-4afe-a077-e1e9121f45bf.png)
-
[5i]
## Nemesis PCEA
#### NOTE: These animations are Recommended for the Player and NPC.
![Nemesis PCEA Settings](https://user-images.githubusercontent.com/78007822/139820342-a119bb60-493e-4131-a2ed-7da9499fc004.png)
-
[5j]
## R.A.S.S Weather
![R A S S Settings](https://user-images.githubusercontent.com/78007822/139821113-f1368d48-a4d5-41e7-a46f-d0e900d8eaf3.png)
#### NOTE: Camera Visual Effects DISABLED is HIGHLY RECOMMENDED for better VR visuals ⬆️ and overall performance.
#
[5k]
## Sounds of Skyrim - Civilization and Wilds
#### NOTE: These are the recommended DISABLED sounds for an overall better audio experience.
![SoS Civ Settings](https://user-images.githubusercontent.com/78007822/139822593-bc3a4b2a-7dd6-42ea-88ec-209f88bbfc12.png)
![SoS Wilds Settings](https://user-images.githubusercontent.com/78007822/139822728-0301c97a-eb06-42ce-b04a-f9ebf54131ad.png)
-
[5l]
## Storm Lightning
#### NOTE: Use Realistic or Ultra Realistic for best VR results.
![Storm Lightning Settings](https://user-images.githubusercontent.com/78007822/139826224-4534dba6-0899-43b7-984a-a42c791d9d43.png)
-
[5m]
## Strike Obstruction Timed Block
#### NOTE: It is HIGHLY RECOMMENDED to DISABLE player parry mechanics, these animations are not triggered in VR.
![Strike Obstruction Timed Block Settings](https://user-images.githubusercontent.com/78007822/139826990-c155d19e-b1ca-42a6-92b1-4f5c3e749f7d.png)
-
[5n]
## Timing is Everything
#### NOTE: It is HIGHLY RECOMMENDED to click ‘LOAD PRESET’ and ENABLE the Lexy FISSES settings.
![Timing is Everything Settings](https://user-images.githubusercontent.com/78007822/139827581-999b3eb6-4e8e-4f70-be62-7b269bd88fe3.png)
-
[5o]
## Unread Books Glow
#### NOTE: In general, plain books glow is not suggested, but it's great for book collecting.
![Unread Books Glow](https://user-images.githubusercontent.com/78007822/139838085-27dec7d9-bed1-49e9-9e42-9665622dcc9c.png)
-
[5p]
## VRIK
#### NOTE: It is CRITICAL to DISABLE 'Adjust Held Weapons Position', otherwise staff casting crosshairs are off-center, and using a bow & arrow will feel awkward.
![VRIK Settings](https://user-images.githubusercontent.com/78007822/140565481-881ed992-5062-476f-bdce-4dd9af9b349d.png)
-
[5q]
## Wonders of Weather
#### NOTE: These settings increase overall rain performance & fantasy visuals.
![WoW Settings](https://user-images.githubusercontent.com/78007822/139839212-26e1ba6f-9108-4146-b1fb-21bea4cb44ef.png)
-
[6]
# The Sharper Eye
#### NOTE: With SteamVR, I recommend using [The Sharper Eye](https://www.nexusmods.com/skyrimspecialedition/mods/46999/) mod with or without TAA, this mod needs to be downloaded manually and placed inside your root SkyrimVR folder, please click the link provided and read the mod page for more info.
![The Sharper Eye](https://user-images.githubusercontent.com/78007822/139843882-792e6293-f0b9-4c05-8564-62e06bfce179.png)
-
[7]
# TAA On or Off
#### NOTE: TAA makes the distant image in VR have less jaggies (shimmer), personally i don't use this feature, as the mild shimmer doesn't bother me, however, it's turned ON by default with DVR, but if you'd like it turned OFF then it is CRITICAL to open your SkyrimVR ini Tweaker tool, ![Skyrim ini Tweaker Small](https://user-images.githubusercontent.com/78007822/140593759-0e282f42-2d72-472c-8f67-88fc89e86b22.png) and simply change bTAAWater = 1 to bTAAWater = 0, otherwise you will see visual anomalies with water.
#
[8]
# NVIDIA Settings
#### NOTE: The SkyrimVR specific nVidia settings I have provided are for better visual clarity for the Rift S, but they likely work fine with a range of other HMDs, do some research online and feel free to experiment with your own settings if these are not sufficient for your GPU.
![nVidia Settings 1](https://user-images.githubusercontent.com/78007822/141846168-66d13665-9fb0-4bc0-818e-823464b8eae4.png)
![nVidia Settings 2](https://user-images.githubusercontent.com/78007822/141846171-0938028d-1f22-4bbb-aa8c-8564271a7402.png)
-
[9]
# SkyrimVR and SkyrimPrefs ini
#### NOTE: If your game feels ‘Off’ or ‘Not Quite Right’ after installing and playing, or if you just want to reset your current Diabolist VR .ini [skyrimprefs.ini & skyrimvr.ini](https://drive.google.com/drive/folders/1HZ2Tgr3YjiP1zxBMwpN3OusSq4kTHT5n?usp=sharing) ⬅️️ click this link to get both current files and then overwrite them inside your ‘DVR\profiles\Diabolist VR’ folder, also make sure to replace these Skyrim.ini file inside your root Skyrim VR folder.
#
[10]
# DO NOT SORT DVR WITH LOOT
#### NOTE: DVR has been manually sorted from top to bottom & using loot WILL destroy the correct plugin order, if you add more mods, you will NEED to know where to place those new plugins and loose files, you will also need to incorporate them into the many custom made patches (if this is needed), additionally, I WILL NOT provide support with changing ANY aspect of this modlist. DVR support is EXCLUSIVE to the modlist provided, that being said, _If_ you mess up the plugins order somehow, you can simply click the circular icon on the Mod Organizer window to restore the original plugin order based on the most recent date.
![No LOOT Sorting](https://user-images.githubusercontent.com/78007822/147396679-c555b0da-7da1-446c-9b08-50529a50b561.png)
-
[11]
# INSTALL IS COMPLETE 
 - ### You’re Ready to Play! 
 - ### Please post on [DVR Discord](https://discord.com/invite/HuqU54gPcv) if you need modlist support. 
# Thanks for downloading Diabolist VR! 
### ...but most importantly...
# Have fun monster hunting & loot hoarding!
![DVR Logo Final Black Short Small 420x](https://user-images.githubusercontent.com/78007822/142841451-46e00818-6d9f-43e8-8ed8-7bc61bdec1dc.png)

#### - Latest DVR Guide Update, 12/25/2021
