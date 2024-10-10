# Qqqmadi
1 Перед сложением или вычитанием вещественных чисел необходимо выравнивать их порядки, чтобы операции происходили корректно. Если порядки не равны, то результат может быть неверным из-за неправильного сдвига значащей части.

2 При выравнивании порядков число с меньшим порядком подвергается сдвигу. Это необходимо, чтобы оба числа имели одинаковый масштаб и их значащие части могли быть правильно сложены или вычтены.

3 Не всегда. Значащая часть сдвигается вправо только в том случае, если выравнивается число с меньшим порядком. Если выравнивается число с большим порядком, то возможно сдвигание значащей части влево.

4 Количество сдвигов определяется разностью порядков двух чисел. Если одно число имеет порядок p1, а другое p2, то количество сдвигов будет равно |p1 - p2|.

5 Да, такое может произойти, если одно из чисел отрицательное и по абсолютной величине больше, чем второе. Например, в случае, когда одно число значительно меньше другого по знаку.

6 Если вещественное число умножить на 2, его порядок увеличивается на 1, что переводится в сдвиг значащей части влево. Для целого числа при удвоении его двоичный код также сдвигается влево.

7 Это может произойти, если число B намного меньше числа A и не вносит значительного вклада в результат из-за ограниченной точности представления чисел (потеря значащих битов).

8 Да, при вычитании может произойти переполнение, если результат выходит за пределы представимого диапазона. Антипереполнение возможно, если результат слишком мал и выходит за пределы нижней границы.

9 Для умножения: порядок результирующего числа равен сумме порядков множителей, а значащая часть умножается.
Для деления: порядок результирующего числа равен разности порядков делимого и делителя, а значащая часть делится.
Да, это верно. Переполнение возникает, когда результат операции выходит за пределы, которое может быть представлено в формате значащей части (больше, чем максимальное представимое значение).

10 Да, нормализация может нарушиться, если результат операции не соответствует нормальным формам (например, слишком мал или слишком велик). В таком случае необходимо провести нормализацию, исправив порядок и значащую часть. Например, если результат равен 0.00001, его можно преобразовать в 1.0 × 10^(-5).

Задачи

1Суммируются два двоичных числа: 1.0 (2^2) и 1.11 (2^1). Какое из них будет сдвигаться при выравнивании порядков? На сколько разрядов? Сдвигаться будет 1.0, так как его порядок меньше. Необходимо сдвинуть его на 1 разряд влево (в сторону меньшего порядка).

2 Выполните сложение двух десятичных чисел 2.5 и 0.125. Десятичные числа:

3 2.5 в двоичном представлении: 10.1 (порядок = 1, значащая часть = 1.01)
0.125 в двоичном представлении: 0.001 (порядок = -3, значащая часть = 1.0)
Сложение двух десятичных чисел 0,1 и 0,2

4 Порядок = -3, Значащая часть = 1.10100.

5 Сложение 1,01 и самого себя
Таким образом, значащая часть не меняется, порядок увеличивается на 1.

6 Сложение A, B, C, D, E
Неправильное представление значащих частей в формате 8 бит может привести к различиям в результатах.

7 Перемножение 0.75 и 1.25
0.9375 в десятичной системе соответствует (1.001 x 2^0).

8 Переполнение при возведении в квадрат
Если порядок идет до 4 бит, это за пределами представимости. Да, произойдет переполнение.

9 Деление 0.75 и 0.25
image

Ответ в десятичной системе будет 3.

10 Деление двоичного числа
Без изменений порядка - результат будет 0.1 (в двоичной системе).
