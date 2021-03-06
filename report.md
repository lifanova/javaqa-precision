# Отчёт о тестировании приложения подсчета бонусов #

## Краткое описание ##

6.03.2021 - 6.03.2021 было проведено тестирование работы приложения подсчета бонусов на предмет:
- приложение запускается и через конечное время завершает работу;
- приложение верно вычисляет суммарный бонус.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
- [Вычисляется неверный результат суммирования бонусов](https://github.com/lifanova/javaqa-precision/issues/1)

## Описание процесса тестирования ##

В процессе тестирования использовались следующие артефакты:

- [Руководство использования приложения подсчета бонусов](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)


В качестве тестовых данных использовались следующие значения:
  regularBonus = 0.3;
  specialBonus = 0.6;

Тестирование производилось в следующем окружении:
- Windows 8, x64
- OpenJDK 11
- Intelij IDEA 2020.3.2 x64