# FUTURE_ML_01
Sales Forecasting using Random Forest Algorithm
## Overview

This project is a Machine Learning based Sales Forecasting system developed as part of the Future Interns ML Task 1.

This project predicts sales in future based on previous sale records, recognizing patterns in sales predicts future sales using

Random Forest Regression.

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

# Machine Learning Concepts Used

* Data Cleaning(Handle missing data)
* Feature Engineering
* Train-Test Split(create data to test and determine patterns)
* Random Forest Regression(predicts patterns)
* Model Training
* Prediction
* Evaluation Metrics

# Dataset Processing

The dataset was processed using the following steps:
1. Loading the dataset
2. Checking missing values
3. Cleaning the dataset
4. Converting date columns
5. Creating year, month, and day features
6. Visualizing sales trends
7. Splitting data into training and testing sets
8. Training the Random Forest model
9. Predicting sales values
10. Evaluating prediction accuracy

# Algorithm Used

## Random Forest Regressor

Random Forest is a machine learning algorithm that uses many decision trees to make better predictions. Each tree looks at different random 

parts of the data and their results are combined by voting for classification or averaging for regression which makes it as ensemble learning

technique. This helps in improving accuracy and reducing errors.

# Project Workflow

Dataset Loading
↓
Data Cleaning
↓
Feature Engineering
↓
Visualization
↓
Train-Test Split
↓
Model Training
↓
Prediction
↓
Evaluation

# Example Libraries Import

```python
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_absolute_error
```

# Model Training

```python
model = RandomForestRegressor()
model.fit(X_train, y_train)
```

# Prediction

```python
predictions = model.predict(X_test)
```

# Evaluation

```python
print(mean_absolute_error(y_test, predictions))
```

# Output

* Sales forecasting predictions
* Visualization graphs
* Model evaluation results

# Conclusion

This project demonstrates the basic Machine Learning workflow for sales prediction using Random Forest Regression.

It helps understand:

* supervised learning
* regression
* training and testing
* prediction workflow
* model evaluation
