# DIABOLIST VR SETUP GUIDE

- [DVR Introduction](dvr-introduction)

- [Development Details and Test Specs](development-details-and-test-specs)

- [DVR Installation Guide](dvr-installation-guide)

  - [SkyrimVR Pre Installation](skyrimvr-pre-installation)

  - [Wabbajack Install](wabbajack-install)


- [Installation] (#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)

    - [Clean Fallout 4](#clean-fallout-4)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Launching the Game](#launching-the-game)
- [Updating](#updating)
- [BiRaitBec Texture Optimization](#biraitbec-texture-optimization)
- [Noteworthy Mods](#noteworthy-mods)
  - [Sim Settlements 2](#sim-settlements-2)
  - [Subway Runner](#subway-runner)
  - [This is Trash - A Scrapping Alternative](#this-is-trash---a-scrapping-alternative)
  - [Buffout 4](#buffout-4)
- [Creation Club Support](#creation-club-support)
- [In-Game MCM Options](#in-game-mcm-options)
- [FAQ](#faq)
- [Controller Support](#controller-support)
- [ENB](#enb)
- [Widescreen Support](#widescreen-support)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)

# DVR Introduction
![Diabolist VR Wolf Right Final 2 0 D-R-R](https://user-images.githubusercontent.com/78007822/139607370-54db657a-af31-498c-acfb-b3474550df9a.jpg)

Diabolist VR pays homage to the hack-n-slash loot-hoarding ARPG of the late 90s, by adding 6 Diablo inspired mods, which includes a custom flame intro and music overhaul, authentic Diablo in-game font, the female Amazon character from Diablo 2 overhauled with spear throwing mechanics, the Horadric Crafting Cube, Imperius Solarion Spear and Tyrael Armor from Diablo 3, increased overall population with hundreds of unique monsters, a sprawling dungeon called Skyrim Underground, along with 65 additional Forgotten Dungeons.

The loot system is **very generous**, like the Diablo series always has been, so you will be sharing loot with followers, tossing away or selling some, but don't expect all Skyrim merchants to have loads of septim for **ALL** of your scored loot, much will be discarded or left behind in dungeons or at your player home, as DVR only hosts merchants with 10x the default amount of septims as vanilla Skyrim gives, that being said, regardless, making income in DVR will **NOT** be an issue due to the treasure chests, bosses and dragons also providing plenty of septims.

This mod list a 5 tier loot system inspired by Diablo 4.

 - Common 
 - Magical 
 - Rare
 - Legendary 
 - Mythic

This loot system also **applies 10 different enchant variations on all tiers**, **EXCEPT** common.

There is random Loot Boxes at several merchants across Skyrim, they are easy to find and they *can be* addictive.

Additionally, you can transmute lower quality items into a higher quality ones, or convert items of one type to another with the [Horadric Cube from Diablo II](https://www.nexusmods.com/skyrim/mods/22806/?tab=description) <- **please read the authors nexus page linked here to see more details on how to do this.**

This mod list is a loot hoarders dream ...and speaking of hoarding, every new character you create starts with a ring that has 10,000 carry weight.

I have stripped out ALL nonsense weapon and armor enchantments from the Summermyst mod, this makes for awesome enchantment combinations for all the items they apply too, you will likely need to crank difficulty as you lvl and find Mythic items, you will become quite powerful.

**Staying true to the original Skyrim content, there are no major storyline addons or game-changing town/city/quest overhauls, it's a large yet surprisingly straight-forward mod list, the Dragonborn storyline and Civil War are still the focal point and on par with vanilla.**

Enemies will be stronger to start but not over-powering, Fine-Tuned difficulty settings flow in both directions for hard-mode or go for easy-mode and use the few optional cheat mods available for casual steam-rolling fun.

VR controller functionality, physics, visuals, performance are all enhanced & improved through various tools, mods & .ini settings.

**I focused heavily on optimizing DVR**, and with that comes using low DynDOLOD settings along with Occlusion, with a surprisingly decent visual outcome.

**DVR *should* have good performance with multiple HMDs on higher-end modern PCs.**

The latest must-have popular VR Quality of Life mods have all been added and fully updated to my knowledge. (this includes the new SkyUI)

Diabolist VR aims to be a simple to setup & play, high-fantasy, Diablo themed mod list, based on dungeon crawling, monster hunting and loot hoarding.

I tried my best to create a nostalgic Diablo vibe while adventuring through the province of Skyrim.

## Development Details and Test Specs

### DVR is developed and tested with this HMD and PC setup:

 - Oculus Rift S.
 - Win 10 ver. 1909 Fully Updated.
 - Ryzen 7 3800x AMD Processor.
 - 32 Gigs of G-Skill 14-34 Low Latency RAM.
 - Kingston NVMe M.2 1tb SSD.
 - Nvidia 3090 GPU.

The initial wabbajack setup file is 4.80 gb & the finished install folder size is 94 gb, for a total size of roughly 99 gb, it’s highly recommended that you install this on a NVMe M.2 SSD for optimal performance, although traditional SSD should be fine.

**I focused heavily on optimizing DVR** via performance tools, mod settings, ini settings and using low DynDOLOD @ 512k with Occlusion.

DVR should have good performance with multiple HMDs combined with medium to high-end modern PC specs. 

Since I use a Rift S, the skyrimvr.ini / skyrimprefs.ini files will reflect that, so a few of these .ini settings need to be adjusted to suit your specific HMD. I will go over that and other recommended settings throughout this guide.

## DVR Installation Guide
### SkyrimVR Pre Installation

It is **CRITICAL** to have a 100% fresh install of SkyrimVR available & ready to play with no other files added, It is also **CRITICAL** to **have your SkyrimVR game installed in a folder outside of  C:/Program Files  and  C:/Program Files (x86)**  just **ignore these 2 folders for the entire process of this install guide, due to possible admin rights restrictions.**

Steam does not easily allow for new install folders, simply follow 
[This Easy Guide](https://drive.google.com/drive/folders/1lOBFqblzA23AbXFz-usTejOKR5UFsPjA?usp=sharing) to change that.

First, start the default Steam version of SkyrimVR to have the game create the appropriate .ini file in the documents folder on your C drive, and also to adjust the game's vanilla settings.

I have provided screenshots of the recommended SkyrimVR settings, along with highly recommended mod settings for DVR, however, all mod options in MCM are relatively safe to experiment with.

Refer to these screenshots below once you first load the game, **(and after Diabolist VR is installed)**... as I will Not be explaining these settings in detail aside from the screenshot **‘NOTES’** i have added, most of this is self-explanatory and also based on your preference and PC performance.

![VR Performance](https://user-images.githubusercontent.com/78007822/139617500-49f12f18-8311-426e-a045-c1b5ae8cf814.png)
-
![VR Performance 2](https://user-images.githubusercontent.com/78007822/139617544-c8bfd44b-a2bf-411a-a283-05d8dc02ac70.png)
![VR Performance 3](https://user-images.githubusercontent.com/78007822/139618123-a1acb305-3ff7-4e7d-8f9b-c0968dd25e31.png)
-
![VR Performance](https://user-images.githubusercontent.com/78007822/139618169-2be4c1db-0a53-4efa-865a-ecd0140ddc9c.png)
![VR General Settings 2](https://user-images.githubusercontent.com/78007822/139618717-47785cc5-81c8-43ac-9f0e-82e693936673.png)
-

## Wabbajack Install

### A NEXUS PREMIUM ACCOUNT IS HIGHLY RECOMMENDED, OTHERWISE 600 MODS WILL HAVE TO BE DOWNLOADED MANUALLY.

Download and install the latest version of Wabbajack,
This first step is mandatory, then download DiabolistVR,
Make a folder on any SSD drive with space and label it DVR.

**IMPORTANT REMINDER: -DO NOT- Install Anything Into Your C:/Program Files or C:/Program Files (x86) Folders, due to admin restrictions.**

Open the Wabbajack file you downloaded to begin the install process, on the bottom right, select the DVR folder you created & the download section will automatically pick the mod folder for you inside of itself, or you can select a different folder to keep the downloaded zipped mods separate, it’s your choice.

Click the big blue arrow, sit back & relax while it installs, if you’re curious you can watch the mod info that pops up to get an idea of what’s being installed, you are downloading over 500 mods so just be patient & let it finish, if it freezes, simply start the process over, to do this, open the Diabolist VR wabbajack file & click the arrow again without doing anything else & it will resume where it left off.
After install is finished, close the Wabbajack window & proceed to the DVR folder, open the Game Files Folder, then drag & drop ALL of these files into your SkyrimVR root folder.





You need a legal copy of Fallout 4 through Steam, with all DLCs **EXCEPT** the High Definition DLC. This is garbage and should not be used in any case ever.

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

Fallout 4 is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**. I really wish I could, but at this time, it simply isn't feasible.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Fallout 4

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Fallout 4` folder in `Documents/My Games/`. **Make sure you run the game once** to establish your registry path - otherwise, Wabbajack will be unable to locate the game directory, and thus cannot install the modlist.

### Using Wabbajack

#### Preparations

Let's get to the actual installation..

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases). You need to download the `Wabbajack.exe` file ONLY. Place the `Wabbajack.exe` file in a blank folder at the root of a drive, such as `C:/Wabbajack`. Please do not put it in a Windows Protected Directory, such as Program Files or your Desktop.

Launch Wabbajack. When it is finished extracting and installing itself, select the `Browse Modlists` option. Click the Download arrow for Magnum Opus, and you will be forwarded to the next screen when it is finished.

Set the `Installation Location` to a blank folder at the root of a drive, such as `D:\Magnum Opus`. The `Download Location` will update automatically. Again, please avoid using Windows Protected Directories.

Click the `Play` arrow.

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait until I update the Modlist. I'm typically extremely quick to respond to a situation such as this.

Most commonly, this will happen if a mod is hidden from Nexus. Contact me in Discord if this happens, and I can force the list to show as Under Maintenance until it comes back, and then I can fix it when it's unhidden.

**Mega links aren't downloading**:

Download this manually, put the archive in your Downloads folder, and restart Wabbajack.  
 - [FO4LODGen Resources](https://mega.nz/file/BZhlVCAJ#s-GqqbnJlZDvCLPiRw1Wm1EWGqMQCuh4CR8Zzn8POM4)  

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Copy Game Folder Files

After Wabbajack turns green and says Installation Complete, you can close it. Go to your installation folder (I will refer to this folder as the MO2 folder from now on) and you'll see a folder named `Game Folder Files`.

Copy the all of the files from the `MO2/Game Folder Files` directory into your game folder.

#### Launching the Game

After you copied the Game Folder Files, launch ModOrganizer.exe from inside your installation folder you chose for Wabbajack. Make sure the bar on the right side says `F4SE` and click Run. **You need to launch the game in this exact way every time in order to play with the installed mods.**

You may notice some mods are deactivated. These are for the Creation Club profile. Please see the [Creation Club Support](#creation-club-support) section a bit further down for more information.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

Magnum Opus updates based on a [Semantic Versioning](https://en.wikipedia.org/wiki/Software_versioning) system.

Generally speaking:  
- Full x.0 (2.0, 3.0, etc) updates requires a new game.  
- Major x.x (2.1, 2.2 etc) updates requires a new game.  
- Minor x.x.x (2.1.1, 2.1.2) updates can be applied to an ongoing playthrough.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

If you wish for Wabbajack to ignore any additional mods you've installed, rename them to say `[NoDelete]` at the beginning of the name.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## BiRaitBec Texture Optimization

**Yes this step is required, stop asking me every single day.**

Go to [BiRaitBec’s Modding Guide](https://www.nexusmods.com/fallout4/mods/23556?tab=description).  
Manually download the **WorkBase** file.  
Manually download the **Main Repack** files (Part One, Part Two, and Part Three).  
  
Extract the WorkBase file with 7zip.  
You should have three folders inside of Workbase: OriginalBa2, PatchedBa2, and PatchedFiles.  
Navigate to your Fallout4/Data folder and **copy** these 15 files:  

'Fallout4 - Textures1.ba2'  
'Fallout4 - Textures2.ba2'  
'Fallout4 - Textures3.ba2'  
'Fallout4 - Textures4.ba2'  
'Fallout4 - Textures5.ba2'  
'Fallout4 - Textures6.ba2'  
'Fallout4 - Textures7.ba2'  
'Fallout4 - Textures8.ba2'  
'Fallout4 - Textures9.ba2'  
'DLCworkshop01 - Textures.ba2'  
'DLCworkshop02 - Textures.ba2'  
'DLCworkshop03 - Textures.ba2'  
'DLCRobot - Textures.ba2'  
'DLCCoast - Textures.ba2'  
'DLCNukaWorld - Textures.ba2'  

**Paste** these files into your **WorkBase/OriginalBa2** folder.
**Extract** Main Repack Part One into a new folder.
Inside the new folder, you should see another folder called “**textures**”. **Cut** this textures folder and **paste** it into **Workbase/PatchedFiles**.
**Repeat the previous two steps** for Part Two and Part Three of the Main Repack archives.
Run the **installer.bat** file inside of WorkBase.
When it is done, you'll see 15 new files inside of the `PatchedBA2s` folder. Cut or copy these archives. Navigate to your Magnum Opus mods folder and find the Workbase folder (`Magnum Opus/mods/[NoDelete] Workbase Optimized Textures`). Paste the archives into here.
  
After all of these steps are complete, you may delete the WorkBase folder. If you have the space, I advise making a backup of both the vanilla ba2 files as well as the patched ba2 files. It will save you the trouble of having to redownload them again later.

Launch Mod Organizer 2, and activate the `[NoDelete] Workbase Optimized Textures` mod.

Your PatchedBA2 files should match these sizes:  
![alt text](https://raw.githubusercontent.com/LivelyDismay/Learn-To-Mod/main/images/workbase%20file%20sizes.png)

## Noteworthy Mods

### Sim Settlements 2

Rebuild the Commonwealth with a mysterious stranger in a brand new, fully voiced, and - quite frankly - absolutely amazing questline in this highly anticipated sequel-of-sorts to the original Sim Settlements. 

Read more about it [here](https://www.nexusmods.com/fallout4/mods/47976)!

### Creative Perks Plus

Perk overhaul built on top of another perk overhaul. Fancy!

Read more about it [here](https://www.nexusmods.com/fallout4/mods/49400)!

### Subway Runner

Explore an expansive, deadly metro system that stretches the length of the entire Commonwealth. No quests here, folks; only loot, exploration, death, radiation, and a new way to travel across the city.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/18639)!

### This is Trash - A Scrapping Alternative

I got tired of individually scrapping every single leaf and rubbish pile every time I started a new game, so I took some inspiration from Wabbajack and automated it. Each settlement will now have a trash can next to the workbench. Scrap it and watch as the area is miraculously cleaned of all those stupid looking shrubs and garbage decals.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/42552)!

### Buffout 4

The equivalent of SSE Engine Fixes, Buffout basically makes lists like this possible. Memory patches, achievements enabler, memory leak warnings, and so much more. This is likely the single most important mod in the entire list.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/47359)!

## Creation Club Support

Magnum Opus now has support for some Creation Club mods as of version 3.2 of the modlist. To make use of this, you must follow a few steps:
1. Click the profile dropdown menu at the top left of Mod Organizer 2, and change the active profile to `Magnum Opus - CC Profile`.
2. Launch the game and download your CC mods from the in-game storefront.
  -  I recommend doing this after launching the game from Mod Organizer 2. This will make all the creations download into your `overwrite` folder, which will make the next step a bit easier.
3. Cut and paste all of your CC mods into `Magnum Opus\mods\Creation Club Content`. 
4. Activate the `Creation Club Content` mod in Mod Organizer 2.
  -  Please take note that you will need all of the CC mods I currently provide support for.

<details>
  
  <summary>Click this to expand the list of supported Creation Club mods</summary>
  
  * Anti-Material Rifle  
  * CR-74L Combat Rifle  
  * Arcade Workshop Pack  
  * Capital Wasteland Mercenaries  
  * Charlestown Condo  
  * Captain Cosmos  
  * Chinese Stealth Armor  
  * Doom BFG  
  * Doom Marine Armor  
  * Fantasy Hero Set  
  * Graphic T-Shirt Pack  
  * Gunners vs Minutemen  
  * Handmade Shotgun  
  * Heavy Incinerator  
  * Hellfire Power Armor  
  * Horse Power Armor  
  * Manwell Rifle Set  
  * Modular Military Backpack  
  * Morgan's Space Suit  
  * Neon Flats  
  * Noir Penthouse  
  * Nuka-Cola Collector Workshop  
  * Pint-Sized Slasher   
  * Prototype Gauss Rifle  
  * Quake Thunderbolt  
  * Sentinel Control System Companion  
  * Settlement Ambush Kit  
  * Shroud Manor  
  * Solar Cannon  
  * Tesla Cannon  
  * TransDOGrifier  
  * Tunnel Snakes Rule  
  * Virtual Workshop: Atomic Crater  
  * Virtual Workshop: Desert Island  
  * Virtual Workshop: GNR  
  * Virtual Workshop: Grid World  
  * X-02 Power Armor  
  * Zetan Arsenal  
  
</details>

Pipboy Paint Jobs and Power Armor Paint Jobs are **NOT** supported.

If you have a Missing Masters warning in Mod Organizer 2 after following this set of instructions for the Creation Club profile, then there are CC mods in this list you don't have.

If you have CC mods that aren't in this list, that means I don't own them (yet?), so I cannot provide support. I'm doing my best here, please bear with me.

You may also notice some other mods are deactivated in the CC Profile - namely, some armors, power armors, and weapons. This is because some CC mods act as pseudo variants of these, and I didn't want "doubles" essentially.

## In-Game MCM Options

*_Note: Anything involving hotkeys can be set up however you like. These are simply the way I have them set up for myself._

Baka Wait Anywhere  
![alt text](https://i.imgur.com/EGePAFk.png)

Companion Command Hotkeys  
![alt text](https://i.imgur.com/QMQqSSu.png)  

Custom Camera - Standard  
![alt text](https://i.imgur.com/UhgV6QN.png)  

Custom Camera - Power Armor  
![alt text](https://i.imgur.com/IwfxTSB.png)  

Custom Camera - Miscellaneous  
![alt text](https://i.imgur.com/ZTexP2Z.png)  

Custom Camera - Features  
![alt text](https://i.imgur.com/PuDef9C.png)  

DLC Timing - Automatron  
![alt text](https://i.imgur.com/gvWlkO6.png)

DLC Timing - Far Harbor  
![alt text](https://i.imgur.com/V8rJPdf.png)

DLC Timing - Nuka World  
![alt text](https://i.imgur.com/4zY7zCG.png)

DLC Timing - Vault-Tec Workshop  
![alt text](https://i.imgur.com/wVaClh8.png)

FallUI - Coloring  
![alt text](https://i.imgur.com/liVn6zL.png)

FallUI - Text Style  
![alt text](https://i.imgur.com/Z6e5BBg.png)

FallUI Workbench - Generic Settings  
![alt text](https://i.imgur.com/FfZ7WHC.png)

FallUI Workbench - Workbench List  
![alt text](https://i.imgur.com/hS3nr3Z.png)

Faster Workshop Hotkey  
![alt text](https://i.imgur.com/kkgYNFT.png)  

QuickTrade  
![alt text](https://i.imgur.com/KeyaCf5.png)

Sim Settlements 2 - Respect Build Limit - Off  
![alt text](https://i.imgur.com/nTuRz20.png)

Some people have reported Cinematic Mode does not allow city plans to build themselves. You may wish to disable that option as well.

Workshop Framework  
![alt text](https://i.imgur.com/QVjhlRd.png)  

Workshop Plus - Options - Disable Clear Weather.  
![alt text](https://i.imgur.com/BGZnDBG.png)  

Workshop Plus - Hotkeys  
![alt text](https://i.imgur.com/aklZPWs.png)

You and What Army - BOS  
![alt text](https://i.imgur.com/SMYUY4x.png)

You and What Army - Railroad  
![alt text](https://i.imgur.com/2CNBPVY.png)

You and What Army - Institute  
![alt text](https://i.imgur.com/fJquOpK.png)

**Holotape Settings:**   
Open the Beantown Interiors Holotape in your Pipboy and select the following options:  

  *  Customize Options  
  *  Other Options  
  *  Mod Compatibility  
  *  Enable Inside Jobs

True Storms Configuration Holotape  
![alt text](https://i.imgur.com/cOjL4z2.png)

That's it! Have fun!  

## FAQ

- Some of my perk chart icons are way off-center.

  - I know. I don't know how to fix it because I don't know how to use flash or jpexs. You can either accept this visual issue or you can...play something else. Sorry, I like the perks and the minor visual issues don't bother me.


- I am having random crashes.

  - Check Magnum Opus' Mod Organizer 2. Look at the top right corner for a red triangle with a yellow number. Click it. If one of the warnings says "incompatible plugins" and spits out an error about Buffout 4, then you're missing the memory patch. This can happen in some cases. Reinstall VCRedit, re-copy Game Folder Files, launch the game through MO2 once, and close it again. The warning should now be gone, Buffout should be loaded properly, and you can go on with your day.
  - Another common cause for this is faulty Workbase files. Go back and verify the sizes of yours match the image above. If not, redo the Workbase steps.


- Is Creation Club content compatible?

  - Some. Please see the [Creation Club Support](#creation-club-support) section above for details.


- Can I add more mods or remove some mods I don't want?

  - Can you? Yes. Will I help you? Maybe, but **please discuss it in either general channels or my personal Discord server**, and be sure to disclose the fact that you've edited the list before reporting any bugs or crashes. If you're open and honest with me, I'm honestly much more willing to help you through your issues.


- Why is my crosshair on my pipboy?

  - You can turn the Power Armor HUD Switcher holotape setting for [Hide Hud in Pipboy] to Off in order to hide the crosshair when not in power armor, but this also makes the pipboy look pretty terrible when using it inside power armor. Your call.


- Why can't I use multiple companions/why can't I use Dogmeat with a vanilla companion?

  - One follower is enough, and Heather (a modded follower from [here](https://www.nexusmods.com/fallout4/mods/23273)) doesn't occupy a "follower" slot, so you can have Heather + one other companion. Considering how overpowered that is, there is no reason I should add Dogmeat to the mix as well.


- I've been following along your [amazing and wonderful modding tutorials](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/Main.md) and they're great! But my added mods are breaking precombines/previs/making shit flicker in and out of existence a lot. What the hell, man?

  - Load your mods ABOVE all the `* Previs.esp` files in the load order.


- I've been following along your [totally shitty modding tutorials](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/Main.md) and they suck! My game keeps crashing when I add stuff after following your instructions! What the hell, man?

  - That sucks. Post in general-f4-discussions in the Wabbajack server, or any channel my personal discord server. If you're not a dick, I'm genuinely more than happy to help if I can.

## Controller Support

If you're playing with a controller (why?), your pipboy map won't work. Open the MO2 INI Editor, select fallout4prefs.ini, and scroll down until you see the `[Display]` section. At the bottom, you'll find two lines:  
`uPipboyTargetHeight=1400`  
`uPipboyTargetWidth=1752`  
Change these two lines to the following:  
`uPipboyTargetHeight=700`  
`uPipboyTargetWidth=876`  
Then find the `[General]` section and change `bGamepadEnable=` from a `0` to a `1`.

### ENB

I don't use an ENB. I never saw the need. The ENB binaries are present for other purposes. If you wish to add an ENB preset, go for it, but I will provide zero support for such endeavors.

## Widescreen Support

I don't own a widescreen monitor, so I can't help directly. I don't mind you guys helping each other though, obviously. A generous discord user by the name of bjdripley wrote an [Ultrawide Compatibility Guide for Magnum Opus](https://docs.google.com/document/d/1EbZ_DpyhctsrpBlylDYc2TXtm1NAOjkcYjRCNZsC958/edit) that you may find useful.

## Credits and Thanks

- Erri120, for all of your work on Wabbajack and the website, and for making a readme template like this easy for an idiot like me to use.
- AUGSpeed, for being a great source of information. I really look up to you, I respect the hell out of your work, and you're somehow the nicest damn dude on the planet.
- Kaethela, for all of your ongoing support - both in regards to the modlist and listening to my endless bitching.
- Total, for your multiple contributions and advice over the last year and a half (and counting).
- Halgari, creator of Wabbajack, without whom none of us would be here. You have improved over 100,000 people's lives and never asked for a single thing in return. That's *insane*.

## Contact

I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack) and [my own personal Discord Server](https://discord.gg/yABEjwB).
