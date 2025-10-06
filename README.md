Пытаюсь описать проект..



# Конвертер Морзе
* [Описание проекта](#chapter-0)
* [Папки проекта](#chapter-1)
* [Схемы подключения](#chapter-2)
* [Материалы и компоненты](#chapter-3)
* [Как скачать и прошить](#chapter-4)
* [FAQ](#chapter-5)
* [Полезная информация](#chapter-6)

<a id="chapter-0"></a>
## Описание проекта
Это устройство, предназначенно для людей, внезапно потерявших способность говорить и нормально двигаться в результате серьезной аварии, предоставляющее им возможность общаться с другими с помощью кода Морзе.

<a id="chapter-1"></a>
## Папки
**ВНИМАНИЕ! Если это твой первый опыт работы с Arduino, читай [инструкцию](#chapter-4)**
- **libraries** - библиотеки проекта. Заменить имеющиеся версии
- **firmware** - прошивка для Arduino, файл в папке открыть в Arduino IDE ([инструкция](#chapter-4))
- **HardwareMonitor** - программа, необходимая для работы устройства (закинуть куда угодно)
- **schemes&PCBs** - принципиальные схемы и печатки

<a id="chapter-2"></a>
## Схемы
![SCHEME](https://github.com/AlexGyver/PCdisplay/blob/master/schemes%26PCBs/scheme_fritzing.png)
![SCHEME](https://github.com/AlexGyver/PCdisplay/blob/master/schemes%26PCBs/scheme_EasyEDA.png)

<a id="chapter-3"></a>
## Материалы и компоненты
* Arduino NANO (при работе от внешнего источника (не USB), будет отсутствовать напряжение 3.3 В, генерируемое микросхемой FTDI, при этом светодиоды RX и TX мигаю только при наличие сигнала высокого уровня на выводах 0 и 1.)
* CW Ключ
* LCD-дисплей LCD1602A
* Преобразователь интерфейса LCD в I2C для дисплеев 1602
* Пассивный пьезоизлучатель 3-12В (PC Speaker)
* Светодиод 5мм (https://amperka.ru/product/led-5mm?srsltid=AfmBOorgVJkefmLiWAwozMOzQmjzlIiv9FZ2O4c5mE9kG0dy5nHZt998#projects)
* Источник питания 5V

<a id="chapter-6"></a>
## Полезная информация
* [YouTube канал про Arduino](https://www.youtube.com/channel/UC4axiS76D784-ofoTdo5zOA?sub_confirmation=1)
* [Первые шаги с Arduino](http://alexgyver.ru/arduino-first/) - подробная статья по началу работы с Ардуино, ознакомиться первым делом!
