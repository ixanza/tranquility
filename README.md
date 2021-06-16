# Tranquillity

![build-status](https://img.shields.io/endpoint?label=%20Status&style=for-the-badge&url=https%3A%2F%2Fbuild.wabbajack.org%2Flists%2Fstatus%2FTranquility%2Fbadge.json)

- [Tranquillity](#tranquillity)
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behaviour](#change-steams-update-behaviour)
      - [Set the Game language to English](#set-the-game-language-to-english)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [ENB](#enb)
  - [The video game has been modified](#the-video-game-has-been-modified)
  - [How to start up Tranquillity](#how-to-start-up-tranquillity)
  - [Updating](#updating)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
    - [Optional Survival Config](#optional-survival-config)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Zoomed in Display](#zoomed-in-display)
    - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

## Preamble

Tranquillity is a Skyrim SE modlist thats aimed at people looking for long lasting, and harder gameplay from traditional Skyrim. It uses several overhauls like Ordinator, Morrowloot, Skyrim Revamped to enhance roleplayability as well as provide a sufficient difficulty increase. Tranquillity is also built around Legacy of the Dragonborn, offering over 20 patches for the mod to fulfil your hoarding desires.

## System Requirements

Download Size: 102GB
Install Size: 129GB

Tranquillity is a mid to high end list in terms of graphics. A minimum of 6GB VRAM is required to play smoothly (60fps) on 1080p and 8GB VRAM to play smoothly (60fps) on 1440p

I made this list with my specs in mind and I am able to get 60FPS (capped so my GPU doesn't work harder than it needs to) in Riverwood and Whiterun outdoors with Rudy ENB for Cathedral Weathers with these specs

- CPU: Ryzen 7 3700x
- GPU: EVGA RTX 3080 FTW3 Ultra
- RAM: 4x8 3200Mhz G-Skill RAM
- SSD: Corsair Force MP510 1TB NVME SSD

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behaviour

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. Alternatively you can use [Skyrim Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133) to remove everything modding related from your Skyrim folder. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics cheque. Do not worry about this part as the installation will replace this graphics settings.
Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Programme Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

Grab the modlist from the [releases](https://github.com/ixanza/tranquillity/releases) tab

1. Open Wabbajack
2. Click on browse Modlists and seelct the modlist you downloaded above
3. Set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Programme Files, Desktop. Put it somewhere easy like `C:/Modlists/Tranquillity`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Path is a zero length string error**:

This error occurs when you don't specify an installation folder in the installation before hitting run

## Post-Installation

### Game Folder

The installation will create a copy of your Skyrim Special Edition game in `Instalation Folder/Stock Games`. This will then contain all the necessary files such as SKSE, ENB Binaries, Reshade Binaries and mod required dlls such as Engine Fixes. There is no need to copy anything to your Steam version of Skyrim as we will be running SKSE from within this folder to play the game

### ENB

Tranquillity comes with [Silent Horizons ENB](https://www.nexusmods.com/skyrimspecialedition/mods/21543) included.

If you want a different ENB. You can choose from a wide variety of ENBs on the Nexus that support Cathedral Weathers. To replace the ENB installed. Delete the enbcache folder, enbseries folder, enbseries.ini and replace those with the new ENB. You don't have to delete the enblocal.ini as that contains tweaks that don't affect how it looks but rather things like screenshot formats, vsync settings.

A few other ENB suggestions are:

- [Serio's ENB](https://www.nexusmods.com/skyrimspecialedition/mods/30506)
- [Rudy ENB for Cathedral Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/39113)
- [Re-engaged ENB](https://www.nexusmods.com/skyrimspecialedition/mods/1089)

## The video game has been modified

Please do not expect the game to be functionally similar to vanilla. There are a lot of mods installed that modify core base game functionality as well as adding on new mechanics.
Please see [Modified Gameplay](https://github.com/ixanza/tranquillity/blob/master/Modified%20Gameplay.md) for a non exhaustive list of changes to Tranquillity.

## How to start up Tranquillity

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please cheque the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Creating your Character

Tranquillity uses Skyrim Unbound Reborn as its Alternate Start. When the game begins you will be looking over a destroyed Helgen. This is where initial scripts are started and should be left alone for about 10-15 seconds. Once it is done you can configure your desired start using the Skyrim Unbound MCM setting. When you are happy with your desired start choice, hit Begin in the MCM. **For the sake of compatibility, please do not create a non dragonborn character**. I am not going to stop you but do not expect the game to function 100% with a feature that disables a core part of Skyrim.

Once you begin you will be taken to character creation and then to your new game

## In-Game MCM Options

All the required MCM options have been automated for you. Enjoy the game or tweak the following to your liking:

- iHud
- SkyUI
- Lucien (If you set a nickname that's supported he can call you by that name)
- XP32 Skeleton Styles

### Optional Survival Config

Included in Tranquillity is SunHelm Survival. It is disabled by default and will prompt to turn on when you sleep or if you manually activate it. If you're not a fan of this, just disable it in the MCM option. **DO NOT UNINSTALL THE MOD**

## Other Post Installation FAQ

### Ultrawide Options

If you have an ultrawide monitor (21:9), the UI will be off and look weird. You will want to install a set of mods meant to help with widescreen monitors

1) Find the Mod Dear Diary on the left pane of MO2 and reinstall with your desired Widescreen aspect ratio
2) Head over to [Complete Widescreen Fix for Vanilla and SkyUI 2.2 and 5.2 SE](https://www.nexusmods.com/skyrimspecialedition/mods/1778)
3) Under Optional File grab `SkyHud - High Resolution Widescreen Fix`
Install the mod, activate it and let it load at the bottom. You should now have a working UI with widescreen support

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
- Edit the mod SSE Display Tweaks.
- Under `[Render]`
- Set Fullscreen to `True`
- Set Borderless to `False`

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack) and on my own discord [Xanza's Emporium](https://discord.gg/867QtkVuUa), I would advise checking the [Issues](https://github.com/ixanza/tranquillity/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
