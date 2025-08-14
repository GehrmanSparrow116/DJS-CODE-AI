# DJS-CODE-AI 
# Bike rental dataset prediction results when only cnt is predicted
1.Simple linear regression model
MSE : 1760510.8979050838
RMSE : 1326.842454063437
MAE : 1128.577045505025
R²   : 0.1274457185411516
2.Decision Tree Regressor
R^2=0.30
3.Decision Tree Regressor by GridSearchCV
Best CV R² Score: 0.5182354255079995
Test R²  : 0.5053
Test RMSE: 1408.43
Test MAE : 1181.06
4.Random Forest Regressor by GridSearchCV
Best CV R² Score: 0.5976723299525826
Test R²  : 0.6286
Test RMSE: 1220.28
Test MAE : 1077.91
5. Gradient Boosting Regressor 
CV R²: 0.57564457654953
Test R²: 0.5955934524536133
# Bike rental dataset prediction results when sum of predictions of casual and registered for cnt
1.Simple linear regression model
R² Score: 0.5506
RMSE: 1342.42
2.Decision Tree Regressor 
R² Score: 0.5383
RMSE: 1360.68
3.Gradient Boosting Regressor
R² Score: 0.6112
RMSE: 1248.59
MAE: 1074.82
4.XG Boost
R² Score: 0.5640
RMSE: 1322.28
MAE: 1084.96
5.XG boost By GridSearchCV
R² Score: 0.6178
RMSE: 1237.97
MAE: 1061.25
6.Light GBM
R² Score: 0.6221
RMSE: 1230.97
MAE: 1063.89
