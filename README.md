# -Kontrolnayarabota
Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Описание решения

1. Объявляем два массива одной длины.
2. Объявляем метод с двумя массивами.
3. Объявляем переменную count,которая будет подсчитывать количество подходящих нам по размеру строк.
4. Циклом _for_ проверяем каждую строку массива. _i_ является индексом элементов 1ого массива.
5. Условием _if_ проверяем строки на количество символов <=3. Переменная _count_ является индексом строк второго массива. Если количество символов нас устраивает, то значние переносится во второй массив, _count_ увеличивается на 1. Значение _i_ увеличивается на 1 в любом случае.
6. После проверки каждого элемента первого массива метод завершается.

##Решение задачи в папке Task, Блок-схема прикреплена отдельным файлом под названием "Блок-схема"
