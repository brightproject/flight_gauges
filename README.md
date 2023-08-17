## О проекте
*Создание авиаприборов, для определения положения, контроля двигателей и систем, использующего два микроконтроллера `esp32` и `stm32`.* 
*Проект будет разрабатываться под лицензией [МИТ](http://ru.wikipedia.org/wiki/Лицензия_MIT).*

## Основной функционал
>Прибор пространственного положения(авиагоризонт) - показывает ориентацию в пространстве, путем определения своего положения с помощью `MEMS` датчиков акселерометра, гироскопа и магнитометра, калибруемых по месту. 

>Прибор контроля двигателя, основан на ОУ, АЦП.

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
* https://thecavepearlproject.org/2015/05/22/calibrating-any-compass-or-accelerometer-for-arduino/
* https://myahrs.wordpress.com/2012/04/25/turning-error-correction/
* https://www.ngdc.noaa.gov/geomag/calculators/magcalc.shtml#declination
