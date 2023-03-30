# Flight_Fare_Price_prediction
The flight fare price prediction model was trained using a Random Forest Regressor algorithm, which initially produced the following evaluation metrics: Mean Absolute Error (MAE) of 1178.33, Mean Squared Error (MSE) of 4372600.91, and Root Mean Squared Error (RMSE) of 2091.08. To improve the model's performance, a hyperparameter tuning method called Randomized Search CV was applied, resulting in the best parameter combination of 'n_estimators': 700, 'min_samples_split': 15, 'min_samples_leaf': 1, 'max_features': 'auto', 'max_depth': 20. This improved the model's performance with the evaluation metrics of MAE: 1165.68, MSE: 4052122.60, and RMSE: 2012.99. These metrics indicate that the model is performing reasonably well in predicting flight fares.



