# Основная информация
Здесь содержатся файлы с функциями для вычисления площади и периметра некоторых фигур: круга, прямоугольника, квадрата, треугольника

# Математические формулы
## Площадь
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle: S = a * h / 2 !

## Периметр
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a
- Triangle: P = a + b + c !

# Функции в файлах
## circle.py
- area(r)\
Принимает число r, возвращает площадь круга радиуса r в виде десятичной дроби, вычисленную по формуле pi * r * r
    >Пример вызова:\
        circle = area(3)\
    Результат:\
        circle = 28.274333882308138
- perimeter(r)\
Принимает число r, возвращает длину окружности радиуса r в виде десятичной дроби, вычисленную по формуле 2 * pi * r
    >Пример вызова:\
        circle_len = perimeter(3)\
    Результат:\
        circle_len = 18.84955592153876

## rectangle.py
- area(a, b)\
Принимает два числа a и b, возвращает площадь прямоугольника co сторонами a и b, вычисленную по формуле a * b 
    >Пример вызова:\
        rec_area = area(7, 8)\
    Результат:\
        rec_area = 56\
- perimeter(r)\
Принимает два числа a и b, возвращает периметр прямоугольника co сторонами a и b, вычисленный по формуле 2 * (a + b)
    >Пример вызова:\
        rec_area = area(7, 8)\
    Результат:\
        rec_area = 30\

## square.py
- area(a)\
Принимает число a, возвращает площадь квадрата co стороной a, вычисленную по формуле a * a 
    >Пример вызова:\
        sq_area = area(10)\
    Результат:\
        sq_area = 100\
- perimeter(a)\
Принимает число a, возвращает периметр квадрата co стороной a, вычисленный по формуле 4 * a 
    >Пример вызова:\
        sq_area = area(10)\
    Результат:\
        sq_area = 40\

## triangle.py
- area(a, h)\
Принимает числа a и h, возвращает площадь треугольника co стороной a и высотой h, проведенной к этой стороне, вычисленную по формуле a * h / 2
    >Пример вызова:\
        tr_area = area(10, 6)\
    Результат:\
        tr_area = 30\
- area(a, b, c)\
Принимает числа a, b, c, возвращает периметр треугольника co сторонами a, b и c, вычисленный по формуле a + b + c
    >Пример вызова:\
        tr_perim = area(3, 4, 5)\
    Результат:\
        tr_perim = 12

# История изменений
- commit 284c019b82c3a916f7f74fa75a377cc242c025bf \
Author: Fofiy <arbraarbra090@gmail.com>
Date: Sep 17 17:21:07 2023 
> added rectangle.py

- commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 \
Author: smartiqa <info@smartiqa.ru>
Date: Mar 4 14:55:29 2021
> L-03: Docs added

- commit 8ba9aeb3cea847b63a91ac378a2a6db758682460 \
Author: smartiqa <info@smartiqa.ru>
Date: Mar 4 14:54:08 2021
> L-03: Circle and square added

# Тестирование
> Проведенные тесты находятся в файле testing.py

> test 13.11.2023
>- ERROR: test_some_string_data (main.CircleTests)\
ERROR: test_string_of_digits_area (main.CircleTests)\
ERROR: test_string_of_digits_perimeter (main.CircleTests)\
ERROR: test_some_str_perimeter (main.RectangleTests)\
ERROR: test_str_of_digits_perimeter (main.RectangleTests)\
ERROR: test_some_str_area (main.SquareTests)\
ERROR: test_str_of_digits_area (main.SquareTests)\
ERROR: test_some_str_area (main.TriangleTests)\
ERROR: test_some_str_perimeter (main.TriangleTests)
>
> 
>- FAIL: test_negative_area (main.CircleTests)\
FAIL: test_negative_perimeter (main.CircleTests)\
FAIL: test_negative_area (main.RectangleTests)\
FAIL: test_negative_perimeter (main.RectangleTests)\
FAIL: test_some_str_area (main.RectangleTests)\
FAIL: test_str_of_digits_area (main.RectangleTests)\
FAIL: test_negative_area (main.SquareTests)\
FAIL: test_negative_perimeter (main.SquareTests)\
FAIL: test_some_str_perimeter (main.SquareTests)\
FAIL: test_str_of_digits_perimeter (main.SquareTests)\
FAIL: test_negative_area (main.TriangleTests)\
FAIL: test_negative_perimeter (main.TriangleTests)\
FAIL: test_str_of_digits_area (main.TriangleTests)\
FAIL: test_str_of_digits_perimeter (main.TriangleTests)
