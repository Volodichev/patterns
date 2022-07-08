# Паттерны в python (Patterns)

**Паттерн проектирования** — это часто встречающееся решение определённой проблемы при проектировании архитектуры программ. Паттерны часто путают с алгоритмами, ведь оба понятия описывают типовые решения каких-то известных проблем. Если привести аналогии, то алгоритм — это кулинарный рецепт с чёткими шагами, а паттерн — инженерный чертёж, на котором нарисовано решение, но не конкретные шаги его реализации.

## Порождающие паттерны(Creational Patterns):
_беспокоятся о гибком создании объектов без внесения в программу лишних зависимостей._


- [Абстрактная фабрика (Abstract Factory)](./abstract_factory#readme) Семейства связанных объектов.
- [Строитель (Builder)](./builder#readme) Cложные объекты пошагово. один код для разных объектов.
- [Фабричный метод (Factory Method)](./factory_method#readme) Общий интерфейс для подклассов изменет тип объектов.
- [Прототип (Prototype)](./prototype#readme) Копируем объекты, не вдаваясь в подробности реализации.
- [Одиночка (Singleton)](./singleton#readme) Класс имеет только один экземпляр, и глобальную точку доступа.
- borg?
- lazy_evaluation?
- pool?

## Структурные паттерны(Structural Patterns):
_показывают различные способы построения связей между объектами._



- [Адаптер (Adapter)](./adapter#readme) Несовместимые интерфейсы
- [Компоновщик (Composite)](./composite#readme) Древовидная структуруа
- [Декоратор/оформитель (Decorator)](./decorator#readme) Функциональность через «обёртки».
- [Фасад (Facade)](./facade#readme) Простой интерфейс к сложной структуре 
- [Мост (Bridge)](./bridge#readme) Абстракция + Реализация
- [Легковес/Приспособленец (Flyweight)](./flyweight#readme) Разделяя общее состояние объектов
- [Заместитель/прокси/суррогат (Proxy/surrogate)](./proxy#readme) Подставляет объекты-заменители.
- _Модуль_ 
- _3-tier_
- _Front controller (единая точка входа)_
- _MVC_

## Поведенческие паттерны(Behavioral Patterns):
_заботятся об эффективной коммуникации между объектами._

- [Команда/действие (Command/action)](./command#readme) Передает запросы в объекты как аргументы.
- [Итератор/указатель (Iterator)](./iterator#readme) Последовательный обход элементов составных объектов.
- [Наблюдатель/слушатель (Observer/Listener)](./observer#readme) Один объект следит за другим.
- [Стратегия (Strategy)](./strategy#readme) Схожие алгоритмы в класс.
- [Посредник (Mediator)](./mediator#readme) Перемещение связей в один класс-посредник.
- [Состояние (State)](./state#readme) Меняет поведение в зависимости от состояния.
- [Шаблонный метод (Template Method)](./template_method#readme) Перекладывает ответственность на подклассы не меняя его общей структуры.
- [Цепочка обязанностей (Chain of Responsibility)](./chain_of_responsibility#readme) Запросы по цепочке обработчиков. 
- [Снимок/Хранитель (Memento)](./memento#readme) Снимки состояния объектов.
- [Посетитель (Visitor)](./visitor#readme) Новые операции, не меняя классы объектов.
- [Классная доска (Blackboard)(доска объявлений)]((./blackboard#readme))
- catalog?
- chaining_method
- publish_subscribe
- specification (спецификация, определение)
- Servant (слуга)
- Subsumption 
- Single-serving visitor (одноразовый посетитель)
- Hierarchical visitor (иерархический посетитель)

## Design for Testability Patterns:
- dependency_injection Dependency injection (внедрение зависимости)
- Lazy initialization (отложенная инициализация)
- 
## Fundamental Patterns:
- delegation_pattern

## Other:
- blackboard
- graph_search
- HSM

- Registry (реестр, журнал записей)

- inheritance?
- wrapper?
- null
- closure
- Object pool (пул объектов)
- Multiton (пул «одиночек»)

[Источник.](https://refactoring.guru/ru/design-patterns)
