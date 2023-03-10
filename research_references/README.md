# Исследование надёжности заёмщиков
Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку. 

# Цель исследования - проверить гипотезы:

1. С увеличением количества детей возрастает количество просроченных платежей.
2. Люди в браке чаще возвращают кредит в срок.
3. С увеличением дохода снижается количество просроченных платежей.
4. Цель кредита вляет на его возврат в срок.

# Задачи исследования:

1. Изучить общую информацию о данных.
2. Избавиться от пропусков в данных.
3. Обработать аномалии в данных.
4. Заменить вещественный тип данных в столбце total_income на целочисленный.
5. Удалить дубликаты.
6. Создать два новых датафрейма, в которых: каждому уникальному значению из education соответствует уникальное значение education_id — в первом; каждому уникальному значению из family_status соответствует уникальное значение family_status_id — во втором.
7. Разделить на категории уровень дохода клиентов и цель получения кредита.
8. Ответить на вопросы:
Есть ли зависимость между количеством детей и возвратом кредита в срок? Есть ли зависимость между семейным положением и возвратом кредита в срок? Есть ли зависимость между уровнем дохода и возвратом кредита в срок? Как разные цели кредита влияют на его возврат в срок? 9. Сделать общий вывод.

Данные о клиентах банка хранятся в таблице "data.csv". Перед проверкой гипотез нужно провести обзор данных.

Сначала необходимо проверить данные на ошибки и оценить их влияние на исследование. Затем, на этапе предобработки исправить самые критичные ошибки данных.

# Таким образом, исследование проходило в три этапа:

1. Обзор данных.
2. Предобработка данных.
3. Проверка гипотез.

| Название проекта | Тема | Сферы деятельности | Направления деятельности | Навыки и инструменты | Ключевые слова проекта |
| :--------------------: | :---------------------: | :---------------------------: | :---------------------: | :---------------------------: | :---------------------------: |
| Исследование надёжности заёмщиков — анализ банковских данных | Предобработка данных | Банковская сфера, Кредитование | Data Analyst, Финансовый аналитик | Python, Pandas, Предобработка данных | обработка данных, дубликаты, пропуски, категоризация, декомпозиция |
