# Состояние (State)


Состояние — это поведенческий паттерн, позволяющий динамически изменять поведение объекта при смене его состояния.

Поведения, зависящие от состояния, переезжают в отдельные классы. Первоначальный класс хранит ссылку на один из таких объектов-состояний и делегирует ему работу.




## Особенности паттерна на PHP

Сложность: 1/3

Популярность: 1/3


Применимость: Паттерн Состояние иногда используют в PHP для превращения громоздких стейт-машин, построенных на операторах switch, в объекты.

Признаки применения паттерна: Методы класса делегируют работу одному вложенному объекту.