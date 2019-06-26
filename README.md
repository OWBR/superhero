Информационные технологии (ИТ) для бизнес-аналитиков
====================================================

Список тем для лекций и занятий.

Аудитория - бизнес-аналитики, которые работают в следующих сферах:

- связь бизнес-стратегии и развития ИТ систем или продуктов
- управление отдельными проектами (solution)
- управление организацией на основе данных, data governance

Основная гипотеза: люди из бизнеса, прошедшие дополнительный цикл (пере)подготовки в области программирования, разработки и ИТ архитектуры, становятся более качественными заказчиками ИТ-услуг, что повышает эффективность команд и компаний в целом.

Подробнее о подходе к преподаванию [см. тут](intro.md).

Список тем
==========

1. [Программирование](#1-программирование)
1. [Работа с данными](#2-работа-с-данными)
1. [Процессы разработки и внедрения, DevOps](#3-процессы-разработки-и-внедрения-devops)
1. [ИТ-архитектура компании, связь бизнеса и ИТ](#4-ит-архитектура-компании-связь-бизнеса-и-ит)
1. [Персональная продуктивность](#5-персональная-продуктивность)
1. [Дополнительные темы и навыки](#дополнительные-темы-и-навыки)

## 1. Программирование

- Языки программирования и логика построения программ. 
- Практика программирования: цели, способы совершенствования, типовые сложности.
- Качество кода, рефакторинг, тестирование, документация.
- Алгоритмы и другие результаты из computer scicence.
- Абстракции, архитектура программ, паттерны. Интерфейсы программ (API).

По программированию [есть детализация тем](programming.md). 

## 2. Работа с данными

Практика:

- Машинно-читаемые форматы данных, сериализация.
- Базы данных, SQL, ORM. NoSQL/GraphQL.
- Визуализация данных - как рисовать картинки, дэшборды.
- Данные в исследованиях: immutable data/"source of truth", DAG.
- АPI получения данных. Примеры хранения (AWS S3). 

Состояние дел:

- Качество данных, data governance.
- Oфициальная статистика и данные в госорганах.
- Корпоративные системы (DWH, lake, mesh). 
- Data privacy, GDPR.


## 3. Процессы разработки и внедрения, DevOps

- Продукт
- Постановка задачи, спецификация, техническое задание.
- DDD и разные "cool-thing"-driven development
- Agile vs waterfall
- Типовые проблемы разработки и опыт работы команд
- Особенности взаимодействия (например, парное программирование)
- Работа фрилансера и с фрилансерами


#### DevOps

- version control (до-git, gitlab/github). Как написать хороший коммит.
- issue traker (Jira, etc)
- CI (travis, circle) / CD(heroku)
- infrastructure as code, AWS, ainsible, 
- "Облако это чей-то компьютер"
- docker


## 4. ИТ-архитектура компании, связь бизнеса и ИТ

- участники процесса (CIO, CDO, команды)
- solution и enterprise архитектура, 
- подходы к цифровизации
- (слабая) связь ИТ со стратегией
- успехи и провалы ИТ проектов
- основы бюджетирования 

## 5. Персональная продуктивность

- работа с командной строкой
- markdown (rst, asciidoc)
- plain text в git
- сервисы AWS
- jupyter notebook, binder
- todo: todo.txt / trello / wip vs trying
- создание онлайн документации, учебников, статические генераторы сайтов
- PDF/latex
- удобный текстовой редактор (oт vim до VS-Code) 

## 6. Дополнительные темы и навыки

- Распределенные системы, интеграция, мониторинг 
- Пользовательские интерфейсы (UI/UX)
- Технические диаграммы (UML, C4 model)
- Подходы к цифровизации
- Работа команд, коммуникаци
- Экономика ИТ компаний, затраты на ИТ в бизнесе
- Преподавание и электронные учебники (jupyter, colab, bookdown)

Не раскрыто, но хотелось бы в будущем:

- операционные системы
- безопасность
- словарь терминов
- больше примеров live coding

Cознательно пропускаем (разные причины):

- фронтэнд, javascript/node.js
- системное программирование
- криптография


Предыстория
-----------

Список основан на опыте преподавания курсов "Машинночитаемая корпоративная отчетность" (ЦМФ), лекций "Введение в ИТ-архитектуру" (МГИМО), обсуждения на митапе Московского клуба программистов 13.06.2019.
