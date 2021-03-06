# Отчёт о тестировании Credit Card Number Validator #

## Краткое описание ##

25.01.2021 было проведено функциональное тестирование по валидации номеров банковских карт.

На тестирование затрачено: *1 час*

В результате тестирования выявлены следующие *дефекты*:

Невалидными оказались следующие номера карт: 
* 4932943345939076534 (Visa).

[При вводе валидных номер карт Visa выводится результат FAIL#1 ](https://github.com/katerinaprf27/1.2.javaCreditCardNumberValidator/issues/1)

## Описание процесса тестирования ##

В процессе тестирования использовались следующие *артефакты*:

* баг-репорты
* отчет о тестировании

В качестве *тестовых данных* использовались данные карт с [freeformatter.com](www.freeformatter.com)

Номера валидных кредитных карт:

**VISA:** 
* 4556717387704330 
* 4932943345939076534

**MasterCard:**
* 5212582092855691 
* 5171507155192269

Тестирование производилось в следующем *окружении*:

* MacOS x64
* Java version "11.0.9.1"
* IntelliJ IDEA