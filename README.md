# Machine Learning Internship Projects

This repository contains three machine learning projects completed using Python and Scikit-learn. Each project demonstrates data preprocessing, model training, evaluation, and visualization.

## Task 1: Iris Flower Classification

**Objective:** Classify Iris flowers into three species using supervised learning.

- **Dataset:** Iris dataset — 150 samples, 4 features, 3 classes
- **Models:** Logistic Regression and Decision Tree
- **Preprocessing:** StandardScaler and an 80/20 train-test split
- **Evaluation:** Accuracy, precision, recall, F1-score, and confusion matrices
- **Visualizations:** Pairplots, confusion matrix heatmaps, and decision boundaries

## Task 2: California Housing Price Prediction

**Objective:** Predict median house values using regression models.

- **Dataset:** California Housing — 20,640 records
- **Models:** Ordinary Least Squares (OLS), Ridge, and Lasso Regression
- **Preprocessing:** Feature scaling, missing-value imputation, and interaction feature engineering
- **Hyperparameter tuning:** GridSearchCV for Ridge and Lasso
- **Evaluation:** RMSE, MAE, and R² score
- **Visualizations:** Correlation heatmap, predicted-versus-actual plots, and residual distributions

## Task 3: Customer Churn Prediction

**Objective:** Predict whether telecom customers are likely to leave their service provider.

- **Dataset:** Telco Customer Churn — 7,043 customers
- **Models:** Random Forest and XGBoost
- **Preprocessing:** Missing-value imputation, OneHotEncoder, and class weighting
- **Evaluation:** Accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrices
- **Best test ROC-AUC:** 0.841 using XGBoost
- **Visualizations:** ROC curves, confusion matrices, and top 10 feature importances

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab

## Repository Contents

1. `Task1_Iris_Classification_Pipeline (1).ipynb`
2. `Task2_Housing_Price_Prediction.ipynb`
3. `Task3_Customer_Churn_Prediction.ipynb`

## Project Status

All three project notebooks have been uploaded to this public repository. Each notebook includes its implementation, evaluation metrics, and visualizations.
