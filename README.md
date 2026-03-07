 AI & ML Project – California Housing Price Prediction

This repository contains two structured Machine Learning tasks using the California Housing dataset.

  Task 1 – Linear Regression Implementation

- Data Loading & Exploratory Data Analysis (EDA)
- Train-Test Split (80-20)
- Linear Regression Model
- Evaluation Metrics: MAE, RMSE, R²
- Model Saving using Pickle


  Task 2 – Feature Engineering & Model Comparison

- Feature Scaling using StandardScaler
- Model Comparison:
  - Linear Regression
  - Ridge Regression
  - Decision Tree Regressor
- Performance Evaluation using RMSE & R²
- Best Model Selection
- Model Saving


  Best Performing Model (Task 2)

Decision Tree Regressor  
R² Score: 0.599

---

  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Git & GitHub



This project demonstrates practical understanding of regression models, feature engineering, evaluation metrics, and version control workflow.

## Task 3 – Model Validation & Hyperparameter Tuning

In this task, we improved model performance and handled overfitting.

Key steps:
- Detected overfitting using Decision Tree
- Applied Cross-Validation to evaluate model stability
- Used GridSearchCV for Hyperparameter Tuning
- Optimized model performance

Final Model Performance:
- RMSE: 0.645
- R² Score: 0.682
