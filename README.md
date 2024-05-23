# EV-Battery

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)

## Project Overview
Predicting the temperature and battery percentage of an EV in use. This project aims to analyze and predict the heating data of electric vehicle (EV) batteries during real driving cycles. The goal is to develop models that can accurately predict the temperature and state of charge (SOC) of EV batteries, which are critical for the efficiency and safety of EVs.

## Dataset Description
The dataset used for this project contains real-life data on an electric vehicle battery, including various features such as temperature, voltage, current, and SOC during different driving cycles. This dataset is sourced from Kaggle and includes detailed recordings of battery parameters over time.

For more details, you can visit the Kaggle dataset: [Battery and Heating Data in Real Driving Cycles](https://www.kaggle.com/datasets/atechnohazard/battery-and-heating-data-in-real-driving-cycles)

## Data Cleaning and Preprocessing
Data cleaning and preprocessing steps are crucial to ensure the quality and usability of the dataset. The following steps were taken:
- Handling missing values
- Removing duplicates
- Correcting data types
- Normalizing data to ensure consistency

--- code placeholder ---

## Feature Engineering
Feature engineering involves creating new features or transforming existing ones to improve the performance of machine learning models. Key steps include:
- Creating time-based features to capture temporal patterns
- Generating statistical summaries of battery parameters over defined intervals
- Encoding categorical variables if any

--- code placeholder ---

## Modeling
Different machine learning models were employed to predict the temperature and SOC of EV batteries. The models include:
- Linear Regression
- Decision Trees
- Random Forest
- Recurrent Neural Networks (RNNs)
- Long Short-Term Memory Networks (LSTMs)

--- code placeholder ---

## Evaluation
The models were evaluated using appropriate metrics to ensure their accuracy and reliability. Common evaluation metrics used are:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

--- code placeholder ---

## Conclusion
This project successfully demonstrates the use of machine learning models to predict EV battery temperature and SOC. The results highlight the importance of feature engineering and the effectiveness of advanced modeling techniques like RNNs and LSTMs in capturing temporal dependencies in the data.

For more detailed insights and code implementations, you can refer to the Kaggle notebook: [Predicting Car Battery Heating Data](https://www.kaggle.com/code/gitanjali1425/predicting-car-battery-heating-data)

