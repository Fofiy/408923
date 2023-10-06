# Main information
This library contains files with functions to calculate area and perimeter of some geometric figures: circle, rectangle, square, triangle

# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle: S = a * h / 2 !

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a
- Triangle: P = a + b + c !

# Functions
## Circle

- area(r)
Принимает число r, возвращает площадь круга радиуса r в виде десятичной дроби, вычисленную по формуле pi * r * r
    Пример вызова:
        circle = area(3)
    Результат:
        circle = 28.274333882308138
- perimeter(r)
Принимает число r, возвращает длину окружности радиуса r в виде десятичной дроби, вычисленную по формуле 2 * pi * r
    Пример вызова:
        circle_len = perimeter(3)
    Результат:
        circle_len = 18.84955592153876

## Rectangle

- area(a, b)
Принимает два числа a и b, возвращает площадь прямоугольника co сторонами a и b, вычисленную по формуле a * b 
    Пример вызова:
        rec_area = area(7, 8)
    Результат:
        rec_area = 56
- perimeter(r)
Принимает два числа a и b, возвращает периметр прямоугольника co сторонами a и b, вычисленный по формуле 2 * (a + b)
    Пример вызова:
        rec_area = area(7, 8)
    Результат:
        rec_area = 30

## Square

- area(a)
Принимает число a, возвращает площадь квадрата co стороной a, вычисленную по формуле a * a 
    Пример вызова:
        sq_area = area(10)
    Результат:
        sq_area = 100
- perimeter(a)
Принимает число a, возвращает периметр квадрата co стороной a, вычисленный по формуле 4 * a 
    Пример вызова:
        sq_area = area(10)
    Результат:
        sq_area = 40

## Triangle

- area(a, h)
Принимает числа a и h, возвращает площадь треугольника co стороной a и высотой h, проведенной к этой стороне, вычисленную по формуле a * h / 2
    Пример вызова:
        tr_area = area(10, 6)
    Результат:
        tr_area = 30
- area(a, b, c)
Принимает числа a, b, c, возвращает периметр треугольника co сторонами a, b и c, вычисленный по формуле a + b + c
    Пример вызова:
        tr_perim = area(3, 4, 5)
    Результат:
        tr_perim = 12
