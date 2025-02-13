# Bank Marketing Campaign Analysis

This project analyzes a bank marketing campaign dataset to predict customer subscription to term deposits. The analysis involves exploratory data analysis (EDA), feature engineering, and model building using machine learning algorithms.

## Dataset

The dataset used is the classic bank marketing dataset from the UCI Machine Learning Repository. It contains information about a marketing campaign of a financial institution, including customer demographics, financial details, and campaign outcomes.

## Analysis Steps

1. **Exploratory Data Analysis (EDA)**:
    - Unwanted columns, missing values, and features with one value are identified.
    - Categorical and numerical features are explored, including their distributions and relationships with the target variable.
    - Outliers and correlations between numerical features are investigated.
    - The dataset's balance based on target values is assessed.
2. **Feature Engineering**:
    - Unwanted features are dropped.
    - Categorical features are handled using one-hot encoding.
    - Feature scaling and outlier removal are considered.
3. **Model Selection**:
    - Random Forest and XGBoost classifiers are evaluated using cross-validation.
    - Grid search is employed to find the best hyperparameters for each model.
4. **Model Building**:
    - The best-performing model (XGBoost) is selected for building the final model.
    - The model is trained on the training set and evaluated on the test set.
    - Feature importances are extracted and visualized.
    - A confusion matrix is generated to assess the model's performance.

## Results

The XGBoost classifier achieves a high accuracy score on the test set, indicating its effectiveness in predicting customer subscription to term deposits. The feature importance analysis reveals the most influential factors in the prediction process.

## Conclusion

This project demonstrates the application of data science and machine learning techniques to analyze a bank marketing campaign and build a predictive model. The insights gained from the analysis can be used to improve future marketing strategies and increase customer acquisition.
