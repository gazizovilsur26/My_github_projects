# Проект по восстановлению золота из руды
## Описание проекта
Задача проекта заключается в разработке прототипа модели машинного обучения для компании, чтобы предсказывать коэффициент восстановления золота из золотосодержащей руды на основе данных о параметрах добычи и очистки, с целью оптимизации производства и избегания запуска предприятия с убыточными характеристиками в золотодобывающей отрасли
## Навыки и инструменты
* python
* pandas
* numpy
* scipy
* sklearn.model_selection.cross_val_score
* sklearn.metrics.mean_squared_error
* sklearn.metrics.mean_absolute_error
* sklearn.preprocessing.StandardScaler
* sklearn.linear_model.LinearRegression
* sklearn.tree.DecisionTreeRegressor
* sklearn.ensemble.RandomForestRegressor
* matplotlib
## Общий вывод
После проведенной работы, полученная модель демонстрирует хорошие результаты на тестовой выборке, с sMAPE равным 9.50, что ниже чем sMAPE константной модели (9.79), что подтверждает её эффективность.
