# Задача: #
## написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. ##

# Решение: #
- объявляем два массива со строковым типом данных(array1, array2); 
 - первый массив заполняем данными(array1), а длину воторго массива ставим равной первому и оставляем пустым(array2);
 - описываем void метод **FillSecondArray** получающий на вход два массива(array1, array2), в котором с помощъю цикла for перебираем первый массив(array1) и ставим условие если длина строки меньше либо равна 3 символам, то значение удовлетворяющее условию переносим во второй массив(array2);
- для того чтобы массив array2 не заполнялся пустыми данными, в методе **FillSecondArray** также вводим переменную count=0, которая соответствует индексу массива array2, при выполнениие условия **(array1[i].Length<=3)** инкрементируем переменную count;
- описываем void метод **PrintArray** получающий на вход массив(array2), который при помощи цикла for выводит наш полученный массив (array2) в консоль;
- объявляем методы **FillSecondArray** и **PrintArray**;

## Блок-схема метода **FillSecondArray** находится в папке **block_diagramm** ##


