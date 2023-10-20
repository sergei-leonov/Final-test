# FINISH
## Задача : 
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
## Описание алгоритма решения:
### Первоначально мы создаем два массива: исходный и второй, с одинаковой длиной. Затем мы определяем метод, в котором используется цикл, выполнение которого зависит от длины массива. Внутри этого цикла проверяется условие (<=3), и если оно верно, мы берем элемент из первого массива и добавляем его в элемент второго массива. Для последовательного заполнения элементов второго массива из первого, мы используем переменную "count", чтобы избежать появления пробелов между элементами. После присваивания элемента второго массива, значение "count" увеличивается на 1, а цикл "for" продолжается с увеличением значения переменной "i" на 1. Это продолжается до завершения цикла.
### Графическое представление метода в папке block diagram в двух файлах разных расширениях.
### Реализация алгоритма по пути Block/Program.cs