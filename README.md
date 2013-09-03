1C77_JSON_parser
================
1С 7.7 JSON парсер предназначен для разбора данных в формате JSON.

Представленный исходный код состоит из двух частей. Первую (глобальный модуль), для повторного использования нужно разместить в глобальном модуле вашей конфигурации, сразу после объявления переменных и функций глобального модуля. Вторая часть может использоваться где угодно.

##Парсер строки с данными в формате JSON. 

Данный исходный код предоставляет возможность сделать парсинг (разбор) строки данных и преобразовать их в структуру вложенных друг в друга типов данных "Список значений".

Вложенные друг в друга структуры разбираются в виде пар "Ключ"-"Значение", если идёт разбор вложенной структуры типа {} или в виде пар "Номер"-"Значение", если вложенная структура завернута в квадратные скобки [].

Возвращаемое значение можно разбирать с помощью стандартной функции <code>Получить(<Имя поля>)</code> для типа переменной "Список значений", или стандартной же функции <code>ПолучитьЗначение(<НомерПоля>[,<Ключ>])</code>.

1С77 JSON парсер
