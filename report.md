# Отчёт о тестировании Legacy

## Краткое описание

12.11.2020 - 12.11.2020 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Валидные ключи не распознаются программой как валидные](https://github.com/ugfan13/Java1.1/issues/1#issue-741564091)
* [Невалидные ключи распознаются в качестве валидных](https://github.com/ugfan13/Java1.1/issues/2#issue-741566198)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство пользователя](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)


В качестве тестовых данных использовались данные из [Руководства пользователя](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md):

* Инструкция по установке OpenJDK11 работает
* Приложение запускается и совместимо с Java 11
* Приложение работает согласно руководству использования

Тестирование производилось в следующем окружении:
* Windows 10 Pro 19042.572
* openjdk version "11.0.9" 2020-10-20