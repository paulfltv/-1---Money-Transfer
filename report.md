# **ОТЧЕТ О ТЕСТИРОВАНИИ ПРИЛОЖЕНИЯ MONEY TRANSFER**

## **Краткое описание:**
Проведено функциональное тестирование приложения Money Transfer, в результате которого было установлено, что при пополнении счета на сумму более 147 483 647 (в рублях без копеек) возникает ошибка.

## **Описание тестов:**
08.12.2020. проведено функциональное тестирование приложения "Money Transfer" по реализации его функции вычисления суммы итогового остатка (rest) после пополнения суммы начального остатка (balance) на сумму перевода (transfer).

## **Описание тестов:**
Проводилось функциональное позитивное тестирование методом граничных значений, эквивалентных значений для переменной перевода (int transfer).

**Результаты:**
* 8 проведенных тестов завершены успешно (100%), при этом 3 теста показали положительный результат, а 5 тестов выявили ошибки в работе приложения.
* Ссылка на баг-репорты: https://github.com/paulfltv/-1---Money-Transfer/issues/1

**Общие рекомендации:**
В виду серьёзности ошибок (Critical), а также важности клиетов, осуществляющих переводы на значительные денежные суммы, рекомендую присвоить данным ошибкам в приложении Money Transfer самый высокий приоритет (High) и приступить к их устанению немедленно.