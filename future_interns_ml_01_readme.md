# Sales Forecasting Project

## Overview
This project is a Machine Learning based Sales Forecasting system developed as part of the Future Interns ML Task 1.

The project predicts sales values using historical sales data and the Random Forest Regression algorithm.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Machine Learning Concepts Used

- Data Cleaning
- Feature Engineering
- Train-Test Split
- Random Forest Regression
- Model Training
- Prediction
- Evaluation Metrics

---

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

---

# Algorithm Used

## Random Forest Regressor

Random Forest is a Machine Learning algorithm that uses multiple decision trees together to improve prediction accuracy.

It learns patterns from historical sales data and predicts future sales values.

---

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

---

# Example Libraries Import

```python
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_absolute_error
```

---

# Model Training

```python
model = RandomForestRegressor()
model.fit(X_train, y_train)
```

---

# Prediction

```python
predictions = model.predict(X_test)
```

---

# Evaluation

```python
print(mean_absolute_error(y_test, predictions))
```

---

# Output

- Sales forecasting predictions
- Visualization graphs
- Model evaluation results

---

# Conclusion

This project demonstrates the basic Machine Learning workflow for sales prediction using Random Forest Regression.

It helps understand:

- supervised learning
- regression
- training and testing
- prediction workflow
- model evaluation

---

# Author

Future Interns ML Task 1 Project

