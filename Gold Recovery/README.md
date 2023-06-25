# Улучшение процесса обогащения золота

[HTML](https://github.com/SancheZzz69/Portfolio/blob/main/Gold%20Recovery/gold_recovery.html)     [ipynb](https://github.com/SancheZzz69/Portfolio/blob/main/Gold%20Recovery/gold_recovery.ipynb)

## Описание проекта

Требуется подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.



## Навыки и инструменты

- **python**
- **pandas**
- **scipy**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**HalvingGridSearchCV**
- sklearn.pipeline.**make_pipeline**
- sklearn.preprocessing.**StandardScaler**
- sklearn.metrics.**make_scorer**
- sklearn.metrics.**mean_absolute_error**
- sklearn.linear_model.**Lasso**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.dummy.**DummyRegressor**
- **matplotlib**
- **seaborn**


## Общий вывод

Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.
Проект демонстрирует потенциал машинного обучения в улучшении процесса восстановления золота и подчеркивает важность анализа данных и прогнозного моделирования в золотодобывающей промышленности.
