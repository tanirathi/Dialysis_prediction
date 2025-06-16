Dialysis Hypotension Risk Prediction Model 

I trained an XGBoost Classifier to predict whether a patient is hypertensive (yes/no) based on various dialysis-related medical parameters.
XGBoost (eXtreme Gradient Boosting) is an open-source machine learning algorithm known for its speed, accuracy, and ability to handle large datasets with mixed data types (categorical, numerical, etc.).
It applies gradient boosting, a technique that combines multiple weak learners (e.g., decision trees) in sequence—each model tries to correct the errors of the previous one to build a strong final model.
Since hypertension is a binary (yes/no) condition, a classifier was used. Had the goal been to predict the exact blood pressure value, a regressor would have been more appropriate.



