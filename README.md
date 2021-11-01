# QWEST

![QWEST-banner](https://raw.githubusercontent.com/SovnSkyrim/QWEST/main/QWEST_New.webp)

Wabbajack Modlist Installer by The Animonculory.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

- [Preamble](#preamble)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Graphical Settings](#graphical-settings)
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
    - [Getting an ENB](#getting-an-enb)
    - [Profiles](#Profiles)
- [Updating](#updating)
- [In Game MCM Options](#in-game-mcm-options)
- [How to start playing](#How-to-start-playing)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
  - [Performance stuff](#Performance-stuff)
    - [Tweaking the ENB](#tweaking-the-enb)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Preamble

Designed to be a "Mighty Modlist for Mini Machines", QWEST was born after a few people were talking about how some people they knew couldn't enjoy a modded Skyrim due to the hardware requirements. The list has a graphical suite that improves the visuals whilst also being friendly to users with 2GB of VRAM. If you can run vanilla Skyrim, you should be able to run this. In QWEST, you will find major mods such as Legacy of the Dragonborn, Interesting NPC's, Wyrmstooth, new armors and weapons, new music and reworked weathers and lighting. Do not expect vanilla gameplay. Many aspects have been changed from the original game. There are many more changes which are detailed in the changes to [gameplay file](https://github.com/Althro/QWEST/blob/main/Changes%20to%20Gameplay.md).

**Please read the ReadMe in Full. The installation process is not completed once you have finished the Wabbajack installation.**

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### **Please also make sure to install Microsoft .Net Runtime v5 so that mo2 can launch the list!!! This is a new update and it is most likely that you DO NOT have this yet!** The latest version can be found [here](https://dotnet.microsoft.com/download/dotnet/5.0/runtime), install the desktop x64 version.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language and Windows Region to English

This entire Modlist is in English and 99% of all mods you will find are also in English. Some mods can break when using a non English version of Windows. Ensure that your Windows Regional Format is set to English. 

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

Due to the way QWEST! is setup is setup, I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

### It is *vital* that your Binkw64.dll is unmodified and *not* a replacement from another mod. If you have a version that is not 292KB in size, delete it and verify your game files.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, OneDrive or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

To prepare the download, and make sure Wabbajack doesn't stall on those files; download these 2 mods manually: 
- https://mega.nz/file/4LxGTALK#7I8XPLnIW0PxR_r_nXMP-9ZUnZ16MlFVMdFdgGy-gF0
- https://mega.nz/file/EcJhgKpY#4Q86Rd1hUepjm233r8Q_7x3fTWx9axJN2CUc8FXrBsg

1. Open Wabbajack and click on browse modlists.
2. Download the modlist from the Wabbajack UI.
3. Once the download is done, set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, Desktop. Put it somewhere easy like `C:/Modlists/QWEST`). The downloads path should automatically fill in the installation path.
4. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish.
5. Select the created folder in 4. as your downloads folder. Place the downloaded MEGA files above AS IS in the downloads folder.
6. Click the Go/Begin button
7. Wait for Wabbajack to finish
8. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait until I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Windows is reporting that a virus has been detected**:

Windows 10 has started to auto quarantine the usvfs_proxy_x86.exe file from the latest version of Mod Organizer 2 saying a threat was detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. An example for windows defender can be found [here](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### **For Version 3.8 update: Please also make sure to install Microsoft .Net Runtime v5 so that mo2 can launch the list!!! This is a new update and it is most likely that you DO NOT have this yet!** The latest version can be found [here](https://dotnet.microsoft.com/download/dotnet/5.0/runtime), install the desktop x64 version.

## Game Folder
The installation will create a copy of your Skyrim Special Edition game in Instalation Folder/Game Root. This will then contain all the necessary files such as SKSE, ENB Binaries and mod required dlls such as Engine Fixes. There is no need to copy anything to your Steam version of Skyrim as we will be running SKSE from within this folder to play the game.

## Graphical Settings

If you wish to change your ini settings, which is recommended if you have 2GB of vram, then navigate to BethINI which is located in `QWEST!\Tools` and run the program. Make sure that you select the correct profile you wish to play, these are show here for [EnaiRim](https://prnt.sc/10ha499) and [SimonRim](https://cdn.discordapp.com/attachments/793809552353132566/818888086079012915/Capture.PNG). If one or the other doesn't show properly, use the browse option to manually set it up.

Listed below is some information regarding the presets in BethINI

- BethINI (Low) (locked to 60 FPS):
  - Everywhere (where it got tested): 60FPS

- BethINI (Medium) (locked to 60 FPS): 
  - Outdoors: 30-40 FPS (average 40)
  - Cities: 40-60 FPS (average 50)
  - Indoors: 60FPS

- If you have 8GB RAM and **NO SSD** or if it still has frame drops, then I recommend:
  - Testing:
    - BethINI (Medium) -> BethINI (Poor) and stopping by the preset that has a playable framerate for you.

## Pagefile in prevention of memory crashes

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.
A pagefile is a file on your disk Windows will use when there is not enough RAM available.
Never disable the pagefile - this may lead to various issues on your system, such as this Skyrim crash.

If you've never touched the pagefile, perform the following steps to prevent from memory crashes:
1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.
Otherwise, set a custom size for the drive it's currently on and increase the maximum size to be at least 20GB.

## Getting an ENB

Whilst this list is aimed towards lower end PCs, that does not mean that an ENB is not an option for you. If you have 2GB of vram, it is advised that you test in game first to check your performance and then come back to this section.

This list includes a custom tweaked variation of [Zangdar's Rudy Cathedral](https://www.nexusmods.com/skyrimspecialedition/mods/39113) that was specifically made for this list. To install this ENB, open MO2, navigate in the dropdown menu on the right to select [ENB Manager](https://media.discordapp.net/attachments/897575788411514962/904131143450898472/unknown.png) and press the big run button. A new window will pop up. Ignore the error it gives you. On the left hand side, click the 3 lines to bring up a menu and click on [presets](https://cdn.discordapp.com/attachments/897575788411514962/904131693089271829/unknown.png). You will see a [new page](https://cdn.discordapp.com/attachments/897575788411514962/904132020626681916/unknown.png) with 2 options, Higher End and Lower End. Simply activate the preset of your choosing by clicking on the little switch underneath the preset name- if it is blue, it is active! You can then exit the enb manager. If you wish to change your preset at any time, simply navigate back to the enb manager, open the presets tab, and switch presets accordingly.

On 2GB Cards, the average fps is 30 with the Low End Preset and Medium Bethini Preset. This is very dependent on your PC, however, so your mileage may vary.

## Personalisation

- Survival. Simply turn off SunHelm in the mcm menu. **DO NOT DISABLE IT IN MOD ORGANIZER.** You can also adjust survival control panel mcm to your preferences. If you do not want to bathe, adjust Dirt&Blood in the mcm to your tastes.

- [Unequip Quiver](http://prntscr.com/xb9k5u). Disabled by default, it'll make your Player Character unequip it's ammunition every time you go out of combat if turned on.

- NPC Difficulty. Disabled by default, this will make your experience much more challenging. Ensure you only activate the correct one for your profile (Adamant for Simonrim, Ordinator for Enairim/Default Profile)

- [Quick Loot](https://cdn.discordapp.com/attachments/897575788411514962/904770688718626826/unknown.png). Disabled by default, it adds a little box showing the inventory of whatever container or corpse that you're currently looking at, so you know what's inside without opening it. (It's under the "Quality of Life" Separator in MO2)

- Gamepad Guide. Disabled by default, ask for the Gamepad guide in the community server (not Wabbajack's) if you want the details on how to use a controller with QWEST!

## How to start up QWEST!

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, you will see a dropdown menu on the left that says Qwest!, and you can choose your profile in there (the default profile is Enairim (Qwest!), and there is a Simonrim profile (Qwest!-Simonrim)). For more information on the profiles, see the changes to gameplay page.

After making sure you are using the correct profile of your choosing, there is a  dropdown box on the top right and a big run button next to it. Ensure it is set to "Go on a QWEST!" by selecting it in the dropdown box and then hitting the run button.

Upon pressing New Game, you will spawn in a room and go into character creation. After creating a character, wait until all of the messages in the top left corner of the screen finish loading. Click away any popups (if smoothcam tells you it can't load a preset, that's normal and fine!) Adjust the mcms as described in the In-Game MCM option section. Please note that after creating your character, you cannot change your race or gender midgame- doing so will break things!  

After character creation and MCM setup, you are free to explore the room. Take a look around at the containers and whatever is on the table, they may be useful for your adventures. When you have finished examining the room, talk to the little dragon next to the door to select a start of your choice, then go through the door to begin your QWEST!

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

### **For Version 3.8 update: Please also make sure to install Microsoft .Net Runtime v5 so that mo2 can launch the list!!! This is a new update and it is most likely that you DO NOT have this yet!** The latest version can be found [here](https://dotnet.microsoft.com/download/dotnet/5.0/runtime), install the desktop x64 version.

## In-Game MCM Options

#### AGO
- Settings
  - Enable/Disable
    - Bow Camera : Disabled
    - Bow Crosshair : Disabled
    - Arrow Wounds (Player) : Disabled
    - Arrow Wounds (NPCs) : Disabled
    - Persistant Arrows : Disabled

#### EVG Conditional Idles
- Player 
    - Modesty Male: Disabled
    - Modesty Female: Disabled
- NPC 
    - Modesty Male: Disabled
    - Modesty Female: Disabled

#### Growl Werebeasts (EnaiRim)
- Features
  - Invulnerable During Transformation: Enabled
- If you want to be a Werebear instead:
  - Immersion : Werebear : Enabled

#### Heartbreaker (Optional) 
- Main Settings
    - Learn Spell Power: Enabled

#### I'm Glad You're Here
- Family Settings
    - Spouse Animation Settings → Exit Dialogue: Disabled
    - Children Animation Settings → Exit Dialogue: Disabled
    - Spouse Welcome Home Settings  →  Exit Dialogue: Disable
    - Children Welcome Home Settings  →  Exit Dialogue: Disable
- General Settings
  - Camera Settings → Force View for Children: Disabled
  - Debug Tools → Open Relationship-editor: Set a hotkey of your choice. Sometimes npcs (usually 3dnpcs) get flagged as a spouse when you aren't married to them, and will have spouse dialogue for hugs. Use this hotkey and target the incorrectly flagged npc to set them as a friend if they are not your spouse.
- Follower Settings
  - SG Follower Animation Pool→ Embrace(DAR):Enable
  - Follower Animation Settings → Exit Dialogue: Disabled
  - Pet Settings → Animal Animation: JaySerpa Pet the Dog

#### LOTD Settings
- LOTD Settings → General → Shippment Crate Locations : 
  - Carriages: Enabled
  - Inns: Enabled
  - Player Houses: Enabled
  - A lot of stuff is very nice in LOTD's MCMs, you should check them all just to know what they do, it'll be useful on the long run.

#### SmoothCam
- Presets
  - Load Preset (There are three presets available for you to use. Try them out and see which one you prefer!)

#### Sunhelm
- You can enable this if you wish to play with survival. Once enabled, back out of the mcm menu wait for all of the messages to finish loading, then go back into mcms.
- General Settings
	- Gameplay Options
		- Toggle Raw Meat Damage [unchecked]
		- Toggle Carry Weight Penalty [unchecked]
		- Toggle Fast Travel [Uncheck(Only if you want to fast travel. Leave as is otherwise)]
    
#### Tentapalooza (Survival)
- Set all tents in all tabs as "Rain and Snow" instead of "No Protection"
    
#### The Ultimate Dodge Mod  
 - Here is where you configure which key will allow you to Sneak (or crouch) and which will allow you to Dodge. TUDM hijacks the vanilla sneak key to have no delay or script lag.
   - A Keybinding example would be:
      - Vanilla Sneak key within Options: C
      - Sneak key within TUDM's MCM: Left Control
  - Now your character will roll/sidestep with C and Sneak with Left Control
  - I also would recommend to use sidestep (personal preference)
  - Please Note: 
    - You cannot dodge in the Starting Cell, you need to choose a path first.
    - **The first time you dodge, you'll be stuck in a weird position in the air. Press G (or your dodge swap key) twice to be unstuck.**

- Npc Settings :
  - NPC Dodge AI: Disabled

#### Thieves Guild Requirements
- Misc Options 
  - Load Preset  
Cycle through all the tabs
 - Load Preset again (now it will stick)

#### Wildcat (EnaiRim)
- Disable Injuries: Enabled
- Allow Wildcat to manage difficulty: Enabled

## FAQ

## Removing the Modlist

You can just remove the MO2 folder and be done with it.

## Ultrawide Options

Although I do not see why someone would have such a screen with the targeted minimals of the list, here's a document made by Mantis to help you solve such problems. [Here](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing)

## I have a question/ I found a bug

Please report it in the support channel or in the relevant channel in the community server.

## The dialogue camera makes me sick/I don't like it!
If The dialogue conversation camera (which is Witcher style) isn't your jam or is making you sick, I have a simple fix for you.  

IN MO2, search for [Alternate Conversation Camera Fixed](https://cdn.discordapp.com/attachments/878666145702481930/904765170784550932/unknown.png). Right click it, open in explorer. Navigate through SKSE>Plugins and open the .ini file in there. You will see a setting that says bswitchtarget=1 you can set this to bswitchtarget=0 to make the camera stop switching in dialogue.

## Some hair/facial hair clips!

The clipping is due to High Poly Head and is currently unfixable. 

## First Person animations are weird, how do I fix??

1st person animations are overhauled by [First Person Combat Animations Overhaul 2.0](https://www.nexusmods.com/skyrimspecialedition/mods/45177). You can safely disable this in the MO2 left pane should you wish to.

## What perk does the new weapons use?
- Rapiers get Sword perks
- Pikes get great sword perks
- Halberds get two handed axe perks
- Quarter Staffs get War Hammer perks
- Claws get dagger perks
- Whips get mace perks

## My character T-Poses!

Cap your framerate, either with BethINI, SSE Display Tweaks, or ENB.

## My Legacy of the Dragonborn (LOTD) Quests are not starting up even though I have the number of Relics the Wiki says I need.
The mod [Quest and Reward Delay for LOTD](https://www.nexusmods.com/skyrimspecialedition/mods/44923) changes the requirements for the quests. Please use their new chart to see the requirements for starting the quests

## The game is a bit too dark/I want to change some ENB settings.

Firstly, please calibrate your monitor to ensure your settings are correct. Most monitors are not properly calibrated when they ship from the factory, so it is advised to calibrate them.

[Quick Light](https://www.nexusmods.com/skyrimspecialedition/mods/12633) is also included to facilitate making the game brighter. You can adjust the brightness of this in the MCM menu.

Should you wish to change the ENB follow this:

- When in game, press Shift+Enter to open ENB Menu. In the right tab, called Shader Parameters at the top, select 'ENBEFFECT.FX' You will see different options for every time of day and night, and a separate slider for Interior Brightness. Dont forget to save configuration all the way in the top left.  

## How do I start the main quest?

In order to start the main quest, you will need to visit Helgen and rent a room at the new inn there with the dialogue option "I'd like to stay for a while. (Start Intro (XX gold))". Once you sleep in the room, a familiar scene unfolds before you.....

**IMPORTANT: Please make sure to disable Survival Control Panel's "sleep to level up" feature in it's mcm BEFORE YOU SELECT THAT INNKEEPER DIALOGUE OPTION, and make sure you start the intro during the DAYTIME, not at night!! It will not work otherwise!**

## Creation Club (CC Content) Support?

Not supported.

## I want to support your work!

I would advise you to donate to [Wabbajack](https://www.patreon.com/user/overview?u=11907933) first, but if you wish to support me you can do so [here](https://www.patreon.com/Althro).

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Halgari and everyone in the WJ Team - Wabbajack is awesome and so are you
- Sovn for the creation of Qwest and allowing the team to take it over. This list would not exist without him intially creating it.
- Mint, Shuckleberry, Chris, Croc and Spaniard for making up the Qwest Team, and all of the wonderful list devs and helpers at the Animonculory.
- zino for testing 2.0 and onwards updates, allowing for accurate feedback on performance for 2GB GPUs.
- My Amazing patrons

## Contact

Whilst I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack) and my server, I would advise checking the [Issues](https://github.com/Althro/QWEST/issues) (open **and** closed ones) on GitHub first if you have any problems. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS**.

## Contributing

See [Contributing](https://github.com/Althro/QWEST/blob/main/Contributing.md).

## Changelog

See [Changelog](https://github.com/Althro/QWEST/blob/main/Changelog.md).
