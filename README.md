# Bonfire_Capstone

## Business Problem Statement
Maverik, a convenience store chain, is expanding rapidly and needs to forecast daily sales for new stores. With limited data, they plan to use historical data to identify trends, understand sales drivers, and build a forecasting model using time series, regression, causal analysis, and machine learning. The model will be evaluated using industry-standard metrics and its ability to adapt to new information. It will help Maverik optimize staffing, inventory, and marketing for new stores, maximizing profits and minimizing losses while ensuring customer satisfaction.

*Please see our full EDA and Modeling Notebook by clicking on the link below. You will also find a detailed explanation of our analytical findings.*

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/only2venkat/Bonfire_capstone/blob/3a93c0dd35b2225a96c0a2d9080fa5b937cfe7a0/Model_notebook.ipynb)

## Exploratory Data Analysis 

![image](https://github.com/only2venkat/Bonfire_capstone/assets/134881202/767009e2-6dc2-4a1a-874f-f31966b34d96)

![image](https://github.com/only2venkat/Bonfire_capstone/assets/134881202/cc73eec2-8edc-4666-8e1d-437a485b997f)


## Sales Forecasting - Model Building 
### Time Series Forecasting and Analysis Overview:

This repository showcases our work on time series forecasting models for Maverik. Our analysis focused on various forecasting techniques, including ARIMA, SARIMA, ETS, and Prophet, driven by insights from exploratory data analysis revealing prominent seasonality patterns in the sales data.

*Key Insights:*

Decomposition and Stationarity: Identified distinct patterns in sales data and confirmed stationarity, vital for ARIMA and SARIMA models.

Clustering and Prophet Model: Cluster analysis revealed varied Prophet model performances across different sales categories, highlighting opportunities for refinement.

ARIMA and SARIMA Challenges: While ARIMA showed promise, challenges in capturing complex sales patterns were observed. SARIMA struggled with weekly seasonality and holiday considerations.

*Next Steps:*

Prophet Model Optimization: Deeper hyperparameter tuning and custom adjustments for improved accuracy, especially in Cluster 1.
Model Ensemble and Validation: Exploration of ensemble models for enhanced accuracy and thorough cross-validation techniques for validation and fine-tuning.
Communication and Reporting: Clear and concise communication of findings, emphasizing model strengths and limitations for effective decision-making.
Continuous Monitoring and Updating: Establishment of a monitoring system for ongoing model performance updates with new data.

Our goal is to refine existing models, explore alternative approaches, and elevate forecasting capabilities to provide actionable insights for Maverik's strategic decisions.
