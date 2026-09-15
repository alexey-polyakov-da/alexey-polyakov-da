# Алексей Поляков

## Data Analyst

Аналитик данных с инженерным и управленческим опытом. Решаю задачи продуктовой и бизнес-аналитики: исследую данные, рассчитываю метрики, проверяю статистические гипотезы и превращаю результаты анализа в практические рекомендации.

📍 Санкт-Петербург · Открыт к предложениям в области анализа данных

## Технологии

### Анализ данных и программирование

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4051B5)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Plotly](https://img.shields.io/badge/Plotly-Visualization-3F4F75?logo=plotly&logoColor=white)

### Базы данных и SQL

![SQL](https://img.shields.io/badge/SQL-336791)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)

`JOIN` · CTE · подзапросы · оконные функции · `LAG/LEAD` · `ROW_NUMBER` · `RANK/DENSE_RANK` · когортный анализ

### BI и визуализация

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![Yandex DataLens](https://img.shields.io/badge/Yandex-DataLens-FFCC00)
![Looker Studio](https://img.shields.io/badge/Looker-Studio-4285F4?logo=looker&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?logo=metabase&logoColor=white)

### Методы анализа

`EDA` · продуктовые метрики · A/B-тестирование · статистические гипотезы · когортный анализ · MAU · retention · LTV · конверсия

## Проекты

### [Yandex Afisha — Product Analytics](https://github.com/alexey-polyakov-da/yandex-afisha-analysis)

Исследование бронирований билетов: динамика спроса, сезонность, категории мероприятий, регионы, партнёры и поведение пользователей разных устройств.

- число заказов выросло с 32 845 в июне до 99 914 в октябре;
- выявлены основные драйверы осеннего спроса — театр и спорт;
- проверены статистические гипотезы для пользователей `mobile` и `desktop`;
- подготовлен интерактивный дашборд в Yandex DataLens.

**Стек:** Python, Pandas, Matplotlib, Seaborn, SciPy, Yandex DataLens.

### [Product Analytics and A/B Testing](https://github.com/alexey-polyakov-da/product-analytics-ab-test)

SQL-анализ метрик сервиса «Яндекс Книги» и оценка A/B-теста нового интерфейса интернет-магазина.

- рассчитаны MAU, retention, LTV и средняя выручка на час;
- проведён аудит качества эксперимента и исключены пересечения с другим тестом;
- конверсия выросла с 28,98% до 31,17%;
- изменение статистически значимо (`p-value = 0,0085`), но целевой эффект +3 п.п. не достигнут.

**Стек:** PostgreSQL, SQL, Python, Pandas, SciPy, Statsmodels, A/B Testing.

### [Анализ рынка недвижимости Санкт-Петербурга и Ленинградской области](https://github.com/alexey-polyakov-da/spb-real-estate-analysis)

SQL-анализ объявлений о продаже недвижимости и интерактивный дашборд для агентства.

- исследованы сроки активности, цены и характеристики объектов;
- сопоставлены Санкт-Петербург и населённые пункты Ленинградской области;
- выявлены сезонные особенности публикации и снятия объявлений;
- доработан дашборд с KPI, фильтрами и детализацией по периодам.

**Стек:** PostgreSQL, SQL, CTE, JOIN, оконные функции, Yandex DataLens.

### [Анализ венчурного финансирования стартапов](https://github.com/alexey-polyakov-da/startup-venture-funding-analysis)

Исследование структуры и динамики венчурного рынка за 2000–2014 годы.

- проанализировано более 54 тыс. записей о компаниях и финансировании;
- выполнены сегментация рынков и поиск выбросов методом IQR;
- сопоставлены популярность, объёмы и возвраты разных типов финансирования;
- сформирована инвестиционная гипотеза для сегмента `software` и венчурной модели.

**Стек:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, EDA.

### [Анализ рынка общественного питания Москвы](https://github.com/alexey-polyakov-da/moscow-catering-market-analysis)

Исследование 8,4 тыс. московских заведений для выбора концепции нового объекта общественного питания.

- изучены категории, административные округа и сетевой статус заведений;
- сопоставлены вместимость, рейтинги и ценовые признаки;
- определены топ-15 сетей и различия среднего чека по округам;
- сформулированы рекомендации и ограничения для инвестиционной оценки.

**Стек:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, EDA.

### [Подготовка данных о рынке видеоигр](https://github.com/alexey-polyakov-da/video-game-industry-analysis)

Подготовка исторических данных о видеоиграх для дальнейшего анализа игровой индустрии за 2000–2013 годы.

- обработаны пропуски, типы данных и дубликаты;
- сформирован аналитический срез из 12 781 записи;
- добавлены категории пользовательских и экспертных оценок;
- определены семь наиболее представленных игровых платформ.

**Стек:** Python, Pandas, NumPy, Jupyter Notebook, Data Cleaning, Feature Engineering.

## Обо мне

- Кандидат технических наук.
- Лауреат премии Правительства Российской Федерации в области науки и техники.
- Имею опыт управления сложными IT-проектами и подготовки аналитической отчётности.
- Прошел профессиональную переподготовку по направлениям «Аналитик данных» и «Дата-инженер».
- Готов выполнить тестовое задание и пройти техническое собеседование.

## Контакты

- GitHub: [alexey-polyakov-da](https://github.com/alexey-polyakov-da)
