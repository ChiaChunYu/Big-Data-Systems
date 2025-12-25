# Big Data Systems

This is the homework for the NDHU CSIEM0410 Big Data Systems (2023 Fall) course. 

## hadoop
Located in `/hadoop_py`. This section consists of various exercises for practicing **Hadoop MapReduce** programming, including TF-IDF calculation, distributed search, and numerical sorting.

## spark
Located in `/spark_py`. This section contains several programming tasks designed to practice **Apache Spark (PySpark)**, such as PageRank, sales data analysis, inverted indexing, and frequent itemset mining.

## NTPC youbike analyze
Located in `/NTPC_youbike_analyze`. A real-time data pipeline project:
* **Data Collection**: A Python script that crawls YouBike JSON data and stores it in **HBase**.
* **Data Analysis**: A Spark-based analysis identifying the top 10 busiest stations and monitoring bike availability trends.


## final project
**Location:** `/stock_price_prediction_app`  

### Stock Price Prediction App
This project is a comprehensive application that integrates **Apache Spark** and **yfinance** to build a machine learning pipeline for forecasting stock market trends. It features an interactive web interface built with **Streamlit**.

### Key Features
* **Dynamic Data Acquisition**: Allows users to fetch historical market data for any stock symbol (e.g., `2330.TW`, `AAPL`) directly through the yfinance API.
* **Spark-Powered Machine Learning**: 
  * Uses **Spark MLlib** to implement a Linear Regression model.
  * Features engineering: The model is trained using historical closing prices and trading volumes to predict future trends.
* **Interactive Dashboard**:
  * **Trend Visualization**: Displays historical charts for stock prices and trading volumes.
  * **Model Validation**: Provides an "Actual vs. Predicted" price comparison chart to visualize model accuracy.
* **Real-time Prediction Tool**: Includes a prediction module where users can input current market parameters to receive an immediate forecast for the next trading day's closing price.
* **Performance Evaluation**: Automatically calculates and displays statistical metrics, including:
  * **RMSE** (Root Mean Squared Error)
  * **MAE** (Mean Absolute Error)
  * **R-squared** (Coefficient of Determination)

### Technical Stack
* **Frameworks**: Apache Spark (PySpark), Streamlit
* **Data Source**: yfinance API
* **Libraries**: Pandas, Matplotlib, Numpy