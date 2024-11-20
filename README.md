# Housing-Price-Prediction


# Project Overview:

This project implements a regression-based model evaluation pipeline using multiple machine learning algorithms:

*  Linear Regression,
*  Random Forest,
*  Gradient Boosting,
*  Support Vector Regression.
  
  
The pipeline allows for hyperparameter tuning, model evaluation, and selection of the best-performing model based on R² score and p-value thresholds. 
The goal is to train, evaluate, and fine-tune models to predict continuous target variables effectively.


Key Features:

* Multiple Regression Models: Linear Regression, Random Forest, Gradient Boosting, Support Vector Regression.
  
* Hyperparameter Tuning: Utilizes GridSearchCV to optimize model parameters.
  
* Model Evaluation: Measures model performance using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² score.
  
* Threshold-Based Model Selection: Filters models based on predefined thresholds for R² score and p-value.

  
Technologies Used:
* Python
* Scikit-Learn
* Statsmodels
* Pandas
* Numpy
