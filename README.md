# Ultra-NX by **[redraz](https://github.com/redraz)**

![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Ultra.png)

### [English Readme](README_ENG.md) | [Группа в телеграме](t.me/UltraNX) | [Wiki](https://github.com/Ultra-NX/Ultra/wiki)

### Ultra - это функциональная кастомная прошивка для Nintendo Switch, с упором в разгон и улучшенный пользовательский опыт.

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
1. **[OC-Suite](https://github.com/hanai3Bi/Switch-OC-Suite/)** - Пакет разгона от Meha/hanai3Bi, открытые исходники гарантируют надежность и отсутствие скрытых гадостей. Вовремя обновляется для поддержки новых возможностей Атмосферы. Используется модифицированный loader.kip от B3711, в котором больше таблиц андервольта CPU (6 уровней против 2х).
   - Временно используется оригинал от Meha.
1. **Установленные пейлоады**:
   * [Lockpick_RCM](https://codeberg.org/rashevskyv/kefir) - Программа для снятия ключей консоли.
   * [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer) - Низкоуровневый файловый менеджер для работы с системой.
1. **Установленные Homebrew**
   * [AiO Switch Updater](https://github.com/HamletDuFromage/aio-switch-updater) - Программа для обновления Ultra до актуальной версии, а так же для скачивания читов.
   * [DBI](https://github.com/rashevskyv/dbi) - Лучший файловый менеджер, менеджер сохранений и установщик программ на консоль. Если вам нужна другая локализация - в Updater есть выбор из EN-RU-PTBR-ZHCN.
1. **Установленные модули**
   * [SaltyNX](https://github.com/masagrator/SaltyNX) - Фоновый модуль, позволяющий модифицировать файлы\процессы в консоли, поддерживает плагины. Не совместим с 32-х битными играми (список на гитхабе проекта).
   * [sys-clk](https://github.com/hanai3Bi/Switch-OC-Suite) - Модуль отвечающий за разгон процессора, памяти и видеочипа - для лучшей производительности. Переодически меняю версии от разных авторов. Оригинальные авторы: Meha/hanai3Bi, lineon, p-sam.
   * [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader/) - С помощью этого модуля осуществляется переключение установленных модулей.
   * [sys-patch](https://github.com/ITotalJustice/sys-patch/) - Создает/обновляет патчи при запуске системы. Не заменяет сигпатчи, но избавляет от регулярного ручного обновления патчей системы.
   * [Ultra Paw Overlay](https://github.com/Ultra-NX/Ultra-Paw-Overlay), форк [Ultrahand Overlay](https://github.com/ppkantorski/Ultrahand-Overlay) - Специальное оверлей-меню для взаимодействия с системой: разгон, управление режимами через ReverseNX, включение читов, прочее. Так же позволяет использовать самописные пакеты, например - Ultra Tuner.
     - **`Ultra-Overlay`**, мод [sys-clk](https://github.com/hanai3Bi/Switch-OC-Suite) - Оверлей для управления модулем sys-clk-oc. Немного изменен мной, но без копания в исходниках.
     - [Ultra Monitor](https://github.com/Ultra-NX/Ultra-Status-Monitor), форк [Status Monitor](https://github.com/masagrator/Status-Monitor-Overlay) - Оверлей позволяющий следить за параметрами консоли в реальном времени. Может выступать в качестве счетчика FPS. Настроить внешность Micro-оверлея можно в Updater.
     - [FPSLocker](https://github.com/masagrator/FPSLocker) - Оверлей, позволяющий разблокировать 60 FPS в играх.
     - [EdiZon](https://github.com/proferabg/EdiZon-Overlay) - Оверлей для использования читов.
     - [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT) - Оверлей для управления модулем ReverseNX.
     - [Sysmodules](https://github.com/WerWolv/ovl-sysmodules/) - Оверлей для включения и отключения установленных системных модулей.
1. **Доступные для скачивания через [Updater](https://github.com/Ultra-NX/Ultra/wiki/Tuner-RU#Updater)**
   * [Daybreak](https://github.com/Atmosphere-NX/Atmosphere/tree/master/troposphere/daybreak) - программа для обновления системного ПО.
   * [Linkalho](https://github.com/rdmrocha/linkalho) - Программа для привязки аккаунта.
   * [ReverseNX Tool](https://github.com/masagrator/ReverseNX-Tool) - Программа для управления модулем ReverseNX.
   * [Battery Desync Fix](https://github.com/CTCaer/battery_desync_fix_nx) - Программа для сброса контроллера батареи. Не используйте просто так!
   * [HB App Store](https://github.com/fortheusers/hb-appstore) - Бесплатный магазин для скачивания Homebrew приложений.
   * [SysDVR](https://github.com/exelix11/SysDVR) - Программа и модуль для передачи изображения с консоли на ПК или другие устройства.
   * [sys-ftpd](https://github.com/cathery/sys-ftpd) - FTP сервер, работающий в фоне.
   * [Observer-Tool](https://github.com/rkuchkarov/Observer-Tool) - Оверлей с максимально подробным отображением статистики системы, напоминает Afterburner на PC.
   * **`MemToolkitNX`** - Бенчмарк и Тестер памяти. Результат сильно зависит от разгона CPU.
   * **`RaytracingNX`** - Бенчмарк цпу.
   * **`stress-nx`** - Стресс-тест/бенчмарк цпу.
   * **`mhz`** - Программа показывающая честную максимальную частоту цпу.


## Лицензии

Ниже перечислены лицензии тех программ, которые были модифицированы специально для Ultra. Следуя положениям этих лицензий, весь код в модификациях распространяется под той же лицензией

[GPL 2.0](https://github.com/Atmosphere-NX/Atmosphere/blob/master/LICENSE): 
  * [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere)
  * [Status-Monitor-Overlay](https://github.com/masagrator/Status-Monitor-Overlay)

[CC-BY-NC-4.0 License](https://github.com/ppkantorski/Ultrahand-Overlay/blob/main/LICENSE)
  * [Ultrahand-Overlay](https://github.com/ppkantorski/Ultrahand-Overlay)

## Благодарности 

* Cooler3D
* Efosamark
* rashevskyv/хНЯ
* snupt/Catcher In The Grain Field
* ppkantorski/b0rd2dEAth
* hanai3Bi/Meha
* 4PDA
#### А так же - отдельная благодарность администрации и участникам Ultra Group

## Поддержка

Если вам понравились результаты моих стараний, и у вас появилось желание закинуть мне на шаурму - я буду очень благодарен.
* Сделать это можно через @wallet telegram, на мой аккаунт @redraz
* Либо через Сбер: 2202200513345833
* Так же по QR через Tinkoff
![](https://github.com/Ultra-NX/Ultra-Resources/raw/main/Tinkoff.png)