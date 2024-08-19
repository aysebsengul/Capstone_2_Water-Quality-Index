# Water Quality Index Prediction
This repository contains the code and documentation for predicting water quality index (WQI) using various analytical methods.

## Table of Contents
- [Project Overview](#project-overview)
- [Directory Structure](#directory-structure)
- [Data](#data)
- [Docs](#docs)
- [Notebooks](#notebooks)
- [Results](#results)
- [Documentation](#documentation)
  
## Project Overview
This project aims to develop an efficient method for predicting the water quality index (WQI), a single metric that encompasses both the Water Quality Classification (WQC) and the overall quality of water. The objective is to streamline the water quality assessment process, reducing the time and resources typically required for manual measurements. Utilizing regression learning techniques, including Linear Regression, Random Forest Regression, and XGBoosting Regression, enabled the prediction of WQI based on key parameters such as dissolved oxygen, nitrite, nitrate, total nitrogen, total phosphorus, total suspended solids, biological oxygen demand, and turbidity.

## Directory Structure
```plaintext
├── Data/
│   └── Water_Quality_Data.csv
├── Docs/
│   ├── 1_Project Proposal
│   ├── 6_Capstone_Final_Report_WQI.pdf
│   ├── 7_Capstone_Presentation_WQI.pdf
│   └── 7_Capstone_Presentation_WQI.pptx
├── Notebook/
│   ├── 2_Data_wrangling.ipynb
│   ├── 3_Exploratory_Data_Analysis.ipynb
│   ├── 4_Preprocessing_and_Training_Data_Development.ipynb
│   └── 5_Modeling.ipynb
├── Results/
│   ├── Model_metrics.txt
└── README.md

## Data
The Data directory contains the water quality dataset used in this project, provided in Water_Quality_Data.csv.

## Docs
The Docs directory contains key project documents that provide comprehensive insights into various aspects of the project. These documents include:

  - 1_Project_Proposal.pdf: This document outlines the project's goals, scope, and planned methodology. It provides a     detailed description of the project's objectives and the approach intended to achieve them.

  - 6_Capstone_Final_Report_WQI.pdf: The final report provides a comprehensive overview of the project, detailing the     problem statement, methodology, findings, and recommendations. It begins with an introduction to the importance       of water quality assessment, followed by a description of the Water Quality Index (WQI) and its significance in       monitoring water resources. The report outlines the four main phases of the project: data wrangling, exploratory      data analysis (EDA), preprocessing, and modeling. Each phase is described in detail, highlighting the key             actions taken, methodologies employed, and insights gained. The findings from the modeling phase, including the       performance of different regression algorithms, are presented and analyzed. The report concludes with                 recommendations for future research and practical applications of the project's findings in water quality             management.

  - 7_Capstone_Presentation_WQI.pdf: A PDF version of the presentation slides used to summarize and present the           project findings. It includes key visualizations, results, and insights derived from the analysis.

  - 7_Capstone_Presentation_WQI.pptx: The PowerPoint version of the presentation slides, suitable for formal              presentations and meetings. It provides a visual summary of the project work and results.
    
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

## Results
The Results directory contains model performance metrics summarized in Model_metrics.txt.

  - Model_metrics.txt: This file summarizes the key parameters, hyperparameters, and performance metrics of the           XGBoost Regression model used in the project.
