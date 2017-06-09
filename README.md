# Информация о проекте

Игрок управляет длинным, тонким существом, напоминающим змею , которое ползает по плоскости (как правило, ограниченной стенками), собирая еду , избегая столкновения с собственным хвостом и краями игрового поля.  Каждый раз, когда змея съедает кусок пищи, она становится длиннее.  Игрок управляет направлением движения головы змеи (обычно 4 направления: вверх, вниз, влево, вправо), а хвост змеи движется следом.
##Интерфейс

Это возможности управления персонажем, взаимодействия персонажей друг с другом, общения игроков между собой и т.д.  Интерфейс игры состоит из  игрового поля. С помощью клавиатуры игроки могут контролировать змею.  Главная задача игрока помогать змею кушать больше еды. 

###Игровое поле:
![Image alt]
(https://github.com/TianYJ1/polytech.cs.2017.spring_project/raw/master/doc/res/play.png)

##Структура директория

Код организован следующим образом:

 Каталог    |  Описание
----------------  |--------------------------
src/            | файлы исходного кода 
doc/            | документация
doc/res/        | ресурсы для документации

## Сборка проекта

Для сборки проекта:
````
make
````
Чтобы восстановить все с нуля, выполните следующее действие:
````
make clean
````
Для сборки документации:
````
make doxygen
````
Для сборки документации в формате PDF:
````
make pdf
````
Для сборки документации в формате HTML:
````
make html
````
##Авторы
---------------------------------------------------------------
* **Тянь Яцзин** -yjcbtp@gmail.com
* **Цай  инин **-809874260@qq.com
*  **Сунь Цзиньхуэй** -sun.jinhui@mail.ru

##Лицензия
---------------------------------------------------------------
Этот проект лицензирован под MIT License - смотри LICENSE файл для подробностей
