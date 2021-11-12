# QWEST

![QWEST-banner](https://raw.githubusercontent.com/SovnSkyrim/QWEST/main/QWEST_New.webp)

Wabbajack Modlist Installer by The Animonculory.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
- [Preamble](#preamble)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
  - [Wabbajack Installation](#wabbajack-installation)
    - [Installing Wabbajack](#installing-wabbajack)
    - [Downloading and Installing Tinvaak](#downloading-and-installing-tinvaak)
    - [Problems with installation](#problems-with-installation)
   - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [Pagefile](#pagefile)
    - [ENB](#enb)
    - [Personalisation](#personalisation)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
- [Updating QWEST!](#updating-the-modlist)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)

# Preamble

Designed to be a "Mighty Modlist for Mini Machines", QWEST was born after a few people were talking about how some people they knew couldn't enjoy a modded Skyrim due to the hardware requirements. The list has a graphical suite that improves the visuals whilst also being friendly to users with 2GB of VRAM. If you can run vanilla Skyrim, you should be able to run this. 

In QWEST, you will find major mods such as Legacy of the Dragonborn, Interesting NPC's, Wyrmstooth, new armors and weapons, new music and reworked weathers and lighting. Do not expect vanilla gameplay. Many aspects have been changed from the original game. There are many more changes which are detailed in the changes to [gameplay file](https://github.com/Althro/QWEST/blob/main/Changes%20to%20Gameplay.md).

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## Installation

Installing QWEST! is relatively easy and, if you have nexus premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing QWEST!, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside /Documents/My Games/.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like C:\Games is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. Use the [Downgrade Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/57618) to downgrade your Skyrim SE. **QWEST DOES NOT WORK WITH ANNIVERSARY EDITION**

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Tinvaak

Downloading and installing QWEST! can take a while depending on your internet connection and computer. To install Tinvaak, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on QWEST! and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\QWEST.
4. Press the play button to begin.
5. Go and pet your nearest fluffy animal whilst Wabbajack does its thing.
6. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

	- One file may continually fail is [Elwaps SpeedTree](https://mega.nz/file/xUc0zRLY#NYwbmmHOZhpSF2hpV7hMRYejgZsL_MAIVv_DfjK9JRM). I recommend you download that manually and place it in the same location as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder
QWEST! uses a new Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.

### BethINI

You will need to use BethINI to change your graphical settings depending on your system. If you have 2GB of vram, it is highly recommended that you do this. To configue the settings, complete the followiing steps.

1. Go to where you have installed the list and open the tools folder.
2. Open the BethINI folder and run the program.
3. Select the correct profile you wish to play, [EnaiRim](https://cdn.discordapp.com/attachments/877299353264472084/887463190621986846/unknown.png) or [SimonRim](https://cdn.discordapp.com/attachments/793809552353132566/818888086079012915/Capture.PNG).
4. Follow the information below.

- BethINI (Low) (locked to 60 FPS):
  - Everywhere (where it got tested): 60FPS

- BethINI (Medium) (locked to 60 FPS): 
  - Outdoors: 30-40 FPS (average 40)
  - Cities: 40-60 FPS (average 50)
  - Indoors: 60FPS

If you have 8GB Ram and **NO SSD** or still have frame drops, complete the following.

1. Set BethINI to Medium
2. Gradually cycle down the presets until you achieve your optimum framerate.

### Pagefile

It is recommended that you increase your pagefile to allow Skyrim to function better and prevent crashes. Never disable the pagefile as this can cause issues on your computer. To setup your pagefile, complete the following steps.

1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. Set a custom size for your drive to be minimum 200000 & maximum 200024 [This is equivalent to 20GB]

### ENB

QWEST! comes with an ENB which is designed for the list and lower spec machines. 2GB vram cards normally achieve 30FPS on BethINI medium with the Low end preset, but your milage may vary. To install the ENB, complete the following steps.

1. Open the installation folder and double click on the program called `ModOrganizer.exe`.
2. Navigate in the dropdown menu on the right to select [ENB Manager](https://media.discordapp.net/attachments/897575788411514962/904131143450898472/unknown.png) and press the big run button.
3. Ignore the error it gives you. On the left hand side, click the 3 lines to bring up a menu and click on [presets](https://cdn.discordapp.com/attachments/897575788411514962/904131693089271829/unknown.png).
4. You will see a [new page](https://cdn.discordapp.com/attachments/897575788411514962/904132020626681916/unknown.png) with 2 options, Higher End and Lower End.
5. Activate the preset of your choosing by clicking on the little switch underneath the preset name- if it is blue, it is active!
6. Exit ENB Manager
7. If you wish to change your preset at any time, simply navigate back to the enb manager, open the presets tab, and switch presets accordingly.

### Personalisation

- Survival. Simply turn off SunHelm in the mcm menu. **DO NOT DISABLE IT IN MOD ORGANIZER.** You can also adjust survival control panel mcm to your preferences. If you do not want to bathe, adjust Dirt&Blood in the mcm to your tastes.

- [Unequip Quiver](http://prntscr.com/xb9k5u). Disabled by default, it'll make your Player Character unequip it's ammunition every time you go out of combat if turned on.

- NPC Difficulty. Disabled by default, this will make your experience much more challenging. Ensure you only activate the correct one for your profile (Adamant for Simonrim, Ordinator for Enairim/Default Profile)

- [Quick Loot](https://cdn.discordapp.com/attachments/897575788411514962/904770688718626826/unknown.png). Disabled by default, it adds a little box showing the inventory of whatever container or corpse that you're currently looking at, so you know what's inside without opening it. (It's under the "HUD" or "Quality of Life" Separator in MO2, depending on profile)

- Gamepad Guide. Disabled by default, ask for the Gamepad guide in the community server (not Wabbajack's) if you want the details on how to use a controller with QWEST!

- Alternate Conversation Camera: Can be adjusted/removed. Please see the FAQ section for more info on this!

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. Once launched, ensure that the correct profile you want to play on is selected in the left-hand dropdown box. By default, it will be set to the Enairim Profile (QWEST!), but you can change it to the SimonRim profile (Qwest!-Simonrim) by selecting that one. 

Make sure the dropdown box on the right is set to `"Go on a QWEST!` and press the run button.

Upon pressing `New Game` you will spawn in a room and begin character creation. Ignore the pop-up message. Create you character and then wait for all messages on screen to dissappear. Confirm any pop-up messages and then complete [In-Game MCM options](#in-game-mcm-options).

After character creation and MCM setup, you are free to explore the room. Take a look around at the containers and whatever is on the table, they may be useful for your adventures. When you have finished examining the room, talk to the little dragon next to the door to select a start of your choice, then go through the door to begin your QWEST.

### In-Game MCM options

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

#### True Directional Movement
- Target Lock
  - Toggle Target Lock: Set a hotkey to this if you want to have a target lock in third person!

#### Wildcat (EnaiRim)
- Disable Injuries: Enabled
- Allow Wildcat to manage difficulty: Enabled

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### Ultrawide Options

Although I do not see why someone would have such a screen with the targeted minimals of the list, here's a document made by Mantis to help you solve such problems. [Here](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing)

### I have a question/ I found a bug

Please report it in the support channel or in the relevant channel in the community server.

### The dialogue camera makes me sick/I want to adjust the dialogue camera!
If The dialogue conversation camera (which is Witcher style) isn't your jam or is making you sick, I have a simple fix for you.  

IN MO2, search for [Alternate Conversation Camera Fixed](https://cdn.discordapp.com/attachments/878666145702481930/904765170784550932/unknown.png). Right click it, open in explorer. Navigate through SKSE>Plugins and open the .ini file in there. You will see a setting that says bswitchtarget=1 you can set this to bswitchtarget=0 to make the camera stop switching in dialogue.

There are also other settings in here that you can tweak to your preferences, such as:
- Camera speed if you want to keep the witcher-style camera, but slow it down, perhaps, fcameraspeed=500 is default speed, increase this number to slow it down.
- Forcing third person can be turned off by bforcethirdperson=0
- Enable letterbox if you want it to look cinematic and you don't have enb letterbox on. bletterbox=1

You can also download [Mint's Alt Convo Cam preset](https://drive.google.com/file/d/1gVmpKLtMFcbAuwsqOT-qDbhBPifueZ3O/view?usp=sharing), which slows down the camera, turns off forced third person and enables letterbox, to make talking to Baalgruf feel like a movie scene. Place the .ini file where Alternate Conversation Camera's folder is in MO2, replacing the current .ini in there.

If you just want the vanilla dialogue camera back, you can safely disable Alternate Conversation Camera in MO2.

### Some hair/facial hair clips!

The clipping is due to High Poly Head and is currently unfixable. 

### First Person animations are weird, how do I fix??

1st person animations are overhauled by [First Person Combat Animations Overhaul 2.0](https://www.nexusmods.com/skyrimspecialedition/mods/45177). You can safely disable this in the MO2 left pane should you wish to.

### What perk does the new weapons use?
- Rapiers get Sword perks
- Pikes get great sword perks
- Halberds get two handed axe perks
- Quarter Staffs get War Hammer perks
- Claws get dagger perks
- Whips get mace perks
- Spears get greatsword perks
- Short spears get sword perls

### My character T-Poses!

Cap your framerate, either with BethINI, SSE Display Tweaks, or ENB.

## My Legacy of the Dragonborn (LOTD) Quests are not starting up even though I have the number of Relics the Wiki says I need.
The mod [Quest and Reward Delay for LOTD](https://www.nexusmods.com/skyrimspecialedition/mods/44923) changes the requirements for the quests. Please use their new chart to see the requirements for starting the quests

### The game is a bit too dark/I want to change some ENB settings.

Firstly, please calibrate your monitor to ensure your settings are correct. Most monitors are not properly calibrated when they ship from the factory, so it is advised to calibrate them.

[Quick Light](https://www.nexusmods.com/skyrimspecialedition/mods/12633) is also included to facilitate making the game brighter. You can adjust the brightness of this in the MCM menu.

Should you wish to change the ENB follow this:

- When in game, press Shift+Enter to open ENB Menu. In the right tab, called Shader Parameters at the top, select 'ENBEFFECT.FX' You will see different options for every time of day and night, and a separate slider for Interior Brightness. Dont forget to save configuration all the way in the top left.  

### How do I start the main quest?

In order to start the main quest, you will need to visit Helgen and rent a room at the new inn there with the dialogue option "I'd like to stay for a while. (Start Intro (XX gold))". Once you sleep in the room, a familiar scene unfolds before you.....

**IMPORTANT: Please make sure to disable Survival Control Panel's "sleep to level up" feature in it's mcm BEFORE YOU SELECT THAT INNKEEPER DIALOGUE OPTION, and make sure you start the intro during the DAYTIME, not at night!! It will not work otherwise!**

### Creation Club (CC Content) Support?

Not supported.

### I want to support your work!

I would advise you to donate to [Wabbajack](https://www.patreon.com/user/overview?u=11907933) first, but if you wish to support me you can do so [here](https://www.patreon.com/Althro).

## Removing the Modlist

You can just remove the MO2 folder and be done with it.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Halgari and everyone in the WJ Team - Wabbajack is awesome and so are you
- Sovn for the creation of Qwest and allowing the team to take it over. This list would not exist without him intially creating it.
- Mint, Shuckleberry, Chris, Croc and Spaniard for making up the Qwest Team, and all of the wonderful list devs and helpers at the Animonculory.
- zino for testing 2.0 and onwards updates, allowing for accurate feedback on performance for 2GB GPUs.
- My Amazing patrons

## Contact

Whilst I am available primarily on my server and the [Wabbajack Discord](https://discord.gg/wabbajack), please check the [issues](https://github.com/Althro/QWEST/issues) tab on github first if you have any issues. DO NOT DM ME ON DISCORD.

You are welcome to [contribute](https://github.com/Althro/QWEST/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/Althro/QWEST/blob/main/Changelog.md) before you do.
