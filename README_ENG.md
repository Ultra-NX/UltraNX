# Ultra-NX by **[redraz](https://github.com/redraz)**

![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Ultra.png)

### [English Readme](README_ENG.md) | [Telegram group](https://t.me/UltraNX)

### Ultra is a functional custom firmware for Nintendo Switch, with a focus on overclocking and an improved user experience.

## Features of Ultra

* Pre-configured OC-Suite with presets.
* The best overclocking customizer for Switch - Ultra-Tuner, that allows you to customize overclocking right from the console. It was the first, and remains unique.
* The CFW is as light as possible. There are no unnecessary things in it, only minimum necessary for overclocking and comfortable use.
* Modular design. A minimum of applications/plugins/overlays are included, but you can always add more via the bundled Updater.
* Choice of cooling system preset, either noisy but cold or quiet but hot.
* Custom Ultra Monitor with FPS and system metrics.
* Regular updates, and an active community.

## Composition of Ultra

1. **[Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)** - Atmosphère, custom firmware for the Nintendo Switch.
1. **[Hekate](https://github.com/CTCaer/hekate)** - Custom Nintendo Switch graphical bootloader, firmware patcher, toolkit and more.
1. **[Ultra Tuner](https://github.com/Ultra-NX/Ultra-Tuner)** - Package for Ultra Paw (fork of Ultrahand), which allows you to fine-tune the OC parameters for your console. In case of unstable overclocking, or if you want to increase the performance of your console, Ultra Tuner is your indispensable assistant.
1. **[OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite/)** - Overclocking package by Meha/hanai3Bi, open source guarantees reliability and no hidden nasties. Updated in time to support new Atmosphere features. Uses modified loader.kip from B3711, which has more CPU undervolt tables (6 levels vs. 4x).
   - The original from Meha is temporarily used.
1. **Installed Payloads**:
   * [Lockpick_RCM](https://codeberg.org/rashevskyv/kefir) - Program for dumping console keys.
   * [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer) - A low-level file manager for working with the system.
1. **Installed Homebrew**
   * [AiO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater) - Program to update Ultra to the current version, as well as to download cheats.
   * [DBI](https://github.com/rashevskyv/dbi) - The best file manager, save manager and program installer on the console. If you need a different localization - Updater has a choice of EN-RU-PTBR-ZHCN.
1. **Installed Modules**
   * [SaltyNX](https://github.com/masagrator/SaltyNX) - Background module allowing to modify files/processes in console, supports plugins. Not compatible with 32-bit games (list on the project's github).
   * [sys-clk](https://github.com/hanai3Bi/Switch-OC-Suite) - Module responsible for overclocking CPU, memory and GPU - for better performance. I change versions from different authors from time to time. Original authors: Meha/hanai3Bi, lineon, p-sam.
   * [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader/) - This module is used to switch the installed modules.
   * [sys-patch](https://github.com/ITotalJustice/sys-patch/) - Creates/updates patches at system startup. Does not replace sigpatches, but saves from regular manual updating of system patches.
   * [Ultra Paw Overlay](https://github.com/Ultra-NX/Ultra-Paw-Overlay), a fork of [Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay) - Special overlay-menu for interacting with the system: overclocking, controlling modes via ReverseNX, enabling cheats, etc. Also allows to use your own packages, for example, Ultra Tuner.
     - **`Ultra-Overlay`**, a mod of [sys-clk](https://github.com/hanai3Bi/Switch-OC-Suite) - Overlay for controlling sys-clk module. Slightly modified by me, but without digging into sources.
     - [Ultra Monitor](https://github.com/Ultra-NX/Ultra-Status-Monitor), a fork of [Status Monitor](https://github.com/masagrator/Status-Monitor-Overlay) - Overlay that allows you to monitor console parameters in real time. It can act as an FPS counter. You can customize Micro-overlay appearance in Updater.
     - [FPSLocker](https://github.com/masagrator/FPSLocker) - An overlay that allows you to unlock 60 FPS in games.
     - [EdiZon](https://github.com/proferabg/EdiZon-Overlay) - An overlay for using cheats.
     - [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT) - ReverseNX control overlay.
     - [Sysmodules](https://github.com/WerWolv/ovl-sysmodules/) - Overlay for enabling and disabling installed system modules.
1. **Available for download via [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater)**
   * [Daybreak](https://github.com/Atmosphere-NX/Atmosphere/tree/master/troposphere/daybreak) - A program for updating OS.
   * [Linkalho](https://github.com/rdmrocha/linkalho) - Account linking program.
   * [ReverseNX Tool](https://github.com/masagrator/ReverseNX-Tool) - ReverseNX control program.
   * [Battery Desync Fix](https://github.com/CTCaer/battery_desync_fix_nx) - Program to reset the battery controller. Do not use unnecessarily!
   * [HB App Store](https://github.com/fortheusers/hb-appstore) - A free store for downloading Homebrew apps.
   * [SysDVR](https://github.com/exelix11/SysDVR) - A program and module for streaming video from a console to a PC or other devices.
   * [sys-ftpd](https://github.com/cathery/sys-ftpd) - FTP server running in background.
   * [Observer-Tool](https://github.com/rkuchkarov/Observer-Tool) - An overlay with the most detailed display of system statistics, similar to Afterburner on PC.
   * **`MemToolkitNX`** - Benchmark and Memory Tester. The result is highly dependent on CPU overclocking.
   * **`RaytracingNX`** - CPU benchmark.
   * **`stress-nx`** - Stress test/benchmark CPU.
   * **`mhz`** - A program that shows the real maximum CPU frequency.


## License

Listed below are the licenses of those programs that have been modified specifically for Ultra. Following the provisions of these licenses, all code in the modifications is distributed under the same license

[GPL 2.0](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE): 
  * [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
  * [Status-Monitor-Overlay](https://github.com/masagrator/Status-Monitor-Overlay)

[CC-BY-NC-4.0 License](https://github.com/ppkantorski/Ultrahand-Overlay/blob/main/LICENSE)
  * [Ultrahand-Overlay](https://github.com/ppkantorski/Ultrahand-Overlay)

## Credits 

* Cooler3D
* Efosamark
* rashevskyv/хНЯ
* snupt/Catcher In The Grain Field
* ppkantorski/b0rd2dEAth
* hanai3Bi/Meha
* 4PDA
#### And also - a special thanks to the administration and members of Ultra Group

## Support

If you liked the results of my labors and you wanted to thank me - I would be very grateful.            
You can do this via @wallet telegram, on my @redraz account            
I am from Russia, so there are no other convenient ways to donate me =(