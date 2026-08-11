# The Homebrew Unlauncher
This repository contains The Homebrew Unlauncher, a [Pico Launcher](https://github.com/LNH-team/pico-loader) fork that can also run NES,Famicom Disk System,Game Boy Game Boy Color,SNES games and RVID and AVI Videos


# DISCLAIMER!*
The Homebrew Unlauncher is provided for educational and personal use only. It does NOT contain any ROMs or Media protected by copyright or Proprietary System files. Users should use their legally dumped ROMs and game backups.
# I DO NOT ENDORSE PIRACY,SOFTWARE DISTRIBUTION OR ANY OTHER ILLEGAL ACTIVITIES,OK?
Plus, The Homebrew Unlauncher Development (including the forked emulators and video players) were accelerated with LLMs,
# this does not mean that this is AI SLOP. This project was also made by a real human! (no way.) LLMs were just used to accelerate code production.
Thank you.

## Features
- Can load homebrew and retail games using [Pico Loader](https://github.com/LNH-team/pico-loader).
- Includes various emulators to run NES,Famicom Disk System,Game Boy and Game Boy Color Games.
  (If you wanna use the emulators,please,check the Disclaimer*.)
- Various display modes
    - Horizontal and vertical icon grid
    - Banner list
    - Coverflow
- [File associations](docs/FileAssociations.md)
- [Covers](docs/Covers.md)
- [Custom Icons & Banners](docs/Customization.md)
- [Material Design 3 and custom themes](docs/Themes.md)
- Support for background music (see [Themes](docs/Themes.md))
- Support for cheats (See [Cheats](docs/Cheats.md))


General usage documentation can be found here: [Usage](docs/Usage.md).

## Setup & Configuration
We recommend using WSL (Windows Subsystem for Linux), or MSYS2 to compile this repository.
The steps provided will assume you already have one of those environments set up.

1. Install [BlocksDS](https://blocksds.skylyrac.net/docs/setup/)

## Compiling

1. Run `make`

The launcher can be found in the root directory under the name `LAUNCHER.nds`.

2. Copy `LAUNCHER.nds` to your SD card.
    - If you are using DSpico, rename to `_picoboot.nds` and place it in the root of your SD card.
3. Copy the `_pico` pico folder to the root of your SD card.


For DSpico the final directory structure will look like this:
```
.
├── _pico
│   ├── themes
│   │   ├── material
│   │   └── brewing-waves
│   ├── aplist.bin
│   ├── nds-bootstrap-release.nds
│   ├── nds-bootstrap-hb-release.nds
│   ├── release-bootstrap.ver
│   ├── savelist.bin
│   ├── picoLoader7.bin
│   └── picoLoader9.bin
└── _picoboot.nds
```
Note: If you want to play DSiWare on the DSpico, additional files are required. See the [Pico Loader](https://github.com/LNH-team/pico-loader) readme for more information.

## License

Icons by [icons8](https://icons8.com/)

This project is licensed under the Zlib license. For details, see `LICENSE.txt`.

Additional licenses may apply to the project. For details, see the following files:
- ArduinoJson.txt (MIT)
- Material.txt (Apache)
- Ubuntu.txt (UFL) (More info are in Ubuntu-Copyright.txt,Ubuntu-FAQ.txt,Ubuntu-Fontlog.txt and Ubuntu-Trademarks.txt)
- dsi_sdmmc.txt (MIT)
- mini-printf.txt (BSD 3-Clause)
- newlib.txt (Multiple licenses,read the text file for more info)
- tlsf.txt (BSD 3-Clause)
- libtwl.txt (zlib)
- PicoLoader.txt (zlib)
- Gameyob.txt (MIT)
- nesDS.txt (Public Domain)
- HMP.txt (MIT)
- tuna-viDS.txt (GNU GPL2)
- lolSNES.txt (GNU GPL3) 
- The Brewing Waves theme is made with the Pico Launcher Theme Creator    
- App URL: https://santiagovalencia109.github.io/pl-Theme-Creator/
- GitHub Repository: https://github.com/santiagovalencia109/pl-Theme-Creator/

## Contributors
- [@Gericom](https://github.com/Gericom)
- [@XLuma](https://github.com/XLuma)
- [@Dartz150](https://github.com/Dartz150)
- [@lifehackerhansol](https://github.com/lifehackerhansol)
