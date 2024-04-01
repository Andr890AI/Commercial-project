# Commercial-project
Здесь собраны некоторые реализованные проекты

| Наименование проекта | Описание  |Стек|
|:------------- |:---------------:| -------------:|
|[Построение ML-продукта для оптимизации классификации заявок на оплату для сервиса Repetit.ru]([https://goo.su/y1Sk41Z](https://clck.ru/39oAU7))|Анализ комментариев пользователей на токсичность|python, pandas, numpy, nltk, sklearn, CatBoost|
|[Улучшение процесса обогащения золота](https://goo.su/pNode)|Выбор лучшей модели для увеличения показателей технологического процесса обогащения золота|python, pandas, numpy, scipy, sklearn, matplotlib|
|[Успешность игр](https://goo.su/C0sZy2)|Изучение закономерностей, определяющих успешность игр|обработка данных, histogram, boxplot, статистический тест, критерий Стьюдента, piechart|
|[Прогноз количества заказов для сервиса такси](https://goo.su/zrchddi)|Прогноз количества заказов в аэропортах для сервиса такси с целью более точного планирования количества доступных автомобилей|python, pandas, numpy, statsmodels, sklearn, CatBoost, matplotlib|






### ПРОЕКТ:
Построение ML-продукта для оптимизации классификации заявок на оплату для сервиса Repetit.ru
- Описание проекта
Сервис Repetit.ru работает с большим количеством заявок от клиентов с данными о предмете, желаемой стоимости, возрасте ученика, целью занятий и тд. К сожалению, 7 из 8 не доходят до оплаты, при этом обработка заявки консультантом увеличивает конверсию в оплату на 30%.
Проблема в том, что консультантов не хватает на все заявки и получается, что чем больше заявок — тем меньше конверсия из заявки в оплату и консультанты тратят время на бесперспективные заявки.
- Задачи:
Разработать модель, которая по имеющейся информации о клиенте и заявке будет предсказывать вероятность оплаты заявки клиентом.
Заказчик хочет понять, какие заявки будут оплачены, а какие нет, чтобы одни обрабатывать вручную консультантами, а другие нет.
Оценка качества модели будет производиться с использованием precision и ROC-AUC.
