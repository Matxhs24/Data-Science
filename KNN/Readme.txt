Model ini dibuat menggunakan dataset IRIS dan didapatkan hasil akurasi nya adalah
==========================================================
Accuracy: 0.9333

Classification Report:
                 precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00        11
Iris-versicolor       0.90      0.90      0.90        10
 Iris-virginica       0.89      0.89      0.89         9

       accuracy                           0.93        30
      macro avg       0.93      0.93      0.93        30
   weighted avg       0.93      0.93      0.93        30
=========================================================
lalu saya coba melakukan tunning menggunakan GridSearchCV dan RandomizedSearchCV
=========================================================
GridSearchCV
=========================================================
Best parameters: {'n_neighbors': 9, 'weights': 'uniform'}
Best cross-validation accuracy: 0.9830

Accuracy of the tuned model on the test set: 0.9333

Classification Report for Tuned Model:
                 precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00        11
Iris-versicolor       0.90      0.90      0.90        10
 Iris-virginica       0.89      0.89      0.89         9

       accuracy                           0.93        30
      macro avg       0.93      0.93      0.93        30
   weighted avg       0.93      0.93      0.93        30
=========================================================
RandomizedSearchCV
=========================================================
Best parameters from RandomizedSearchCV: {'n_neighbors': 9, 'p': 2, 'weights': 'uniform'}
Best cross-validation accuracy from RandomizedSearchCV: 0.9830

Accuracy of the best RandomizedSearchCV model on the test set: 0.9333

Classification Report for Best RandomizedSearchCV Model:
                 precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00        11
Iris-versicolor       0.90      0.90      0.90        10
 Iris-virginica       0.89      0.89      0.89         9

       accuracy                           0.93        30
      macro avg       0.93      0.93      0.93        30
   weighted avg       0.93      0.93      0.93        30
=========================================================
