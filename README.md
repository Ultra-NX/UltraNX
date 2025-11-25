# UltraNX by **[redraz](https://github.com/redraz)**

![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Ultra.png)

# [English Readme](README_ENG.md)

### [Группа в телеграме](https://t.me/UltraNX) | [Wiki](https://github.com/Ultra-NX/Ultra/wiki)

### Ultra - это функциональная кастомная прошивка для Nintendo Switch, с упором в разгон и улучшенный пользовательский опыт.

### [UltraNX 2.6|R3](https://github.com/Ultra-NX/UltraNX/releases/tag/2.6-R3) Поддерживает все HOS до 20.5.0 включительно

### [UltraNX 2.7|Pre2](https://github.com/Ultra-NX/UltraNX/releases/tag/2.7-Pre2) Поддерживает все HOS до 21.0.1 включительно. Не полноценный релиз!



## Особенности Ultra

* Предварительно настроенный OC Switchcraft (Преемник OC-Suite, аналог 4IFIR) с пресетами.
* Небольшой андервольт (сниженные вольтажи) в стоке, что заметно снижает потребление консоли, и заметный разгон памяти, который сделает игры плавнее.
* Лучший кастомизатор разгона для Свитч - [Ultra-Tuner](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Ultra-Tuner), позволяющий настраивать разгон прямо с консоли. Был первым, и остается неповторимым.
* Сборка максимально легкая и не нагруженная. В ней нет лишнего, минимум необходимый для разгона и комфортного использования.
* Модульная конструкция. В составе минимум приложений/плагинов/оверлеев, но вы всегда можете поставить еще через [Ultra Tuner](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater).
* Кастомная настройка работы системы охлаждения, и пресеты на выбор.
* Регулярные обновления, и активное комьюнити.
* DBI с встроенным notUltraNX репозиторием игр, больше не нужно каждый раз искать новый шоп Тинфоила.
* Подробная [Wiki](https://github.com/Ultra-NX/Ultra/wiki) в которой есть ответы почти на все вопросы.
* [Форки](https://github.com/Ultra-NX/Ultra-Resources/tree/main/patches) (свои модификации) программ и компонентов, нужные для удобства, безопасности и расширения возможностей:
   * Форк Атмосферы с прописанной версией Ультры в информации о системе, и отключенными репортами, обычно засоряющими сд карту, тратящими ее ресурс и ломающими файловую систему.
   * Форк Mission Control, с вырезанной "пасхалкой", делающей джойконы жовто-блакитными.



## Состав Ultra

1. **[Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)** - Atmosphère, кастомная прошивка для Nintendo Switch.
1. **[Hekate](https://github.com/CTCaer/hekate)** - Пользовательский графический загрузчик Nintendo Switch, патчер прошивки, инструментарий и многое другое.
1. **[Ultra Tuner](https://github.com/Ultra-NX/Ultra-Tuner)** - Пакет для Ultrahand, позволяющий произвести тонкую настройку параметров под свою консоль. В случае нестабильной работы разгона, или при желании увеличить производительность консоли, Ultra Tuner - Ваш незаменимый помощник.
1. **[OC-Switchcraft](https://github.com/halop/OC-Switchcraft-EOS/releases)**, форк **[OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite/)** - Загрузчик Атмосферы с разгоном от B3711 и Meha, позволяет выжать из N.Switch мощность Xbox One. Вовремя обновляется для поддержки новых возможностей Атмосферы.


1. **Установленные пейлоады**:
   * [Lockpick RCM](https://github.com/impeeza/Lockpick_RCMDecScots) - Программа для снятия ключей консоли.
   * [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer) - Низкоуровневый файловый менеджер для работы с системой.


1. **Установленные Homebrew**
   * [Sphaira](https://github.com/ITotalJustice/sphaira) - Современное Хоумбрю Меню, аналог nx-hbmenu
   * [AiO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater) - Программа для обновления UltraNX до актуальной версии, а так же для скачивания читов и HOS.
   * [Daybreak](https://github.com/Atmosphere-NX/Atmosphere) - Программа для обновления HOS (системного ПО).
   * [DBI](https://4pda.to/forum/index.php?showtopic=939714&st=1100#entry86288632) - Лучший файловый менеджер, менеджер сохранений и установщик программ на консоль.


1. **Установленные модули**
   * [SaltyNX](https://github.com/masagrator/SaltyNX) - Фоновый модуль, позволяющий модифицировать файлы\процессы в консоли, поддерживает плагины.
   * [sys-clk](https://github.com/ppkantorski/sys-clk) - Модуль отвечающий за разгон процессора, памяти и видеочипа - для лучшей производительности.
   * [nx-ovlloader](https://github.com/ppkantorski/nx-ovlloader) - С помощью этого модуля осуществляется переключение установленных модулей.
   * [sys-patch](https://github.com/impeeza/sys-patch) - Патчит систему на работу неподписанного софта вместо сигпатчей.
   * [Mission Control](https://github.com/ndeadly/MissionControl) - Модуль, позволяющий подключать практически любые геймпады к консоли по Bluetooth.
   * [sys-con](https://github.com/o0Zz/sys-con) - Модуль, позволяющий подключать практически любые геймпады к консоли по USB.
   * [Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay) - Специальное оверлей-меню для взаимодействия с системой: разгон, управление режимами через ReverseNX, включение читов, прочее. Также позволяет использовать самописные пакеты, например - Ultra Tuner.
     - **`Ultra OC (sys-clk)`**, мод [sys-clk](https://github.com/ppkantorski/sys-clk) - Оверлей для управления модулем sys-clk. Немного изменен мной, но без копания в исходниках (Так как они закрыты).
     - [Status Monitor](https://github.com/ppkantorski/Status-Monitor-Overlay), форк [Status Monitor](https://github.com/hanai3Bi/Status-Monitor-Overlay) - Оверлей позволяющий следить за параметрами консоли в реальном времени. Может выступать в качестве счетчика FPS. Сменить пресет Micro-оверлея можно в Tuner.
     - [FPSLocker](https://github.com/masagrator/FPSLocker) - Оверлей, позволяющий разблокировать 60 FPS в играх.
     - [EdiZon](https://github.com/ppkantorski/EdiZon-Overlay) - Оверлей для использования читов, включая графические.
     - [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT) - Оверлей для переключения запущенной игры в портатив\док, меняет настройки графики\разрешения в играх.
     - [Sysmodules](https://github.com/ppkantorski/ovl-sysmodules) - Оверлей для включения\отключения установленных системных модулей.


1. **Доступные для скачивания через [Ultra Tuner](https://github.com/Ultra-NX/UltraNX/wiki/Tuner-RU#ultra-tuner)**
   * Homebrews:
      * [DBI](https://4pda.to/forum/index.php?showtopic=939714&st=1100#entry86288632) - Здесь можно скачать DBI или обновить имеющийся.
      * [Linkalho](https://gbatemp.net/download/linkalho.38822) - Программа для привязки аккаунта. Без привязки не будут работать некоторые игры.
      * [Sphaira](https://github.com/ITotalJustice/sphaira) - Здесь можно обновить Sphaira\обновить ее конфиг.
      * [PPSSPP](https://gbatemp.net/threads/ppsspp-switch-standalone-beta.544071/post-10492671) - Эмулятор PSP.
      * [Moonlight](https://github.com/XITRIX/Moonlight-Switch) - Клиент Moonlight, позволяет транслировать на консоль игры с PC.
      * [ThemezerNX](https://github.com/suchmememanyskill/themezer-nx) + [NXThemes Installer](https://github.com/exelix11/SwitchThemeInjector) + [Theme Patches](https://github.com/exelix11/theme-patches) - Поиск и установка тем на свитч.
      * [Battery Desync Fix](https://github.com/CTCaer/battery_desync_fix_nx) - Программа для сброса контроллера батареи. Не используйте просто так!
      * [MemToolkitNX](https://discord.com/channels/854839758815363072/1173171845139288114/1324099100202766408) - Бенчмарк и Тестер памяти. Результат сильно зависит от разгона CPU.
      * [MemToolkitNX OLD](https://discord.com/channels/854839758815363072/1173171845139288114/1276196700750479480) - Бенчмарк и Тестер памяти. Результат сильно зависит от разгона CPU. Старая версия, которая многим нравится больше новой.
      * [MicroMemBench](https://github.com/rashevskyv/4IFIR) - Бенчмарк. Результат сильно зависит от разгона CPU. Версия из Чифира которая в реальном времени тестирует CPU Copy, что позволяет быстро узнать результат после изменения таймингов.

   * Overlays:
      * [Status Monitor](https://github.com/ppkantorski/Status-Monitor-Overlay) - Форк Status Monitor от kantorski.
      * [Tetris](https://github.com/ppkantorski/Tetris-Overlay) - Та самая игра в виде оверлея. Работает только на последних версиях Ultrahand.
      * [MasterVolume](https://github.com/averne/MasterVolume) - Регулировка глобальной громкости, позволяет поднять громкость выше максимума. Использовать аккуратно!
      * [NX-FanControl](https://github.com/Insektaure/NX-FanControl) - Модуль для ручной регулировки оборотов кулера. Изменения применяются сразу, модуль смотрит на температуру SOC а не Skin, как Атмосфера.
      * [BT Audio](https://github.com/masagrator/BT_Audio-ovl) - Оверлей, позволяющий быстро отключаться\подключаться к bluetooth-гарнитуре.
      * [Fizeau](https://github.com/averne/Fizeau) - Модуль для изменения цветового профиля экрана.
      * [sys-tune](https://github.com/HookedBehemoth/sys-tune) - Оверлей-музыкальный плеер, работает в фоне.

   * Other:
      * [FPSLocker Patches](https://github.com/masagrator/FPSLocker-Warehouse) - Пакет патчей для FPSLocker, позволяет обновить все патчи сразу, вместо скачивания по одному через оверлей FPSLocker'а. В Ультре по умолчанию всегда последние патчи, так что достаточно своевременно обновлять сборку.
      * [DVR Patches](https://github.com/exelix11/dvr-patches) - Патчи SysDVR, работают и без системного модуля, активируя фоновую запись в играх, где это изначально запрещено.
      * [Mod Alchemist](https://github.com/ppkantorski/Mod-Alchemist) - Пакет для скачивания, установки и управления модами для игр.
      * [sys-ftpd](https://github.com/tomvita/sys-ftpd-light) - FTP сервер, работающий на фоне.




## Лицензии

Ниже перечислены лицензии тех программ, которые были модифицированы специально для Ultra. Следуя положениям этих лицензий, весь код в модификациях распространяется под той же лицензией

[GPL 2.0](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE): 
  * [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)




## Благодарности 

* B3711
* ppkantorski
* Meha
* duckbill
* snupt
#### А так же - отдельная благодарность администрации и участникам Ultra Group



## Поддержка

Если вам нравится проект, и у вас появилось желание поддержать меня копеечкой - я буду очень благодарен.
У меня в данный момент нет других заработков, так что любая денежная помощь очень ценна для меня. 
```
СБП (Т-Банк): +79168089980

Альфа : 2200152336577997
Т-Банк : 2200700170486970
Сбер : 2202200513345833

TON:  UQA9My51bkGZHbYhbdRZfp6B60N7VJfsnKl0sakgw9YhAPct
BTC:  18K6NN8NEavvMJL5Do3VTyJbL8NeZPHo93
USDT TRC20: TUZ5szAmRsnvBuC4rFB8RaAoCbN6Ucy4sL
```           

### Т-Банк QR
![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Tinkoff%20small.png)