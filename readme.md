# Проекты для специализации "Аналитик данных" 


Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных"

| Название проекта | Описание | Навыки и инструменты | 
| :---------------------- | :---------------------- | :---------------------- |
| [Музыка больших городов](01_music_big_cities) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница)| `Python` `Pandas`|
| [Исследование надёжности заёмщиков](02_bank_reliability) | На основе данных кредитного отдела банка исследованы влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три. | `предобработка данных` `Python` `Pandas` |
| [Aнализ рынка недвижимости](03_nedv_spb) | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | `Python` `Pandas` `Matplotlib` `исследовательский анализ данных` `визуализация данных` `предобработка данных` |
| [Определение выгодного тарифа для телеком компании](04_megaline_tarif) | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. | `Python` `Pandas` `Matplotlib` `NumPy` `SciPy` `описательная статистика` `проверка статистических гипотез` |
| [Изучение закономерностей, определяющих успешность игр](05_games_success) | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использован критерий Стьюдента для независимых выборок. | `Python` `Pandas` `NumPy` `Matplotlib` `предобработка данных` `исследовательский анализ данных` `описательная статистика` `проверка статистических гипотез` | 
| [Анализ рынка инвестиций(SQL)](06_sql_investitions) | Анализ рынка инвестиций с помощью SQL - запросов | `SQL` `PostgreSQL` |
| [Анализ бизнес-показателей](07_procrasinate_pro) | Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным. | `Python` `Pandas` `Matplotlib` `когортный анализ` `юнит-экономика` `продуктовые метрики` `Seaborn` |
| [Оценка результатов A/B теста (Проверка гипотез по увеличению выручки в интернет-магазине)](08_ab_test) | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем проведен анализ результатов A/B-теста, построены графики кумулятивной выручки, среднего чека, конверсии по группам, вычислена статистическая значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа было принято решение о нецелесообразности дальнейшего проведения теста. | `Python` `Pandas` `Matplotlib` `SciPy` `A/B-тестирование` `проверка статистических гипотез` |
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](09_cafe_moscow) | Был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков использованы библиотеки seaborn и plotly.  | `Python` `Pandas` `Seaborn` `Plotly` `визуализация данных` |
| [Анализ пользовательского поведения в мобильном приложении](10_sbor_app) | Изучены принципы событийной аналитики. Построена воронка продаж, исследован путь пользователей до покупки. Проанализированы результаты A/B-теста введения новых шрифтов. Сравнены 2 контрольные группы между собой, доказано правильное разделение трафика. Проведено сравнение с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей. | `Python` `SQLAlchemy` `PostgreSQL` `dash` `Tableau` `продуктовые метрики` `построение дашбордов` |
| [Создание дашборда по пользовательским событиям для Яндекс.Дзен](11_dzen) | Работа проведена на удаленной машине в сервисе Yandex.Cloud. Был установлен PostgreSQL, развернута база данных. Написан скрипт пайплайна, который позволил собирать данные за определенный временной период, и настроена его автономную работу через crontab. Для визуализации собранных данных написан скрипт дашборда с несколькими фильтрами и запущен на удаленной машине. По результатам была подготовлена презентация с полученными графиками | `Python` `SQLAlchemy` `PostgreSQL` `dash` `Tableau` `продуктовые метрики` `построение дашбордов` |
| []() |  |  |
| []() |  |  |
| []() |  |  |
| []() |  |  |

