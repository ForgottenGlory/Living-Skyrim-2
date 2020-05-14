# Living Skyrim
Current version: 5/15/2020 2.0.0 Alpha 1

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Preface](#preface)
  - [Warnings/Disclaimers](#warningsdisclaimers)
  - [System Specifications](#system-specifications)
  - [Important Links](#important-links)
    - [Screenshots](#screenshots)
    - [Videos](#videos)
- [Pre-Installation](#pre-installation)
  - [Skyrim Setup](#skyrim-setup)
  - [Steam Setup](#steam-setup)
  - [Launching Skyrim](#launching-skyrim)
  - [Wabbajack Preparations](#wabbajack-preparations)
- [Wabbajack Installation](#wabbajack-installation)
  - [With Nexus Premium](#with-nexus-premium)
  - [Without Nexus Premium](#without-nexus-premium)
- [Post-Wabbajack Install](#post-wabbajack-install)
  - [Game Folder Files](#game-folder-files)
  - [Mod Organizer 2](#mod-organizer-2)
    - [Configuration-Specific](#configuration-specific)
  - [ENB](#enb)
- [Updating Living Skyrim](#updating-living-skyrim)
- [Important Mods You Need to Know About](#important-mods-you-need-to-know-about)
  - [The Population Mods wip needs rewrite](#the-population-mods-wip-needs-rewrite)
  - [The Quest Mods wip](#the-quest-mods-wip)
  - [Master of Disguise](#master-of-disguise)
  - [Sustained Magic](#sustained-magic)
  - [Archery Gameplay Overhaul](#archery-gameplay-overhaul)
  - [Inez wip](#inez-wip)
  - [Vitality Mode wip](#vitality-mode-wip)
  - [Immersive Spell Learning](#immersive-spell-learning)
  - [The HUD Mods](#the-hud-mods)
  - [Nether's Follower Framework](#nethers-follower-framework)
- [Launching Living Skyrim](#launching-living-skyrim)
  - [The MCM Settings](#the-mcm-settings)
  - [Final Thoughts & Best Practices](#final-thoughts--best-practices)
    - [Getting Started in Living Skyrim](#getting-started-in-living-skyrim)
    - [NeverNude?](#nevernude)
- [Credits & Thanks](#credits--thanks)

## Preface
The Living Skyrim Modlist focuses heavily on adding highly interactive content. New questlines and world spaces are given high priority as well as mods that add NPCs, followers, and things to do. Some prominent examples are Interesting NPCs, Immersive Creatures, Legacy of the Dragonborn V5, VIGILANT, Falskaar, Animallica, and more. The core idea of Living Skyrim is to make the world feel full of life and activity in almost every area, whether it's a bandit patrol from OBIS or a conversation overheard between NPCs provided by Realistic Conversations. It is designed as a complete overhaul and expansion to many of the systems present in the game. It is aimed at providing a lore-friendly experience that enhances the core game rather than adding tedium and monotony to the game. Some mods are avoided intentionally so that unnecessary systems that slow down the game aren't included. The few inclusions that do slow things down are included for balance and pacing reasons.  

Additionally, Living Skyrim is intended to provide replayability and roleplay potential. Classic Classes & Birthsigns, Ordinator, and other related mods allow for nearly infinite character customization to play the character you want, whether it be raving barbarian, paladin of Akatosh, archmage of Winterhold, or a hunter in the woods. The Take Notes mod allows you to chronicle your adventures and build a story that is uniquely yours. Sharing your stories with others is welcome and would be amazing to see.  

All of this is on top of a high-quality graphics package intended for higher-end PCs. 4K textures and 2K normals have been given preference except in situations where there is little to no noticeable difference or a 4K option isn’t available. The ENB, Weather, and Flora/Fauna package are intended to ensure that your lighting, effects, and landscape are the highest quality possible without causing your computer to explode. See System Specifications for more details of a reasonable computer that can run this list consistently at 60 FPS.  

As for stability and conflict resolution, Living Skyrim includes a number of patches, fixes, and compatibility resolutions including Bash and Smash Patches. Custom patches have also been created for certain awkward interactions between some mods (most notably, Awakened Magicka, Invested Magicka, and Ordinator.) It also includes DynDOLOD, TexGen, and SSELODGEN data pre-packaged for ease of install.  

Lastly, Living Skyrim exists solely as a Wabbajack installer. A manual installation guide is not planned.

### Warnings/Disclaimers
Wabbajack no longer requires that you have Nexus Premium to install the modlist, however, having Nexus Premium will cut your install time to a fraction of what it would be instead of downloading each mod individually (and save you a thousand clicks or so).  

As of v2.0.0, the modlist requires ~273GB (85GB Downloads/187GB Mods) of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing onto an SSD/NVMe is not required, but **strongly recommended**. Download and installation times vary based on your computer and internet speeds but expect the entire process to take a few of hours.

**NSFW Warning:** By default this modlist contains nude models for male and female NPCs. See the NeverNude section of this readme if you want to switch to NeverNude.

Support is **not** provided for adding to or changing the list in *any way*. If you’re uncertain of how to use xEdit at a minimum, making any changes at all is a great way to have a **Bad Time™**.

### System Specifications
Living Skyrim v2.0.0 is brutal on computers. Almost every texture is 4K and the ENB you choose can cause *drastic* impacts on your performance. The following is the computer Living Skyrim was compiled and tested on and it averaged 30-40FPS in exteriors with ENB enabled and 40-50FPS in interiors. Without ENB, it averaged 40-50FPS in exteriors and 50-60FPS in interiors.

- CPU: Intel i5-8600K Overclocked to 4.2GHz 
- RAM: 16GB (16299MB actual)
- GPU: nVidia GTX 1070 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz

Skyrim is very heavy on processors. Generally, anything above 3GHz should be fine but I can’t guarantee it. 

**Important!: 2/4GB graphics cards will severely struggle to run Living Skyrim. You will likely get 10-20FPS everywhere, possibly less. Support is not provided for improving your performance. You'll have to test things on your own to see if performance can be improved.** 6GB of VRAM is the *absolute, no questions asked minimum requirement* to run Living Skyrim at any sort of playable framerate.

And before you ask: No, a less intense version of Living Skyrim is not planned.

### Important Links
[The Modlist Spreadsheet](https://docs.google.com/spreadsheets/d/1sKG690CbutxCFhDLfTH7C6yYCz0dOkZkuKfYAqRBRVU/edit?usp=sharing)  
[Living Skyrim FAQ](FAQ.md)  
[Living Skyrim Bug & Suggestions Tracker](https://github.com/ForgottenGlory/Living-Skyrim/issues)  
[User Testimonials](https://drive.google.com/open?id=1eXeG852teL9EOnIHTAFTLW4Rq1c_pYGRYPtW_eNJqLg)  
[Living Skyrim Discord](https://discord.gg/9dFvGnc)  
[Living Skyrim Patreon](https://www.patreon.com/LivingSkyrim)

#### Screenshots
Need screenshots of LS2 cuz it's different

#### Videos
[Leora Allavi (full roleplay playlist, v1.6.x)](https://www.youtube.com/watch?v=J2z0dHdK7GM&list=PL-faYc4gzQfCvfu0EBCDK_WmOrhGcVeYs) 

## Pre-Installation
### Skyrim Setup
As with any modlist, it is strongly recommended that you start with a clean, unmodified installation of Skyrim: Special Edition. To get your Skyrim SE to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall). 
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Properties… > Local Files > Browse Local Files…), delete them.
3. Install Skyrim: Special Edition.

### Steam Setup
1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties... > General > Enable the Steam Overlay while in-game checkbox)
   
### Launching Skyrim
Launch Skyrim SE to create any INI or registry entries the game needs. Immediately exit after the launcher has successfully selected a graphics preset for your hardware. The INIs will be overwritten by the ones included in the Wabbajack installer.

### Wabbajack Preparations
1. Download the latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases). Do not run anything until instructed to do so.
2. Create a new folder in the root of the drive where you want Wabbajack to be installed. (C:\ will be used as an example, but it can be placed in any drive.) Name this folder “Wabbajack”. **Important!:** Wabbajack must be placed in a separate folder from where the installation will occur. 
3. Create a second folder called C:\Living Skyrim. This folder is where everything will be installed. 
4.  Ensure that C:\Living Skyrim is **completely empty.**
5.  Ensure that Wabbajack.exe is in C:\Wabbajack.

## Wabbajack Installation
If you are updating your existing installation of Living Skyrim, skip to [Updating Living Skyrim](#updating-living-skyrim).

1. Run Wabbajack.exe. At the bottom of the window, click Browse Modlists. Select Living Skyrim from the UI and download it.
2. Once downloaded, click the play button in the Living Skyrim panel to begin.
3. Set the Installation Location to C:\Living Skyrim. The download location does not need to be set manually unless you have drive space limitations. Downloading to a separate folder is fine (for example, on a HDD), but as before it is recommended that the actual install be placed on a SSD. **Important!:** Do not install the modlist to your Skyrim SE installation folder OR the folder that Wabbajack.exe is in.
4. Click Run.

### With Nexus Premium
5. Wabbajack will walk you through logging into the Nexus and authorizing an API key so it can download mods if you have not done so previously.
6. Let Wabbajack do its thing. This will take a little while (usually 2-3 hours at most), so go get a snack and read a book for a bit. If you have good enough internet, YouTube is also your friend here. You could also read up on the mods included by checking out the [Important Mods You Need to Know About](#important-mods-you-need-to-know-about) section of this document and the [Modlist Spreadsheet](https://docs.google.com/spreadsheets/d/1sKG690CbutxCFhDLfTH7C6yYCz0dOkZkuKfYAqRBRVU/edit?usp=sharing).

### Without Nexus Premium
5. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take a really long time, possibly more than one day. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Put on some music or a TV show and make a day of it.

Once complete, Wabbajack will say “Installation complete! You may exit the program.” If it does not, visit the [Wabbajack Discord server](https://discord.gg/wabbajack) for assistance. **Don’t forget to upload your log file!**  

If Wabbajack fails to download a particular mod, it means that the mod has likely been updated. This also means that an update to Living Skyrim is imminent. Be patient and wait for the new release. **Do not ask other people to share older files as this is a violation of the Nexus ToS.**  

## Post-Wabbajack Install
### Game Folder Files
Now you have to copy some files to their correct locations. Navigate to C:\Living Skyrim\Game Folder Files. Copy all of the files inside the Game Folder Files folder into [Steam Install Location]\steamapps\common\Skyrim Special Edition\ and Overwrite if prompted.  

### Mod Organizer 2
1. Navigate to C:\Living Skyrim and open ModOrganizer.exe. Your Mod Organizer window will have the Wabbajack theme already selected. If it doesn’t, something has gone wrong and you’ll likely need to do the Wabbajack installation again.
2. A dialogue will appear and ask if you want to associate Mod Organizer with nxm links. Click **Yes.**

#### Configuration-Specific
If you are using a widescreen monitor, make sure to enable Complete Widescreen Fix for SkyUI 5.2 SE in the left pane of MO2. If you are **not** using a widescreen monitor, make sure to **disable** Complete Widescreen Fix for SkyUI 5.2 SE in the left pane of MO2.

### ENB
ENB is not required to run Living Skyrim, but it is intended to be used with it. You may skip these instructions if you don’t want to use ENB. Skipping ENB is *strongly recommended* for weaker computers. 

If you have 6GB of VRAM, it is recommended that you use either the Rudy's ENB or Re-Engaged (Performance) ENB presets. If you have 8GB (or more) of VRAM, it is recommended that you use either the Pinnacle Reality or Silent Horizons ENB presets. However, you are welcome to use any preset you like as long as it is compatible with Obsidian Weathers.

In general, the process to install an ENB preset is:

1. Download the latest ENB Binary from http://enbdev.com/download_mod_tesskyrimse.htm
2. Open the .zip file, go into the WrapperVersion folder, and copy ONLY d3d11.dll and d3dcompiler_46e.dll into your Skyrim SE installation folder. (Usually located at C:\Steam\steamapps\common\Skyrim Special Edition)
3. Download your selected ENB preset. **Important!: Make sure it is compatible with Obsidian Weathers!**
4. Follow any installation instructions included with your Preset. Every ENB has slight variations in their requirements, so make sure to follow the instructions included for that preset. **You should not need to download any additional files other than the preset. Things like ENB Helper and Particle Patch are already included!**

## Updating Living Skyrim
If you are updating Living Skyrim, the process is very simple. Before you update, you should at a minimum backup your saves. Updating will delete any saves that are present.

1. Run Wabbajack.exe. At the bottom of the window, click Browse Modlists. Select Living Skyrim from the UI and download it.
2. Once downloaded, click the play/arrow button in the Living Skyrim panel to begin.
3. Set the Installation Location to wherever you already have Living Skyrim installed. **Important!:** Set your downloads folder path to the same downloads folder location you used when you first installed Living Skyrim.
4. Click Run.
5. When prompted if you would like to overwrite the existing installation, click "Confirm."

## Important Mods You Need to Know About
This section details the most asked about mods included in Living Skyrim and is intended to give you a basic understanding of what to expect when you start the game.

### The Population Mods wip needs rewrite
Living Skyrim includes a number of mods that increase the population of both creatures and characters in the world. The first and most important one is [Populated Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/5017). This mod adds well over 100 new NPCs to locations throughout the world: cities, dungeons, caves, etc. Next is [OBIS](https://www.nexusmods.com/skyrimspecialedition/mods/4145), which adds a ton of mid to high-level bandits to the world. Also for your consideration: [Immersive World Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/18330), [Immersive Patrols](https://www.nexusmods.com/skyrimspecialedition/mods/718), and [Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194). For creatures, you'll find [SkyTEST](https://www.nexusmods.com/skyrimspecialedition/mods/1104), [Skyrim Immersive Creatures](https://www.nexusmods.com/skyrimspecialedition/mods/12680), and [Animallica](https://www.nexusmods.com/skyrimspecialedition/mods/20456).

What does this mean? Well, to put it simply, there are *a lot* of NPCs to find and interact with now. Silent Moons Camp for example now has somewhere in the range of *40, yes, forty* enemies to fight. It is impossible to go more than 5 minutes without coming across an NPC of some kind be it bandits, a patrol, or an animal. Getting a follower or two (or five) is highly encouraged. This also means you will come across enemies that are significantly higher level than you when starting out. Embershard Mine can be about 50% cleared at level 3-5 before encountering *level 30* enemies. You will have to revisit dungeons once you are stronger. The [Take Notes](https://www.nexusmods.com/skyrimspecialedition/mods/13570) mod is included to chronicle your adventure and also to help you remember what places you need to revisit.

### The Quest Mods wip
Not So Fast, good guys, etc

### Master of Disguise
[Master of Disguise](https://www.nexusmods.com/skyrimspecialedition/mods/9959) is a very simple mod: If you dress like a faction, you will be treated as that faction. So, if you dress as a necromancer, you will be attacked as if you are a necromancer by guards, soldiers, townsfolk, and so on. Be careful what you wear! This also allows you to infiltrate enemy factions if you dress carefully, but beware: they have a chance to see through your disguise and figure out you're an imposter.

### Sustained Magic
[Sustained Magic](https://www.nexusmods.com/skyrimspecialedition/mods/15871) is another simple mod, with much larger gameplay consequences. Certain spells, such as Oakflesh, now last forever instead of having to recast them every 60-90 seconds. This does come at the cost of reducing your maximum available Magicka, so be careful how many spells you have sustained or you'll very quickly find yourself with near zero Magicka to use for spells like Flames. To dispel the effects of a Sustained Magic spell (and therefore recoup your Magicka), either cast the spell again or cast the "Dispel Magic, Personal" spell.

### Archery Gameplay Overhaul
[Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296) completely revamps the archery system in Skyrim. You'll find it now has much more realistic gameplay including arm fatigue, the ability to spread poisons across multiple arrows, stamina drain while the bowstring is pulled, and so on. This mod is highly configurable via its MCM menu, so feel free to tweak it to suit your playstyle.

### Inez wip
Encounter zones mod

### Vitality Mode wip
needs mod

### Immersive Spell Learning
[Immersive Spell Learning](https://www.nexusmods.com/skyrimspecialedition/mods/33375) completely changes how your character learns new spells. Instead of "eating" the book and learning the spell, you now have to spend time studying notes about the spell to learn it over time. The amount of time it takes to learn new spells is completely configurable through this mod's MCM menu, so feel free to tweak it to your liking. This mod's inclusion is intended to help balance magic as the combination of magic mods included in Living Skyrim make magic *significantly* stronger.

### The HUD Mods
Living Skyrim includes a completely different UI and HUD experience than what you're used to, probably even if you've played modded Skyrim before. [SkyHUD](https://www.nexusmods.com/skyrimspecialedition/mods/463) is 100% customizable and has a number of presets available you can choose from to relocate the health/stamina/magicka bars and also relocate any HUD element, such as the stealth indicator. [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246) changes the dialogue menu to be easier to read and use and is also 100% configurable. See the mod description pages for EZ2C and SkyHUD to see how to configure these to your liking. [Immersive HUD](https://www.nexusmods.com/skyrimspecialedition/mods/12440) keeps pesky HUD elements out of the way when you don't need to see them. Lastly, [Favorite Things](https://www.nexusmods.com/skyrimspecialedition/mods/27177) greatly expands the SkyUI Favorites menu to make it larger, easier to use, and more customizable. 

### Nether's Follower Framework
[Nether's Follower Framework](https://www.nexusmods.com/skyrimspecialedition/mods/18076) has too many features to list, but what you need to know is this: You can have multiple followers, you can configure just about anything about them, and you'll have a lot more flexibility with controlling your followers. You can also import followers added by mods to be able to use NFF's features on them. **Important!:** *Do NOT* import standalone followers (Inigo, Lucien, etc.) into Nether's Follower Framework. It will 100% break them. The notable exceptions to this are Auri, Sophia, and any of the Interesting NPCs followers.

## Launching Living Skyrim
The hard part is now over. Carry on, the end is in sight!

1. In Mod Organizer 2, select SKSE from the drop-down menu next to the Run button and click Run. This is how Living Skyrim should always be launched. You can create a shortcut on your desktop if you wish using the Shortcut button under the Run button.
2. Once Skyrim starts, create a new game. **Loading an old save at this point will corrupt that save, do not do this.** 
3. Create your character and name them whatever you’d like.
4. **As soon as you gain control of your character, do nothing.** The mods are loading and this can take a little bit of time. You’ll see a list of mods initializing in the top left of the screen.
5. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

### The MCM Settings
1. If you want the true Living Skyrim experience, consult the [Living Skyrim MCM Configuration](MCM%20Configuration.md) document and follow all listed steps. Note that some settings in this document are required for certain mods to work properly, namely Hunterborn, Lock Overhaul, OBIS, Immersive HUD, and XPMSE.
2. Otherwise, configure the MCMs how you want. Feel free to experiment and turn the difficulty up/down to your preference.
3. Don’t forget to save your game after configuring the MCMs, I promise you don’t want to have to do this step more than once.

### Final Thoughts & Best Practices
- If you are not familiar with the contents of this modlist, links are provided in the [LS2 Spreadsheet](https://docs.google.com/spreadsheets/d/1i31E32PtFQv_soryzrH8dOmk-Yk3n1GZIuQnuFsy2XY/edit?usp=sharing) to every mod so you can review their content/changes.
- Autosaves and Quicksaves are disabled. These save options are known to cause issues with heavily scripted games.Quicksaves are automatically turned into Manual Saves. It is recommended to save **early** and **often**. Every 15 minutes and before interacting with quest NPCs, quest objects, and entering new zones should be sufficient. **Old saves can be deleted, but forgetting to save loses progress forever!**
- Wabbajack supports updating/upgrading over an existing installation, but it will automatically delete any files that aren’t used for the modlist installation. This means if you have changed the modlist in any way, Wabbajack will delete those changes and **may even delete your saves.** Keep backups of any changes you do make (as ill-advised as making changes may be).
- **NEVER** save right after a loading screen. Wait 30 seconds before saving to let scripts finish executing.
- **NEVER** use autosaves. Autosaves are unpredictable at best, and save-corrupting at worst.

#### Getting Started in Living Skyrim
If you're coming from a previous version of Living Skyrim (1.x.x), throw out everything you thought you knew. If you're new to Living Skyrim, welcome! It's gonna be a bumpy ride - at first.

- 

#### NeverNude?
Living Skyrim 2 can be made NeverNude. The first thing you need to do is watch this video by Gopher: https://www.youtube.com/watch?v=Wkwtgp3x25s The video is for Fallout 4, but the process of using BodySlide is exactly the same for Skyrim Special Edition.

Once you've watched that, follow these instructions:
1. Reinstall "Caliente's Beautiful Bodies Enhancer -CBBE-" with "Vanilla Shape" and "NeverNude" options
2. Download this mod https://www.nexusmods.com/skyrimspecialedition/mods/16097 - "Bijin Family Bodyslides - CBBE NeverNude" using MO2
3. Install "Bijin Family Bodyslides - CBBE NeverNude" and select: Bijin NPCs, Bijin Warmaidens, Bijin Wives and Serana and Enable it
4. Open BodySlide, and then rebuild these bodies using your preferred CBBE preset: CBBE NeverNude, Bijin NPCs - Body, Bijin Warmaidens- Body, Bijin Wives - Body and Serana - Body

## Credits & Thanks
- Living Skyrim created by ForgottenGlory
- Living Skyrim 2 Dev Team:
  - Volk
  - Haazen
  - Melisandre
  - JaceVenture
  - Magnus Hellfire
  - Bearnard
- Contributors & Beta Testers:
  - Patchier
  - DwarfDude
  - Qwerrecd
  - Timboman
  - NexxusDrako
  - Total
  - Dispo
  - Dracosaber
  - Sentrus
  - Nechrion
- Halgari & The Wabbajack Team
  - Thank you for creating Wabbajack, you’re amazing!
  - [Halgari’s Patreon](https://www.patreon.com/user?u=11907933)
- Special Thanks
  - The TUCO Modding Team - Their modlist is a great way to get a Vanilla+ experience with a tutorial that is extremely helpful for learning the basics of creating a modlist.
  - DarkLadyLexy - Her LotD list is an invaluable resource not only for an awesome modlist, but also for learning many fundamentals of modding and compiling a modlist.
  - EzioTheDeadPoet - For their SME(FT) modlist. The ability to start from scratch on a whim while building this list has been invaluable.
- Mod Authors
  - None of this would be possible without the people who make the quality content we’ve grown to know and love. Please endorse the authors’ works.
