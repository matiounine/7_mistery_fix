# Решатель квадратных уравнений

Программа находит действительные корни квадратного уравнения.

# Как использовать

Программа содержит функцию get_roots(), принимающую в качестве аргументов коэффициенты квадратного уравнения (a, b, c).
Функция get_roots() возвращает действительные значения корней, вычисляемые с использованием дискриминанта, в виде кортежа, состоящего из двух элементов (root1, root2).
Для нахождения квадратного корня (необходимого в общей формуле вычисления корней квадратного уравнения) импортируем из библиотеки math функцию sqrt.

# Пример работы программы

```python
    from quadratic_equation import get_roots # импортируем функцию get_roots()
    ...
    get_roots(3,4,1) # вызываем функцию и передаём параметры
    ...
    root1 = (-b - sqrt(discriminant)) / (2 * a)
    root2 = (-b + sqrt(discriminant)) / (2 * a)
    ...
    return root1, root2   # результат (-1.0, -0.3333333333333333)
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
