# Ultra-NX by **[redraz](https://github.com/redraz)**

![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Ultra.png)

### [Telegram group](https://t.me/UltraNX) - Don't be afraid to write in English, we will understand everything and answer you!
#
### Ultra is a functional custom firmware for Nintendo Switch, with a focus on overclocking and an improved user experience.

### [Ultra 2.3](https://github.com/Ultra-NX/Ultra/releases/latest/) Supports HOS 19.0.1 and all console revisions



## Features of Ultra

* Pre-configured OC Switchcraft (Successor to OC-Suite) with presets.
* The best overclocking customizer for Switch - Ultra-Tuner, that allows you to customize overclocking right from the console. It was the first, and remains unique.
* The CFW is as light as possible. There are no unnecessary things in it, only minimum necessary for overclocking and comfortable use.
* Modular design. A minimum of applications/plugins/overlays are included, but you can always add more via the Ultra Tuner.
* Manual adjustment of cooling system curves, and presets.
* Regular updates, and an active community.
* [Forks](https://github.com/Ultra-NX/Ultra-Resources/tree/main/patches) (own modifications) of programs and components needed for convenience, security and empowerment:
   * Atmosphere fork with Ultra version in system information, and disabled reports, which usually clogs up the SD card, wastes its resource and breaks the file system.
   * SaltyNX and FPSLocker forks, with support for changing screen refresh rate and with OLED support.
   * Mission Control fork, with the “easter egg” cut out, making the joycons yellow-blue.
   * Status Monitor fork with display of current voltages and unique Micro Overlay modules, whose presets can be changed via Ultra Tuner.



## Content of Ultra

1. **[Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)** - Atmosphère, custom firmware for the Nintendo Switch.
1. **[Hekate](https://github.com/CTCaer/hekate)** - Custom Nintendo Switch graphical bootloader, firmware patcher, toolkit and more.
1. **[Ultra Tuner](https://github.com/Ultra-NX/Ultra-Tuner)** - Package for Ultrahand, which allows you to fine-tune the OC parameters for your console. In case of unstable overclocking, or if you want to increase the performance of your console, Ultra Tuner is your indispensable assistant.
1. **[OC-Switchcraft](https://github.com/halop/OC_Toolkit_SC_EOS)**, a fork of **[OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite/)** - Atmosphere Loader with overclocking from B3711, allows you to reach from N.Switch power Xbox One. Updated in time to support new Atmosphere features.


1. **Installed Payloads**:
   * [Lockpick_RCM](https://gbatemp.net/download/lockpick_rcm-1-9-13-fw-19-zoria-source.38837/) - Program for dumping console keys.
   * [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer) - A low-level file manager for working with the system.


1. **Installed Homebrew**
   * [AiO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater) - Program to update Ultra to the current version, as well as to download cheats.
   * [Daybreak](https://github.com/Atmosphere-NX/Atmosphere) - A program for updating OS.
   * [DBI](https://github.com/rashevskyv/dbi) - The best file manager, save manager and program installer on the console. If you need a different localization - Updater has a choice of EN-RU-PTBR-ZHCN.


1. **Installed Modules**
   * [SaltyNX](https://github.com/masagrator/SaltyNX) - Background module allowing to modify files/processes in console, supports plugins. Not compatible with 32-bit games (list on the project's github).
   * [sys-clk](https://github.com/halop/OC_Toolkit_SC_EOS) - Module responsible for overclocking CPU, memory and GPU - for better performance. I change versions from different authors from time to time. Original authors: Meha/hanai3Bi, lineon, p-sam.
   * [nx-ovlloader](https://github.com/ppkantorski/nx-ovlloader) - This module is used to switch the installed modules.
   * [sys-patch](https://github.com/impeeza/sys-patch) - Patches the system to run unsigned software instead of sigpatches.
   * [Mission Control](https://github.com/ndeadly/MissionControl) - A module that allows you to connect almost any gamepads to the console via bluetooth.
   * [sys-con](https://github.com/o0Zz/sys-con) - A module that allows you to connect almost any gamepads to the console via USB.
   * [Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay) - Special overlay-menu for interacting with the system: overclocking, controlling modes via ReverseNX, enabling cheats, etc. Also allows to use your own packages, for example, Ultra Tuner.
     - **`Ultra OC (sys-clk)`**, a mod of [sys-clk](https://github.com/halop/OC_Toolkit_SC_EOS) - Overlay for controlling sys-clk module. Slightly modified by me, but without digging into sources (Since they're closed).
     - [Status Monitor](https://github.com/Ultra-NX/Status-Monitor-Overlay), a fork of [Status Monitor](https://github.com/masagrator/Status-Monitor-Overlay) - Overlay that allows you to monitor console parameters in real time. It can act as an FPS counter. You change preset of Micro-overlay appearance in Updater.
     - [FPSLocker](https://github.com/masagrator/FPSLocker) - An overlay that allows you to unlock 60 FPS in games.
     - [EdiZon](https://github.com/proferabg/EdiZon-Overlay) - An overlay for using cheats.
     - [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT) - ReverseNX control overlay.
     - [Sysmodules](https://github.com/WerWolv/ovl-sysmodules/) - Overlay for enabling and disabling installed system modules.


1. **Available for download via [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater)**
   * Homebrews:
      * [Linkalho](https://gbatemp.net/download/linkalho.38822/) - Account linking program.
      * [Tinfoil](https://tinfoil.io) - Installer and game store.
      * [HB App Store](https://github.com/fortheusers/hb-appstore) - A free store for downloading Homebrew apps.
      * [PPSSPP](https://gbatemp.net/threads/ppsspp-switch-standalone-beta.544071/post-10492671) - PSP emulator.
      * [ThemezerNX](https://github.com/suchmememanyskill/themezer-nx) + [NXThemes Installer](https://github.com/exelix11/SwitchThemeInjector) + [Theme Patches](https://github.com/exelix11/theme-patches) - Searching and installing themes on Switch.
      * [Battery Desync Fix](https://github.com/CTCaer/battery_desync_fix_nx) - Program to reset the battery controller. Do not use unnecessarily!
      * **`MemToolkitNX`** - Benchmark and Memory Tester. The result is highly dependent on CPU overclocking.

   * Overlays:
      * [Tetris](https://github.com/ppkantorski/Tetris-Overlay/) - "That" game in the form of an overlay. Works only on the latest versions of Ultrahand.
      * [BT Audio](https://github.com/masagrator/BT_Audio-ovl) - An overlay that allows you to quickly disconnect/connect to a bluetooth headset.
      * [MasterVolume](https://github.com/averne/MasterVolume) - Global volume control, allows you to raise the volume above the maximum. Use with care!
      * [Fizeau](https://github.com/averne/Fizeau) - Module for changing the screen color profile.
      * [sys-tune](https://github.com/HookedBehemoth/sys-tune) - Overlay music player, works in background.

   * Other:
      * [FPSLocker Patches](https://github.com/masagrator/FPSLocker-Warehouse) - Patches for FPSLocker, so you don't have to download a separate patch for each game through the overlay.
      * [DVR Patches](https://github.com/exelix11/dvr-patches) - SysDVR patches, work without the system module, activating background recording in games where it is initially prohibited.
      * [TriPlayer](https://github.com/DefenderOfHyrule/TriPlayer) - A homebrew music player that runs through the system module, and can minimize while running in the background.
      * [sys-ftpd](https://github.com/tomvita/sys-ftpd-light) - FTP server running in background.



## License

Listed below are the licenses of those programs that have been modified specifically for Ultra. Following the provisions of these licenses, all code in the modifications is distributed under the same license

[GPL 2.0](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE): 
  * [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
  * [Status-Monitor-Overlay](https://github.com/masagrator/Status-Monitor-Overlay)

[MIT License](https://github.com/masagrator/FPSLocker/blob/main/LICENSE)
  * [FPSLocker](https://github.com/masagrator/FPSLocker)



## Credits 

* B3711
* ppkantorski
* Meha
* duckbill
* snupt
* Cooler3D
* 4PDA
#### And also - a special thanks to the administration and members of Ultra Group



## Support

If you like the project and you have a desire to support me with a penny - I will be very grateful.
I have no other income at the moment, so any monetary help is very valuable to me.            
```
TON:  UQDioCnnPI5sk4KvxWzfPWsWbAyWCkzwhaYjy8Qpg2QwWMiL
BTC:  1HsC4z8X1YkZzcSKZz1t7MXRa7rPi8qChV
USDT: TQi3qLVrNGcr6avfVQBXRjpPTyvp5JZ7i2
```