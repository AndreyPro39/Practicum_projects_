1. Исследование по выявлению потенциально прибыльных игровых платформ.

Описание проекта

Мы работаем в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

2. Используемые инструменты:

1. Pandas
2. numpy
3. seaborn
4. matplotlib
5. sklearn.tree(DecisionTreeClassifier, DecisionTreeRegressor)
6. sklearn.neighbors(KNeighborsClassifier, KNeighborsRegressor)
7. sklearn.linear_model(LogisticRegression, LinearRegression)
8. sklearn.preprocessing(OneHotEncoder, OrdinalEncoder, StandardScaler, LabelEncoder)
9. sklearn.impute(SimpleImputer)
10. sklearn.model_selection(train_test_split) 
11. sklearn.preprocessing(StandardScaler, MinMaxScaler, RobustScaler)
11. phik_matrix

3. Вывод

4. На основании проведенного исследовательского анализа данных создали портрет пользователя в каждом регионе,
5. Проверили 2 гипотезы:
    * 5.1. Средние пользовательские рейтинги платформ XOne и PC одинаковые 
    * 5.2. Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные. И с уверенностью можем утверждать, что первая гипотеза подтвердилась, а вторая была отвергнута.
