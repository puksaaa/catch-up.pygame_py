## Проект "Догонялки"
Проект напсиан на языке Python и библиотеке pygame

```window``` - создание окна с размерами 700×500px с фоном, находящимся в файле background.png


```sprite1``` - создание игрока №1 с размерами 100×100, с фоновой картинкой из файла sprite1.png


```sprite2``` - создание игрока №2 с размерами 100×100, с фоновой картинкой из файла sprite2.png

```x1, x2``` - исходное положение двух спрайтов с координатами 200px, 400px по x

```y1, y2```- исходное положение двух спрайтов с координатами 250px по y

```window.blit``` - отрисовка каких-либо объектов на экране  

``` for e in event.get(): if e.type == QUIT:```- получение данных, проверка условия и выполнение если условие == "True" о нажатии на крестик. Завершение работы приложения

```if keys_pressed[K_LEFT] and x1 > 5:```  
```x1 -= speed ``` - если клавиша "стрелка влево" нажата и если координата местоположения sprite1 больше 5px,
то от значения местоположения отнимаем собственную скорость, тем самым производя процесс передвижения
влево. Такой же алгоритм при нажатии на различные стрелки с клавиатуры
