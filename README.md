# Physical Activity Recognition through Analysis of Wearable Sensor Data
## Machine Learning Model + Report

## Overview
With the advent of wearable technology sensors like the Apple Watch, Fitbit, and others, there has been a surge in the volume of useful data these devices collect.

This project aims to delve into the possibilities of what can be achieved with this data in the realm of personal healthcare and fitness. 
We attempt to create a robust and high performance multi-class classifier to recognize specific physical activities from wearable sensor data, utilizing the PAMAP2 Physical Activity Monitoring dataset.

## Objective
The primary objective is to design a predictive model that is:
- Accurate + High-Performance: Provides a balance of high accuracy, recall, and precision in recognizing physical activities
- Robust: Handles anomalies and outliers effectively.
- Efficient: Uses resources optimally and provides quick results.

Promising results may help in personalizing healthcare suggestions, optimizing fitness routines, and potentially pave the way for future innovations in the growing wearable tech industry.

## Dataset: PAMAP2 Physical Activity Monitoring
The PAMAP2 dataset comprises of data points collected from multiple wearable sensors. It captures various physical activities and is a comprehensive source of raw data for our analysis and predictions.

For detailed insights into the dataset, visit the [PAMAP2 Dataset Link](https://archive.ics.uci.edu/dataset/231/pamap2+physical+activity+monitoring).

## Features
- **Data Preprocessing**: Cleaning the dataset for missing values and outliers, and normalizing values.
- **Exploratory Data Analysis**: Provides visual and informational insights into the dataset, including box plots, bar graphs, T-tests, etc...
- **Pre-processing and Model Training**: Generate robust models using Decision Tree, Random Forest, and XGBoost, comparing results.
- **Evaluation**: Cross-validated accuracy, AUC, precision, recall, F1 score, F-importances, etc.

## How to Use:
Because the file is an ipynb file, one can simply view the notebook and the accompanying report directly from the GitHub repository.
Otherwise, download the notebook and open it in a platform such as Google Colab or VSCode for easy viewing.
The report is in PDF format.
