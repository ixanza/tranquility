# Serenity

- [Serenity](#serenity)
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
    - [Getting an ENB](#getting-an-enb)
- [Updating](#updating)
- [In Game MCM Options](#in-game-mcm-options)
- [Creating your Character](#creating-your-character)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
  - [Tweaking Performance](#tweaking-performance)
    - [Tweaking the ENB](#tweaking-the-enb)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Preamble

![serenity-banner](cover/Cover.png)

Serenity is my goal of having a barebones Requiem experience in Skyrim Special Edition. The aim is to provide the feeling of requiem with the stability of Skyrim Special Edition as well as a slew of bug fixes, graphical improvements and Legacy of the Dragonborn integration. This is an ongoing project and changes will definitely be made along the way but the aim is to not stray away from the core Requiem experience. 

Serenity uses the Loverslab 3.4 Requiem conversion and has some armor mods supported by the Requiem Out-fitted mod and contains DLC sized mods which are 
  - Wyrmstooth (with requiem patch from lilmoefow)
  - Vigilant (with requiem patch from lilmoefow)
  - Dragonborn (via Fozar's Dragonborn Patch)
  - Legacy of the Dragonborn (with requiem patch from lilmoefow)

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Click on _High_
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Let's get to the actual installation. Grab the latest release of Serenity from [the release tab](https://github.com/ixanza/serenity/releases).

Download the release to a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack
2. Load the Modlist from Disk
3. Adjust the download and installation paths
4. Click the Go/Begin button
5. Wait for Wabbajack to finish

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Copy Game Folder Files

Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and copy `d3d11.dll` and `d3dcompiler_46e.dll` to your game folder.

Copy the all of the files from the `MO2/Game Folder Files` directory into your game folder.

#### Getting an ENB

This list uses Cathedral Weathers so you want to get an ENB that is compatible. Here is a list of compatible ENBs that I can recommend
- [Ljoss](https://www.nexusmods.com/skyrimspecialedition/mods/30971)
- [Soul Spectrum](https://www.nexusmods.com/skyrimspecialedition/mods/29675)
- [Semirealis](https://www.nexusmods.com/skyrimspecialedition/mods/25163)
- [Silent Horizons](https://www.nexusmods.com/skyrimspecialedition/mods/21543)
- [SkyrimSE Re-Engaged ENB](https://www.nexusmods.com/skyrimspecialedition/mods/1089)
- [NVT](https://www.nexusmods.com/skyrimspecialedition/mods/11203)

Once you found a preset you like. Download it and extract the enbseries folder, enbseries.ini and enblocal.ini to your Skyrim Special Edition directory. 

**Note : Please check that vsync is set to disable in enblocal.ini otherwise you will be stuck compiling shaders**

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## In-Game MCM Options
Once the game has loaded. Wait until there are no more messages on the top left corner. Then you can hit escape and click on Mod Configuration to continue this section.

#### A Matter of Time
- Presets :
  - Load user settings

#### Cathedral Weather
- Settings → General :
  - Configuration Spell: Disabled
- Settings → Weather :
  - Seasonal Perspective: Enabled

#### Follower Framework
 - System → Save/Load Configuration : 
  - Load from File : Click

#### LOTD Settings
- LOTD Settings → General → Shippment Crate Locations : 
  - Carriages: Enabled
  - Inns: Enabled
  - Player Houses: Enabled

#### Quick Light
- Quick Light → Brightness :
  - Brightness - Bright

#### SkyUI
- General → Item List :
  - Font Size : Small
  - Category Icon Theme : CELTIC
- Advanced → SWF Version Checking : 
  - Map Menu : Disabled
  - Favorites Menu : Disabled
  - Inventory Menu : Disabled
  - Barter Menu : Disabled
  - Container Menu : Disabled
  - Crafting Menu : Disabled

#### Storm Lightning
- Preset → Load Preset : 
  - Realistic : Enabled
- Settings → Fork Lightning : 
  - Minimum Fork Distance : 1

#### VioLens
- Profile System → Menu Settings : 
  - Load : SERENITY
  
## Creating your Character

Simply step up to the statue of mara and choose a start.

## FAQ

### Ultrawide Options
If you have an ultrawide monitor (21:9), the UI will be off. You will want to reinstall Dear Diary with the widescreen option. Pick any options on the FOMOD you want but ensure Extended UI, More Informative Console and Morehud is ticked

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- lilmoefow - for the requiem patches over on the requiem discord
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/ixanza/xanzas_lotd/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
