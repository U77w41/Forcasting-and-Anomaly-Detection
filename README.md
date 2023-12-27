# Forecasting and Anomaly Detection Project

## Overview

In the "Forecasting-and-Anomaly-Detection" project, we delved into the realm of machine learning to enhance our understanding of Walmart sales data. The project focused on both time series forecasting and anomaly detection, employing a diverse set of techniques to achieve accurate predictions and identify unusual patterns in the sales data.

## Forecasting Techniques

### Regression Techniques

- **Polynomial Regression:** Leveraging the flexibility of polynomial functions to capture non-linear relationships in the data.
- **Multiple Linear Regression:** Utilizing multiple features to model the sales data and uncover complex dependencies.
- **Lasso Linear Regression:** Introducing L1 regularization to encourage sparsity in the model, selecting only the most influential features.
- **Ridge Linear Regression:** Applying L2 regularization to prevent overfitting and improve the generalization of the model.
- **Elastic Net Regression:** Combining L1 and L2 regularization to harness the strengths of both techniques.

### Time Series Forecasting

- **ARMA (AutoRegressive Moving Average):** Employing ARMA models to understand and predict the temporal patterns in Walmart sales data.

## Anomaly Detection Techniques using Unsupervised Learning Approaches

### Supervised Learning Approach

- **KNN Regressor:** Utilizing the K-nearest neighbors algorithm to detect anomalies based on the deviation from the expected sales values.
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise):** Identifying anomalies by clustering the sales data and isolating points that do not conform to any cluster.
- **LSTM with Autoencoders:** Leveraging Long Short-Term Memory networks combined with autoencoders for capturing complex temporal dependencies and detecting anomalies in the sales data.

## Data Version Control (DVC)

To maintain the integrity and traceability of our project, we adopted the Data Version Control (DVC) Python library. DVC facilitated the versioning of our data, ensuring reproducibility and providing a robust framework for collaboration.

This project represents a holistic exploration of machine learning techniques for forecasting and anomaly detection, combining traditional regression methods with cutting-edge time series forecasting and unsupervised learning approaches.
