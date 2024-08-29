# Ultra-NX by **[redraz](https://github.com/redraz)**

![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Ultra.png)

# [English Readme](README_ENG.md)

### [Группа в телеграме](https://t.me/UltraNX) | [Wiki](https://github.com/Ultra-NX/Ultra/wiki)

### Ultra - это функциональная кастомная прошивка для Nintendo Switch, с упором в разгон и улучшенный пользовательский опыт.

### [Ultra 2.2](https://github.com/Ultra-NX/Ultra/releases/latest) Поддерживает HOS 18.1.0 и все ревизии консолей



## Особенности Ultra

* Предварительно настроенный OC Switchcraft (Преемник OC-Suite) с пресетами.
* Лучший кастомизатор разгона для Свитч - [Ultra-Tuner](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Ultra-Tuner), позволяющий настраивать разгон прямо с консоли. Был первым, и остается неповторимым.
* Сборка максимально легкая и не нагруженная. В ней нет лишнего, минимум необходимый для разгона и комфортного использования.
* Модульная конструкция. В составе минимум приложений/плагинов/оверлеев, но вы всегда можете поставить еще через [Ultra Tuner](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater).
* Кастомная настройка работы системы охлаждения, и пресеты на выбор.
* Регулярные обновления, и активное комьюнити.
* DBI с встроенным notUltraNX репозиторием игр, больше не нужно каждый раз искать новый шоп Тинфоила.
* Подробная [Wiki](https://github.com/Ultra-NX/Ultra/wiki) в которой есть ответы почти на все вопросы.
* [Форки](https://github.com/Ultra-NX/Ultra-Resources/tree/main/patches) (свои модификации) программ и компонентов, нужные для удобства, безопасности и расширения возможностей:
   * Форк Атмосферы с прописанной версией Ультры в информации о системе, и отключенными репортами, обычно засоряющими сд карту, тратящими ее ресурс и ломающими файловю систему.
   * Форки SaltyNX и FPSLocker, с поддержкой изменения частоты обновления экрана и с поддержкой OLED.
   * Форк Status Monitor с отображением текущих вольтажей и уникальными модулями Микро Оверлея, пресеты которых можно менять через Ultra Tuner.



## Состав Ultra

1. **[Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)** - Atmosphère, кастомная прошивка для Nintendo Switch.
1. **[Hekate](https://github.com/CTCaer/hekate)** - Пользовательский графический загрузчик Nintendo Switch, патчер прошивки, инструментарий и многое другое.
1. **[Ultra Tuner](https://github.com/Ultra-NX/Ultra-Tuner)** - Пакет для Ultrahand, позволяющий произвести тонкую настройку параметров под свою консоль. В случае нестабильной работы разгона, или при желании увеличить производительность консоли, Ultra Tuner - Ваш незаменимый помощник.
1. **[OC-Switchcraft](https://github.com/halop/OC_Toolkit_SC_EOS)**, форк **[OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite/)** - Лоадер атмосферы с разгоном от B3711, позволяет выжать из N.Switch мощность 1/2 Xbox One. Вовремя обновляется для поддержки новых возможностей Атмосферы.


1. **Установленные пейлоады**:
   * [Lockpick_RCM](https://www.gamebrew.org/wiki/Lockpick_RCM_Switch) - Программа для снятия ключей консоли.
   * [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer) - Низкоуровневый файловый менеджер для работы с системой.


1. **Установленные Homebrew**
   * [AiO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater) - Программа для обновления Ultra до актуальной версии, а так же для скачивания читов.
   * [Daybreak](https://github.com/rashevskyv/kefir/releases/latest) - Программа для обновления системного ПО.
   * [DBI](https://github.com/rashevskyv/dbi) - Лучший файловый менеджер, менеджер сохранений и установщик программ на консоль. Если вам нужна другая локализация - в [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater) есть выбор из EN-RU-PTBR-ZHCN.


1. **Установленные модули**
   * [SaltyNX](https://github.com/masagrator/SaltyNX) - Фоновый модуль, позволяющий модифицировать файлы\процессы в консоли, поддерживает плагины. Не совместим с 32-х битными играми (список на гитхабе проекта).
   * [sys-clk](https://github.com/halop/OC_Toolkit_SC_EOS) - Модуль отвечающий за разгон процессора, памяти и видеочипа - для лучшей производительности. Периодически меняю версии от разных авторов. Оригинальные авторы: Meha/hanai3Bi, lineon, p-sam.
   * [nx-ovlloader](https://github.com/ppkantorski/nx-ovlloader) - С помощью этого модуля осуществляется переключение установленных модулей.
   * [sys-patch](https://www.gamebrew.org/wiki/Sys-patch_Switch) - Патчит систему на работу неподписанного софта вместо сигпатчей.
   * [Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay) - Специальное оверлей-меню для взаимодействия с системой: разгон, управление режимами через ReverseNX, включение читов, прочее. Так же позволяет использовать самописные пакеты, например - Ultra Tuner.
     - **`Ultra-Overlay`**, мод [sys-clk](https://github.com/halop/OC_Toolkit_SC_EOS) - Оверлей для управления модулем sys-clk. Немного изменен мной, но без копания в исходниках (Так как они закрыты).
     - [Status Monitor](https://github.com/Ultra-NX/Status-Monitor-Overlay), форк [Status Monitor](https://github.com/hanai3Bi/Status-Monitor-Overlay) - Оверлей позволяющий следить за параметрами консоли в реальном времени. Может выступать в качестве счетчика FPS. Сменить пресет Micro-оверлея можно в Updater.
     - [FPSLocker](https://github.com/masagrator/FPSLocker) - Оверлей, позволяющий разблокировать 60 FPS в играх.
     - [EdiZon](https://github.com/proferabg/EdiZon-Overlay) - Оверлей для использования читов.
     - [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT) - Оверлей для управления ReverseNX.
     - [Sysmodules](https://github.com/WerWolv/ovl-sysmodules/) - Оверлей для включения и отключения установленных системных модулей.


1. **Доступные для скачивания через [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater)**
   * Homebrews:
      * [Linkalho](https://www.gamebrew.org/wiki/Linkalho_Switch) - Программа для привязки аккаунта.
      * [Tinfoil](https://tinfoil.io) - Установщик и каталог игр.
      * [HB App Store](https://github.com/fortheusers/hb-appstore) - Бесплатный магазин для скачивания Homebrew приложений.
      * [ThemezerNX](https://github.com/suchmememanyskill/themezer-nx) + [NXThemes Installer](https://github.com/exelix11/SwitchThemeInjector) + [Theme Patches](https://github.com/exelix11/theme-patches) - Поиск и установка тем на свитч.
      * [ReverseNX Tool](https://github.com/masagrator/ReverseNX-Tool) - Программа для управления ReverseNX.
      * [Battery Desync Fix](https://github.com/CTCaer/battery_desync_fix_nx) - Программа для сброса контроллера батареи. Не используйте просто так!
      * **`MemToolkitNX`** - Бенчмарк и Тестер памяти. Результат сильно зависит от разгона CPU.
   * Overlays:
      * [MasterVolume](https://github.com/averne/MasterVolume) - Регулировка глобальной громкости, позволяет поднять громкость выше максимума. Использовать аккуратно!
      * [Fizeau](https://github.com/averne/Fizeau) - Модуль для изменения цветового профиля экрана.
      * [sys-tune](https://github.com/HookedBehemoth/sys-tune) - Оверлей-музыкальный плеер, работает в фоне.
   * Other:
      * [FPSLocker Patches](https://github.com/masagrator/FPSLocker-Warehouse) - Патчи для FPSLocker, что бы не качать отдельно патч для каждой игры через оверлей.
      * [DVR Patches](https://github.com/exelix11/dvr-patches) - Патчи SysDVR, работают и без системного модуля, активируя фоновую запись в играх, где это изначально запрещено.
      * [TriPlayer](https://github.com/DefenderOfHyrule/TriPlayer) - Хоумбрю-музыкальный плеер, который работает через системный модуль, и может сворачиваться, работая в фоне.
      * [Mission Control](https://github.com/ndeadly/MissionControl) - Модуль, позволяющий подключать практически любые геймпады к консоли по Bluetooth.
      * [sys-con](https://github.com/o0Zz/sys-con) - Модуль, позволяющий подключать практически любые геймпады к консоли по USB.
      * [sys-ftpd](https://github.com/tomvita/sys-ftpd-light) - FTP сервер, работающий на фоне.


1. **Содержимое [Homebrews Pack](https://github.com/Ultra-NX/Ultra/releases/latest)**
*
   * [HB App Store](https://github.com/fortheusers/hb-appstore) - Бесплатный магазин для скачивания Homebrew приложений.
   * [Tinfoil](https://tinfoil.io) - Установщик и каталог игр.
   * [ThemezerNX](https://github.com/suchmememanyskill/themezer-nx) + [NXThemes Installer](https://github.com/exelix11/SwitchThemeInjector) + [Theme Patches](https://github.com/exelix11/theme-patches) - Поиск и установка тем на свитч.
   * [Mission Control](https://github.com/ndeadly/MissionControl) - Модуль, позволяющий подключать практически любые геймпады к консоли по Bluetooth.
   * [sys-con](https://github.com/o0Zz/sys-con) - Модуль, позволяющий подключать практически любые геймпады к консоли по USB.




## Лицензии

Ниже перечислены лицензии тех программ, которые были модифицированы специально для Ultra. Следуя положениям этих лицензий, весь код в модификациях распространяется под той же лицензией

[GPL 2.0](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE): 
  * [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
  * [Status-Monitor-Overlay](https://github.com/masagrator/Status-Monitor-Overlay)

[MIT License](https://github.com/masagrator/FPSLocker/blob/main/LICENSE)
  * [FPSLocker](https://github.com/masagrator/FPSLocker)




## Благодарности 

* Meha
* B3711
* ppkantorski
* Cooler3D
* rashevskyv
* snupt
* 4PDA
#### А так же - отдельная благодарность администрации и участникам Ultra Group



## Поддержка

Если вам нравится проект, и у вас появилось желание поддержать меня копеечкой - я буду очень благодарен.
У меня в данный момент нет других заработков, так что любая денежная помощь очень ценна для меня.            

### Tinkoff QR
![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Tinkoff%20small.png)
```
TON:  UQDioCnnPI5sk4KvxWzfPWsWbAyWCkzwhaYjy8Qpg2QwWMiL
BTC:  1HsC4z8X1YkZzcSKZz1t7MXRa7rPi8qChV
USDT: TQi3qLVrNGcr6avfVQBXRjpPTyvp5JZ7i2

Сбербанк: 2202200513345833
Tinkoff:  2200700170486970
```