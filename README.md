# Building Energy Consumption Prediction using Machine Learning
📌 Project Overview

This project focuses on analyzing building energy consumption patterns and developing a complete machine learning pipeline for energy prediction and anomaly detection using the Building Data Genome Project 2 dataset. The study explores the relationship between energy usage, weather conditions, and time-based features to gain meaningful insights into building energy behavior.
The project implements an end-to-end data science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, predictive modeling, and anomaly detection. An Isolation Forest model was used to detect abnormal energy consumption patterns that may indicate system faults, inefficiencies, or sensor errors. Additionally, an advanced XGBoost regression model was developed for energy consumption prediction, achieving excellent performance with an R² score of 0.95


🎯 Objectives

1.Analyze building electricity consumption patterns

2.Perform data cleaning and preprocessing

3.Conduct exploratory data analysis (EDA)

4.Engineer meaningful features from time-series and weather data

5.Anomaly Detection

6.Build and evaluate machine learning models for energy prediction

7.Compare baseline and advanced regression models

📊 Dataset

Building Data Genome Project 2
The dataset contains large-scale time-series data of electricity consumption from multiple buildings, along with weather information.

* Key Components:

     * Electricity meter readings
     * Weather data (temperature, humidity, etc.)
     * Timestamp-based features

* Preprocessing Steps:

     * Merging multiple datasets
     * Handling missing values
     * Feature extraction from timestamps
     * Data normalization and transformation


⚙️ Methodology

1. Data Loading & Integration

    * Combined multiple datasets including building meter data and weather information.

2. Data Cleaning & Preprocessing

    * Handled missing values
    * Removed anomalies and noise
    * Performed feature scaling

3. Exploratory Data Analysis (EDA)

    * Visualized energy consumption trends
    * Studied correlations with weather conditions
    * Analyzed time-based usage patterns

4. Feature Engineering

    * Extracted time-based features (hour, day, month, weekday)
    * Created weather interaction features

5. Anomaly Detection

   * Implemented **Isolation Forest** to detect abnormal energy usage patterns
   * Identified unusual spikes and drops that may represent system faults, energy inefficiencies, or sensor errors
   * Visualized anomalies using time-series and scatter plots.


6. Model Development

    * Baseline Model: Linear Regression
    * Advanced Model: XGBoost Regression

7. Model Evaluation

    * Performance metric: R² Score
    * XGBoost achieved R² = 0.95


🛠️ Technologies Used
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Scikit-learn
7. Jupyter Notebook
8.XGBoost


📈 Results
- Successfully modeled complex building energy consumption patterns
- XGBoost regression achieved R² score of 0.95
- Identified strong relationships between:

  - Energy usage and temperature
     - Time-based features and consumption patterns

- Demonstrated the effectiveness of machine learning for energy forecasting
- Accurate detection of abnormal energy consumption behavior


📌 Conclusion

This project demonstrates a complete **energy intelligence pipeline** by integrating **energy forecasting and anomaly detection**. It provides valuable insights into building energy behavior and highlights how machine learning can support **energy optimization, fault detection, and operational efficiency** in real-world building management systems

   
