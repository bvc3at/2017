# Python 2017

Ссылка на курс: https://github.com/mos-polytech/2017


## План

### Занятие 1: Введение

- Общее знакомство с `Python`, его историей и перспективами
- Общее знакомство с версиями `Python` 2.7 и 3.5
- `print('Hello Pythonic world!')`, первый commit и push на github
- Детальный разбор, что же произошло в пункте выше
- Знакомство с базовым синтаксисом, базовые типы данных
- Что такое переменная? Как ее объявить, и где ее видно?
- Знакомство со структурами языка: ветвления, циклы, условия
- Stackoverflow-driven development, секция о том, как самому найти ответы на свои вопросы

### Занятие 2: "Сложные" типы данных

- Что такое `Iterable`?
- Какие итерабильные типы данных бывают?
- Знакомство с кортежами и списками
- Что такое "mutable" и "immutable" типы?
- Знакомство со словарями
- Что такое "hashable" и "unhashable" типы?

### Занятие 3: Функции

- Что такое функция?
- Что такое сигнатура функции?
- Какие параметры могут принимать функции?
- Что может возвращать функция?
- Что такое замыкание?
- Краткая информация о функциональном подходе в Python

### Занятие 4: Введение в ООП

- Что такое ООП? Какие задачи оно решает?
- Что такое класс?
- Что такое объект?
- 4 основных принципа ООП, и зачем они нужны
- Основы динамической типизации
- Магические методы
- Модули

### Занятие 5: Паттерны проектирования

- Композиция и агрегация
- DRY, KISS, YAGNI, SOLID
- Композиция и наследование
- Pythonic-way
- Зависимости и pip

### Занятие 6: Усложненение синтаксиса

- Декораторы
- Контекстные менеджеры
- Работа с файлами
- Списковые выражения
- Генераторы

### Занятие 7: Тестирование приложений

- Зачем нужно тестирование?
- Какое бывает тестирование?
- Что такое unittest?
- Что такое pytest?
- Лучшие практики по написанию тестов

### Занятие 8: Scrapy

- Как устроен интернет? Знакомство с `TCP/IP`, `DNS` и клиент-серверной архитектурой
- Зачем нам `http` перед адресом? Знакомство с протоколом `HTTP` с модулем `urllib`
- Что такое регулярное выражение? Модуль `re`
- Что такое веб-паук? Когда им пользоваться и зачем?
- Написание веб-паука на основе `Scrapy`, который будет получать статусы со страницы соц.сети и сохранять результаты в файле

### Занятие 9: Django

- Что такое `Django`? И как работает данный фреймворк?ъ
- Какой путь проходит запрос в жизненном цикле приложения?
- Знакомство с middleware
- url-routing, `include()` и `reverse()`
- `Django`'s MVC и MVT, знакомство с `Django-Templates`
- `views` и `class-based views`
- Простые формы, валидация форм
- Статические файлы
- Организация настроек приложения

### Занятие 10: Django ORM

- Знакомство с моделями
- Установка и настройка `PostgreSQL`
- Отношения моделей между собой: `OneToOne`, `ManyToMany` и `ForeingKey`
- Как написать запрос?
- Сигналы
- Миграции, обзор исторического `South` и текущего `Django-Migrations`

### Занятие 11: Работа с моделями в Django

- Как написать сложный запрос? `annotate()`, `aggregate()`
- Как сделать сложный запрос проще? `select_related()`, `prefetch_related()`, `values()`
- Следим за запросами с помощью `django-debug-toolbar`
- Создание и валидация `ModelForm`
- Работа в `FileField` и `ImageField`, сохранение пользовательских медиа файлов
- Наследование моделей, абстрактные модели и миксины
- Менеджеры
- `raw queries`: плюсы и минусы

### Занятие 12: Администрирование Django приложений

- Как устроена админская панель?
- Как администрировать приложение?
- Авторизация пользователей, группы и права доступа
- Создание собственных `admin-view`
- Знакомство с `django-admin-tools`
- `Django Management Commands`, создание своих комманд
- Как правильно вести логи?

### Занятие 13: Celery

- Настройка и установка `Celery with Redis`
- Знакомство с асинхронными задачами
- Периодичные задания с `Celery Beat`
- Конроль выполнения задач с `Celerycam`
- Мониторинг `Redis`
- Как дебажить `Celery`?
- Написание асинхронных задач

### Занятие 14: Django Rest Framework

- Что такое REST?
- Что такое Serializer?
- Что такое Router?
- Генерируем авто-документацию для DRF
- Знакомство с JWT и Stateless-авторизацией
