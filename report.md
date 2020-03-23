# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
21.03.2020 - 21.03.2020 было проведено функциональное тестирование приложения Credit Card Number Validator. Было проведено тестирование негативных и позитивных сценариев.

На тестирование затрачено: 1 час

## В результате тестирования выявлены следующие дефекты:

https://github.com/nicklada/JavaHW1Task2/issues/2
https://github.com/nicklada/JavaHW1Task2/issues/1
https://github.com/nicklada/JavaHW1Task2/issues/3
https://github.com/nicklada/JavaHW1Task2/issues/4
https://github.com/nicklada/JavaHW1Task2/issues/5
https://github.com/nicklada/JavaHW1Task2/issues/6
https://github.com/nicklada/JavaHW1Task2/issues/7

## Описание процесса тестирования
### Артефакты:

Тест - кейс 1
Тест - кейс 2
Bug Report 1: https://github.com/nicklada/JavaHW1Task2/issues/1
Bug Rerort 2: https://github.com/nicklada/JavaHW1Task2/issues/2
Bug Rerort 3: https://github.com/nicklada/JavaHW1Task2/issues/3
Bug Rerort 4: https://github.com/nicklada/JavaHW1Task2/issues/4
Bug Rerort 5: https://github.com/nicklada/JavaHW1Task2/issues/5
Bug Rerort 6: https://github.com/nicklada/JavaHW1Task2/issues/6
Bug Rerort 7: https://github.com/nicklada/JavaHW1Task2/issues/7

В качестве тестовых данных использовались данные из генератора валидных номеров кредитных карт:

5351719427810741

+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is OK

535171942781074100

+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is FAIL

5404 3685 0691 3567

+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is FAIL

5404-3685-0691-3567

+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is FAIL

535171942781074

+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is FAIL

5351719427810
+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is FAIL

5351719427810741111
+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is FAIL

53517194278107411
+ Ожидаемый результат: 
Вывод программы: Result is OK
+ Фактический результат:
Вывод программы: Result is FAIL


### Тестирование производилось в следующем окружении:

<версия и разрядность ОС>
<версия Java>
<другое ПО, при необходимости>
