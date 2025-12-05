Model Machine Learning ini menggunakan dataset diamond untuk menghitung harga sebuah berlian
Acuan metric pada model ini ada di R² score nya semakin mendekati angka 1 semakin bagus, kenapa menjadikan R² score menjadi acuan? karena regresi menentukan nilai target berdasarkan pola di data yang ada.
dan karena R² score membandingkan dengan baseline yang jelas yaitu mean(rata-rata) dari target, berbeda dengan MAE dan RMSE yang hanya mengukur dari seberapa besar error nya.

R²   : 0.9221982562588074
MAE  : 731.5479381456985
RMSE : 1102.1476745082157

source:
https://www.kaggle.com/datasets/shivam2503/diamonds
