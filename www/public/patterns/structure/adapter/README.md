# Адаптер (Adapter)

Адаптер — это структурный паттерн, который позволяет подружить несовместимые объекты.

Адаптер выступает прослойкой между двумя объектами, превращая вызовы одного в вызовы понятные другому.

## Особенности паттерна на PHP

Сложность: 1/3

Популярность: 3/3

Применимость: Паттерн можно часто встретить в PHP-коде, особенно там, где требуется конвертация разных типов данных или совместная работа классов с разными интерфейсами.

Признаки применения паттерна: Адаптер получает конвертируемый объект в конструкторе или через параметры своих методов. Методы Адаптера обычно совместимы с интерфейсом одного объекта. Они делегируют вызовы вложенному объекту, превратив перед этим параметры вызова в формат, поддерживаемый вложенным объектом.

## Пример из реальной жизни

Паттерн Адаптер позволяет использовать сторонние или устаревшие классы, даже если они несовместимы с основной частью кода. Например, вместо того, чтобы переписывать интерфейс уведомлений вашего приложения для поддержки каждого стороннего сервиса вроде Slack, Facebook, SMS и прочих, вы создаёте под эти сервисы набор специальных обёрток, которые приводят вызовы из приложения к требуемым сторонними классами интерфейсу и формату.