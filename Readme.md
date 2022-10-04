**Контрольная работа!**
**Задача.**
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Пример:

["hello", "2", "world", ":-)"] Вывод: ["2", ":-)"]
["1234", "1567", "-2", "computer science"] Вывод: ["-2"]
["Russia", "Denmark", "Kazan"] Вывод: []
**Решение.**
В моем случае, массив получаем с клавиатуры. С помощью .Split(" ") получаем из введенных слов в консоли через пробел, массив. Полученный масив присваеваем переменной array.

Далее с помощью метода FindElementsLen3 проходим по всему массиву и находим элементы, длина которых меньше, либо равна 3. Далее записываем их в переменную temp через пробел.

Последний шаг, это преобразовать строки из temp в новый массив arrayElLen3. Используем снова .Split(" "), получаем массив из элементов, длина которых не больше 3-х элементов. Далее выводим массив.

**Блок-схема.**
![Блок схема](block-diagram.png)