# Rossmann-Store-Sales

In this dataset the number of closed stores is greater than the number of open stores so I do some feature engineering to have more information about the closed stores and holidays. Also, the feature named promo2 has a strong effect on sales and I append it to train and test datasets. Finally, I train four models Randomforest, XGBoost, CatBoost and LightGBM.

Randomforest
Mean train RMSPE: 0.5264 +/- 0.0248
Mean val   RMSPE: 0.5407 +/- 0.0689

model         mean_rmspe  
LightGBM        0.5432         
CatBoost        0.5447         
 XGBoost        0.5522
 
https://www.kaggle.com/competitions/rossmann-store-sales/overview
