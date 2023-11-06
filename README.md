# Every Bike Counts
This project focuses on analyzing bike-sharing data from the Capital Bikeshare system between 2011 and 2012. Bike-sharing programs have gained popularity as eco-friendly transportation options in cities worldwide. This dataset provides hourly counts of rented bikes, along with weather and seasonal information. The primary objective is to apply various machine learning algorithms to predict bike usage accurately.

# Objectives

+ The main goals of this project are:

+ Utilize machine learning algorithms to predict bike usage based on historical data.

+ Perform in-depth data exploration to understand the dataset's characteristics.

+ Evaluate model performance using appropriate metrics for comparison.

# Dataset Exploration

The dataset contains 17 columns, including information about date, time, weather conditions, and bike usage counts. It encompasses 17,379 rows and lacks missing values. Key insights from the data exploration include the impact of working days, holidays, and weather on bike usage.

# Data Preprocessing

Before modeling, the dataset underwent preprocessing. Irrelevant columns were removed, and data normalization was applied to standardize features. The dataset was split into training and testing sets for model evaluation.

# Model Selection

Three machine learning models were trained and evaluated: Decision Tree Regressor, Random Forest Regressor, and Support Vector Machine (SVM). The SVM model outperformed the others, demonstrating the highest accuracy in predicting bike usage.

# Hyperparameter Tuning

Hyperparameter tuning was performed to optimize model performance. Grid search was employed to find the best parameters for each model. The selected parameters improved model accuracy.

# Model Evaluation
Evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) were used to assess model performance. The SVM model exhibited the lowest MAE and MSE, along with the highest R2 score, making it the most accurate predictor of bike usage.

Conclusion
In conclusion, this project successfully analyzed bike-sharing data using machine learning algorithms. The SVM model, with optimized parameters, proved to be the most accurate in predicting bike usage. Decision Tree models are discouraged for regression problems due to their limitations with continuous numerical variables. Future work in regression should consider more advanced algorithms for improved accuracy.
