# Выявление законемерностей, определяющих успешность игр
Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. Перед вами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года. В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

**Цель исследования** - выявить определяющие успешность игры закономерности.

**Задачи исследования:**

1. Подготовить данные:
- Заменить названия столбцов;
- Преобразовать данные в нужные типы;
- Обработать пропуски;
- Посчитать суммарные продажи во всех регионах и записать их в отдельный столбец.

2. Посмотреть, сколько игр выпускалось в разные годы.

3. Посмотреть, как менялись продажи по платформам. Выберать платформы с наибольшими суммарными продажами и построить распределение по годам.

4. Для данных за соответствующий актуальный период:
- Какие платформы лидируют по продажам, растут или падают? Выберать несколько потенциально прибыльных платформ.
- Построить график «ящик с усами» по глобальным продажам игр в разбивке по платформам.
- Посмотреть, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков. Построить диаграмму рассеяния и посчитать корреляцию между отзывами и продажами.
- Соотнести выводы с продажами игр на других платформах.
- Посмотреть на общее распределение игр по жанрам. Что можно сказать о самых прибыльных жанрах? Выделяются ли жанры с высокими и низкими продажами?

5. Составить портрет пользователя каждого региона:
- Самые популярные платформы (топ-5). Описать различия в долях продаж.
- Самые популярные жанры (топ-5). Пояснить разницу.
- Влияет ли рейтинг ESRB на продажи в отдельном регионе?

6. Проверить гипотезы:
- Средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
- Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.

| Название проекта | Тема | Сферы деятельности | Направления деятельности | Навыки и инструменты | Ключевые слова проекта |
| :--------------------: | :---------------------: | :---------------------------: | :---------------------: | :---------------------------: | :---------------------------: |
| Выявление законемерностей, определяющих успешность игр | Первый сборный проект DS | Бизнес, Интернет-магазин | Data Analyst, Машинное обучение | Python, Pandas, Scikit-learn | обработка данных, дубликаты, пропуски, логическая индексация, группировка, сортировка |