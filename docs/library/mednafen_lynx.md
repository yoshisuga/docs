# Atari Lynx (Beetle Handy)

## Background
Beetle/Mednafen LYNX is an Atari Lynx video game system emulator that can be used as a libretro core. Specifically it's a port of Mednafen Lynx which is a fork of [Handy](https://wiki.libretro.com/index.php?title=Handy). Authors K. Wilkins|Mednafen Team

## License

Zlib, GPLv2

## Extensions

lnx

## BIOS
|   Filename    |    Description        |              md5sum              |
|:-------------:|:---------------------:|:--------------------------------:|
|lynxboot.img   |Lynx Boot Image        | fcd403db69f54290b51035d82f835e7b |


## Feature Support
These are libretro features, not frontend or standalone emulator features.

##### Features:
| Saves | Save | states | Rewind | Netplay | RetroAchievements | Cheats | Controllers |
|-------|------|--------|--------|---------|-------------------|--------|-------------|
| yes   |   -  |   yes  |  yes   |   no    |         -         |    no  |    yes      |

| Rumble | Sensors | Camera | Location | Subsystem |
|--------|---------|--------|----------|-----------|
|   no   |    no   |   no   |    no    |    no     |

## Options

This core does not feature core options.

## Controllers

The core supports controller setting:
* Joypad: Controller
![Atari Lynx_Gamepad_Diagram](images/Controllers/mednafen_lynx_joypad.png)

Supported combinations

* Option 1 + Pause = Restarts game
* Option 2 + Pause = Flips Screen

| [RetroPad](RetroPad)                                           | Joypad |
|----------------------------------------------------------------|--------|
| ![RetroPad_A](images/RetroPad/Retro_A_Round.png)               |A Button |
| ![RetroPad_B](images/RetroPad/Retro_B_Round.png)               |B Button |
| ![RetroPad_Dpad](images/RetroPad/Retro_Dpad.png)               | D-Pad |
| ![RetroPad_L1](images/RetroPad/Retro_L1.png)                   |Option 1 |
| ![RetroPad_L2](images/RetroPad/Retro_L2_Temp.png)              |        |
| ![RetroPad_L3](images/RetroPad/Retro_L3.png)                   |        |
| ![RetroPad_Left_Stick](images/RetroPad/Retro_Left_Stick.png)   |        |
| ![RetroPad_R1](images/RetroPad/Retro_R1.png)                   |Option 2|
| ![RetroPad_R2](images/RetroPad/Retro_R2.png)                   |        |
| ![RetroPad_R3](images/RetroPad/Retro_R3.png)                   |        |
| ![RetroPad_Right_Stick](images/RetroPad/Retro_Right_Stick.png) |        |
| ![RetroPad_Select](images/RetroPad/Retro_Select.png)           |        |
| ![RetroPad_Start](images/RetroPad/Retro_Start.png)             |Pause |
| ![RetroPad_X](images/RetroPad/Retro_X_Round.png)               |        |
| ![RetroPad_Y](images/RetroPad/Retro_Y_Round.png)               |        |

## Compatibility

| Game                                  | Issue                          |
|---------------------------------------|--------------------------------|
|**RoadBlasters**                       |Graphics glitches. Minor flickering and glitches after starting a race.|

## External Links

* [Official Website](http://mednafen.sourceforge.net/)  
* [Libretro Repository](https://github.com/libretro/beetle-lynx-libretro)
* [Report Issues Here](http://github.com/libretro/libretro-meta/issues)
