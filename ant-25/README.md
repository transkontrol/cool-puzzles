Муравей на бесконечной плоскости
================================

На бесконечной координатной сетке находится муравей. Муравей может
 перемещаться на 1 клетку вверх (x,y+1), вниз (x,y-1), влево (x-1,y),
 вправо (x+1,y), по одной клетке за шаг.

Клетки, в которых сумма цифр в координате X плюс сумма цифр в
 координате Y больше чем 25 недоступны муравью. Например, клетка с
 координатами (59, 79) недоступна, т.к. 5+9+7+9=30, что больше 25.

Сколько клеток может посетить муравей, включая начальную клетку,
 если его начальная позиция (1000,1000)?

Ответом должно быть число клеток, решение на языке Python и скрипт
 на JavaScript, отрисовывающего на canvas площадь доступную муравью.

----

- [ant.ipynb](ant.ipynb) - решение на Python 
- [ant.html](ant.html) - скрипт на JavaScript

После выполнения Python-кода будет создан файлик данных (ant.js) для
 рисования JavaScript-ом. Что бы не плодить сущности, сам JavaScript
 код помещен в HTML-файл.
