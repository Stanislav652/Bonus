# Отчёт о тестировании приложения Main.java по внедрению бонусной системы для клиентов #

## Краткое описание ##

05.12.2020 было проведено: тестирование работоспособности приложения по внедрению бонусной системы для клиентов. Для тестирования использовали текущие значения бонусов, записанные в коде. Данный код при сложении двух значений бонусов выдает некорректную сумму.

На тестирование затрачено: 20 минут

## Описание процесса тестирования ##

Для проверки работоспособности кода использовали тестирование запуска.
Для тестирования использовались тестовые данные из самого кода: regularBonus = 0.3 specialBonus = 0.6.

## Результаты ##

 - Ожидаемый результат: 0.9 
- Фактический результат: 0.8999999

В результате тестирования выявлен следующий дефект:
https://github.com/Stanislav652/Bonus/issues/1


Тестирование производилось в следующем окружении:
 
 ОС: Windows 10 Home, 
 64-разрядная Java: 11.0.9,
 IntelliJ IDEA 2020.2
