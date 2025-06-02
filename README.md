📈 Yes Bank Stock Closing Price Prediction | Machine Learning Project
🧠 Project Overview
This project focuses on predicting the closing price of Yes Bank's stock using historical data and regression-based machine learning models. It demonstrates a full workflow of data preprocessing, exploratory data analysis, feature transformation, model building, and evaluation using Python.

📁 Dataset Summary
Source: Historical Yes Bank stock data
Period: Monthly (2005–2020)
Records: 185 rows
Target Variable: Close price
Features: Open, High, Low, Date
🛠 Tools & Libraries Used
    

Pandas, NumPy – Data cleaning and manipulation
Scikit-learn – Model training and evaluation
PowerTransformer – Feature transformation
Matplotlib, Seaborn – Data visualization
mplfinance – Financial chart formatting
GridSearchCV – Hyperparameter tuning
🔄 Workflow Summary
1. Data Preprocessing
Converted date column to datetime
Checked for missing/null values (none found)
Applied feature scaling & Power Transformation
Split into 80% training and 20% testing set
2. Model Building & Evaluation
Trained multiple regression models including:

Linear Regression
KNN Regressor
Ridge & Lasso Regression
Random Forest Regressor
ElasticNet
✅ Ridge Regression delivered the best result with an R² score of 0.993

📌 Key Learnings
Feature transformation reduced multicollinearity
Ridge Regression performed best due to regularization
Multiple models tested with consistent cross-validation
Learned how to handle financial data in real-world ML scenarios
