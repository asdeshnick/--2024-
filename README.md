## Процедурая генерация уровня плтаформера(бета)!

В начале мы запускаем алгоритм с помощью повторение циклического алгоритма
потом случайное выбирается число от -1 до 2(правую границы не включая)
если случайно выбранное число будет 1 то мы к координате Y добавляем 1,
если 0  то координате X добавляем 1 если же 0, то Y - 1,
но неважное от решения 0 ,1 или -1 мы все ровно добавляем 1 к X.
Потом мы смотрим на список которые мы задавили ранее и если наш круг по счету будет равен элементу этого список,
то мы к Y добавляем 1, так же это условия остается, но мы выбираем новое случайное число от 1 до 3 если выпадает 1,
то мы добавляем 1 к координате Y если 2 то  X + 1. Если получится так что x1 будет равен х2 то мы к X2 добавляем 1.
Координаты х2 и у2 в начале равны х1 и у1.

Список задается в начале координаты тоже

- список
- x1
- y1
- Количество платформ(циклов)
 ![Пример генераци](https://imgur.com/a/4M85egm)
