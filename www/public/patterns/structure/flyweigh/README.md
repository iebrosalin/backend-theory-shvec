# Легковес (Flyweight)

Легковес — это структурный паттерн, который экономит память, благодаря разделению общего состояния, вынесенного в один объект, между множеством объектов.

Легковес позволяет экономить память, кешируя одинаковые данные, используемые в разных объектах.

## Особенности паттерна на PHP

Сложность: 3/3

Популярность: 0/3


Применимость: Весь смысл использования Легковеса — в экономии памяти. Поэтому, если в приложении нет такой проблемы, то вы вряд ли найдёте там примеры Легковеса.

Паттерн особенно редко актуален для PHP-приложений, из-за самой природы языка. Скрипты почти всегда работают с данными приложения частями, никогда не загружая все данные в память одновременно.

Признаки применения паттерна: Легковес можно определить по создающим методам класса, которые возвращают закешированные объекты, вместо создания новых.

## Пример из реальной жизни

Прежде чем мы начнём, обратите внимание, что реальное применение паттерна Легковес на PHP встречается довольно редко. Это связано с однопоточным характером PHP, где вы не должны хранить ВСЕ объекты вашего приложения в памяти одновременно в одном потоке. Хотя замысел этого примера только наполовину серьёзен, и вся проблема с ОЗУ может быть решена, если приложение структурировать по-другому, он всё же наглядно показывает концепцию паттерна, как он работает в реальном мире. Итак, я вас предупредил. Теперь давайте начнём.

В этом примере паттерн Легковес применяется для минимизации использования оперативной памяти объектами в базе данных животных ветеринарной клиники только для кошек. Каждую запись в базе данных представляет объект-Кот. Его данные состоят из двух частей:

1. Уникальные (внешние) данные: имя кота, возраст и инфо о владельце.
2. Общие (внутренние) данные: название породы, цвет, текстура и т. д.

Первая часть хранится непосредственно внутри класса Кот, который играет роль контекста. Вторая часть, однако, хранится отдельно и может совместно использоваться разными котами. Эти совместно используемые данные находятся внутри класса РазновидностиКотов. Все коты, имеющие схожие признаки, привязаны к одному и тому же классу РазновидностиКотов, вместо того чтобы хранить повторяющиеся данные в каждом из своих объектов.