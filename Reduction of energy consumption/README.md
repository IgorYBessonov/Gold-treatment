# Choosing the best machine learning model to reduce power consumption at the steel processing stage `Выбор лучшей модели машинного обучения для уменьшения потребления электроэнергии на этапе обработки стали`
[HTML](ссылка) [ipynb](ссылка)

## Project description `Описание проекта`
It is required to prepare a prototype of a machine learning model in order to reduce electricity consumption at the steel processing stage. The model should predict the temperature of the steel. This will help to optimize production costs. The customer is a metallurgical plant.

`Требуется подготовить прототип модели машинного обучения, чтобы уменьшить потребление электроэнергии на этапе обработки стали. Модель должна предсказывать температуру стали. Это поможет оптимизировать производственные расходы. Заказчик - металлургический комбинат.`

## Skills and tools `Навыки и инструменты`
* pandas
* seaborn
* matplotlib
* numpy

* sklearn.metrics.**mean_absolute_error** 
* sklearn.metrics.**make_scorer**
* sklearn.preprocessing.**StandardScaler**
* sklearn.model_selection.**cross_val_score**
* sklearn.linear_model.**LinearRegression**
* sklearn.tree.**DecisionTreeRegressor**
* sklearn.ensemble.**CatBoostRegressor**
* sklearn.dummy.**Dummy Regressor**
* sklearn.model_selection.**GridSearchCV**
* research data analysis


## General conclusion `Общий вывод`
Research data analysis and data preprocessing were carried out. New features have been prepared for machine learning purposes. MAE (average absolute error) was chosen as the metric.Three models were trained. The CatBoost model was selected for testing on a test sample. The results of the model were compared with the constant DummyRegressor model. 

`В ходе проекта были исследованы данные, проведена предобратка данных. Для целей машинного обучения были подготовлены новые признаки. В качестве метрики была выбрана МАЕ (средняя абсолютная ошибка).Были обучены три модели. Для проверки на тестовой выборке была выбрана модель CatBoost. Результаты модели сравненили с константной моделью DummyRegressor.`


