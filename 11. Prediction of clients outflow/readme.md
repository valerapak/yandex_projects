# Прогнозирование вероятности оттока пользователей для фитнес-центров (построение моделей прогнрозирования)

**Направление деятельности:** Маркетинг-аналитик, Аналитик (универсал)

**Навыки и инструменты:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn, машинное обучение, классификация, кластеризация

**Статус проекта:** выполнен

## Описание проекта:
Изучение оттока клиентов фитнес-центра «Культурист-датасаентист» и подготовка плана действий по удержанию клиентов

## Цели исследования:
1) Научиться прогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
2) Сформировать типичные портреты клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
3) Проанализировать основные признаки, наиболее сильно влияющие на отток;
4) Сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами:
   - выделить целевые группы клиентов;
   - предложить меры по снижению оттока;
   - определить другие особенности взаимодействия с клиентами.
  
## Ход исследования:

1) Исследовательский анализ данных (EDA);
2) Модель прогнозирования оттока клиентов;
3) Кластеризация клиентов;
4) Общие выводы и рекомендации.

## Результаты исследования:

1) Были изучены признаки, влияющие на отток посетителей, построены графики распределения признаков и матрица корреляции, которая показала влияние проведения промоакций и скидок на посещаемость.
2) Модели прогнозирования оттока методами логистической регрессии и случайного леса показали высокие значения метрик 'Accuracy'(>0.91), 'Precision' (>0.83), и 'Recall'(>0.81). Немного выше эти значения у логистической регрессии.
3) Была спрогнозирована кластеризация клиентов на основании алгоритма K-Means. В результате все клиенты фитнес-центра были распределены на 5 кластеров. Самая высокая доля оттока - молодые люди не старше 30 лет, записавшиеся на 1-2 месяца, посещающие 1 (реже 2) раза в неделю, с низкими затратами на дополнительные услуги. Их 'lifetime' - не дольше 3 месяцев. Самая низкая доля оттока - люди более старшего возраста (за 30 лет), воспользовавшиеся спецпредложениями и промоакциями, заключившие договор на год, занимающиеся не реже 2 раз в неделю и охотно пользующиеся дополнительными услугами.

На основании построенных моделей прогнозорования можно выделить две стратегии дальнейшего развития:
- сделать клуб более привлекательным для молодежи и снизить ее отток: открыть группы более молодежной направленности, пересмотреть дополнительные услуги, разработать акции и скидки для молодежи (например, скидки для клиентов до 28 лет), изменить меню в кафе клуба, и т.п.
- сконцентрироваться на удержании и привлечении более взрослой аудитории (к примеру, открыть семейные/детские группы, чтобы приходили всей семьей), устраивать семейные праздники фитнеса, предоставить больше скидок для тех, кто занимается всей семьей, и т.д.;
- для новых клиентов нужно сделать дополнительные скидки на первое время, чтобы удержать их. Например, предложить только для новых клиентов абонемент на 1 месяц + месяц в подарок, возможность посетить платные и групповые занятия бесплатно, Для постоянных клиентов стоит создать программу лояльности, когда заработанные бонусы можо потратить на дополнительные услуги, и т.п.
