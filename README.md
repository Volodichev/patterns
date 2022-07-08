# Паттерны в python (Patterns)


## Порождающие паттерны(Creational Patterns):

- [Абстрактная фабрика (Abstract Factory)](./abstract_factory#readme) Семейства связанных объектов.
- [Строитель (Builder)](./builder#readme) Cложные объекты пошагово. один код для разных объектов.
- [Фабричный метод (Factory Method)](./factory_method#readme) Общий интерфейс для подклассов изменет тип объектов.
- [Прототип (Prototype)](./prototype#readme) Копируем объекты, не вдаваясь в подробности реализации.
- [Одиночка (Singleton)](./singleton#readme) Класс имеет только один экземпляр, и глобальную точку доступа.
- borg?
- lazy_evaluation?
- pool?

## Структурные паттерны(Structural Patterns):

- [Адаптер (Adapter)](./adapter#readme) Несовместимые интерфейсы
- [Компоновщик (Composite)](./composite#readme) Древовидная структуруа
- [Декоратор (Decorator)](./decorator#readme) Функциональность через «обёртки».
- [Фасад (Facade)](./facade#readme) Простой интерфейс к сложной структуре 
- [Мост (Bridge)](./bridge#readme) Абстракция + Реализация
- [Легковес/Приспособленец (Flyweight)](./flyweight#readme) Разделяя общее состояние объектов
- [Заместитель (Proxy)](./proxy#readme) Подставляет объекты-заменители.
- Модуль 
- 3-tier
- front_controller
- MVC

## Поведенческие паттерны(Behavioral Patterns):

- [Команда (Command)](./command#readme) Передает запросы в объекты как аргументы.
- [Итератор (Iterator)](./iterator#readme) Последовательный обход элементов составных объектов.
- [Наблюдатель (Observer)](./observer#readme) Один объект следит за другим.
- [Стратегия (Strategy)](./strategy#readme) Схожие алгоритмы в класс.
- [Посредник (Mediator)](./mediator#readme) Перемещение связей в один класс-посредник.
- [Состояние (State)](./state#readme) Меняет поведение в зависимости от состояния.
- [Шаблонный метод (Template Method)](./template_method#readme) Перекладывает ответственность на подклассы не меняя его общей структуры.
- [Цепочка обязанностей (Chain of Responsibility)](./chain_of_responsibility#readme) Запросы по цепочке обработчиков. 
- [Снимок/Хранитель (Memento)](./memento#readme) Снимки состояния объектов.
- [Посетитель (Visitor)](./visitor#readme) Новые операции, не меняя классы объектов.
- Классная доска (Blackboard)
- catalog?
- chaining_method
- publish_subscribe
- registry
- specification

## Design for Testability Patterns:
- dependency_injection

## Fundamental Patterns:
- delegation_pattern

## Other:
- blackboard
- graph_search
- HSM


- inheritance?
- wrapper?
- null
- closure

[Источник.](https://refactoring.guru/ru/design-patterns)
