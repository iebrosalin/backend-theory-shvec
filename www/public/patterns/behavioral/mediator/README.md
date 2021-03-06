# Посредник (Mediator)

Посредник — это поведенческий паттерн, который упрощает коммуникацию между компонентами системы.

Посредник убирает прямые связи между отдельными компонентами, заставляя их общаться друг с другом через себя.

## Особенности паттерна на PHP

Сложность: 2/3

Популярность: 0/3


Применимость: Посредник не столь актуален в PHP, как в других языках, из-за того, что разные компоненты приложения не часто общаются друг с другом в пределах одной сессии скрипта.

Тем не менее, примерами паттерна могут служить EventDispatcher-ы многих фреймворков, а также некоторые реализации контроллеров в MVC фреймворках.

## Пример из реальной жизни

В этом примере паттерн Посредник расширяет базовую идею паттерна Наблюдатель, предоставляя централизованный диспетчер событий. Он позволяет любому объекту отслеживать и запускать события в других объектах, независимо от их классов.