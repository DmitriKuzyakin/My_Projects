# My_Projects
Репозитарий для хранения выполненных в процессе обучения на курсе "Яндекс.Практикум Аналитика данных" самостоятельных проектов
| Название проекта | Описание | Используемые библиотеки | Навыки |
| :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| [Оптимизация маркетинговых затрат в Яндекс.Афише](https://github.com/DmitriKuzyakin/My_Projects/tree/main/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D0%B1%D0%B8%D0%B7%D0%BD%D0%B5%D1%81%20%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9)| **Задача: на основе изучения данных о посещениях сайта Яндекс.Афиши необходимо оптимизировать рекламный бюджет.**<br>  В ходе проекта проведен когортный анализ. Рассчитаны метрики LTV, CAC, Retention rate, DAU, WAU, MAU, ROMI| *Python,* *Pandas,* *Matplotlib,* | *Когортный анализ;* <br>  *Юнит-экономика;* <br> *Продуктовые метрики;*|
| [Проверка гипотез по увеличению выручки в интернет-магазине — оценка результатов A/B теста](https://github.com/DmitriKuzyakin/My_Projects/tree/main/AB%20test) | **Задача: на основе данных интернет-магазина провести приоритизацию гипотез, оценить результаты A/B-тестирования и проверить корректность его проведения.** <br>Для приоритизации гипотез использовались фреймворки ICE и RICE. Проведен анализ графика кумулятивной выручки, среднего чека, конверсии по группам. Рассчитана статистическая значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа был сделан вывод о нецелесообразности дальнейшего проведения теста | *Python,* *Pandas,* *Matplotlib,* *Numpy,* *SciPy,* *Seaborn*| *A/B-тестирование;* <br>*Проверка статистических гипотез* |
|[Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](https://github.com/DmitriKuzyakin/My_Projects/tree/main/%D0%A0%D1%8B%D0%BD%D0%BE%D0%BA%20%D0%BE%D0%B1%D1%89%D0%B5%D0%BF%D0%B8%D1%82%D0%B0%20%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D1%8B)| **Задача: На основе исследования рынка общественного питания Москвы, оценить перспективность открытия кафе, в котором гостей обслуживают роботы-официанты.**  <br> Выводы и рекомендации по результатам анализа представлены в презентации для инвесторов. Для визуализации использовались библиотеки seaborn и plotly. В ходе анализа, возникла задача группировки данных по категориальным переменным, а также определения района расположения кафе-конкурентов. Для ее решения была применена лемматизация, реализованная с помощью библиотеки PyMystem3, для поисков шаблонов использовались регулярные выражения, с помощью библиотеки re| *Python,* *Pandas,* *Matplotlib,* *Numpy,* *SciPy,* *Seaborn,* *Plotly,* *PyMystem3*, *Re* | *Визуализация данных;* <br>*Лемматизация;* <br>*Регулярные выражения;* |
| [Анализ пользовательского поведения в мобильном приложении](https://github.com/DmitriKuzyakin/My_Projects/tree/main/AAB%20test) |**Задача: На основе данных использования мобильного приложения для продажи продуктов питания построить и проанализировать воронку продаж, а также оценить результаты и корректность проведения A/A/B-тестирования.**<br> В ходе анализа была построена воронка продаж для исследования «пути потребителя». После оценки корректности проведения теста (проверка на не пересечения групп, правильном разделении трафика; расчет стат. значимости различий АА теста и т.д.), была произведена проверка статистически значимых различий между долями пользователей на каждом шагу воронки.|  *Python,* *Pandas,* *Matplotlib,* *Numpy,* *SciPy,* *Seaborn,* *Plotly,* | *Cобытийная аналитика;* <br>*Продуктовые метрики;* <br>*Проверка статистических гипотез;* <br>*Визуализация данных* |
| [Прогнозирование вероятности оттока пользователей для фитнес-центров](https://github.com/DmitriKuzyakin/My_Projects/tree/main/Churn_Fitness) | **Задача: на основе анализа данных спрогнозировать вероятность оттока для каждого клиента в следующем месяце; Сегментировать пользователей.** <br> С помощью алгоритмов машинного обучения, спрогнозирована вероятность оттока пользователей на следующий месяц. Выявлены сегменты пользователей, проанализированы основные признаки, которые наиболее сильно влияют на факт оттока.| *Python,* *Pandas,* *Matplotlib,* *Numpy,* *SciPy,* *Seaborn,* *Scikit-learn* | *Машинное обучение;* *Классификация;* *Кластеризация;*|
| [Анализ поведения пользователей мобильного приложения](https://github.com/DmitriKuzyakin/My_Projects/tree/main/Segmentation) | **Задача: На основе анализа данных сегментировать пользователей** <br> В ходе анализа были рассчитаны следующие метрики:  DAU, WAU (проанализированы различия по источникам); Ratation Rate (анализ различий по когортам); Количество времени, которое в среднем пользователь проводит в приложении (в день, до целевого действия); Частота событий (в среднем по пользователям и по дням). Проведена кластеризация пользователей, и с учетом выявленных сегментов построены воронки конверсий. После чего рассчитана статистическая значимость различий в конверсию по источникам для каждого сегмента | *Python,* *Pandas,* *Matplotlib,* *Numpy,* *SciPy,* *Scikit-learn,* *Seaborn,* *Plotly,* *Tableau* | *Cобытийная аналитика;* <br>*Продуктовые метрики;* <br>*Проверка статистических гипотез;* *Кластеризация;*<br>*Визуализация данных;*<br>*Пстроение дашбордов*|
