## О проекте
*Создание авиаприборов, для определения положения, контроля двигателей и систем, использующего два микроконтроллера `esp32` и `stm32`.* 
*Проект будет разрабатываться под лицензией [МИТ](http://ru.wikipedia.org/wiki/Лицензия_MIT).*

## Основной функционал
>Прибор пространственного положения(авиагоризонт) - показывает ориентацию в пространстве, путем определения своего положения с помощью `MEMS` датчиков акселерометра, гироскопа и магнитометра, калибруемых по месту. 
![photo1692643955 (2)](https://github.com/brightproject/flight_gauges/assets/1788098/e7576890-f83f-41bc-8826-f875ff39386a)
>Прибор контроля двигателя, основан на ОУ, АЦП.
![display2 8_1](https://github.com/brightproject/flight_gauges/assets/1788098/2b3fbf88-03fe-4920-8a84-b9e4f066109c)

## Инструментарий


* С/С++, Arduino IDE, Notepad++ 

## Необходимая информация

>определение и направление ветра в полете
* https://www.youtube.com/watch?v=CRpOotfHOEs
>фиксация полетных данных для построения профиля полете в Google Earth 
* https://www.youtube.com/watch?v=3uhJy9_XnCg
>изучить и повторить интерфейс `Horizont Kanardia AHRS`
* https://www.youtube.com/watch?v=ASEE_p26Gl8
>изучить и повторить меню  `AvMap Horison`
* https://www.youtube.com/watch?v=tenRbLOGkMU
>калибровка магнитометра 
* https://www.youtube.com/watch?v=lpLx8sViZEQ
* https://www.youtube.com/watch?v=PMTW73KUHKE
* https://thecavepearlproject.org/2015/05/22/calibrating-any-compass-or-accelerometer-for-arduino/
* https://myahrs.wordpress.com/2012/04/25/turning-error-correction/
* https://www.ngdc.noaa.gov/geomag/calculators/magcalc.shtml#declination
>передача данных в UART
* https://arduino.stackexchange.com/questions/72138/send-structure-through-serial

## Испытания экспериментальная авиа

* https://www.garant.ru/products/ipo/prime/doc/72167168/

## Интерфейс приборов

> Flybox Avionics
* https://www.youtube.com/watch?v=tSnoWODZJL8
> LX iris series
* https://www.youtube.com/watch?v=g-cPiKwTiac
> uAvionix AV-30
* https://www.youtube.com/watch?v=_3SjbeZtruQ&t=30s
* https://www.youtube.com/watch?v=4bzphsGhboY
> ULTRA AvMap
* https://youtu.be/dvTStJWv6WY?t=92

## Испытания приборов

AV-30 Flight Test
https://www.youtube.com/watch?v=nh9DiMPpKAA
