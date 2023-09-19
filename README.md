# AutoMl

Цель: Оценить работу библиотек: FeatureTools, H2O и CatBoost
Задачи: 1. Сгенерировать фичи с помощью FeatureTools и посмотреть как это изменит качество модели 2. Сравнить, что лучше H2O или CatBoost
Данные: Обучение проводили на данных по прививкам от гриппа. Даны две вакцины: h1n1 и сезонная, нужно предсказать на сколько вероятно, что люди получат вакцину [более подробно тут](https://www.drivendata.org/competitions/66/flu-shot-learning/page/211/)
Результат: AUC для AutoML с featuretools 0.8551 AUC для CatBoost с featuretools и feature selection 0.8676 AUC для CatBoost с featuretools 0.8671 AUC для CatBoost c optuna 0.8713
Вывод: Чтобы улучшить нашу модель в AutoML необходимо еще отобрать лучшие параметры, но даже так, мы получили достаточно высокий AUC.

