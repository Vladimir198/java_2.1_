# Отчёт о тестировании Money Transfer

## Краткое описание

23.01.2021 было проведено функциональное тестирование приложения .

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* [При сложении чисел (сумма которых больше 2_000_000_000), результат не верный.](https://github.com/Vladimir198/java_2.1_/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* IntelliJ IDEA


В качестве тестовых данных использовались данные:
* [Код программы](https://github.com/Vladimir198/java_2.1_/blob/master/Main.java)
* balance = 2_000_000_000
* translation = 500_000_000

Тестирование производилось в следующем окружении:
* ОС: Windows 10 (32-бита)
* Версия Java: "11.0.9.1" 2020-11-04