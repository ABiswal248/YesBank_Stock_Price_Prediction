# YesBank_Stock_Price_Prediction

## Project Overview

This project focuses on analyzing and predicting the closing stock prices of Yes Bank using Exploratory Data Analysis (EDA) and multiple Machine Learning regression models. The main objective of this project is to study historical stock market trends, understand relationships among stock price variables, and build predictive models for forecasting future closing prices.

The project includes data preprocessing, visualization, statistical analysis, feature engineering, machine learning model implementation, performance evaluation, and comparison of multiple regression algorithms.

---

# Problem Statement

Stock market prediction is an important application of data science and machine learning in the financial domain. Accurate stock price prediction can help investors and analysts make informed financial decisions.

This project aims to predict the closing stock price of Yes Bank using historical stock market data and machine learning techniques.

---

# Objectives

- Perform data preprocessing and cleaning
- Conduct Exploratory Data Analysis on stock market data
- Visualize stock price trends and distributions
- Identify relationships among stock price features
- Implement multiple machine learning regression models
- Evaluate model performance using regression metrics
- Compare different algorithms and select the best-performing model

---

# Dataset Information

The dataset contains historical monthly stock prices of Yes Bank.

## Features Used

- Date
- Open Price
- High Price
- Low Price
- Close Price

---

# Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Visual Studio Code
- Git and GitHub

---

# Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the structure and characteristics of the dataset. Various visualization techniques were used to analyze stock price movements and feature relationships.

## EDA Techniques Implemented

- Line Charts
- Histograms
- Boxplots
- Scatter Plots
- Correlation Heatmap
- Density Plots
- Moving Average Analysis
- Feature Distribution Analysis

---

# Machine Learning Models Implemented

The following regression algorithms were implemented and evaluated:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. ElasticNet Regression
5. Decision Tree Regressor
6. Random Forest Regressor
7. Extra Trees Regressor
8. Gradient Boosting Regressor
9. AdaBoost Regressor
10. XGBoost Regressor
11. K-Nearest Neighbors Regressor
12. Support Vector Regressor
13. Bayesian Ridge Regression
14. Extra Tree Regressor
15. Dummy Regressor

---

# Evaluation Metrics

The performance of machine learning models was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score

---

# Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Best Model Selection

---

# Results

Multiple regression models were trained and compared to predict Yes Bank closing stock prices. Ensemble learning algorithms such as Random Forest and XGBoost achieved strong prediction performance compared to traditional regression methods.

The project demonstrates how machine learning techniques can be applied to financial datasets for stock market analysis and predictive modeling.

---

# Insights

- Open, High, Low, and Close stock prices are strongly correlated with each other.
- Historical stock prices show fluctuations across different time periods, indicating varying market conditions.
- Ensemble models such as Random Forest and XGBoost produced better prediction accuracy than traditional regression models.
- Data visualization techniques helped identify hidden trends and relationships in the dataset.
- Feature analysis indicated that High and Open prices significantly influence closing stock prices.
- Machine learning techniques can effectively support financial forecasting and stock market analysis.

---

# Conclusion

This project successfully analyzed historical Yes Bank stock price data using Exploratory Data Analysis and machine learning techniques. The implementation of multiple regression algorithms helped compare prediction performance and identify suitable models for stock price forecasting.

The project highlights the practical application of machine learning in financial analytics and demonstrates the importance of data visualization and model evaluation in predictive analysis.

---

# Folder Structure

```text
YesBank_Project
│
├── data
│   └── data_YesBank_StockPrices.csv
│
├── notebooks
│   ├── YesBank_EDA.ipynb
│   └── YesBank_ML_Model.ipynb
│
├── outputs
│
├── README.md
├── requirements.txt
└── .gitignore
How to Run the Project
Clone Repository
git clone <repository-url>
Move to Project Folder
cd YesBank_Project
Create Virtual Environment
python -m venv venv
Activate Virtual Environment
Windows
venv\Scripts\activate
Linux / Mac
source venv/bin/activate
Install Required Libraries
pip install -r requirements.txt
Run Jupyter Notebook
jupyter notebook
Future Enhancements
Implement Deep Learning models such as LSTM
Integrate real-time stock market APIs
Deploy the project using Flask or Streamlit
Add a live stock prediction dashboard
Improve prediction accuracy using advanced ensemble methods

Author:-

ARJYA BISWAL

License:-

This project is developed for educational and academic purposes.
