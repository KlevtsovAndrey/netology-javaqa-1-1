# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

07.08.2021 - 07.08.2021 было проведено <перечисление видов тестирование> приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [При использовании карточек American Express программа выдает результат FAIL](https://github.com/KlevtsovAndrey/netology-javaqa-1-1/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались данные с сайта [getCreditCardNumbers](https://www.getcreditcardnumbers.com/):
* 5385167177611382 - Result is OK
* 4532446238626190 - Result is OK
* 6011783018839287 - Result is OK 
* 378267431240752 - Result is OK 


Тестирование производилось в следующем окружении:
* ОС: Windows 10 Pro x86
* Версия java: 15.0.2 2021-01-19
