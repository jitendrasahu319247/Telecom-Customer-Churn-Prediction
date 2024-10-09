# Telecom Customer Churn Prediction

This project focuses on predicting customer churn for a telecom company. By analyzing customer data using machine learning, this project helps identify key factors influencing churn rates, visualize customer insights, and support strategic decision-making.

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [ETL Process](#etl-process)
- [Power BI Dashboard](#power-bi-dashboard)
- [Results](#results)
  
## Project Overview

Customer churn is a significant issue for telecom companies, affecting revenue and profitability. This project utilizes a machine learning approach to predict which customers are likely to churn. We also build a Power BI dashboard to visualize customer data, providing insights that help in retaining customers.

## Tech Stack

- **Programming Language**: Python
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (Random Forest)
- **Database**: SQL Server
- **Visualization**: Power BI
- **Data Handling**: Excel

## Data Preprocessing

The customer data was first preprocessed before feeding it into the machine learning model. This includes:
- Handling missing values.
- Encoding categorical variables.
- Scaling numerical features.
- Splitting data into training and testing sets.

Key libraries used: `Pandas`, `NumPy`, `Sklearn`.

## Model Building

We utilized the **Random Forest** algorithm for predicting churn. The steps involved are:
1. Training a Random Forest model using training data.
2. Evaluating model performance on test data.
3. Measuring key metrics like accuracy, precision, recall, and F1-score.

Key libraries used: `Scikit-learn`.

## ETL Process

The ETL (Extract, Transform, Load) process was performed using **SQL Server**:
- Extracted customer data from various sources.
- Transformed the data by cleaning and normalizing it.
- Loaded the cleaned data into a data warehouse for analysis and modeling.

## Power BI Dashboard

An interactive **Power BI** dashboard was created to visualize customer data and provide insights into churn patterns. Key features include:
- Visualizing churn rates by customer segments.
- Identifying churn influencers.
- Providing actionable insights for decision-making.

## Results

- **Model Accuracy**: Achieved over **90% accuracy** in predicting churn.
- **Key Insights**: Identified factors such as contract type, payment method, and tenure as major drivers of churn.
- **Interactive Dashboard**: Enabled better decision-making by allowing exploration of customer profiles and churn patterns.
