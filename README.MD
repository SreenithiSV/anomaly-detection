
# Anomaly Detection System

This repository contains code for an anomaly detection project in cybersecurity. The project aims to detect and classify anomalies or cyber attacks within network traffic data.

## Overview

The project involves several steps including data preprocessing, feature engineering, model building, and evaluation. Here's a brief overview of each step:

1. **Data Exploration**: The project begins with exploring the raw dataset to understand its structure, features, and distribution. This step helps in gaining insights into the data and identifying potential challenges or areas for improvement.

2. **Data Preprocessing**: Raw data often contains missing values, outliers, or inconsistencies. The preprocessing step involves handling these issues by performing tasks such as imputation, outlier detection, and data normalization. Categorical variables are encoded to make them suitable for machine learning models.

3. **Feature Engineering**: Feature engineering plays a crucial role in enhancing the predictive power of machine learning models. New features are created or extracted from existing ones to capture meaningful information. For example, timestamp data is parsed to extract temporal features such as hour of the day and month.

4. **Model Building**: Several machine learning models are trained using the preprocessed data to detect anomalies. These models include Random Forest Classifier, Logistic Regression, and Gradient Boosting Classifier. Model performance is evaluated using appropriate metrics such as accuracy scores and classification reports.

5. **Unsupervised Clustering**: Unsupervised clustering techniques like KMeans are applied to identify inherent patterns within the data. Clustering helps in segmenting the data into groups or clusters based on similarity. Visualization techniques such as PCA are used to visualize the clusters and understand the data distribution.

6. **Anomaly Detection**: Anomaly detection techniques, such as Isolation Forest, are utilized to detect outliers or unusual patterns within the data. Isolation Forest is particularly effective in identifying anomalies in high-dimensional datasets. Thresholds are set to classify data points as normal or anomalous based on their anomaly scores.

## Getting Started

To run the code, follow these steps:

Clone the repository to your local machine by running the following command in your terminal environment:

```bash
git clone https://github.com/SreenithiSV/anomaly-detection
```

Install the necessary dependencies by running the following command: 

```bash
pip install -r requirements.txt
```

Ensure you have the required dataset (`cybersecurity_attacks.csv`) in the specified file path.

Examine the results and model performance metrics.

## Dataset

The dataset (`cybersecurity_attacks.csv`) contains information about cybersecurity attacks, including various features such as Protocol, Packet Type, Traffic Type, Timestamp, etc. The goal is to detect anomalies or suspicious activities within this data.
