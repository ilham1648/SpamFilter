# SpamClassifier
Классификатор текстовый сообщений на спам и не спам

## Результаты с использованием sklearn

    Тренировочная выборка
                  precision    recall  f1-score   support

             ham       0.99      1.00      1.00      2356
            spam       0.99      0.97      0.98       374

        accuracy                           0.99      2730
       macro avg       0.99      0.98      0.99      2730
    weighted avg       0.99      0.99      0.99      2730

    Тестовая выборка
                  precision    recall  f1-score   support

             ham       0.99      1.00      0.99      1021
            spam       0.98      0.90      0.94       149

        accuracy                           0.98      1170
       macro avg       0.98      0.95      0.96      1170
    weighted avg       0.98      0.98      0.98      1170

## Результаты с реализацией метода наивного байеса  

    Тестовая выборка
                  precision    recall  f1-score   support

             ham       0.99      1.00      0.99      1448
            spam       0.97      0.95      0.96       224

        accuracy                           0.99      1672
       macro avg       0.98      0.97      0.98      1672
    weighted avg       0.99      0.99      0.99      1672
