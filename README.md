![Camina Shell Shell Blade Mods](https://github.com/user-attachments/assets/3b7241da-b317-4fd6-a7ce-49dbd5b13c8d)

# Stellar Blade Mods

This folder contains all the mods that I have selected, tested, and use for Stellar Blade. Compressed with 7-Zip to multiple 50MB (47,185,920 byte) archives to avoid Git Large File Storage issues.

### Summary of adjustments:

1. I did not like the appearance of the original EVE character - she looked innocent, naive, and weak to me. I prefer a stronger character design, and ultimately combined:
   - the [(head skin) face](https://www.nexusmods.com/stellarblade/mods/290) & [(extreme tagless) hair](https://www.nexusmods.com/stellarblade/mods/387) of Raven
   - [voice](https://www.nexusmods.com/stellarblade/mods/911) & [moveset](https://www.nexusmods.com/stellarblade/mods/975) of Tachy
   - a [red iris set](https://www.nexusmods.com/stellarblade/mods/1124) for eyes
   - a [capeless Royal Guard body frame](https://www.nexusmods.com/stellarblade/mods/496) & [mask](https://www.nexusmods.com/stellarblade/mods/1022)
   - and a [YoRHa decaled weapon](https://www.nexusmods.com/stellarblade/mods/815)
3. [100% increase to running speed](https://www.nexusmods.com/stellarblade/mods/492), with 0% difference to walking speed.
4. A [fix for walking drift](https://www.nexusmods.com/stellarblade/mods/301), for a more natural movement.
5. [Increased drone scan distance and reduced cooldown](https://www.nexusmods.com/stellarblade/mods/633).
6. [Branding Logo](https://www.nexusmods.com/stellarblade/mods/321) for main menu.
7. [Vignette removal](https://www.nexusmods.com/stellarblade/mods/420) from camera view.
8. [Copyright removal](https://www.nexusmods.com/stellarblade/mods/240) for (photomode) screenshots.
9. [Cosmetic Freedom](https://www.nexusmods.com/stellarblade/mods/654), which apparently removes cost of upgrades or something.

### Those which aren't really in use or seen:

- [White hair color](https://www.nexusmods.com/stellarblade/mods/138) to EVE long ponytail.
- [Blacked out Shadow Kunoichi](https://www.nexusmods.com/stellarblade/mods/896) outfit.
- [Back holster](https://www.nexusmods.com/stellarblade/mods/764) (which doesn't seem work for me, but okay with it).
- [Rael weapon holster](https://www.nexusmods.com/stellarblade/mods/764), which I presume also requires [_the mod for the weapon of Rael_](https://www.nexusmods.com/stellarblade/mods/565) to work.
- [Skip startup logos](https://www.nexusmods.com/stellarblade/mods/483) (which also doesn't seem to work for me). 

I am only interested in cyber/tech cosmetics, and quality of life related mods. There are not any adult/NSFW mods in this collection.

## Mod Credits & Disclaimer

All credit given to those that created these mods. Please refer to their respective mod pages for more information. I do not own or modify any of the mods listed below, and have them here for my own backup purposes.

I will consider creating a mod collection for Stellar Blade on Nexus Mods if there is enough interest in the community.

[Stellar Blade Mods at NexusMods.com - https://www.nexusmods.com/games/stellarblade/mods](https://www.nexusmods.com/games/stellarblade/mods)

## Current Setup

- CPU: AMD Ryzen 9 5900X (24) @ 4.95 GHz
- GPU: AMD Radeon RX 7800 XT [Discrete]
- SSD: WD Black SN850X
- RAM: 128GB 3200MHz DDR4
- Fedora Linux 41 Workstation (GNOME/Wayland)
- Kernel 6.15.4
- Mesa 25.0.7
- Flatpak Steam Runtime
- Reshade 6.5.1 (via https://github.com/kevinlekiller/reshade-steam-proton?tab=readme-ov-file#misc)
- Running Stellar Blade in full screen window mode at 2560x1440 resolution

## Installation

1. Download all the files to a location of your choice
2. Extract the contents of the zip file to the location of your choice
3. Copy the contents of the `~mods` folder to your game folder under `StellarBlade/SB/Content/Paks/~mods`

> [!NOTE]
> Most of these mods will **NOT** render correctly for the demo version of Stellar Blade due to the demo game missing many assets from the full game, as shown in the image below.
> 
> ![Test in Demo Version](https://github.com/user-attachments/assets/05f50cac-07f2-4b92-acbb-187c04fdbb5a)

## Reshade User Settings

I have included a custom Reshade preset that I designed for playing Stellar Blade in SDR and have not noticed a performance difference using this preset configuration. It does however, add up to additional 40~50 watts of power on my GPU along side a 15% increase in processing, depending on the scene. Lower with only color adjustments.

- Copy the files within the `Shaders` to where you have Reshade shaders installed
- Copy the preset file to where you have Reshade presets installed 

NOTE: If you're running Stellar Blade from Steam, you will need to add the following to the game launch options:

```txt
WINEDLLOVERRIDES="d3dcompiler_47=n;dxgi=n,b" %command%
```

| VANILLA | RESHADE |
|:------:|:------:|
| <img width="2560" height="1440" alt="VANILLA" src="https://github.com/user-attachments/assets/26b6f3b2-ebde-4699-a860-b951d3b8df88" /> | <img width="2560" height="1440" alt="RESHADE" src="https://github.com/user-attachments/assets/9c55490a-37f9-4ea5-8b84-81b7abc4f9aa" /> |

## Mods in Collection

All mods sourced from nexusmods.com:

- `Compessed Total Size: 341.5 (8 items)`
- `Extracted Total Size: 561.8 MB (68 items)`

```txt
4sfasterscan_P.pak
4sfasterscan_P.ucas
4sfasterscan_P.utoc

Better_Menu_Logo_P.pak
Better_Menu_Logo_P.ucas
Better_Menu_Logo_P.utoc

cosmetic-Freedom_P.pak
cosmetic-Freedom_P.ucas
cosmetic-Freedom_P.utoc

Eyes10_P.pak
Eyes10_P.ucas
Eyes10_P.utoc

No_Photo_Mode_Copyright_P.pak
No_Photo_Mode_Copyright_P.ucas
No_Photo_Mode_Copyright_P.utoc

Rael_Mask_For_Eve_P.pak
Rael_Mask_For_Eve_P.ucas
Rael_Mask_For_Eve_P.utoc

RAVEN_Head_Skin_P.pak
RAVEN_Head_Skin_P.ucas
RAVEN_Head_Skin_P.utoc

ShadowKunoichiBlackoutV2_P.pak
ShadowKunoichiBlackoutV2_P.ucas
ShadowKunoichiBlackoutV2_P.utoc

SkipStartupLogos_P.pak
SkipStartupLogos_P.ucas
SkipStartupLogos_P.utoc

SqFasterEve_P.pak
SqFasterEve_P.ucas
SqFasterEve_P.utoc

Tachy_Moveset_P.pak
Tachy_Moveset_P.ucas
Tachy_Moveset_P.utoc

TachyActionVoice_P.pak
TachyActionVoice_P.ucas
TachyActionVoice_P.utoc

VoiceEve2Tachy_P.pak
VoiceEve2Tachy_P.ucas
VoiceEve2Tachy_P.utoc

WalkFix_P.pak
WalkFix_P.ucas
WalkFix_P.utoc

WhiteHair_P.pak
WhiteHair_P.ucas
WhiteHair_P.utoc

YoRHaBlade_P.pak
YoRHaBlade_P.ucas
YoRHaBlade_P.utoc

zCRubino_BackHolster_P.pak
zCRubino_BackHolster_P.ucas
zCRubino_BackHolster_P.utoc

zCRubino_RAEL_SUITONLY_P.pak
zCRubino_RAEL_SUITONLY_P.ucas
zCRubino_RAEL_SUITONLY_P.utoc

zCRubino_RAEL_WEAPON_HOLSTER_P.pak
zCRubino_RAEL_WEAPON_HOLSTER_P.ucas
zCRubino_RAEL_WEAPON_HOLSTER_P.utoc

zCRubino_RavenHairExtreme_P.pak
zCRubino_RavenHairExtreme_P.ucas
zCRubino_RavenHairExtreme_P.utoc

zNoVignetteSB_P.pak
```

![Screenshot From 2025-07-10 17-31-23](https://github.com/user-attachments/assets/f626974e-589c-46c4-8cc8-3228c4131d7d)
![Screenshot From 2025-07-10 17-31-33](https://github.com/user-attachments/assets/288c8da5-d096-4ff5-8d19-c820fe45de77)

### Additional Files

```txt
ReShade-CaminaShell.ini

Clarity.fx
DepthSharpen.fx
PD80_03_Filmic_Adaptation.fx
PD80_03_Levels.fx
PD80_04_Color_Gradients.fx
qUINT_mxao.fx
```

### Client Settings

![Screenshot From 2025-07-10 17-30-19](https://github.com/user-attachments/assets/578ff4d8-1ac8-44fc-a40d-ed1ba676ed6c)
![Screenshot From 2025-07-10 17-29-52](https://github.com/user-attachments/assets/424a83ce-2fad-41c3-aaf7-7203214a3726)
![Screenshot From 2025-07-10 17-30-58](https://github.com/user-attachments/assets/e6d6cab8-17b5-47b2-8504-9ea26ebf2da6)
![Screenshot From 2025-07-10 17-30-37](https://github.com/user-attachments/assets/f01af88b-fb15-4b94-9e0c-73d5b090c82a)
![Screenshot From 2025-07-10 17-30-33](https://github.com/user-attachments/assets/aee78de5-e0e4-4c64-ad31-30378cafa9d4)

## Example Video

[![Example Video](https://img.youtube.com/vi/XDI5khU-JxI/maxresdefault.jpg)](https://www.youtube.com/watch?v=XDI5khU-JxI)

> Click image above to watch video.
