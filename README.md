# Решатель квадратных уравнений

Код решает квадратные уравнения методом вычисления дискриминанта.
Автотест к решению квадратных уравнений методом вычисления дискриминанта

# Как использовать

В get_roots из модуля quadratic_equation.py передается 3 параметра - (a,b,c) - аргументы квадртаного уравнения. Ответ возвращается в результате функции get_roots в виде tuple со значениями корней уравнения.

пример:
```from quadratic_equation import get_roots

root1, root2 = get_roots(1, 2, -3)
```

результат в виде:
```(1,-3)
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
