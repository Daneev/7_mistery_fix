# Решатель квадратных уравнений

Функция для извлечения корней квадратных уравнений общего вида: _**ax ^ 2 + bx + c = 0**_.



# Как использовать

Импорт модуля осуществляется инструкцией:
```python
from quadratic_equation import get_roots
```

В функцию `get_roots()` передаются три аргумента, соответствующие коэффициентам уравнения.
 
```python
root1, root2 = get_roots(a, b, c)
```

в результате выполнения функции, будет получено решение в зависимости от заданных коэффициентов.

например:

```python
from quadratic_equation import get_roots

a  =  1
b  =  2
c  = -3

print(get_roots(a, b, c))
```

результат: -3, 1

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
