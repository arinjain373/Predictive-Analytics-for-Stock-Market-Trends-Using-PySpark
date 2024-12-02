# Predictive Analytics for Stock Market Trends Using PySpark and MLlib

This project leverages PySpark to analyze and predict stock market trends using historical stock data. The pipeline includes data preprocessing, exploratory analysis, trend visualization, and predictive modeling using PySpark's MLlib.

## Features

- **Data Loading and Preprocessing**:
  - Load historical stock price data (e.g., date, open, high, low, close, volume).
  - Clean data by handling missing values, filtering columns, and formatting date fields.

- **Data Aggregation and Analysis**:
  - Calculate daily, weekly, and monthly average closing prices for stocks.
  - Identify stocks with the highest average monthly price for a given year.
  - Analyze stock price volatility to find stocks with significant price fluctuations.

- **Visualization**:
  - Plot closing price trends for specific stocks using PySpark and Matplotlib.

- **Predictive Modeling**:
  - Train a linear regression model using PySpark MLlib to predict stock closing prices based on features like open, high, low, and volume.
  - Evaluate model performance using metrics such as R-squared.

## Technologies Used

- PySpark for data processing and analysis  
- MLlib for building and evaluating machine learning models  
- Matplotlib for data visualization  
- Pandas and yFinance for data handling and retrieval  


