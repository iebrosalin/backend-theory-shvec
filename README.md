# Погружение в паттерны проектирования

Репозиторий содержит примеры реализаций паттернов на PHP по одноимённой [книге][RefBook] за авторством Александра Швец.
В серъёз изучать её начал 19.01.2020. Для меня книга открыла мир паттернов, потому что книга  доступно написана, иллюстрированная великолепно, с примерами кода на PHP. Так же у книги есть удобная веб-версия в виде сайта. В ней нет ничего лишнего и что могло 
бы устареть (инструменты разработки и виртуализации, и т.п...).  
 
В таблицах приведены списки паттернов сгруппированые по их типам. Несвойственные PHP паттерны не имеют примеров.

### Производящие

|Название                                                 | Статус        | Наличие примера на PHP|
|-----------------------                                  |-------        | ----------------------|
|[Фабричный метод (Factory method)][FactoryMethod]        || +                     |
|[Абстрактная фабрика (Abstract factory)][AbstractFactory]|| +                     |
|[Стритель (Builder)][Builder]                            || +                     |
|[Прототип (Prototype)][Prototype]                        || +                     |
|[Одиночка (Singleton)][Singleton]                        || +                     |

### Структурные

|Название                                                             | Статус        | Наличие примера на PHP|
|-----------------------                                              |-------        | ----------------------|
|[Адаптер (Adapter)][Adapter]                                         || +                     |
|[Мост (Bridge)][Bridge]                                              || +                     |
|[Компоновщик (Composite)][Composite]                                 || +                     |
|[Декоратор (Decorator)][Decorator]                                   || +                     |
|[Фасад (Facade)][Facade]                                             || +                     |
|[Легковес (Flyweight)][Flyweight]                                    || -                     |
|[Заместитель (Proxy)][Proxy]                                         || +                     |

### Поведенческие

|Название                                                             | Статус        | Наличие примера на PHP|
|-----------------------                                              |-------        | ----------------------|
|[Цепочка обязанностей (Chain of responsibility)][ChainResponsobility]|| +                     |
|[Комманда (Command)][Command]                                        || +                     |
|[Итератор (Iterator)][Iterator]                                      || +                     |
|[Посредник (Mediator][Mediator]                                      || +                     |
|[Снимок (Memento)][Mediator]                                         || -                     |
|[Наблюдатель (Observer)][Observer]                                   || +                     |
|[Состояние (State)][State]                                           || -                     |
|[Статегия (Strategy)][Strategy]                                      || +                     |
|[Шаблонный метод(Template method)][TemplateMethod]                   || +                     |
|[Посетитель(Visitor][Visitor]                                        || +                     |

[RefBook]:<https://refactoring.guru/ru/design-patterns/book>


[FactoryMethod]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/reproducing/factory_method>
[AbstractFactory]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/reproducing/absctract_factory>
[Builder]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/reproducing/builder>
[Prototype]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/reproducing/prototype>
[Singleton]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/reproducing/singleton>


[Adapter]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/structure/adapter>
[Bridge]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/structure/bridge>
[Composite]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/structure/composite>
[Decorator]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/structure/decorator>
[Facade]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/structure/facade>
[Flyweight]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/structure/flyweigh>
[Proxy]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/structure/proxy>

[ChainResponsobility]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/chain_of_responsibility>
[Command]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/command>
[Iterator]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/iterator>
[Mediator]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/mediator>
[Memento]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/memento>
[Observer]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/observer>
[State]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/state#%D1%81%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D0%B5-state>
[Strategy]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/strategy>
[TemplateMethod]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/template_method>
[Visitor]:<https://github.com/iebrosalin/public_web/tree/backend/theory/shvec/www/public/patterns/behavioral/visitor>
