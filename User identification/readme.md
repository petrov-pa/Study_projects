# Идентификация пользователей по посещенным веб-страницам

## Цель проекта: 
Идентифицировать пользователя по его поведению в сети. Идея такая: пользователи Интернета по-разному переходят по ссылкам, и это может помочь их идентифицировать.

## Датасет:
В качестве исходных данных мы имеем информацию о 3372 пользователях (сайт и время посещения) за 6,5 месяцев.

## Работа с данными:
Создание выборки для обучения.

Создание новых признаков и их анализ.

Разделение выборки на обучающую, проверочную и тестовую.

## Обученные модели и результаты:
SGDClassifier: Точность - 0.88688, ROC-AUC -0.941

AdaBoostClassifier c L1-регуляризацией: ROC-AUC - 0.893

MultinomialNB: ROC-AUC - 0.751



