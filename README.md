# Solar Power Prediction

This repository contains a comprehensive machine-learning project aimed at forecasting solar power generation (AC Power) for two solar plants in India. By leveraging historical power generation and environmental data, this project demonstrates the application of regression, clustering, and classification models to achieve accurate predictions and actionable insights.

## 📂 Project Overview
### Objective:
To predict solar power generation (AC Power) based on historical data and environmental features, enabling better resource utilization, reduced operational costs, and scalability in solar energy adoption.

### Key Features:
- **Feature Engineering:** Extracted temporal and environmental features to enrich the dataset.
- **Clustering:** Identified patterns and anomalies using KMeans and HDBSCAN clustering methods.
- **Classification:** Categorized power generation into Low, Medium, and High using Random Forest.
- **Regression:** Built and evaluated models like Linear Regression and Random Forest Regression for accurate power forecasting.

## 📊 Dataset Description
- **Source:** Data from two solar power plants in India over 34 days.
- **Features:** Includes DC Power, AC Power, daily and total yield, irradiance, and temperature.
- **Target Variable:** AC Power (continuous variable).

## 🚀 Workflow
1. **Data Preprocessing:** Combined data from two plants, handled missing values, and ensured timestamp alignment.
2. **Feature Engineering:** Extracted time-based and environmental features.
3. **Clustering:** Used KMeans and HDBSCAN to explore patterns and detect anomalies.
4. **Classification:** Built Random Forest classifier to categorize power output into classes.
5. **Regression:** Developed Linear Regression and Random Forest models for power forecasting.
6. **Evaluation:** Assessed models using metrics like MAE, MSE, R², and F1-Score.

## 📈 Results
- **Regression Models:** Random Forest outperformed Linear Regression in predicting AC Power.
- **Classification Models:** Random Forest classifier achieved high accuracy for power classification.
- **Clustering:** Provided insights into operational anomalies and power generation patterns.

## 🌟 Business Value
- Optimized solar resource utilization.
- Reduced downtime and operational costs.
- Improved revenue potential and scalability in solar adoption.

## 🛠️ Tools Used
- Python (pandas, numpy, sklearn, matplotlib, seaborn, hdbscan)
- Jupyter Notebook

