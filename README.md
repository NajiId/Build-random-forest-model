# Airline Passenger Satisfaction Prediction

## Introduction
This project aims to predict passenger satisfaction based on various features such as age, flight distance, seat comfort, and others using machine learning algorithms.

## Data Preprocessing
- Imported the necessary libraries including pandas, numpy, pickle, and scikit-learn.
- Loaded the dataset and performed exploratory data analysis.
- Handled missing values by dropping rows with missing values.
- Converted categorical variables into dummy variables using one-hot encoding.
- Split the dataset into training and testing sets.

## Model Training
- Utilized the Random Forest Classifier algorithm for prediction.
- Implemented GridSearchCV for hyperparameter tuning.
- Evaluated the model's performance using precision, recall, accuracy, and F1-score.

## Results
- Achieved a precision of 95.0%, recall of 94.5%, accuracy of 94.2%, and F1-score of 94.7% on the test set.
- Compared the performance of the tuned Random Forest model with a tuned Decision Tree model.

## Conclusion
The tuned Random Forest model demonstrated improved performance compared to the Decision Tree model, making it suitable for predicting passenger satisfaction in the airline industry.

