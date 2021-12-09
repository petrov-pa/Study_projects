# Обнаружение защитной каски на изображении

## Датасет:
5000 изображений с аннотациями трех классов: голова, каска, человек. https://www.kaggle.com/andrewmvd/hard-hat-detection

## Используемые функции:
Предобработка данных: TfidfVectorizer, train_test_split, TruncatedSVD

## Обученные модели и результаты:
LogisticRegression: Точность - 0.88688, ROC-AUC - 0.9577

LogisticRegression c L1-регуляризацией: Количество признаков - 107, Точность - 0.81264, ROC-AUC - 0.8958

RandomizedLogisticRegression: Количество признаков - 13, Точность - 0.73696, ROC-AUC - 0.8106

LogisticRegression после SVD: Количество признаков - 100, Точность - 0.85584, ROC-AUC - 0.9371

RandomForestClassifier после SVD: Количество признаков - 100, Точность - 0.82512, ROC-AUC - 0.9039

