# Сборщиков Е.И. ПР-23.106 
## Практическая работа № 2
### ПМ.11 Разработка, администрирование и защита баз данных
### МДК 11.01 Технология разработки и защиты баз данных

#### Вариант № 12

<image src="primer1.png" alt="Пример1">
<image src="primer2.png" alt="Пример2">
<image src="primer3.png" alt="Пример3">

Скрипт запроса:
``` sql
SELECT
    r,
    w,
    fi1,
    l,
    fi,
    j,
    ((X + 1)^2 + 0.5) AS fx,
    (r * w * (SIN(fi1) + (l / 2) * SIN(2 * fi + 4.9 * POWER(10,-7)) - POWER(l,j) * COS(fi1))) AS y
FROM (
    SELECT
        -3 AS X,
        a1 AS r,
        a2 AS w,
        a3 AS fi1,
        a4 AS l,
        a5 AS fi,
        a6 AS j
); <-- a1..a6 - любые числа>
```
