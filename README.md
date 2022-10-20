# Код семинаров группы 221 на курсе "Основы программирования на Python", КНАД 2022

[Wiki курса с планом занятий](http://wiki.cs.hse.ru/%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%BD%D0%B0_Python_%D0%9A%D0%9D%D0%90%D0%94_22/23)

[Записи лекций и семинаров](https://disk.yandex.ru/d/a8pqUSkd94Ehyg)

[Ведомость с оценками](https://docs.google.com/spreadsheets/d/1bai8MBrcFtNN8bbMRXEirJc3a-NHUZONeXtsTF77pSU/edit?usp=sharing)

## Прошедшие семинары
- [08.09.2022](seminar_1_intro.ipynb) -- Первое знакомство с языком. Установка среды разработки. Переменные. Булевые операции. Системы счисления.
- [09.09.2022](seminar_2_strings.ipynb) -- Вещественные числа. Операции со строками. Форматирование строк.
- [15.09.2022](seminar_3_sequences.ipynb) -- Другие последовательности: bytes, list. Внутреннее устройство списка ("список" -- это массив ссылок). Операции со списками. Изменяемость списков. Range. (продолжено на следующем) Tuple и моменты с его неизменяемостью. Запись и чтение из файлов. Arrays. 
- [16.09.2022](seminar_4_func_basics.ipynb) -- Функции. Области видимости. Применение рекурсии. Binary search рекурсией и циклом. Модуль Bisect. Рекурсивный GCD.
- [22.09.2022](seminar_5_regexp.ipynb) -- Повторение пройденных тем. Решение задачи на поиск элемента в отсортированном массиве со "сдвигом" (бинпоиск). Простые примеры на регулярные выражения. (продолжено на следующем) Удаление стопслов и символов с помощью регулярок. Парсинг времени. 
- [23.09.2022](seminar_6_decorators.ipynb) -- Элементы функционального программирования (map, filter, itemgetter, attrgetter, methodcaller, partial). yield. lambda-функции. Декораторы. Пример декоратора @clock для подсчета времени. @wraps для сохранения внутренних полей исходной функции. Добавление параметра в декоратор на примере '@clock(active=True/False)'. @lru_cache.
- [29.09.2022](seminar_7_dicts.ipynb) -- Reduce, accumulate. Dict и Set, основные операции. Задача подсчета символов в строке. Задача поиска пар элементов с заданной суммой (2-sum).
- [30.09.2022](seminar_8_various.ipynb) -- Counter, Defaultdict. Решение задач: сумма цифр рекурсией, RLE циклом и рекурсией, самые частые слова в тексте, пересечение списков, номер появления слова, поиск наибольшего подмассива с заданной суммой.
- [06.10.2022](seminar_9_classes_decos.ipynb) -- Декораторы применяются на этапе интерпретации кода. Логирование. Декоратор-логгер. Обработка исключений. Callable класс как декоратор. Декорирование классов.
- [07.10.2022](seminar_10_oops.ipynb) -- Примеры дескрипторов. Написание "сумасшедшего" класса. Возможные проблемы при наследовании от стандартных типов. Наследование от abc.Sequence.
- [13.10.2022](seminar_11_telegram.ipynb) -- Live написание telegram-бота.
- [14.10.2022](seminar_12_testing.ipynb) -- Тесты в докстроке. Unittests. Написание тестов для отдельных функций, классов и для одной из функций телеграм бота с предыдущего семинара.




## Бонусные задачки
В конце семинаров я предлагаю решить задачи для практики по теме. Сдавать их можно до разбора на одном из последующих семинаров. 
За решение предлагается ~бесценный полученный опыт!~ бонусный балл, который равносилен одной задаче из домашнего контеста.

- ~Семинар 2: "Удаление стопслов методами строк"~. Разобрано в [третьем](seminar_3_sequences.ipynb) семинаре.
- ~Семинар 4: "Палиндром"~. Разобрано в [пятом](seminar_5_regexp.ipynb) семинаре.
- ~Семинар 5: Задачи на регулярные выражения (total 3 балла)~. Разобрано в [13](seminar_13_parsing.ipynb) семинаре.
- Семинар 9: Декоратор, проверяющий типы (3 балла)

