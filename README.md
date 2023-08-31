# Yandex_practikum
Это репозиторий о моих учебных проектах в Яндекс практикуме. Курс Аналитик данных

### Основные инструменты и навыки, полученные при обучении:

- Языки: Python, SQL
- Анализ данных: библиотеки Pandas, NumPy, SciPy, Statsmodels
- Визуализация: Matplotlib, Plotly, Seaborn
- Построение дашбордов: Tableau
- Метрики юнит-экономики, когортный анализ
- А/В-тестирование
- Работа с гипотезами


# Проекты


| Название проекта  | Сферы деятельности | Направление деятельности | Навыки и инструменты | Задачи проекта | Описание | 
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|1. [Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов](Music_project.ipynb)|`Интернет-сервисы` `Стриминговый сервис`|Data Analyst|`Python` `Pandas`|На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.|Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс.Музыки я проверила данные и сравнила поведение пользователей двух столиц.|
|2. [Исследование надёжности заёмщиков — анализ банковских данных](zaem2.ipynb)|`Банковская сфера` `Кредитование`|`Data Analyst` `Финансовый аналитик`|`предобработка данных` `Python` `Pandas`|На основе данных о платёжеспособности клиентов исследовать влияние семейного положения и количество детей клиента на факт возврата кредита в срок|На основе данных кредитного отдела банка исследовала влияние семейного положения и количества детей на факт погашения кредита в срок. Получила информация о данных. Нашла и обработала пропуски. Заменила типы данных на соответствующие хранящимся данным. Удалила дубликаты. Категоризировала данные. Декомпозировала один датафрейм на три.|
|3. [Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](RealEstate.ipynb)|`Интернет-сервисы` `Площадки объявлений`|`Data Analyst` `Маркетинг аналитик` `Fraud-аналитик`|`предобработка данных` `Python` `Pandas` `Matplotlib` `исследовательский анализ данных` `визуализация данных`|Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир|На основе данных сервиса Яндекс.Недвижимость определила рыночную стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведела предобработку данных. Добавила новые данные. Построила гистограммы, боксплоты, диаграммы рассеивания.|
| 4. [Определение лучшего тарифа для телеком компании](best_tarif.ipynb) |`Статистический анализ данных`|`Телеком`|`Маркетинг аналитик` `Продуктовый аналитик` `Data Analyst`|`Python` `Pandas` `Matplotlib` `NumPy` `описательная статистика` `проверка статистических гипотез`|Проверите гипотезы телеком-компании, чтобы помочь вырастить бизнес.|Провела предварительный анализ использования тарифов на выборке клиентов компании, проанализировано поведение клиентов при использовании услуг. Проведена предобработка данных, их анализ. Проверены статистические гипотезы на основе имеющихся данных.|
| 5. [Изучение закономерностей, определяющих успешность игр](games.ipynb) |`Gamedev` `Интернет-магазины`|`Продуктовый аналитик` `Маркетинг аналитик`|`Python` `Pandas` `Matplotlib` `NumPy` `предобработка данных` `описательная статистика` `проверка статистических гипотез` `исследовательский анализ данных` |Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры |Выявила параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовила отчет для магазина компьютерных игр для планирования рекламных кампаний. Провела предобработку данных, анализ. Выбрала актуальный период для анализа. Составила портреты пользователей каждого региона. Проверила гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовала критерий Стьюдента для независимых выборок.|
| 6. Исследование данных об инвестиции венчурных фондов в компании-стартапы | Content Cell  | Content Cell  |Content Cell  |Content Cell  |Content Cell  |
| 7. [Анализ бизнес-показателей приложения ProcrastinatePRO+](metrics_pro.ipynb) |`Интернет-сервисы` `Стартапы`|Продуктовый аналитик` `Маркетинг аналитик`|`Python` `Pandas` `Matplotlib` `когортный анализ` `юнит-экономика` `продуктовые метрики` `Seaborn`|Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс.|Провела анализ данных от ProcrastinatePRO+. Рассчитала различные метрики, использовала когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использовала ранее написанные функции расчёта метрик. Сделала выводы по полученным данным.|
| 8. [Анализ сервиса вопросов и ответов по программированию](sql_adv.txt) | Content Cell  | Content Cell  |`SQL` |Content Cell  |С помощью Python и SQL подключаемся к базе данных, считаем и визуализируем ключевые метрики сервис-системы вопросов и ответов о программировании.|
| 9. Проверка гипотез по увеличению выручки в интернет-магазине. Оценка результатов A/Bтеста | Content Cell  | Content Cell  |Content Cell  |Content Cell  |Content Cell  |
| 10. Анализ пользовательского поведения в мобильном приложении | Content Cell  | Content Cell  |Content Cell  |Content Cell  |Content Cell  |
|11. Исследования рынка общепита в Москве для принятия решения об открытии нового заведения | Content Cell  | Content Cell  |Content Cell  | Content Cell  | Content Cell  |
| 12. Создание дашборда по пользовательским событиям для агрегатора новостей | Content Cell  | Content Cell  |Content Cell  | Content Cell  | Content Cell  |
| 13. Выпускной проект | Content Cell  | Content Cell  |Content Cell  | Content Cell  | Content Cell  |




