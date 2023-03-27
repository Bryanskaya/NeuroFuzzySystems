# Матрица ошибок
**Матрица ошибок**  -— это таблица, которая позволяет визуализировать эффективность алгоритма классификации путем сравнения прогнозируемого значения целевой переменной с ее фактическим значением. Столбцы матрицы представляют наблюдения в прогнозируемом классе, а строки — наблюдения в фактическом классе (или наоборот).

![error matrix](./img/matrix.png)

![error matrix explain](./img/matrixExplain.png)

**Истинно позитивное предсказание** (True Positive, TP)

> Вы предсказали положительный результат, и женщина действительно беременна.

**Истинно отрицательное предсказание** (True Negative, TN)

> Вы предсказали отрицательный результат, и мужчина действительно не беременен.

**Ошибочно положительное предсказание** (False Positive, FP)

> Вы предсказали положительный результат (мужчина беременен), но на самом деле это не так.

**Ошибочно отрицательное предсказание** (False Negative, FN)

> Вы предсказали, что женщина не беременна, но на самом деле она беременна.

---
Энтропия -- мера случайности или неопределённости от 0 до 1
0 = подмножество чистое, в нём нет случайных элементов. 
1 = высокая степень случайности

Точность -- процент правильных положительных прогнозов по отношению к общему количеству положительных прогнозов.
Отзыв -- процент правильных положительных прогнозов по отношению к общему количеству фактических положительных результатов.
Оценка F1 -- Чем ближе к 1, тем лучше модель. 2 * (Точность * Отзыв) / (Точность + Отзыв)
