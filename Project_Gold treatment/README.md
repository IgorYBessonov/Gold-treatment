# Improving the gold enrichment process `Улучшение процесса обогащения золота`
[ipynb_ENG] [ipynb_RUS](https://github.com/IgorYBessonov/Portfolio/blob/main/Project_Gold%20treatment/Gold%20treatment_RUS.ipynb)

## Project description `Описание проекта`
It is required to prepare a prototype of a machine learning model that should predict the recovery rate of gold from gold-bearing ore based on data with extraction and purification parameters. The model will help optimize production and helps not to launch an enterprise with unprofitable characteristics. The project was provided by the company "Zyfra" 

`Требуется подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. Проект предоставлен компанией "Цифра"` [Zyfra WebSite](https://www.zyfra.com/)

## Skills and tools `Навыки и инструменты`
* pandas
* seaborn
* matplotlib
* numpy

* sklearn.metrics.**mean_absolute_error** 
* sklearn.metrics.**make_scorer**
* sklearn.model_selection.**cross_val_score**
* sklearn.linear_model.**LinearRegression**
* sklearn.tree.**DecisionTreeRegressor**
* sklearn.ensemble.**RandomForestRegressor**
* sklearn.dummy.**Dummy Regressor**
* sklearn.model_selection.**GridSearchCV**
* customized metrics
* research data analysis


## General conclusion `Общий вывод`
The selected models were trained for the stages of coarse and fine cleaning, the selected trained models were tested on a test set and one was selected for production 

`Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.`
