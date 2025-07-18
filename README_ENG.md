# UltraNX by **[redraz](https://github.com/redraz)**

![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Ultra.png)

### [Telegram group](https://t.me/UltraNX) - Don't be afraid to write in English, we will understand everything and answer you!
#
### Ultra is a functional custom firmware for Nintendo Switch, with a focus on overclocking and an improved user experience.

### [Ultra 2.5|R1](https://github.com/Ultra-NX/UltraNX/releases) Supports HOS 20.2.0 and all console revisions



## Features of Ultra

* Pre-configured OC Switchcraft (Successor to OC-Suite) with presets.
* By default, there's already an undervolt that noticeably reduces the console's consumption, and a slight memory overclock that will make games smoother.
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
1. **[OC-Switchcraft](https://github.com/halop/OC-Switchcraft-EOS/releases)**, a fork of **[OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite/)** - Atmosphere Loader with overclocking from B3711, allows you to reach from N.Switch power Xbox One. Updated in time to support new Atmosphere features.


1. **Installed Payloads**:
   * [Lockpick RCM](https://github.com/impeeza/Lockpick_RCMDecScots) - Program for dumping console keys.
   * [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer) - A low-level file manager for working with the system.


1. **Installed Homebrew**
   * [Sphaira](https://github.com/ITotalJustice/sphaira) - Modern Homebrew Menu, analogous to nx-hbmenu
   * [AiO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater) - Program to update Ultra to the current version, as well as to download cheats.
   * [Daybreak](https://github.com/Atmosphere-NX/Atmosphere) - A program for updating OS.
   * [DBI](https://4pda.to/forum/index.php?showtopic=939714&st=1100#entry86288632) - The best file manager, save manager and program installer on the console.


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
     - [Sysmodules](https://github.com/ppkantorski/ovl-sysmodules) - Overlay for enabling and disabling installed system modules.


1. **Available for download via [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater)**
   * Homebrews:
      * [DBI](https://4pda.to/forum/index.php?showtopic=939714&st=1100#entry86288632) - Here you can download a DBI or update an existing one.
      * [Linkalho](https://gbatemp.net/download/linkalho.38822/) - Account linking program.
      * [HB App Store](https://github.com/fortheusers/hb-appstore) - A free store for downloading Homebrew apps.
      * [PPSSPP](https://gbatemp.net/threads/ppsspp-switch-standalone-beta.544071/post-10492671) - PSP emulator.
      * [Moonlight](https://github.com/XITRIX/Moonlight-Switch) - Moonlight client, allows to stream games from PC.
      * [ThemezerNX](https://github.com/suchmememanyskill/themezer-nx) + [NXThemes Installer](https://github.com/exelix11/SwitchThemeInjector) + [Theme Patches](https://github.com/exelix11/theme-patches) - Searching and installing themes on Switch.
      * [Battery Desync Fix](https://github.com/CTCaer/battery_desync_fix_nx) - Program to reset the battery controller. Do not use unnecessarily!
      * [MemToolkitNX](https://discord.com/channels/854839758815363072/1173171845139288114/1324099100202766408) - Benchmark and Memory Tester. The result is highly dependent on CPU overclocking.
      * [MemToolkitNX OLD](https://discord.com/channels/854839758815363072/1173171845139288114/1276196700750479480) - Benchmark and Memory Tester. The result is highly dependent on CPU overclocking. The old version, which many people like better than the new one.
      * [MicroMemBench](https://github.com/rashevskyv/4IFIR) - Benchmark. The result is highly dependent on CPU overclocking. A version from 4ifir that tests CPU Copy in real time, which allows you to quickly find out the result after changing timings.

   * Overlays:
      * [Status Monitor Ultra](https://github.com/Ultra-NX/Status-Monitor-Overlay) - Status Monitor fork for UltraNX, supports many Micro-overlay presets, and has a number of unique features.
      * [Tetris](https://github.com/ppkantorski/Tetris-Overlay/) - "That" game in the form of an overlay. Works only on the latest versions of Ultrahand.
      * [MasterVolume](https://github.com/averne/MasterVolume) - Global volume control, allows you to raise the volume above the maximum. Use with care!
      * [NX-FanControl](https://github.com/Zathawo/NX-FanControl) - Module for manually adjusting the speed of the cooler. The changes are applied immediately, the module works from SOC temperature and not Skin temperature like Atmosphere.
      * [BT Audio](https://github.com/masagrator/BT_Audio-ovl) - An overlay that allows you to quickly disconnect/connect to a bluetooth headset.
      * [Fizeau](https://github.com/averne/Fizeau) - Module for changing the screen color profile.
      * [sys-tune](https://github.com/HookedBehemoth/sys-tune) - Overlay music player, works in background.

   * Other:
      * [FPSLocker Patches](https://github.com/masagrator/FPSLocker-Warehouse) - Patches for FPSLocker, so you don't have to download a separate patch for each game through the overlay.
      * [DVR Patches](https://github.com/exelix11/dvr-patches) - SysDVR patches, work without the system module, activating background recording in games where it is initially prohibited.
      * [Mod Alchemist](https://github.com/ppkantorski/Mod-Alchemist) - A package for downloading, installing, and managing mods for games.
      * [sys-ftpd](https://github.com/cathery/sys-ftpd) - FTP server running in background.



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
#### And also - a special thanks to the administration and members of Ultra Group



## Support

If you like the project and you have a desire to support me with a penny - I will be very grateful.
I have no other income at the moment, so any monetary help is very valuable to me.            
```
TON:  UQA9My51bkGZHbYhbdRZfp6B60N7VJfsnKl0sakgw9YhAPct
BTC:  18K6NN8NEavvMJL5Do3VTyJbL8NeZPHo93
USDT TRC20: TUZ5szAmRsnvBuC4rFB8RaAoCbN6Ucy4sL
```