<h1><center> Прогнозирование вероятности оттока пользователей для фитнес-центров </center></h1> 

## Данные
Разрабатывается стратегия по взаимодействию с клиентами сети фитнес-центров.

В наличии следующие данные:
-  Churn — факт оттока в текущем месяце;
-  gender — пол
- Near_Location — проживание или работа в районе, где находится фитнес-центр
- Partner — сотрудник компании-партнёра клуба (сотрудничество с компаниями, чьи сотрудники могут получать скидки на абонемент в таком случае фитнес-центр хранит информацию о работодателе клиента)
- Promo_friends — факт первоначальной записи в рамках акции «приведи друга» (использовал промо-код от знакомого при оплате первого абонемента)
- Phone — наличие контактного телефона
- Age — возраст
- Lifetime — время с момента первого обращения в фитнес-центр (в месяцах)
- Contract_period — длительность текущего действующего абонемента (месяц, 3 месяца, 6 месяцев, год)
- Month_to_end_contract — срок до окончания текущего действующего абонемента (в месяцах)
- Group_visits — факт посещения групповых занятий
- Avg_class_frequency_total — средняя частота посещений в неделю за все время с начала действия абонемента
- Avg_class_frequency_current_month — средняя частота посещений в неделю за предыдущий месяц
- Avg_additional_charges_total — суммарная выручка от других услуг фитнес-центра: кафе, спорт-товары, косметический и массажный салон



## Задача
- Спрогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
- Сформировать типичные портреты клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
- сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами


## Описание проекта
  В данном проекте мной были изучены основы машинного обучения.<br>
  Модель прогнозирования оттока клиентов - это модель бинарной классификации клиентов, где целевой признак — факт оттока клиента в следующем месяце. Она была построена на основе логистической регрессии (LogisticRegression) и алгоритма случайный лес (RandomForestClassifier)<br>
  Оптимальные параметры модели подбирались с помощью GridSearchCV, оптимизировалась метрика ROC_AUC. <br>
  Также, при сравнение моделей, уделялось особое внимание метрики recall, так как согласно поставленным целям работы, нам нужно разработать рекомендации по повышению качества работы с клиентами и не «пропустить» клиента, который может потенциально уйти.<br>
  Для формирования типичного портрета клиентов, была построена дендрограмма, На основании полученного графика определили предполагаемое количество кластеров и была построена модель кластеризации на основании алгоритма K-Means.<br>
  В результате анализа удалось определить, что ключевыми являются признаки: длительность контракта, частота посещений, активность (т.е. посещение групповых занятий, посещение вместе с друзьями).<br>
  В качестве рекомендаций, можно предложить, провести стимулирующие маркетинговые акции: например, скидки при покупке годового абонемента или (и) скидки мотивирующие к регулярному посещению центра, скидочная программа для друзей, для групповых занятий и т.д.<br>

## Навыки и инструменты
-	*Python*
-	*Pandas*
-	*Matplotlib*
-	*Numpy*
-	*Seaborn*
-	*SciPy*
-  *Scikit-learn*
-	*Машинное обучение*
-	*Классификация*
-	*Кластеризация*
