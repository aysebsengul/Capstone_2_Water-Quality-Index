# Water Quality Index Prediction Project
This repository contains the code and documentation for predicting water quality index (WQI) using various analytical methods.

## Table of Contents
- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Data](#data)
- [Docs] (#docs)
- [Notebooks](#notebooks)
- [Results](#results)
- [Documentation](#documentation)
  
## Project Overview
This project aims to develop an efficient method for predicting the water quality index (WQI), a single metric that encompasses both the Water Quality Classification (WQC) and the overall quality of water. The objective is to streamline the water quality assessment process, reducing the time and resources typically required for manual measurements. Utilizing regression learning techniques, including Linear Regression, Random Forest Regression, and XGBoosting Regression, enabled the prediction of WQI based on key parameters such as dissolved oxygen, nitrite, nitrate, total nitrogen, total phosphorus, total suspended solids, biological oxygen demand, and turbidity.

## Directory Structure
├── Data/
│   └── Water_Quality_Data.csv
├── Docs/
│   ├── 1_Project_Proposal.pdf
│   ├── 6_Capstone_Final_Report_WQI.pdf
│   ├── 7_Capstone_Presentation_WQI.pdf
│   └── 7_Capstone_Presentation_WQI.pptx
├── Notebooks/
│   ├── 2_Data_wrangling.ipynb
│   ├── 3_Exploratory_Data_Analysis.ipynb
│   ├── 4_Preprocessing_and_Training_Data_Development.ipynb
│   └── 5_Modeling.ipynb
├── Results/
│   └── Model_metrics.txt
└── README.md

## Data
The Data directory contains the water quality dataset used in this project, provided in Water_Quality_Data.csv.

## Docs
The Docs directory contains key project documents that provide comprehensive insights into various aspects of the project. These documents include:

  - 1_Project_Proposal.pdf: The initial project proposal.
  - 6_Capstone_Final_Report_WQI.pdf: The final report provides a comprehensive overview of the project, detailing the     problem statement, methodology, findings, and recommendations. It begins with an introduction to the importance       of water quality assessment, followed by a description of the Water Quality Index (WQI) and its significance in       monitoring water resources. The report outlines the four main phases of the project: data wrangling, exploratory      data analysis (EDA), preprocessing, and modeling. Each phase is described in detail, highlighting the key             actions taken, methodologies employed, and insights gained. The findings from the modeling phase, including the       performance of different regression algorithms, are presented and analyzed. The report concludes with                 recommendations for future research and practical applications of the project's findings in water quality             management.
  - 7_Capstone_Presentation_WQI.pdf: Presentation slides summarizing the project.
  - 7_Capstone_Presentation_WQI.pptx: PowerPoint version of the presentation.
    
## Notebooks
The Notebook directory contains Jupyter notebooks used for data wrangling, exploratory data analysis (EDA), preprocessing, and modeling. These notebooks provide step-by-step procedures and visualizations used to clean the data, explore its characteristics, and build the predictive models. The main notebooks included are:

  - 2_Data_wrangling.ipynb: This notebook encompasses code for loading the dataset, cleaning and preparing the 
    data, computing the water quality index, and ultimately storing the processed data for subsequent analysis..
  - 3_Exploratory Data Analysis.ipynb: This notebook entails exploratory data analysis (EDA), including data   
    visualization, outlier detection, and statistical analysis to gain insights into the dataset's characteristics 
    and distributions.
  - 4_Preprocessing and Training Data Development.ipynb: This notebook encompasses the preprocessing phase of the 
    project, which involves transforming the raw dataset into a format suitable for training machine learning models. 
    It includes steps such as data splitting into training and testing sets, feature scaling, encoding categorical 
    variables, and addressing outliers.
  - 5_Modeling.ipynb: Various machine learning algorithms are applied to build predictive models for water quality 
    assessment. It includes the selection and implementation of regression models such as Linear Regression, Lasso 
    Regression, Ridge Regression, Random Forest Regression, and XGBoost Regression. The notebook covers 
    hyperparameter tuning, model evaluation using appropriate metrics such as R-squared, Mean Squared Error (MSE), 
    and Mean Absolute Error (MAE), and the comparison of model performance to identify the most effective algorithm 
    for predicting water quality index.




    
5. **6_Capstone_Final_Report_WQI.pdf**: The final report provides a comprehensive overview of the project, detailing the problem statement, methodology, findings, and recommendations. It begins with an introduction to the importance of water quality assessment, followed by a description of the Water Quality Index (WQI) and its significance in monitoring water resources. The report outlines the four main phases of the project: data wrangling, exploratory data analysis (EDA), preprocessing, and modeling. Each phase is described in detail, highlighting the key actions taken, methodologies employed, and insights gained. The findings from the modeling phase, including the performance of different regression algorithms, are presented and analyzed. The report concludes with recommendations for future research and practical applications of the project's findings in water quality management.
6. **Model_metrics.txt**: This file summarizes the key parameters, hyperparameters, and performance metrics of the XGBoost Regression model used in the project.

## Project Report
The detailed project report can be found (https://github.com/aysebsengul/Capstone_2_Water-Quality-Index/blob/74c59e1022b95877dfb759f1adf406ff39a70ea8/6_Capstone_Final_Report_WQI.pdf).

## Model Metrics
The model metrics file can be accessed (https://github.com/aysebsengul/Capstone_2_Water-Quality-Index/blob/77176ba9e30f3203ed059fd6d0449f0b18b3a46b/Model_metrics.txt).

## Recommendations
Further research into feature engineering, exploration of temporal and spatial patterns in water quality data, and investigation of deep learning methods for improved predictions are recommended based on our findings.

## Conclusion
This project demonstrates the potential of machine learning techniques in predicting water quality index and provides insights into enhancing water resource management strategies.
