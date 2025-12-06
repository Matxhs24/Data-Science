Model Machine Learning ini menggunakan dataset lung Cancer untuk memprediksi seseorang terjangkit penyakit paru-paru atau tidak.
karena target dataset ini bersifat biner 1/0 maka saya menggunakan model naive bayes bernoulli. lalu karena target pada dataset imbalanced saya menggunakan ADASYN untuk melakukan oversampling agar dsitribusi target 
seimbang. setelah melakukan oversampling saya menggunakan Pipe line Cross Validation untu mengecek apakah model bias atau tidak. kenapa saya menggunakan pipeline daripada Cross Validation yang lain? karena pipeline
memastikan oversampling hanya terjadi pada data training di setiap fold, bukan pada seluruh dataset.
              precision    recall  f1-score   support

           0       0.94      0.94      0.94        47
           1       0.94      0.94      0.94        50

    accuracy                           0.94        97
   macro avg       0.94      0.94      0.94        97
weighted avg       0.94      0.94      0.94        97



source:
https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer
