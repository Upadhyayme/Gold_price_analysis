# Gold_price_analysis
# Project Overview: Gold Price Prediction
This project focuses on analyzing and predicting gold prices using machine learning techniques. The dataset includes historical data with multiple financial indicators such as:
Date — Date of observation
SPX — S&P 500 Index
GLD — Gold ETF price (proxy for gold price)
USO — Crude Oil ETF price
SLV — Silver ETF price
EUR/USD — Euro to US Dollar exchange rate

The project utilizes Python libraries for data preprocessing, visualization, and predictive modeling to forecast gold prices based on these features.
#📦 Requirements
The following Python libraries are used in this project:
bash
Copy
Edit
pandas
numpy
matplotlib
seaborn
scikit-learn

# You can install all the required libraries using:
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
 
 # ⚙ Libraries Used and Their Purpose
pandas: For data manipulation and analysis.
numpy: For numerical operations.
matplotlib: For data visualization (static plots).
seaborn: For enhanced visualizations and statistical graphics.
scikit-learn: For building and evaluating machine learning models.

# Project Description
The project includes the following main steps:
Data Loading and Exploration
Load the historical data of gold price along with other financial indicators and explore correlations between these features.
Data Preprocessing
Handle missing values.
Convert date fields if necessary.
Feature selection based on correlation.
# Visualization
Use correlation heatmaps and scatter plots to identify relationships between the features, especially how SPX, USO, SLV, and EUR/USD impact gold price (GLD).
# Model Building
Train a machine learning regression model (likely Linear Regression or Random Forest) to predict gold price using selected features.

# Model Evaluation
Evaluate the model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), or R² score.

# Prediction
Use the trained model to predict gold prices on unseen data.

# 🎯 Outcome
The project successfully demonstrates how multiple economic indicators can be used to predict the price of gold. It also showcases the complete machine learning pipeline, from data preprocessing to model evaluation.
