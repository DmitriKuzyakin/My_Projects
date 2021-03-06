<h1><center>Анализ пользовательского поведения в мобильном приложении (A/A/B-эксперимент)</center></h1> 


## Данные

В наличии были следующие данные о проведении A/A/B-эксперимента для стартапа, который продаёт продукты питания.
-	EventName — название события;
-	DeviceIDHash — уникальный идентификатор пользователя;
-	EventTimestamp — время события;
-	ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.


## Задача

На основе данных использования мобильного приложения для продажи продуктов питания построить и проанализировать воронку продаж, а также оценить результаты A/A/B - эксперимента. Тестируется влияние на пользователей изменения шрифтов во всём приложении


## Описание проекта


В данном проекте мной были изучены принципы событийной аналитики. Я определил цепочку действий пользователя до целевого действия, построил воронку продаж.<br>
Проанализировал результаты АА-теста. Так как в ходе работы проводилась проверка множества гипотез, уровень значимости был скорректирован методом Шидака. Проверка проводилась
с помощью z-критерия.<br>
Статистически значимых различий между долями пользователей на каждом шагу воронки групп А (246 и 247)– выявлено не было. То есть можно говорить о корректном провидении тестирования.<br>
После чего была рассчитана статистическая значимость различий между А и В группами (их мы тоже я тоже не обнаружил).<br>
Исходя из того, что размеры выборок и период проведения эксперимента – были посчитаны верно, можно заключить, что "изменение шрифтов" в приложение - никак не влияет на переходы пользователей по станицам.<br>
В качестве рекомендаций, можно предложить посмотреть другие метрики – средний чек, например, возможно там есть стат. значимое различие

## Навыки и инструменты
-	*Python*
-	*Pandas*
-	*Matplotlib*
-	*Numpy*
-	*Seaborn*
-	*Plotly*
-	*Cобытийная аналитика*
-	*Продуктовые метрики*
-	*A/B-тестирование*
-	*Проверка статистических гипотез*
-	*Визуализация данных*


