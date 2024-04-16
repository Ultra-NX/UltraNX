# Ultra-NX by **[redraz](https://github.com/redraz)**

![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Ultra.png)

### [English Readme](README_ENG.md) | [Группа в телеграме](https://t.me/UltraNX) | [Wiki](https://github.com/Ultra-NX/Ultra/wiki)

### Ultra - это функциональная кастомная прошивка для Nintendo Switch, с упором в разгон и улучшенный пользовательский опыт.

### [Ultra 2.1](https://github.com/Ultra-NX/Ultra/releases/tag/2.1-R1) Поддерживает HOS 18 и все ревизии консолей

## Особенности Ultra

* Предварительно настроенный OC-Suite с пресетами.
* Лучший кастомизатор разгона для Свитч - [Ultra-Tuner](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Ultra-Tuner), позволяющий настраивать разгон прямо с консоли. Был первым, и остается неповторимым.
* Сборка максимально легкая и не нагруженная. В ней нет лишнего, минимум необходимый для разгона и комфортного использования.
* Модульная конструкция. В составе минимум приложений/плагинов/оверлеев, но вы всегда можете поставить еще через комплектный [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater).
* Выбор пресета работы системы охлаждения, либо шумно но холодно, либо тихо но горячо.
* Кастомный Ultra Monitor c FPS и системными метриками.
* Регулярные обновления, и активное коммьюнити.
* Подробная [Wiki](https://github.com/Ultra-NX/Ultra/wiki) в которой есть ответы почти на все вопросы.

## Состав Ultra

1. **[Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)** - Atmosphère, кастомная прошивка для Nintendo Switch.
1. **[Hekate](https://github.com/CTCaer/hekate)** - Пользовательский графический загрузчик Nintendo Switch, патчер прошивки, инструментарий и многое другое.
1. **[Ultra Tuner](https://github.com/Ultra-NX/Ultra-Tuner)** - Пакет для Ultra Paw (форка Ultrahand), позволяющий произвести тонкую настройку параметров под свою консоль. В случае нестабильной работы разгона, или при желании увеличить производительность консоли, Ultra Tuner - Ваш незаменимый помощник.
1. **`OC-Switchcraft`**, форк **[OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite/)** - Лоадер атмосферы с разгоном от B3711, позволяет выжать из N.Switch мощность Xbox One. Вовремя обновляется для поддержки новых возможностей Атмосферы.
1. **Установленные пейлоады**:
   * [Lockpick_RCM](https://sigmapatches.su) - Программа для снятия ключей консоли.
   * [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer) - Низкоуровневый файловый менеджер для работы с системой.
1. **Установленные Homebrew**
   * [AiO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater) - Программа для обновления Ultra до актуальной версии, а так же для скачивания читов.
   * [Daybreak](https://codeberg.org/rashevskyv/kefir) - Программа для обновления системного ПО.
   * [DBI](https://github.com/rashevskyv/dbi) - Лучший файловый менеджер, менеджер сохранений и установщик программ на консоль. Если вам нужна другая локализация - в [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater) есть выбор из EN-RU-PTBR-ZHCN.
1. **Установленные модули**
   * [SaltyNX](https://github.com/masagrator/SaltyNX) - Фоновый модуль, позволяющий модифицировать файлы\процессы в консоли, поддерживает плагины. Не совместим с 32-х битными играми (список на гитхабе проекта).
   * [sys-clk](https://github.com/hanai3Bi/Switch-OC-Suite) - Модуль отвечающий за разгон процессора, памяти и видеочипа - для лучшей производительности. Периодически меняю версии от разных авторов. Оригинальные авторы: Meha/hanai3Bi, lineon, p-sam.
   * [nx-ovlloader](https://github.com/zdm65477730/nx-ovlloader/) - С помощью этого модуля осуществляется переключение установленных модулей.
   * [Ultra Paw Overlay](https://github.com/Ultra-NX/Ultra-Paw-Overlay), форк [Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay) - Специальное оверлей-меню для взаимодействия с системой: разгон, управление режимами через ReverseNX, включение читов, прочее. Так же позволяет использовать самописные пакеты, например - Ultra Tuner.
     - **`Ultra-Overlay`**, мод [sys-clk](https://github.com/hanai3Bi/Switch-OC-Suite) - Оверлей для управления модулем sys-clk. Немного изменен мной, но без копания в исходниках.
     - [Ultra Status Monitor](https://github.com/Ultra-NX/Ultra-Status-Monitor), форк [Status Monitor](https://github.com/hanai3Bi/Status-Monitor-Overlay) - Оверлей позволяющий следить за параметрами консоли в реальном времени. Может выступать в качестве счетчика FPS. Сменить пресет Micro-оверлея можно в Updater.
     - [FPSLocker](https://github.com/masagrator/FPSLocker) - Оверлей, позволяющий разблокировать 60 FPS в играх.
     - [EdiZon](https://github.com/proferabg/EdiZon-Overlay) - Оверлей для использования читов.
     - [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT) - Оверлей для управления ReverseNX.
     - [Sysmodules](https://github.com/WerWolv/ovl-sysmodules/) - Оверлей для включения и отключения установленных системных модулей.
1. **Доступные для скачивания через [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater)**
   * [Linkalho](https://github.com/rdmrocha/linkalho) - Программа для привязки аккаунта.
   * [ReverseNX Tool](https://github.com/masagrator/ReverseNX-Tool) - Программа для управления ReverseNX.
   * [Battery Desync Fix](https://github.com/CTCaer/battery_desync_fix_nx) - Программа для сброса контроллера батареи. Не используйте просто так!
   * [HB App Store](https://github.com/fortheusers/hb-appstore) - Бесплатный магазин для скачивания Homebrew приложений.
   * [SysDVR-conf](https://github.com/exelix11/SysDVR) - Программа для установки/удаления dvr патчей для игр. Патчи включают возможность записи в тех играх, где она отключена, но ломают некоторые другие игры, например "Ведьмак 3".
   * [sys-ftpd](https://github.com/tomvita/sys-ftpd-light) - FTP сервер, работающий на фоне.
   * [sys-con](https://github.com/cathery/sys-con) - Модуль, позволяющий подключать практически любые геймпады к консоли по USB.
   * [Mission Control](https://codeberg.org/rashevskyv/kefir) - Модуль, позволяющий подключать практически любые геймпады к консоли по Bluetooth.
   * [Observer-Tool](https://github.com/rkuchkarov/Observer-Tool) - Оверлей с максимально подробным отображением статистики системы, напоминает Afterburner на PC.
   * **`MemToolkitNX`** - Бенчмарк и Тестер памяти. Результат сильно зависит от разгона CPU.


## Лицензии

Ниже перечислены лицензии тех программ, которые были модифицированы специально для Ultra. Следуя положениям этих лицензий, весь код в модификациях распространяется под той же лицензией

[GPL 2.0](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE): 
  * [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
  * [Status-Monitor-Overlay](https://github.com/masagrator/Status-Monitor-Overlay)

[CC-BY-NC-4.0 License](https://github.com/ppkantorski/Ultrahand-Overlay/blob/main/LICENSE)
  * [Ultrahand-Overlay](https://github.com/ppkantorski/Ultrahand-Overlay)

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