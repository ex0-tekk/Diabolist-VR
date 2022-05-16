# Diabolist VR Install Guide

![DVR Flame Banner Header](https://user-images.githubusercontent.com/78007822/167721350-d832133f-a067-4c42-90a1-2569b356b969.png)

---

## **DVR Install Index**

---

- **[1. Introduction](#1-introduction)**
- **[2. PC Requirements for DVR](#2-pc-requirements-for-dvr)**
- **[3. Mod List Features](#3-mod-list-features)**
  
---

- **[4. Gameplay Prep](#4-gameplay-prep)**
  - **[4A. SkyrimVR and Steam Install](#4a-skyrimvr-and-steam-install)**
  - **[4B. Visual C Runtime Installs](#4b-visual-c-runtime-installs)**
  - **[4C. Windows Antivirus and Firewall Settings](#4c-windows-antivirus-and-firewall-settings)**
  - **[4D. Windows Paging File Size](#4d-windows-paging-file-size)**
  - **[4E. Wabbajack and DVR Install](#4e-wabbajack-and-dvr-install)**
  - **[4F. SkyrimVR ini Tweaker](#4f-skyrimvr-ini-tweaker)**
  - **[4G. CPU Threads](#4g-cpu-threads)**
  
---

- **[5. MCM Recorder Auto-Load Settings](#5-mcm-recorder-auto-load-settings)**
  - **[5A. Fine-Tuned Challenge](#5a-fine-tuned-challenge)**
  - **[5B. RLE-SiC-Mihail Monsters](#5b-rle-sic-mihail-monsters)**
  - **[5C. Nethers Follower Framework](#5c-nethers-follower-framework)**
  
---

- **[6. The Sharper Eye](#6-the-sharper-eye)**
- **[7. TAA On or Off](#7-taa-on-or-off)**
- **[8. Nvidia Settings](#8-nvidia-settings)**
- **[9. SkyrimVR and SkyrimPrefs ini](#9-skyrimvr-and-skyrimprefs-ini)**
- **[10. DO NOT SORT DVR WITH LOOT](#10-do-not-sort-dvr-with-loot)**
- **[11. INSTALL IS COMPLETE](#11-install-is-complete)**

---

## **1. INTRODUCTION**

---

### **Diabolist VR is a high fantasy theme-based mod list that pays homage to the hack-n-slash loot-hoarding Action RPG of the late 90s, it does this by adding 10 Diablo inspired mods and so much more, this includes:**

---

- **A custom flame Diablo intro.**
  
- **Solarion Spear intro replacer.**
  
- **Authentic in-game Diablo font.**
  
- **Intro and in-game music overhaul.**
  
- **The Secret Cow level from Diablo II.**
  
- **Gauntlet mouse cursor from Diablo II.**
  
- **A classicly generous 3 tier loot system.**
  
- **A dual town portal spell called Voidgate.**
  
- **The Horadric Crafting Cube from Diablo II.**
  
- **Various weapons inspired by the Diablo series.**
  
- **The female Amazon from Diablo II visually improved over the LE version.**
  
- **The Imperius Solarion Spear and Tyrael Armor from Diablo III, these can only be crafted.**
  
- **Hundreds of unique monsters with more aggro range, enhanced combat abilities and increased population.**
  
- **A sprawling multi-dungeon system called Skyrim Underground, along with 65 additional Forgotten Dungeons.**

---

## **2. PC REQUIREMENTS FOR DVR**

---

DVR should run well on modern PC-VR configurations from medium to high end, **I focused heavily on optimizing all performance related settings** via ini files, mods, tools and using a low 512k res DynDOLOD configuration for hybrid 3D trees.

### **Minimum and Recommended PC-VR Setup for DVR:**

- 20xx graphics cards **_(30xx cards are highly recommended, and 1080 should still work but it will be laggy and require further performance tweaking, users will need to troubleshoot these issues on their own.)_**
- AMD Ryzen-5 or Intel-5. _(7 or 9 is recommended.)_
- 16 GB RAM. _(32 GB is recommended.)_
- Solid State Drive. _(**M.2 drives are Highly Recommended for the best performance**, but a SSD **MUST** be used, **DO NOT Use a traditional hard drive.**)_

**This should be a good start for decent performance.**

A complete DVR install has a total size of roughly 110 GB, (_this size includes the initial DVR file download from the Wabbajack software._)

Since I use a Rift S, the skyrimvr.ini files will reflect that, so a few of these .ini settings will need to be adjusted to suit your specific HMD and PC. **I will go over that and other recommended settings throughout this guide.**

---

**DVR is developed and tested with this PC-VR setup:**

- Oculus Rift S.
- Win 10 ver.20H2 Fully Updated.
- Ryzen 7 3800x AMD Processor.
- 32 Gigs of 14-34 Low Latency RAM.
- Kingston NVMe M.2 1tb SSD.
- Nvidia 3090 GPU.

---

## **3. MOD LIST FEATURES**

---

**To save space on the in-game loot card, DVR uses a 3 tier STAR Halgaris RPG loot system.**

**The Percentages displayed below are the item drop rates.**

- **No Star = No enchant (Vanilla) = 66%**
- **1 Star = 1 Enchant = 26%**
- **2 Stars = 2 Enchants = 5%**
- **3 Stars = 3 Enchants = 3%**
  
**NOTE:** _Some_ hard-coded vanilla gear and quest items still have 1 or more enchants with No Star, this cannot be changed, **additionally, there is 10 randomly enchanted item variations on all tiers, EXCEPT No Star & No Enchant (Vanilla).**

- The loot system in DVR is **VERY GENEROUS**, just like the Diablo series is known for, so you will **often** be upgrading, tossing away or selling items, **Nethers Follower Framework** provides a dialogue option to make your followers run to town and sell any gear you give them regardless of where you are or the funds available on merchants, **using this feature is HIGHLY RECOMMENDED** as you continue gathering loot if you don't want to always travel and sell. Making income in DVR should not be an issue regardless of you and your followers selling items, due to the boss chests and dragons providing plenty of gold, additionally, in an attempt to balance bartering and trade, I have added an increase in overall cost for buying items and subsequently less income for selling all items, along with other barter tweaks such as: increased merchant gold, increased ferry and horse carriage costs, sleeping at the inn costs more and other currency adjustments.

- **Loot Boxes** are placed at merchants across 7 different cities, they are easy to find and they _can be_ addictive, but loot keys are not cheap.

- This mod list is a **loot hoarders dream**, and with that in mind, every new character you create starts with a **10,000lb carry weight ring.**

- Transmuting lower quality items into a higher quality ones, or convert items of one type into another with the [**Horadric Cube from Diablo II**](https://www.nexusmods.com/skyrim/mods/22806/?tab=description) please read the authors nexus page linked here to see more details on how to do this.

- Voidgate is a spell every player starts with in DVR, you simply access it from your magic menu and cast a dual portal to step into, for example: you're dungeon crawling and you want to goto town to sell or buy... ok, so you cast the spell and a blue swirling portal opens, now you open your map and goto your desired location (DVR lets you teleport out from ANY dungeon via your map), once you're finished, you simply cast the spell again and a 2nd portal opens, walk into the swirling portal, this returns you back to the spot where you were previously adventuring.

- **The Fine-Tuned Challenge mod replaces the traditional Skyrim difficulty settings, they flow in both directions for hard-mode, easy-mode, and everything in between,** with a few _optional_ cheat mods available for casual steam-rolling fun.

- **Look for _QoL Enhancements, Difficulty Options, Cheats & Level Lists_ on the left side of your MO2 window and click on Visit on Nexus if you'd like to read what they do, you will find these _OPTIONAL_ cheat mods placed throughout this category and these cheats are directly accessed in game through your inventory or MCM.**

- All nonsense weapon and armor enchantments from the Summermyst Enchantments mod have been removed, this makes for some amazing enchantment combinations, you will likely need to increase the difficulty up as you continue to level, before long you will become quite powerful by coming across 2 star & 3 star items, and by also enchanting your own gear.

- Most of the 'must-have' popular VR Quality of Life mods have been installed and fully updated and will be updated as DVR evolves over time until support ends.

- VR controller functionality, physics, visuals, performance and LOD are all enhanced & improved through various tools, mods & .ini settings.

- While being a large yet surprisingly straight-forward mod list, DVR still hosts plenty of noticable changes, but the Dragonborn storyline and Civil War are still the focal point and on par with vanilla.

- Diabolist VR is a high performance, simple to setup, Diablo themed VR modlist... based on dungeon crawling, monster hunting and loot hoarding.

---

## **4. GAMEPLAY PREP**

---

**From here forward, I will be using 2 terms Over and Over.**

**HIGHLY RECOMMENDED**  and  **CRITICAL.**
  
---

- **HIGHLY RECOMMENDED is IMPORTANT**, but also with flexibility towards other configurations if the player desires.

- **CRITICAL is MANDATORY** and **-MUST BE DONE-** in order to make the game run properly, or as DVR was intended to run, in all aspects.

- **PLEASE PAY ATTENTION TO THESE 2 WORDS FOR THE REST OF THIS INSTALL GUIDE.**

---

### **4A. SkyrimVR and Steam Install**

---

It is **CRITICAL** to have a **100% fresh install of SkyrimVR ON THE ROOT C DRIVE.**

**DO NOT USE** --> C:\Program Files  and  C:\Program Files (x86) <-- **Ignore these 2 folders for the entire process of this install guide, due to possible admin rights restrictions.**

**It is also HIGHLY RECOMMENDED and BEST PRACTICE to have STEAM INSTALLED ON THE ROOT C DRIVE.**

### **EXAMPLE:**

**Steam Install Location:**

- C:\Steam

**SkyrimVR Install Location:**

- C:\Steam\steamapps\common\SkyrimVR

**Diabolist VR Install Location:**

- C:\DVR

---

- If you want to use another drive for Steam or SkyrimVR, that's fine too, simply follow [**This Easy Guide**](https://drive.google.com/drive/folders/1lOBFqblzA23AbXFz-usTejOKR5UFsPjA?usp=sharing) to change Steams game install locations, but regardless of this, **The Root C Drive is ALWAYS Highly Recommended for ALL installs regarding Steam, SkyrimVR and DVR.**

- After you have confirmed Steam and SkyrimVR are installed correctly, **start the default Steam version of SkyrimVR to have the game create the appropriate .ini file in the documents folder on your C drive**, once you see the Bethesda logo pop up, you can close the game and continue following this guide.

---

### **4B. Visual C Runtime Installs**

---

- It's **CRITICAL** to install the All-In-One **[Visual C Runtime Packages](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/)** available if you don't already have it, as the Feb 2022 release is a requirement for the 3D audio files from the **[Binaural 3D Surround Sound for SkrimVR](https://www.nexusmods.com/skyrimspecialedition/mods/26916?tab=description)** mod on the Nexus, simply install the AIO package to cover all Visual C updates.

---

### **4C. Windows Antivirus and Firewall Settings**

---

- It's **CRITICAL** to add SkyrimVR.exe and ModOrganizer2.exe (DVR) to your Windows Antivirus Exclusion settings, this is to prevent random CTD _**(even if you have antivirus turned off, it still performs background scans.)**_

- Go to **Start > Settings > Update & Security > Windows Security > Virus & threat protection,** under **Virus & threat protection** settings, select **Manage settings,** and then under **Exclusions**, select **Add or remove exclusions.**
  
- Now select **Add an exclusion** and point it towards your **SkyrimVR.exe** and then **repeat this a second time to include ModOrganizer.exe.**

  ![v1-420](https://user-images.githubusercontent.com/78007822/147438064-82fd9c74-a749-472e-95f8-4b448e37cd2b.png)

  ![v2-420](https://user-images.githubusercontent.com/78007822/147438073-0799b866-fbd4-4344-a00f-bc776c81b588.png)

  ![v3](https://user-images.githubusercontent.com/78007822/147438122-4d442b97-0aa9-45b7-99f6-352a612ad8a2.png)

---

- ### **WINDOWS FIREWALL**

---

- It is **CRITICAL to BLOCK SkyrimVR.exe (Inbound & Outbound)**, within your windows **firewall settings**, to prevent random CTD produced by Bethesda server pings.

- Open your windows search function and type in Firewall, then click on **'Windows Defender Firewall with Advanced Security.**

  ![Firewall Settings 1](https://user-images.githubusercontent.com/78007822/140569744-80e05750-decc-48e4-976e-a84ac707259a.png)

- **When the Windows Firewall options pops up, follow these steps below:**

- Click Inbound Rules
- Click New Rule
- Click Program, then Next.

  ![Firewall Settings 2](https://user-images.githubusercontent.com/78007822/140570706-82949ebb-a4eb-47a4-ae45-13f6f6031696.png)

- **Now direct this window as shown below to your SkyrimVR root folder and select SkyrimVR.exe.**

  ![Firewall Settings 3](https://user-images.githubusercontent.com/78007822/140577020-ba21dac5-6462-4fdc-b5bf-25893ec53587.png)

  ![Firewall Settings 4](https://user-images.githubusercontent.com/78007822/140572008-768a8955-f3a7-4cdc-8a3c-aa9dec013d86.png)

- **Make SURE you select BLOCK** and another window will pop up with Domain, Private and Public, **make sure they are ALL selected**

  ![Firewall Settings 5](https://user-images.githubusercontent.com/78007822/140572430-5546eb0d-5fea-4ed7-8b4c-a9242217ebb2.png)

- **Name this field below to whatever you want** or use what I have put in the screenshot provided, then **click finish.**

  ![Firewall Settings 6](https://user-images.githubusercontent.com/78007822/140572798-048e221d-0f9e-43dd-a3af-9984fca91ac8.png)

- **NOTE: MAKE SURE YOU REPEAT THE EXACT SAME STEPS FOR THE OUTBOUND BLOCK OPTIONS, AS THESE STEPS YOU'VE JUST COMPLETED ONLY COVER INBOUND BLOCKING.**

---

### **4D. Windows Paging File Size**

---

- It is **CRITICAL** to set your **pagefile size to 20GB (20,000mb).**
20GB is the **modded SkyrimVR standard** if you have 16GB RAM, I personally use 40GB pagefile size with 32GB of physical RAM, as I prefer the extra overhead.
- Use this number for **both** the initial size and max size on 1 free SSD with enough space.
- There is **no need** to apply this pagefile size setting to multiple hard drives.
Keeping your Windows drive (typically the C: Drive) set to SYSTEM MANAGED SIZE Is **HIGHLY RECOMMENDED** while using the pagefile setup with 1 free hard drive in this fashion and this info and how to configure the Windows Paging File Size is explained [**HERE**](https://www.howto-connect.com/tweak-paging-file-for-better-windows-10-performance/)

  ![Virtual Memory](https://user-images.githubusercontent.com/78007822/139851096-1b8f5275-4070-48ed-b974-58e80fb25349.png)

---

### **4E. Wabbajack and DVR Install**

---

### **NOTE: A NEXUS PREMIUM ACCOUNT IS HIGHLY RECOMMENDED, OTHERWISE 500+ MODS WILL HAVE TO BE DOWNLOADED MANUALLY 😵.**

---

- Download and install [**Wabbajack**](https://www.wabbajack.org/).

- Next, make a folder **Preferably ON THE ROOT C DRIVE** and label it **DVR**.

- **IMPORTANT REMINDER:** **-DO NOT-** install **ANYthing** into your C:/Program Files or C:/Program Files (x86) folders, due to admin restrictions.

- **Download Diabolist VR from the Wabbajack VR drop down menu on the top section of the software to begin the install process**, once that initial download is done, a new Wabbajack window will pop up, go ahead and select the **Installation Location (3 Dots ...)** on the right side middle field section, then select the DVR folder you created peviously, **preferably on the Root C Drive to make things easier**, once you do that the download section will automatically pick the Mod folder for you inside of itself, or you can select a different folder to keep the downloaded zipped mods separate, it’s your choice.

- Now click the big blue arrow, sit back & relax while it installs, if you’re curious, you can watch the mod info that pops up to get an idea of what’s being installed, you can also go to the [**Wabbajack website**](https://www.wabbajack.org) and search for this modlist in the VR section, and then **look for the Archive Search button** on the bottom left of the Diabolist VR panel, this lets you see the mods currently installed. **A friendly reminder:** you are downloading 500+ mods so just be patient & let it finish, if it Freezes or Fails Install (**this may happen several times during the download and install process**), simply start the process over, just re-open the DVR wabbajack file & click the arrow again without doing anything else & it will resume where it left off, **If You Cannot Download This FIRST DVR Wabbajack File Whatsoever**, then **Please Join the** [**DVR & LoSVR Discord**](https://discord.com/invite/HuqU54gPcv) for further assistance and a mirrored link to the same install file.

- After install is finished, close the Wabbajack window & proceed to the DVR folder, open the folder called **Game Files Folder**, then **drag & drop ALL of these files into your SkyrimVR root folder**, there _should_ be **only 1 overwrite notification** for the Skyrim.ini file, this overwrite is correct, **do it.**

---

### **4F. SkyrimVR ini Tweaker**

---

- There are a few .ini settings you _should_ be aware of, because we don’t all use the same PC / HMD, so it’s best to adjust these based on your HMD resolution and CPU threads.

- **NOTE**: Windows 11 users can **ONLY** use ModOrganizer 2.4.2 or later.

- **Look inside the DVR folder & open ModOrganizer.exe**

- Once it’s open, click on this icon.
![Skyrim ini Tweaker Small](https://user-images.githubusercontent.com/78007822/139736342-91ff8313-2d95-460a-b9ab-b8483e5fbc0b.png)

- **This configuration window will pop up ⬇️.**

  ![SkyrimVR ini Tweaker Settings](https://user-images.githubusercontent.com/78007822/139736900-0332834d-5369-47de-add5-c8462af09bec.png)

- Having personalized .ini tweaks will help overall visuals based on SuperSampling settings.

- **Example:** using 150% SS with SteamVR works out to 2016 x 2172 per eye on the Oculus Rift S, and this resolution is reflected with two .ini settings seen below.

---

- iHudMenuTextureSize = 2172

- iProjectedMenuTextureSize = 2172

---

- These 2 sets of numbers above will **always** equal the largest number of your headsets resolution & they **_should_** be adjusted with this ini configuration tool to match your VR headset for best in-game menu size.

---

### **4G. CPU Threads**

---

- iNumHWThreads = ?

- iNumThreads = ?

---

- These 2 ini settings seen above **represent how many threads your CPU has**, it’s set to 16 threads in the skyrimvr.ini and **this will need to be changed to your own CPU threads if it is not 16**, (or you can reset this entire thread of ini settings back to SkyrimVR default if you prefer) a good program to find out how many threads your processor is using, would be [**CPUID**](https://www.cpuid.com/softwares/cpu-z.html), ⬅️️ click to install, **if more help is needed with this, don't hesitate to post in the** [**Discord DVR Support Chat Channel**](https://discord.gg/HuqU54gPcv).

- ### **You can close the SkyrimVR ini Tweaker now.**

---

## **5. MCM Recorder Auto-Load Settings**

---

- Start DVR through SKSE on the top right section of ModOrganizer, once you finish creating your new character and you spawn into the starting area it will spam the top of your screen with MCM mods being enabled in DVR, **It will also Auto-Load and streamline ALL Highly Recommeneded and Critical specific settings.**

- **These Auto-Load settings are Highly Recommended and some are CRITICAL for the best DVR experience.** This process will give users a notification if they try to interrupt and it will warn them to let it finish, **PLEASE LET THIS FINISH**, when it's done loading you will be notified.

  ![Finished DVR MCM Setup2](https://user-images.githubusercontent.com/78007822/156894808-f57a4461-6c00-4692-9be7-a5034f7ddf26.png)
![Finished DVR MCM Setup3](https://user-images.githubusercontent.com/78007822/156894810-ed5bf4f2-f158-4fe5-91e6-84b5fb4db75b.png)

- The **[MCM Recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719)**
nexus link is provided for further information and the author provides a short YouTube video to help you fully understand how this mod works.

---

### **5A. Fine-Tuned Challenge**

---

**DVR uses Adept difficulty by default, this is CRITICAL to utilize the Fine-Tuned Challenge mod**, because the dmg & spawn multiplier numbers will not function as intended if any other vanilla difficulty setting is used, **this mod simply REPLACES the vanilla difficulty settings with detailed % numbers.** Experiment if you want, however, Fine-Tuned DEFAULT % with ADEPT set is a good start if you want easy dungeon crawling, but **for the best experience you would set the multipliers progressively higher**, for example **I use: Easy: 130%, Medium: 140%, Hard: 150%, Very Hard: 160%**, then adjust the Dmg taken & Dmg inflicted sliders based on your own preferences, **I use 80% Dmg Inflicted and 120% Dmg Taken, I also take followers on my adventures, you'll probably want to do the same..**

![Fine-Tuned Challenge Settings](https://user-images.githubusercontent.com/78007822/139785982-11c9f46d-1439-4129-a33e-d783dc2c8b3b.png)

---

### **5B. RLE-SiC-Mihail Monsters**

---

DVR uses several monster mods at its core which have either been repaired or enhanced with xEdit and CAO (or both), and to optimize and minimize any 4k textures down to 1k or 2k: Hosting over 50 Mihail Monsters, along with Rogue Like Encounters(RLE), Skyrim Immersive Creatures(SiC), Scary Night Spawner(SNS) and Creepy Zombies(CZ).. additionally, Skyrim Underground has it's own set of monsters spread out between 2 massive underground dungeons

RLE provides 3 Combat modules to pick from and **DVR uses the Clean Combat Module**, which only alters the enemy combat styles, **this module adds NO further difficulty, and it lets Fine-Tuned Challenge handle all base difficulty aspects.**

---

### **RLE Combat Features, Quoted From The Author:**

---

- **RAID ADDS:** Dragons (and many other creatures) now have mmo-style adds which spawn mid-fight, regular dragons get two or more dragonlings at 50% health, Alduin gets dragonlings at 50% and 2 or more Blackguards of Akatosh (black daedroths wielding daedric greatswords) at 25%.

- **DIRE ARROWS:** Distributed throughout the world, morrowind-style, are creature types that use enchanted arrows... these may be crafted or collected to be used at will, their damage ratings are much higher than normal arrows, and many of them explode upon impact.

- **MULTI-FORM ENEMIES:** There is special enemies in the world that have more than one form, by this I mean when their health reaches zero, they change into a weaker or stronger version of themselves. Some examples are Troll Pillages, Earth-bound Sinners, Grand Flame Atronachs, and certain Wisp Mothers.

- **ROGUES:** Distributed throughout the world are versions of intelligent enemies that can visibly stealth and perform poisonous backstab attacks.

- **CRITICAL HITS:** Most non-humans now have a 1 in 10 chance to do critical damage with melee or ranged attacks.

- **BLOCK-RUNNING, QUICK-DRAW, & FASTER MOVEMENT WHILE AIMING:** Most humanoid enemies will frequently be pretty decent at positioning themselves in a fight and have these custom perks to mirror that.

- **CLEAVES:** Most creatures in the world, but very rarely humanoids, attack in arcs, hitting everything in those arcs. These were added to punish players who always group their party close together when fighting something large and tough. If a giant can hit everyone, for instance, with a single swing, it will, the same goes for most other creatures.

- **BLOOD LUST:** All living creatures drop blood, hearts, spinal fluid, and flesh, consumed by mortals, they do nothing, but when consumed by the cursed (vampires and werewolves), they restore health, stamina, and magicka. Likewise... the cursed are now unable to recieve any benefits from non-meat based food as well as stamina, health, and magicka potions... hearts can be consumed for stamina and health without being in werewolf form in order to still contribute to the leveling process.

- **DRAGON COMBAT MODULE ADDITIONS:** Dragons now have conjuration magic, disarming power words to combat weapon users, necromancy, and more breath weapons in the dlc areas. Common dragon-like creatures also have a large assortment of abilities.

- **NO KILLMOVES:** This is for fighting to the very bitter end every single time, uninterrupted by killmove animations.

- **NUMIDIUM NORMAL WEAPON SOUNDS:** This is for the god-weapons dropped by children of numidium bosses in dwemer dungeons as they might sound too loud and noisey for some.

---

### **5C. Nethers Follower Framework**

---

Difficulty Settings for Followers GIVING DAMAGE can be adjusted in the Nethers Follower Framework mod settings inside MCM. It is also possible to ADD custom Followers like Inigo and Lucien into the Framework so they can use the NFF rules, I have tested this feature extensively over months of playtime as I always take these followers with me on ALL playthrough adventures, and it works like a charm, Access their dialogue menu after recruiting them into your party and then simply choose the NFF Import option. Please read this very helpful **[PDF Guide](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=153383&game_id=1704)** from the author of this mod, if needed, as NFF has a slew of options to get acquainted with

Also included is **[Ashien's Cursed Rings](https://www.nexusmods.com/skyrim/mods/64530).** This mod is a set of rings located in a Riverwood chest near the trader merchant, these will help your followers effectively TAKE DAMAGE at higher levels, so as to not be god-like DMG sponges if you decide to NOT Use Nethers Follower Framework for these exact same options.

![NFF](https://user-images.githubusercontent.com/78007822/139795556-8f090a9c-5fd6-473e-98be-26f89e807455.png)

---

## **6. The Sharper Eye**

---

With SteamVR, **I Highly Recommend** using **[The Sharper Eye mod](https://www.nexusmods.com/skyrimspecialedition/mods/46999/)** with or without TAA, this mod needs to be downloaded manually and simply unziped and placed inside of the main SkyrimVR folder, It includes the preset, the required shader and a custom VR-enabled Reshade build, additionally, these are the settings **I use for a relatively sharp image without TAA for BEST overall performance**, **There is also performance mode available on the bottom right corner but it is NOT needed, as My Settings are on par with peformance mode, but click it if you want to experiment anyways, **to Enable this window below**, **click HOME on your keyboard to open and close this window**, it will be **visible on your desktop VR screen when clicking the HOME Button.**

![Sharper Eye Settings](https://user-images.githubusercontent.com/78007822/168633499-93cde32b-afc2-41d3-a74d-74e1c469f374.png)

---

## **7. TAA On or Off**

---

TAA makes the distant image in VR have less jaggies (less shimmer but more blur), but this setting also has a rather noticable performance impact, personally I dont mind a tiny bit of shimmer with a sharper image over a blurry FPS drop rates, so **this mod list comes with TAA Turned OFF by default**, but if you decide to enable this setting then it will be enhanced by a TAA auto-load feature from FPS Stabilizer, this just tweaks the sharpness of TAA, however, **you must open your SkyrimVR ini Tweaker tool ![Skyrim ini Tweaker Small](https://user-images.githubusercontent.com/78007822/140593759-0e282f42-2d72-472c-8f67-88fc89e86b22.png) and **enable these ini 2 settings (1 for TAA itself, 1 for TAA Water)** and example is shown below, this setting is to keep using TAA without manually enabeling it everytime you load your game, and the water is needed to avoid visual glitches while TAA is enabled.** 

(**OVERALL, I SUGGEST LEAVING TAA OFF FOR THE BEST IMAGE QUALITY WHILE USING SHARPER EYE, WITH MY CUSTOM SETTINGS.**)

---

bTAAWater = 1

bUseTAA = 1

 Additionally, it is **CRITICAL** these steps are **ONLY taken IF you decide to Enable TAA.**

---

## **8. NVIDIA Settings**

---

The SkyrimVR specific nVidia Control Panel settings I have provided are for better visual clarity for the Rift S, but they likely work fine with a range of other HMDs, do some research online and feel free to experiment with your own settings if these are not sufficient for your GPU.

![SkyrimVR nVidia Settings 1 smaller](https://user-images.githubusercontent.com/78007822/162099918-831f4b69-5a8e-4c2a-b2bb-f8d2a1460a4e.png)
![SkyrimVR nVidia Settings 2 smaller](https://user-images.githubusercontent.com/78007822/162099923-cc4071cb-9d95-4e30-898e-b302dd468b48.png)

---

## **9. SkyrimVR and SkyrimPrefs ini**

---

If you want to reset your Diabolist VR .ini files back to install defaults: [**skyrimprefs.ini & skyrimvr.ini**](https://drive.google.com/drive/folders/1HZ2Tgr3YjiP1zxBMwpN3OusSq4kTHT5n?usp=sharing) ⬅️️ click this link to get both current files and then overwrite them inside your ‘DVR\profiles\Diabolist VR’ folder, also make sure to grab the Skyrim.ini file and place it inside your root SkyrimVR folder

---

## **10. DO NOT SORT DVR WITH LOOT**

---

DVR has been manually sorted from top to bottom & **using loot WILL destroy the correct plugin order**, if you add more mods, **you will NEED to know where to place those new plugins and loose files**, you will also **need to incorporate them into the many custom made patches (if this is needed)**, additionally, **I WILL NOT provide support with changing ANY aspect of this modlist. DVR support is EXCLUSIVE to the modlist provided**, that being said, **_If_** you mess up the plugins order somehow, you can simply click the circular icon on the Mod Organizer window to restore the original plugin order based on the most recent date.![No LOOT Sorting](https://user-images.githubusercontent.com/78007822/147396679-c555b0da-7da1-446c-9b08-50529a50b561.png)

---

## **11. INSTALL IS COMPLETE**

---

- **You’re Ready to Play!**
- Please post on [**LoSVR / DVR Discord**](https://discord.com/invite/HuqU54gPcv) support channels if you need any additional support **or** if you find any critical bugs to report.
- Friendly general chat is also available. **:)**

---

**Thanks for downloading Diabolist VR.**

**...but most importantly ...**

**Have fun Dungeon Crawling, Monster Hunting and Loot Hoarding!**

![DVR Flame Banner Footer](https://user-images.githubusercontent.com/78007822/167721606-8675ef17-d6e8-4353-a376-5f5c61306479.png)

Latest DVR Guide Update, 05/15/2022.

---
