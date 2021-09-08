# Отчёт о тестировании модуля Money Transfer

## Краткое описание

9.09.2021 было проведено модульное тестирование приложения Money Transfer.

На тестирование затрачено: 10 минут

В результате тестирования выявлен следующий дефект:
* [Ошибка вывода баланса счета при операции Money Transfer] (https://github.com/bella291/java_hw1/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [тест-кейс пополнения счета VIP клиента] (https://github.com/bella291/java_hw1/blob/bd1e9957220e35ae94867bb84af583b2904b0a21/src/test-case.md)

В качестве тестовых данных использовались данные операции Money Transfer при пополнении счёта VIP-клиента банка:
* текущий баланс счёта клиента - 2 000 000 000 рублей (два миллиарда рублей);
* сумма перевода - 500 000 000 рублей (пятьсот миллионов рублей);
* итоговая сумма - 2 500 000 000 рублей (два миллиарда пятьсот миллионов рублей).

Тестирование производилось в следующем окружении:
* Windows 10 Pro, x64
* AdoptOpenJDK (HotSpot) version 11.0.11