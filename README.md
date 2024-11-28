## AI Research Project: Parkinson's Telemonitoring with a Regression Predictive Model

### Abstract
The Unified Parkinson’s Disease Rating Scale (UPDRS) is used to assess the severity and progression of Parkinson’s disease, consisting of 50 motor and non-motor questions that reflect a patient's quality of life and daily functioning. This study utilizes the Oxford Parkinson’s Disease Telemonitoring dataset along with the PyCaret machine learning library to predict UPDRS scores based on variables such as age. Various machine learning models were trained and evaluated to identify the best model through performance metrics (MAE, MSE, RMSE, R2, etc). The results indicated that Extra Trees Regressor achieved the highest R² score and lowest RMSE, but its tendency to overfit the training data (with a perfect R² score of 1.0 on the training set) led to the decision to use CatBoost instead. The CatBoost model delivered accurate predictions with reasonable RMSE differences, making it the preferred choice for this task.

### Video Link
[Video Demo](https://youtu.be/NMPCTBccjjE)
