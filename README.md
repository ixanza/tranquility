# Tranquility

<!-- TOC -->

- [Tranquility](#tranquility)
    - [Preamble](#preamble)
    - [System Requirements](#system-requirements)
    - [Installation](#installation)
        - [Pre-Installation](#pre-installation)
            - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
            - [Installing Microsoft .Net Framework 5.0 Runtime](#installing-microsoft-net-framework-50-runtime)
            - [Steam Config](#steam-config)
                - [Disable the Steam Overlay](#disable-the-steam-overlay)
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
    - [How to start up Tranquility](#how-to-start-up-tranquility)
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

<!-- /TOC -->

## Preamble

A complete overhaul of Skyrim, Tranquility is a modlist aimed at people wanting an easy to learn but hard to master playthrough. It features the full Simonrim suite of mods, no nudity, complete Creation Club support ($20 for Anniversary Upgrade is required), body and armor physics.

The complete modlist can be found [here](https://loadorderlibrary.com/lists/tranquility).

## System Requirements

Download Size: 90.6GB
Install Size: 129.8GB

Tranquility is a mid- to high-end list in terms of graphics. A minimum of 6GB VRAM is required to play smoothly (60fps) on 1080p and 8GB VRAM to play smoothly (60fps) on 1440p.

I made this list with my specs in mind, and I am able to get 60FPS (capped so my GPU doesn't work harder than it needs to) in Riverwood and Whiterun outdoors with Rudy ENB for Cathedral Weathers and these specs:

- CPU: Ryzen 7 3700x
- GPU: EVGA RTX 3080 FTW3 Ultra
- RAM: 4x8 3200Mhz G-Skill RAM
- SSD: Corsair Force MP510 1TB NVME SSD

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Installing Microsoft .Net Framework 5.0 Runtime

This package is required for the mod Scrambled Bugs to work. Without this installed, the game would not launch. Download and install the x64 version under "Run desktop apps" from [Microsoft](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime). [Direct Link](https://download.visualstudio.microsoft.com/download/pr/2bfb80f2-b8f2-44b0-90c1-d3c8c1c8eac8/409dd3d3367feeeda048f4ff34b32e82/windowsdesktop-runtime-5.0.13-win-x64.exe)

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting its contents.
A fully updated Skyrim (1.6.353 at the current version of Tranquility) is required. Do not run the Downgrade Patcher or the list will not install.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and and let it do the initial graphics check. Do not worry about this part as the installation will overwrite these graphics settings.
Start the game. Log in to the Creation Club and download all of the Creation Club content.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Programme Files folder. It's best to create a Wabbajack folder near the root level of your drive, e.g. `C:/Wabbajack`.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Open Wabbajack.
2. Click on browse Modlists and select Tranquility.
3. Set the Installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Programme Files, Desktop. Put it somewhere easy like `C:/Modlists/Tranquility`). The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend restarting Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

The following files have updated and are no longer accessible however they have open distribution permissions so grab it from here:
- FFXIV Reshade Shaders: https://mega.nz/file/cZBHzYiT#e1wKnVSP1xsp4Vf07vqzpR4TxDlK2S14rorLy2jICeg

The following folder contains mirrors of my generated files for DynDOLOD, Bodyslide, Nemesis, if Wabbajack fails to download these, download them manually from this folder:
- https://mega.nz/folder/RYBVmIjZ#Qntk7ENLrrgX4fcBx82YkA

The files downloaded from the links above should be placed in the downloads location set in Step 3 of [Downloading and Installing](#downloading-and-installing).

If a mod is no longer accessible and it isn't listed above, Notify me and I will more than likely have to upload a mirror if it has open permissions or I would have to recompile the list.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

**Path is a zero length string error**:

This error occurs when you don't specify an installation folder in the installation before hitting run.

## Post-Installation

### Game Folder

The installation will create a copy of your Skyrim Special Edition game in `Installation Folder/Stock Games`. This will then contain all the necessary files such as SKSE, ENB Binaries, Reshade Binaries, and mod required dlls such as Engine Fixes. There is no need to copy anything to your Steam version of Skyrim as we will be running SKSE from within this folder to play the game

### ENB

Tranquility comes with [Rudy ENB for Cathedral Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/39113) included.

If you want a different ENB, you can choose from a wide variety of ENBs on the Nexus that support Cathedral Weathers. To replace the ENB installed: Delete the enbcache folder, enbseries folder, and enbseries.ini, and replace those with the new ENB. You don't have to delete the enblocal.ini as that contains tweaks that don't affect how it looks but rather things like screenshot formats, VSYNC settings, etc.

A few other ENB suggestions are:

- [Serio's ENB](https://www.nexusmods.com/skyrimspecialedition/mods/30506)
- [Silent Horizons ENB](https://www.nexusmods.com/skyrimspecialedition/mods/21543)
- [Re-engaged ENB](https://www.nexusmods.com/skyrimspecialedition/mods/1089)

## The video game has been modified

Please do not expect the game to be functionally similar to vanilla. There are a lot of mods installed that modify core base game functionality as well as adding on new mechanics.
Please see [Modified Gameplay](https://github.com/ixanza/tranquility/blob/master/Modified%20Gameplay.md) for a non-exhaustive list of changes in Tranquility.

## How to start up Tranquility

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

If this Modlist receives an update please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Creating your Character

Tranquility uses Alternate Perspective as its alternate start mod. When the game begins you will be in an inn room. This is where initial scripts are started and should be left alone for about 10-15 seconds. Once it is done you can speak to the dragon to choose your desired start. Once you're ready, walk out of the door and your adventure will begin.

## In-Game MCM Options

All the required MCM options have been automated for you. Enjoy the game or tweak any of the MCMs to your liking

### Optional Survival Config

Included in Tranquility is SunHelm Survival. It is disabled by default and will prompt to turn on when you sleep or if you manually activate it. If you're not a fan of this, just disable it in the MCM option. **DO NOT UNINSTALL THE MOD**

## Other Post Installation FAQ

### Ultrawide Options

Tranquility comes with an Ultrawide preset created "Cashtro" on the discord. If you use a widescreen monitor, just tick the 'Tranquility Widescreen Add-On' option at the bottom of the modlist

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to turn either this or your ENB version off. Do not have the game AO and an ENB AO turned on at the same time.
- `Remove Shadows`: If you really struggle, use this. This will disable all shadows (not recommended).

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows.

Or edit the mod SSE Display Tweaks:

- Under `[Render]` set Fullscreen to `True` and Borderless to `False`.

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- erri120 & jdsmith2816 - Repository template
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack) and on my own Discord [Emporio's Emporium](https://discord.gg/867QtkVuUa), I would advise checking the [Issues](https://github.com/ixanza/tranquility/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
