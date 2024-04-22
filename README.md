# Water Quality Index Prediction Project

## Overview
This project aims to develop an efficient method for predicting the water quality index (WQI), a single metric that encompasses both the Water Quality Classification (WQC) and the overall quality of water. The objective is to streamline the water quality assessment process, reducing the time and resources typically required for manual measurements. Utilizing regression learning techniques, including Linear Regression, Random Forest Regression, and XGBoosting Regression, enabled the prediction of WQI based on key parameters such as dissolved oxygen, nitrite, nitrate, total nitrogen, total phosphorus, total suspended solids, biological oxygen demand, and turbidity.

## Project Files
1. **2_Data_wrangling.ipynb**: This notebook encompasses code for loading the dataset, cleaning and preparing the data, computing the water quality index, and ultimately storing the processed data for subsequent analysis..
2. **3_Exploratory Data Analysis.ipynb**: This notebook entails exploratory data analysis (EDA), including data visualization, outlier detection, and statistical analysis to gain insights into the dataset's characteristics and distributions.
3. **4_Preprocessing and Training Data Development.ipynb**: This notebook encompasses the preprocessing phase of the project, which involves transforming the raw dataset into a format suitable for training machine learning models. It includes steps such as data splitting into training and testing sets, feature scaling, encoding categorical variables, and addressing outliers.
4. **5_Modeling.ipynb**: Various machine learning algorithms are applied to build predictive models for water quality assessment. It includes the selection and implementation of regression models such as Linear Regression, Lasso Regression, Ridge Regression, Random Forest Regression, and XGBoost Regression. The notebook covers hyperparameter tuning, model evaluation using appropriate metrics such as R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE), and the comparison of model performance to identify the most effective algorithm for predicting water quality index.
5. **6_Capstone_Final_Report_WQI.pdf**: The final report provides a comprehensive overview of the project, detailing the problem statement, methodology, findings, and recommendations. It begins with an introduction to the importance of water quality assessment, followed by a description of the Water Quality Index (WQI) and its significance in monitoring water resources. The report outlines the four main phases of the project: data wrangling, exploratory data analysis (EDA), preprocessing, and modeling. Each phase is described in detail, highlighting the key actions taken, methodologies employed, and insights gained. The findings from the modeling phase, including the performance of different regression algorithms, are presented and analyzed. The report concludes with recommendations for future research and practical applications of the project's findings in water quality management.
6. **Model_metrics.txt**: This file summarizes the key parameters, hyperparameters, and performance metrics of the XGBoost Regression model used in the project.

## Project Report
The detailed project report can be found (https://github.com/aysebsengul/Capstone_2_Water-Quality-Index/blob/77176ba9e30f3203ed059fd6d0449f0b18b3a46b/6_Capstone_Final_Report_WQI.pdf).

## Model Metrics
The model metrics file can be accessed (https://github.com/aysebsengul/Capstone_2_Water-Quality-Index/blob/77176ba9e30f3203ed059fd6d0449f0b18b3a46b/Model_metrics.txt).

## Recommendations
Based on our findings, we recommend further research into feature engineering, exploring temporal and spatial patterns in water quality data, and investigating deep learning methods for improved predictions.

## Conclusion
This project demonstrates the potential of machine learning techniques in predicting water quality index and provides insights into enhancing water resource management strategies.
![image](https://github.com/aysebsengul/Capstone_2_Water-Quality-Index/assets/143531090/718b1930-9db5-479f-991a-91b5a2e7529d)
