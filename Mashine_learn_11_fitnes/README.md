# Оптимизация стратегии удержания клиентов сети фитнес-центров


## Данные

**Описание данных**
- Churn — факт оттока в текущем месяце

**Данные клиента за предыдущий до проверки факта оттока месяц**
- gender — пол
- Near_Location — проживание или работа в районе, где находится фитнес-центр
- Partner — сотрудник компании-партнёра клуба
- Promo_friends — факт первоначальной записи в рамках акции «приведи друга»
- Phone — наличие контактного телефона
- Age — возраст
- Lifetime — время с момента первого обращения в фитнес-центр (в месяцах)

**Информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента**
- Contract_period — длительность текущего действующего абонемента (месяц, 3 месяца, 6 месяцев, год)
- Month_to_end_contract — срок до окончания текущего действующего абонемента (в месяцах)
- Group_visits — факт посещения групповых занятий
- Avg_class_frequency_total — средняя частота посещений в неделю за все время с начала действия абонемента
- Avg_class_frequency_current_month — средняя частота посещений в неделю за предыдущий месяц
- Avg_additional_charges_total — суммарная выручка от других услуг фитнес-центра: кафе, спорт-товары, косметический и массажный салон

## Задача

Спрогнозировать вероятность оттока посетителях сети фитнес-центровдля каждого клиента в следующем месяце, сформировать с помощью кластеризации портреты пользователей.  

## Используемые библиотеки
*pandas*, *numpy*, *matplotlib*, *scipy*,*seaborn*, *sklearn*