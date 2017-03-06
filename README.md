# Реализация необратимого алгоритма шифрования на основе элементарного клеточного автомата
Моя небольшая реализация простого и быстрого алгоритма шифроввния. Как он работает?

## Суть алгоритма

- На вход получаем символ для закодирования и правило элементарного клеточного клеточного автомата, реализованное в виде класса Rule (*см. конструкторы класса Field*).

- Внутри код полученного символа переводится в двоичную систему счисления и полученная вереница 1 и 0 передаётся элементарному клеточному автомату, далее просчитываем эволюцию и возвращаем обратно код символа.

Из описания выше ясно, что алгоритм прост для реализации и понимания. Если русский язык вы позабыли со своим программированием, то милости прошу к коду, там всё понятнее).