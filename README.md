**This readme is incomplete and still a work in progress, but it is up to date enough to allow the list to be installed.**


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
  - [The Population Mods](#the-population-mods)
  - [The Quest Mods](#the-quest-mods)
  - [Master of Disguise](#master-of-disguise)
  - [The Magic Mods](#the-magic-mods)
  - [The Combat Mods](#the-combat-mods)
  - [The SkyRem Suite](#the-skyrem-suite)
  - [Vitality Mode](#vitality-mode)
  - [The HUD Mods](#the-hud-mods)
  - [Nether's Follower Framework](#nethers-follower-framework)
- [Launching Living Skyrim](#launching-living-skyrim)
  - [The MCM Settings](#the-mcm-settings)
- [Final Thoughts & Best Practices](#final-thoughts--best-practices)
  - [Getting Started in Living Skyrim](#getting-started-in-living-skyrim)
  - [NeverNude?](#nevernude)
- [Troubleshooting & FAQ](#troubleshooting--faq)
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

### The Population Mods
Living Skyrim includes a number of mods that increase the population of both creatures and characters in the world. The first and most important one is [Genesis](https://www.nexusmods.com/skyrimspecialedition/mods/5033), which replaced Populated Skyrim in Living Skyrim 2.0.0. This mod dynamically spawns more enemies in dungeons and optionally in overworld locations as well. It is customizable with a book that is added to your inventory upon character creation. Be warned: Setting the spawn number too high (above 50) will result in an absolutely absurd number of enemies being added to dungeons. Additionally, if the setting is too high you may experience enemies spawning directly on top of you or in areas you've already cleared out. Be careful when playing with the settings for this mod. A spawn number of 40 is recommended.

Next is [OBIS](https://www.nexusmods.com/skyrimspecialedition/mods/4145), which adds a ton of mid to high-level bandits to the world. In general this covers most of the overworld locations, which is why the surface spawns setting for Genesis is recommended to be turned off.

[Organic Factions](https://www.nexusmods.com/skyrimspecialedition/mods/10289) adds groups of enemies that dynamically expand, recruit, and find new leaders. They will spread to conquer new territory and if left unchecked can take over entire holds. Keep an eye on the notifications for this mod, as it will keep you up to date on who is in control of what regions. You can also stumble across battles between factions if their territories overlap.

Also for your consideration: [Immersive World Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/18330), [Immersive Patrols](https://www.nexusmods.com/skyrimspecialedition/mods/718), and [Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194). For creatures, you'll find [SkyTEST](https://www.nexusmods.com/skyrimspecialedition/mods/1104), [Skyrim Immersive Creatures](https://www.nexusmods.com/skyrimspecialedition/mods/12680), and [Animallica](https://www.nexusmods.com/skyrimspecialedition/mods/20456).

What does this mean? Well, to put it simply, there are *a lot* of NPCs to find and interact with now. Silent Moons Camp for example now has somewhere in the range of 30 enemies to fight. It is impossible to go more than 5 minutes without coming across an NPC of some kind be it bandits, a patrol, or an animal. Getting a follower or two (or five) is highly encouraged. You will have to revisit some dungeons once you are stronger. The [Take Notes](https://www.nexusmods.com/skyrimspecialedition/mods/13570) mod is included to chronicle your adventure and also to help you remember what places you need to revisit.

### The Quest Mods
Very few quests are untouched by Living Skyrim. Whether it's a location revamp like [Bleak Falls Barrow Revisited](https://www.nexusmods.com/skyrimspecialedition/mods/33251), or a modification like [Finding Helgi and Laelette](https://www.nexusmods.com/skyrimspecialedition/mods/28973), it's unlikely you'll play any quest the same as you would in vanilla. This isn't even to mention all of the new quests added by Living Skyrim. See below for a complete list of quest-related changes and the new quests added by this list.

|               Quest Changes              |         New Quests         |
|:----------------------------------------:|:--------------------------:|
| Timing is Everything                     | Helgen Reborn              |
| Not So Fast - Main Quest                 | Legacy of the Dragonborn   |
| Not So Fast - Mage Guild                 | Vigilant SE                |
| Opulent Thieves Guild                    | Moonpath to Elsweyr        |
| The Brotherhood of Old                   | Carved Brink               |
| All Thieves Guild Jobs Concurrently      | The Gray Cowl of Nocturnal |
| Thieves Guild Requirements               | The Falkreath Hauntings    |
| The Paarthurnax Dilemma                  | The Forgotten City         |
| The Choice is Yours                      | Moon and Star              |
| Boethiah for Good Guys                   | Wyrmstooth                 |
| Better College Application               | Clockwork                  |
| Namira for Good Guys                     | Darkend                    |
| The Companions - Don't be a Milk Drinker | Project AHO                |
| House of Horrors Divine Intervention     | Immersive World Encounters |
| Finding Helgi and Laelette               | Missives                   |
| Bounties are Worthwhile                  | Konahrik's Accoutrements   |
| Even Better Quest Objectives             |                            |
| Thieves Guild for Good Guys              |                            |

### Master of Disguise
[Master of Disguise](https://www.nexusmods.com/skyrimspecialedition/mods/9959) is a very simple mod: If you dress like a faction, you will be treated as that faction. So, if you dress as a necromancer, you will be attacked as if you are a necromancer by guards, soldiers, townsfolk, and so on. Be careful what you wear! This also allows you to infiltrate enemy factions if you dress carefully, but beware: they have a chance to see through your disguise and figure out you're an imposter.

### The Magic Mods
[Sustained Magic](https://www.nexusmods.com/skyrimspecialedition/mods/15871) is another simple mod, with much larger gameplay consequences. Certain spells, such as Oakflesh, now last forever instead of having to recast them every 60-90 seconds. This does come at the cost of reducing your maximum available Magicka, so be careful how many spells you have sustained or you'll very quickly find yourself with near zero Magicka to use for spells like Flames. To dispel the effects of a Sustained Magic spell (and therefore recoup your Magicka), either cast the spell again or cast the "Dispel Magic, Personal" spell.

[Immersive Spell Learning](https://www.nexusmods.com/skyrimspecialedition/mods/33375) completely changes how your character learns new spells. Instead of "eating" the book and learning the spell, you now have to spend time studying notes about the spell to learn it over time. The amount of time it takes to learn new spells is completely configurable through this mod's MCM menu, so feel free to tweak it to your liking. This mod's inclusion is intended to help balance magic as the combination of magic mods included in Living Skyrim make magic *significantly* stronger.

[Apocalypse](https://www.nexusmods.com/skyrimspecialedition/mods/1090), [Forgotten Magic](https://www.nexusmods.com/skyrimspecialedition/mods/12711), [Thunderchild](https://www.nexusmods.com/skyrimspecialedition/mods/1460), [Summermyst](https://www.nexusmods.com/skyrimspecialedition/mods/6285), [iUnlock](https://www.nexusmods.com/skyrimspecialedition/mods/35438), and [Wintersun](https://www.nexusmods.com/skyrimspecialedition/mods/22506) are all included to make magic as diverse as possible with a huge breadth of options. It's entirely possible to spend multiple playthroughs exploring all the magic-related playstyles. Wintersun covers the religious aspect of the game, Summermyst covers enchantments, and Thunderchild covers shouts. Apocalypse, Forgotten Magic, and iUnlock all add new spells.

One final special mention: [Glory's Scaling Standing Stones](https://www.nexusmods.com/skyrimspecialedition/mods/35820). This is a custom mod hand-made by yours truly, ForgottenGlory. It is a lightweight overhaul of the standing stone effects and also makes them scale with you. If you are finding the game too difficult when starting out, I highly encourage you to seek out the standing stones - the Warrior, Thief, and Mage stones are particularly strong when starting out. Don't get used to having these bonuses though - they get weaker as you gain levels!

### The Combat Mods
The core combat package of Living Skyrim is [Ultimate Combat](https://www.nexusmods.com/skyrimspecialedition/mods/10289), [Wildcat](https://www.nexusmods.com/skyrimspecialedition/mods/10289), [TK Dodge](https://www.nexusmods.com/skyrimspecialedition/mods/15309), and [VioLens](https://www.nexusmods.com/skyrimspecialedition/mods/668). Assuming a fair fight this generally means that combat will be fast-paced and somewhat deadly. You won't get one-shot unless you're fighting an enemy that is significantly higher level than you (10+ levels above your own).

[Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296) completely revamps the archery system in Skyrim. You'll find it now has much more realistic gameplay including arm fatigue, the ability to spread poisons across multiple arrows, stamina drain while the bowstring is pulled, and so on. This mod is highly configurable via its MCM menu, so feel free to tweak it to suit your playstyle.

Also for your consideration: [SkyTEST](https://www.nexusmods.com/skyrimspecialedition/mods/1104), [Deadly Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/23723), [Skyrim Revamped](https://www.nexusmods.com/skyrimspecialedition/mods/14598), and [Encounter Zones Unlocked](https://www.nexusmods.com/skyrimspecialedition/mods/19608). Enemies in general will be smarter and stronger across the board, and will dynamically update their levels to match you as appropriate.

### The SkyRem Suite
Living Skyrim contains almost the entire lineup of SkyRem, with a couple of exceptions. The entirety of [SkyRem Grace](https://www.nexusmods.com/skyrimspecialedition/mods/26207) is included alongside SkyRem [Inez](https://www.nexusmods.com/skyrimspecialedition/mods/27103), [Eve](https://www.nexusmods.com/skyrimspecialedition/mods/26325), and [Mia](https://www.nexusmods.com/skyrimspecialedition/mods/26272).

Grace is focused entirely on making each character you make unique. You'll get different bonuses based on race, gender, how you assign points in attributes, and even what your character's early life was like. At higher levels, the Cori portion of Grace will allow you to select a class to specialize your character even further. 

Inez changes how encounter zones in the game are calculated, increasing the variety of levels of enemies you'll find. Combined with the aforementioned Genesis and Encounter Zones Unlocked, no dungeon will ever play out the same. Mia is a very simple immersion mod that modifies the text you see when you go to interact with an object. Eve is an economy mod that, when combined with the other economy mods, makes Skyrim's economy incredibly diverse. It will be almost impossible to find the same item for the same price at two vendors.

### Vitality Mode
[Vitality Mode](https://www.nexusmods.com/skyrimspecialedition/mods/16308) is the needs mod of choice for Living Skyrim. It covers all of the basics: hunger, thirst, and fatigue and also covers Werewolf and Vampire needs. It doesn't change how many of the food and drink items work in the game, and also allows you to buy or make water. This mod features an MCM that allows you to completely customize your needs experience or turn it off entirely if you wish.

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
1. If you want the true Living Skyrim experience, consult the [Living Skyrim MCM Configuration](ls2mcm.md) document and follow all listed steps. Note that some settings in this document are required for certain mods to work properly, namely Hunterborn, OBIS, Immersive HUD, and XPMSE, Genesis, and GRACE.
2. Otherwise, configure the MCMs how you want. Feel free to experiment and turn the difficulty up/down to your preference.
3. Don’t forget to save your game after configuring the MCMs, I promise you don’t want to have to do this step more than once.

## Final Thoughts & Best Practices
- If you are not familiar with the contents of this modlist, links are provided in the [LS2 Spreadsheet](https://docs.google.com/spreadsheets/d/1i31E32PtFQv_soryzrH8dOmk-Yk3n1GZIuQnuFsy2XY/edit?usp=sharing) to every mod so you can review their content/changes.
- Autosaves and Quicksaves are disabled. These save options are known to cause issues with heavily scripted games.Quicksaves are automatically turned into Manual Saves. It is recommended to save **early** and **often**. Every 15 minutes and before interacting with quest NPCs, quest objects, and entering new zones should be sufficient. **Old saves can be deleted, but forgetting to save loses progress forever!**
- Wabbajack supports updating/upgrading over an existing installation, but it will automatically delete any files that aren’t used for the modlist installation. This means if you have changed the modlist in any way, Wabbajack will delete those changes and **may even delete your saves.** Keep backups of any changes you do make (as ill-advised as making changes may be).
- **NEVER** save right after a loading screen. Wait 30 seconds before saving to let scripts finish executing.
- **NEVER** use autosaves. Autosaves are unpredictable at best, and save-corrupting at worst.

### Getting Started in Living Skyrim
If you're coming from a previous version of Living Skyrim (1.x.x), throw out everything you thought you knew. If you're new to Living Skyrim, welcome! It's gonna be a bumpy ride - at first.

- 

### NeverNude?
Living Skyrim can be made NeverNude. The first thing you need to do is watch this video by Gopher: https://www.youtube.com/watch?v=Wkwtgp3x25s The video is for Fallout 4, but the process of using BodySlide is exactly the same for Skyrim Special Edition.

Once you've watched that, follow these instructions:
1. Reinstall "Caliente's Beautiful Bodies Enhancer -CBBE-" with "Vanilla Shape" and "NeverNude" options
2. Download this mod https://www.nexusmods.com/skyrimspecialedition/mods/16097 - "Bijin Family Bodyslides - CBBE NeverNude" using MO2
3. Install "Bijin Family Bodyslides - CBBE NeverNude" and select: Bijin NPCs, Bijin Warmaidens, Bijin Wives and Serana and Enable it
4. Open BodySlide, and then rebuild these bodies using your preferred CBBE preset: CBBE NeverNude, Bijin NPCs - Body, Bijin Warmaidens- Body, Bijin Wives - Body and Serana - Body

## Troubleshooting & FAQ
Additions will be made to this FAQ as needed.

**What do/don’t you support?**  
All unmodified Wabbajack installs of Living Skyrim are supported. Pirated copies of Skyrim are illegal and not supported. Any modlist that changes Living Skyrim by adding/removing mods is not supported. Manually installed reproductions of Living Skyrim are not supported (though kudos will be given if you figure it out for yourself.). Re-shade and alternate ENBs are not supported. Mods from LE/Oldrim are not supported and will never be included in Living Skyrim. Converting old saves to Living Skyrim is not supported, only new saves created after Living Skyrim is installed are supported.

**The installer isn’t working, what can I do?**  
The short answer: wait for an update. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Living Skyrim is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

**How often does Living Skyrim update?**  
There’s no set schedule for Living Skyrim updates. If a mod updates and the list requires a revision, I’ll try to get to it as quickly as possible, but I make no promises. Sometimes troubleshooting updates and rebuilding the list can take days. Anytime there is an update, it will be clearly communicated on the Wabbajack Discord server. That being said, as long as nothing else changes, you should be safe to continue playing an existing installation unless there is an update to Skyrim itself. Remember: the point of all modlists is to play the game. If you’re spending more time updating your list than playing, you’re doing it wrong.

**I found a bug! How do I report it?**  
Check the [LS Issues](https://github.com/ForgottenGlory/Living-Skyrim-2/issues). If it’s not already on there, submit a new issue. Be as specific as possible, including screenshots if possible. If it is related to a specific mod, include the name of the mod and the exact steps to reproduce the issue. The best thing you can send for things like incorrect numbers/values or dark face NPCS (if there are any)  is a screenshot of the thing in question selected with the console including the ID of the object/character. Vague reports such as “my game randomly CTDs” will be ignored if they do not include more details.

**Can I play this list on a 75/100/144hz screen?**  
Yes. The SKSE64 Havok Fix is included.

**Is [mod name] included in this list?**  
Probably not. Check the [LS spreadsheet](https://docs.google.com/spreadsheets/d/1i31E32PtFQv_soryzrH8dOmk-Yk3n1GZIuQnuFsy2XY/edit?usp=sharing) to be certain. 

**The modlist updated! Do I have to update and start a new save?**  
If your game is working, you’re not required to update. It’s always recommended though, as updates likely fix bugs, update mods, or add new mods or remove unsatisfactory ones. As for starting a new save, it depends on the version. In general, anything that is an x.x.# update won’t break your save, and is usually just for when a mod updates and the list needs to be recompiled to make it work again. Anything that is an x.#.0 update adds or removes mods, which likely will break your save (unless otherwise specified). Any full version number changes, #.0.0, are major overhauls/rebuilds of the list and are guaranteed to break your save.

**Can my computer run this list? [insert specs]**  
If you have to ask, my guess is probably not. LS2 requires a strong computer to run well. You can reduce some of the demand on your computer by not using ENB, but for the most part computers with 4 or less VRAM are going to be unable to play LS2. PCs with 6GB of VRAM will perform moderately well. To get good performance, you'll need at least 8GB of VRAM on a relatively new graphics card.

**Some Alternate Starts are impossible/OP!**  
Unlikely. Fighting everything isn’t an option in this list, OBIS, Populated Skyrim, and the combat mods make sure of that. Running away is required sometimes. On the flip side, you’ll quickly run into enemies that are stronger than you even with the “OP” starts. Sometimes you’ll need to clear part of a dungeon and then come back to it later when you’re stronger. The Take Notes mod is very helpful for remembering places you need to revisit. If you’re struggling to level up, Missives and just exploring is your friend. Hunting wildlife is also viable. Most of the first few quests of the major factions/guilds are possible early on, but the main quest will likely need to wait until you’ve established yourself somewhat.

**Can I stream/Let’s Play this modlist?**  
Absolutely.

**My equipment animations are broken/weird!**  
First, check to make sure you’ve followed the MCM instructions for XPMSE. This should fix any weirdness (sword on hip but being drawn from back, for example.). If you’ve just equipped a new weapon/shield, the animation to draw it may be weird for a few seconds but it will eventually fix itself. XPMSE and AllGUD need a few seconds to register the new weapon configuration and should fix themselves. This is not a bug, just be patient and the mods will figure it out eventually.

**Master of Disguise asks me to update every time I load the game.**  
Yep, it’s really annoying. You can turn it off in the MCM for Master of Disguise in the Advanced Menu. Turn off the Factions Update Auto Run.

**My game freezes when saving.**  
Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. 

**Can I use this list on an ultrawide monitor?**  
Yes, [Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778) is included by default. Just make sure to enable it.

**What the heck is going on with the dialogue menu?**
It's being modified by [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246/). Check that mod's page for details of how to configure it if it's not to your liking.

**Immersive Spell Learning allows me to still read the spell tome to learn spells instantly!**
Yes, this is a known issue and is somewhat intended. Legacy of the Dragonborn's museum counts spell tomes towards its display count, so rather than have players find/buy two copies of a spell tome (one to learn from and the other to store in the museum), I've opted to allow spell tomes to stay in your inventory. If you don't like having the temptation of "cheating" and don't mind having to hunt down a second copy of the book, you can always enable "Destroy Spell Tomes" in the Immersive Spell Learning MCM.

## Credits & Thanks
- Living Skyrim created by ForgottenGlory
- Living Skyrim 2 Dev Team:
  - Volk
  - Haazen
  - Melisandre
  - JaceVenture
  - Magnus Hellfire
  - Bearnard
  - Volkaru
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
