# Урок 1. Принципы ООП: Инкапсуляция, наследование, полиморфизм

Создайте иерархию классов для представления различных геометрических фигур. Каждая фигура должна иметь метод для вычисления площади (calculateArea) и метод для вычисления периметра (calculatePerimeter). Реализуйте следующие фигуры:

Круг (Circle):

Свойства: радиус (radius).
Методы: calculateArea и calculatePerimeter для вычисления площади и периметра соответственно.


Прямоугольник (Rectangle):

Свойства: длина (length) и ширина (width).
Методы: calculateArea и calculatePerimeter для вычисления площади и периметра соответственно.


Квадрат (Square), который является подклассом прямоугольника:

Свойства: сторона (side).
Методы: calculateArea и calculatePerimeter для вычисления площади и периметра соответственно. И переопределите методы родительского класса, чтобы они соответствовали квадрату.