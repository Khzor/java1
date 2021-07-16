# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

10.07.2021 - 11.07.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 30 минут

В результате тестирования выявлено, что номера карт платежных систем **American Express** и **Diners Club - International** не валидируются.
Были созданы следующие Issues.

American Express:

* [Issue #1](https://github.com/Khzor/java1/issues/1)
* [Issue #2](https://github.com/Khzor/java1/issues/2)
* [Issue #3](https://github.com/Khzor/java1/issues/3)
* [Issue #4](https://github.com/Khzor/java1/issues/4)
* [Issue #5](https://github.com/Khzor/java1/issues/5)

Diners Club - International:

* [Issue #6](https://github.com/Khzor/java1/issues/6)
* [Issue #7](https://github.com/Khzor/java1/issues/7)
* [Issue #8](https://github.com/Khzor/java1/issues/8)
* [Issue #9](https://github.com/Khzor/java1/issues/9)
* [Issue #10](https://github.com/Khzor/java1/issues/10)


## Описание процесса тестирования

В качестве тестовых данных использовались данные (Номера карт были сгенерированы [здесь](https://www.freeformatter.com/credit-card-number-generator-validator.html)):

Visa:
* 4024007137498027 
* 4929819938894220
* 4916613876602579
* 4024007156919507
* 4532463691902646

Mastercard:
* 5306725115364087
* 5268752302302833
* 5381960590264951
* 5302328328178032
* 5419023254625367

American Express:
* 375733913662154
* 346242442093721
* 375076351141491
* 345804816384142
* 345016014887202

Visa Electron:
* 4508212274979996
* 4175002890349423
* 4175009705434662
* 4026305268662561
* 4913673253627105

Maestro:
* 5018482856593727
* 5018646092242832
* 5018863323453928
* 6761130108023749
* 6761495503975052

Diners Club - International:
* 36118356006195
* 36318244007195
* 36402721600597
* 36777151284735
* 36102497715682

Тестирование производилось в следующем окружении:
* Windows 10 Pro x64 19041.685
* Java version 11
* IntelliJ IDEA 2021.1.3