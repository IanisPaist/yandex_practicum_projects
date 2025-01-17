# Репозиторий Персональных Проектов

Описание проектов:

| Название              | Описание           | Используемые библиотеки и инструменты                     |
| :-------------------- | :--------------------- |:---------------------------|
| [Предсказание температуры плавления стали](https://github.com/IanisPaist/Projects/tree/main/production-costs-prediction-ML) | На основании данных о процессе нагрева стали (температуры сплава на различных этапах нагрева, добавленные добавки в сплав, объем использованного газа), построена модель, которая предсказывает температуру нагрева сплава стали. Бизнес цель - уменьшить затраты на электроэнергию. | pandas, numpy, sklearn, LightGBM, CatBoost |
| [Прогнозирование заказов такси](https://github.com/IanisPaist/Projects/tree/main/time-series-analysis-taxi-orders) | (TimeSeries) На основании исторических данных о заказах такси в зависимости от времени - необходимо построить модель предсказания заказов такси на следующий час | pandas, numpy, sklearn, LinearRegression, LightGBM, seasonal_decompose, adfuller |
| [Предсказание количества золота](https://github.com/IanisPaist/Projects/tree/main/gold-enrichment-prediction-ML) | На основании данных о техологическом процессе обогащения золотосодержащей руды, построена модель, которая предсказывает количество золота на финальном этапе в двух разных сплавах. Использована кастомная метрика для оценки качества.  | pandas, numpy, sklearn, LinearRegression, Decision Tree, Random Forest |