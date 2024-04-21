# G-Helper - Легкий инструмент управления ноутбуками Asus
[![GitHub release](https://img.shields.io/github/release/seerge/g-helper)](https://GitHub.com/seerge/g-helper/releases/) 
[![Github all releases](https://img.shields.io/github/downloads/seerge/g-helper/total)](https://GitHub.com/seerge/g-helper/releases/)

Небольшая и легкая альтернатива Armory Crate для ноутбуков Asus, предлагающая практически ту же функциональность без дополнительной нагрузки и ненужных сервисов. Работает со всеми популярными моделями, такими как ROG Zephyrus G14, G15, G16, M16, Flow X13, Flow X16, Flow Z13, TUF Series, Strix/Scar Series, ProArt, Vivobook, Zenbook, ROG Ally и многими другими! 

# [:floppy_disk:Download](https://github.com/seerge/g-helper/releases/latest/download/GHelper.zip)

- [FAQ](https://github.com/seerge/g-helper/wiki/FAQ)
- [НАстройки и требования](https://github.com/seerge/g-helper/wiki/Requirements)
- [Поиск неисправностей](https://github.com/seerge/g-helper/wiki/Troubleshooting)
- [Настройки для опытных пользователей](https://github.com/seerge/g-helper/wiki/Power-user-settings)

### Поддержка проекта: [:euro: Paypal EUR](https://www.paypal.com/donate/?hosted_button_id=4HMSHS4EBQWTA) | [💵 Paypal USD](https://www.paypal.com/donate/?hosted_button_id=SRM6QUX6ACXDY)  | [🪙 Stripe](https://buy.stripe.com/00gaFJ9Lf79v7WobII)

[![Скачать G-Helper](https://github.com/seerge/g-helper/assets/5920850/4d98465a-63a5-4498-ae14-afb3e67e7e82)](https://github.com/seerge/g-helper/releases/latest/download/GHelper.zip)

## :loudspeaker: Обзоры и гайды на YouTube
| [![Youtube review Josh Cravey](https://i.ytimg.com/vi/hqe-PjuE-K8/hqdefault.jpg)](https://www.youtube.com/watch?v=hqe-PjuE-K8) | [![Youtube review cbutters Tech](https://i.ytimg.com/vi/6aVdwJKZSSc/hqdefault.jpg)](https://www.youtube.com/watch?v=6aVdwJKZSSc) |
| ----------------- | ---------------- | 
| [Josh Cravey](https://www.youtube.com/watch?v=hqe-PjuE-K8) | [cbutters Tech](https://www.youtube.com/watch?v=6aVdwJKZSSc) | 

## :gift: Преимущества 

1. Бесшовное и автоматическое переключение графического процессора
2. Все режимы производительности можно полностью настроить с помощью ограничений мощности и кривых вентилятора.
3. Легкий. Ничего не устанавливает в вашу систему. Просто один exe для запуска
4. Простой и понятный собственный пользовательский интерфейс с легким доступом ко всем настройкам.
5. FN-Lock и пользовательские горячие клавиши

![Screenshot 2024-03-11 104354](https://github.com/seerge/g-helper/assets/5920850/626a5a6e-fdae-431c-843e-92886c8420ee)

### :zap: Особенности

1. Режимы производительности: Тихий, Сбалансированный, Турбо (встроенный, с кривыми вентилятора по умолчанию).
2. Режимы графического процессора: Eco — Standard — Ultimate — Optimized
3. Управление частотой обновления экрана с помощью функции Display Overdrive (OD)
4. Редактор пользовательских кривых вентилятора, ограничения мощности и выбор турбонаддува для каждого режима производительности.
5. Управление освещением Anime Matrix или Slash, включая анимированные GIF-файлы, часы и визуализатор звука.
6. Режимы и цвета анимации подсветки
7. Пользовательские горячие клавиши (M-клавиши, клавиши FN+X)
8. Отслеживайте температуру процессора и графического процессора, скорость вращения вентиляторов и состояние батареи.
9. Ограничение заряда аккумулятора для сохранения его работоспособности
10. Разгон и понижение напряжения графического процессора NVIDIA
11. Мобильное управление XG
12. Андервольтинг процессора AMD
13. Обновления BIOS и драйверов
14. Настройки мыши Asus
15. Многозонный переключатель с мини-светодиодом
16. Затемнение без мерцания и визуальные режимы

### :gear: Автоматизация
- Переключение режима производительности при работе от батареи или подключении к сети
- Режим оптимизированного графического процессора — отключает dGPU при работе от батареи и включает при подключении к сети.
- Автоматическая частота обновления экрана (60 Гц при работе от батареи и макс. Гц при подключении к сети)
- Тайм-аут подсветки клавиатуры при работе от батареи или при подключении к сети

_Чтобы автоматическое переключение и горячие клавиши работали, приложение должно продолжать работать в трее. Он не потребляет никаких ресурсов._

### :rocket: Режимы производительности

<img align="right" width="300" src="https://github.com/seerge/g-helper/assets/5920850/3e119674-db8d-486b-aa65-2bf9b61f9aa6">

Все режимы **встроены в BIOS** вместе с кривыми вентиляторов по умолчанию и ограничениями мощности, и они **такие же**, как и в Armory Crate.

Каждый режим BIOS связан с соответствующим режимом питания Windows. Вы можете настроить этот параметр в разделе ``Fans + Power``

1. **Тихий режим** в BIOS + **Энергопотребления** Лучший режим
2. **Сбалансированный** (производительность при переменном токе)  в BIOS  + режим **сбалансированного** питания
3. **Турбо ** в BIOS + режим **максимальной производительности**
   

### :video_game: Режимы графического процессора

1. **Эко** :  включен только встроенный графический процессор с низким энергопотреблением, приводы iGPU встроены в дисплей.
2. **Стандарт** (MS Hybrid) : включены iGPU и dGPU, диски iGPU встроены в дисплей.
3. **Ultimate**: iGPU и dGPU включены, но диски dGPU имеют встроенный дисплей (поддерживается на моделях 2022+)
4. **Оптимизировано**: отключает dGPU от батареи (Эко) и включает при подключении (Стандарт)

![Screenshot 2024-03-11 111818](https://github.com/seerge/g-helper/assets/5920850/fd69a81e-978d-4d5c-a0a8-26da51f90a5b)

![GPU Modes](https://github.com/seerge/g-helper/assets/5920850/65c6bdd5-728c-4965-b544-fcf5a85ed6a2)


### :mouse: Поддержка Asus Mouse и других периферийных устройств

[Поддерживаемые модели](https://github.com/seerge/g-helper/discussions/900)
- ROG Chakram X (P708)
- ROG Chakram Core (P511)
- ROG Gladius II and Gladius II Origin (P502 and P504)
- ROG Gladius III
- ROG Gladius III Wireless
- ROG Harpe Ace Aim Lab Edition
- ROG Keris Wireless
- ROG Strix Carry (P508)
- ROG Strix III Gladius III Aimpoint Wireless (P711)
- ROG Strix Impact III (P518)
- ROG Spatha
- ROG Strix Impact II Wireless
- TUF Gaming M4 Wireless (P306)
- TUF Gaming M3
- TUF Gaming M3 Gen II

Огромное спасибо [@IceStormNG](https://github.com/IceStormNG) 👑 за вклад и исследования (!).

### ⌨️ Горячие клавиши

- ``Fn + F5 / Fn + Shift + F5`` - Переключение режимов производительности вперед/назад.
- ``Ctrl + Shift + F5 / Ctrl + Shift + Alt + F5`` - Переключение режимов производительности вперед/назад.
- ``Ctrl + Shift + F12`` - Открыть окно G-Helper
- ``Ctrl + M1 / M2`` -  Яркость экрана вниз/вверх
- ``Shift + M1 / M2`` - Яркость подсветки Вниз/Вверх
- ``Fn + C`` - Fn-Lock
- ``Fn + Shift + F7 / F8`` - Matrix / Slash Lighting brightness Down / Up
- ``Fn + Shift + F7 / F8`` - Screenpad brightness Down / Up
- ``Ctrl + Shift + F20`` - Отключение микрофона
- ``Ctrl + Shift + Alt + F13`` - Переключение частоты обновления дисплея
- ``Ctrl + Shift + Alt + F14`` - Эко-режим графического процессора
- ``Ctrl + Shift + Alt + F15`` - Стандартный режим графического процессора
- ``Ctrl + Shift + Alt + F16`` - Тихий режим
- ``Ctrl + Shift + Alt + F17`` - Сбалансированный режим
- ``Ctrl + Shift + Alt + F18`` - Турбо режим
- ``Ctrl + Shift + Alt + F19`` - Custom 1 (если существует)
- ``Ctrl + Shift + Alt + F20`` - Custom 2 (если существует)
- [Custom keybindings / hotkeys](https://github.com/seerge/g-helper/wiki/Power-user-settings#custom-hotkey-actions)

### 🎮ROG Ally горячие клавиши
- ``M + DPad Left / Right`` - Яркость дисплея
- ``M + DPad Up`` - Сенсорная клавиатура
- ``M + DPad Down`` - Показать рабочий стол
- ``M + Y`` - Переключить наложение AMD
- ``M + X`` - Скриншот
- ``M + Right Stick Click`` - Режим контроллера

------------------
#### Если вам нравится приложение, вы можете сделать пожертвование

| [Paypal in EUR](https://www.paypal.com/donate/?hosted_button_id=4HMSHS4EBQWTA) | [Paypal in USD](https://www.paypal.com/donate/?hosted_button_id=SRM6QUX6ACXDY) |
| ------------------------------------------ | ----------------------------------------------- |
| [![QR Code](https://user-images.githubusercontent.com/5920850/233658717-0441494d-fede-4a2c-b4f2-4b16a184a69a.png)](https://www.paypal.com/donate/?hosted_button_id=4HMSHS4EBQWTA) | [![QR Code](https://github-production-user-asset-6210df.s3.amazonaws.com/5920850/239492811-b487e89a-3df6-42ea-bdb8-24c455ab2310.png)](https://www.paypal.com/donate/?hosted_button_id=SRM6QUX6ACXDY) |

------------------

### 🔖 Важное примечание

G-Helper **НЕ** является операционной системой, прошивкой или драйвером. В любом случае он **НЕ** «запускает» ваше оборудование в режиме реального времени.

Это приложение, которое позволяет вам выбрать один из предопределенных режимов работы, созданных производителем (и сохраненных в BIOS), и при необходимости (!) Установить некоторые настройки, которые уже существуют на вашем устройстве, так же, как это может сделать Armory Crate. Он делает это с помощью «драйвера» интерфейса управления системой Asus, который Armory использует для этого.

Если вы используете эквивалентный режим/настройки, как в Armory Crate, производительность и поведение вашего устройства не будут отличаться.

Роль G-Helper для вашего ноутбука аналогична роли пульта дистанционного управления для вашего телевизора.

### Используемые библиотеки
- [Ядро Linux](https://github.com/torvalds/linux/blob/master/drivers/platform/x86/asus-wmi.c) для некоторых базовых конечных точек в интерфейсе ASUS ACPI/WMI.
- [NvAPIWrapper](https://github.com/falahati/NvAPIWrapper) для доступа к Nvidia API
- [Starlight](https://github.com/vddCore/Starlight) для протокола связи anime matrix  
- [UXTU](https://github.com/JamesCJ60/Universal-x86-Tuning-Utility) для пониженного напряжения с использованием Ryzen System Management Unit
- [AsusCtl](https://gitlab.com/asus-linux/asusctl) за вдохновение и небольшой реверс-инжиниринг

### Отказ от ответственности
«ROG», «TUF» и «Armory Crate» являются товарными знаками и принадлежат компании AsusTek Computer, Inc. Я не предъявляю претензий на эти или какие-либо активы, принадлежащие AsusTek Computer, и использую их исключительно в информационных целях.

ПРОГРАММНОЕ ОБЕСПЕЧЕНИЕ ПРЕДОСТАВЛЯЕТСЯ «КАК ЕСТЬ» И БЕЗ КАКИХ-ЛИБО ГАРАНТИЙ, ЯВНЫХ ИЛИ ПОДРАЗУМЕВАЕМЫХ, ВКЛЮЧАЯ, НО НЕ ОГРАНИЧИВАЯСЬ, ГАРАНТИЯМИ ТОВАРНОЙ ЦЕННОСТИ, ПРИГОДНОСТИ ДЛЯ ОПРЕДЕЛЕННОЙ ЦЕЛИ И НЕНАРУШЕНИЯ ПРАВ. НЕПРАВИЛЬНОЕ ИСПОЛЬЗОВАНИЕ ЭТОГО ПРОГРАММНОГО ОБЕСПЕЧЕНИЯ МОЖЕТ ПРИВЕСТИ К НЕСТАБИЛЬНОСТИ ИЛИ НЕИСПРАВНОСТИ СИСТЕМЫ.
