Analog Dreamers – Core Collection v1.1 — Definitive Edition
(RG35XX Plus / RGCubeXX MinUI Build)

🌈 Overview
Welcome to the Analog Dreamers Core Collection v1.1 — a fully tested, plug-and-play retro experience for RG35XX Plus and RGCubeXX users.
Each system is configured for maximum compatibility and ease of use, following the “Robust Edition” standard used throughout this build.

🎮 Included Robust Systems
# | System | Core | BIOS Folder | Notes
1 | Atari 2600 | stella2014_libretro.so | — | Fast, no BIOS required
2 | Atari 5200 | atari800_libretro.so | /Bios/AT5200/ | Requires 5200.rom
3 | Atari Lynx | handy_libretro.so | /Bios/ATLYNX/ | Requires lynxboot.img
4 | Atari 7800 | prosystem_libretro.so | /Bios/AT7800/ | 7800 BIOS (U).rom or (E).rom
5 | Sega CD | genesis_plus_gx_libretro.so | /Bios/SEGACD/ | Region BIOS files required
6 | PC Engine / TurboGrafx-16 | beetle_pce_fast_libretro.so | /Bios/PCECD/ | syscard1.pce, syscard2.pce, syscard3.pce
7 | Neo Geo | fbalpha2012_neogeo_libretro.so | /Bios/NEOGEO/ | Requires neogeo.zip
8 | C64 | vice_x64_libretro.so | /Bios/C64/ | Original C64 BIOS set
9 | Amiga | puae_libretro.so | /Bios/AMIGA/ | kick13.rom, kick20.rom, kick31.rom
10 | Amiga CD | puae_libretro.so | /Bios/AMIGACD/ | CD32 BIOS set required
11 | Atari ST | hatari_libretro.so | /Bios/ATARIST/ | Requires tos.img
12 | CPS / CPS2 / CPS3 | fbalpha2012_cps_libretro.so | — | No BIOS required
13 | SG-1000 | genesis_plus_gx_libretro.so | /Bios/SG1000/ | Optional BIOS
14 | Sega 32X | picodrive_libretro.so | /Bios/SEGA32X/ | Region BIOS files required
15 | Naomi / Atomiswave | flycast_libretro.so | /Bios/NAOMI/ | Requires correct ROM set
16 | Game & Watch | gw_libretro.so | — | Minimal system, no BIOS

⚙️ Installation Guide
1️⃣ Copy all folders from this ZIP to your SD Card root.
2️⃣ Place BIOS files in their matching folders (names must match exactly as listed).
3️⃣ ROMs go into the corresponding /Roms/[SystemName]/ folders.
4️⃣ Start your device and select the .pak file for the desired system.
5️⃣ Play instantly — no setup required!

🖥️ Display Settings
All systems are configured as:
- Aspect Ratio: Core Provided
- Integer Scale: OFF
- Stretch: FULLSCREEN (for compatible cores only)
You can change these later in RetroArch if you prefer custom scaling.

💾 Folder Layout Example
/mnt/sdcard/
├── Bios/
│   ├── AT5200/5200.rom
│   ├── ATLYNX/lynxboot.img
│   ├── PCECD/syscard3.pce
│   └── ...
├── Roms/
│   ├── Atari 2600/
│   ├── Sega CD/
│   ├── Amiga CD/
│   └── ...
└── Emus/
    ├── rg35xxplus/
    │   ├── A2600.pak/
    │   ├── A5200.pak/
    │   └── ...

🧠 Tips
- Keep BIOS filenames exactly as written — MinUI depends on them.
- Use .zip ROMs for arcade systems; .bin/.cue for CD systems.
- You can edit retroarch-[system].cfg to change scaling or shader preferences.

🖤 Credits
Created by Timo & Sophie — The Analog Dreamers
“Keep Pixels Alive — Forever.”
Dedicated to all retro fans preserving the 8-bit soul.
