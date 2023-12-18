# Cardiovascular Disease Risk Prediction Model

## Project Overview

This project aims to develop a machine learning model to predict the risk of cardiovascular disease (CVD) in patients. Utilizing the 2021 Behavioral Risk Factor Surveillance System (BRFSS) Dataset, the model is designed to aid healthcare professionals in early detection and efficient management of CVD risks.

## Dataset

The dataset comprises approximately 309,000 observations from the 2021 BRFSS, featuring demographic and health-related attributes including age, sex, general health, exercise habits, smoking history, and the presence of various diseases.

## Methodology

Our approach involves several key stages:

- **Data Preprocessing**: Cleaning and preparing the data for analysis.
- **Feature Engineering**: Generating new features and selecting relevant ones for the model.
- **Model Selection and Evaluation**: Employing various machine learning models and choosing the best performer based on recall rate and other metrics.

## Exploratory Data Analysis (EDA)

Key insights from EDA include:

- **Age and CVD**: A significant increase in CVD risk with age.
- **BMI and CVD**: Higher BMI categories showing increased risk.
- **Smoking and CVD**: Smoking history doubling the likelihood of CVD.
- **Exercise and CVD**: Regular exercise associated with lower CVD risk.
- **Gender Differences**: Males showed a higher propensity for CVD compared to females.

## Feature Engineering and Modeling

- Implemented techniques like outlier handling, encoding, and interaction terms.
- Developed models including Logistic Regression, Random Forest, and XGBoost.
- Logistic Regression showed the best performance, particularly in terms of recall.

## Key Variables

Important variables for prediction include age category, general health, smoking history, and gender.

## Insights and Recommendations

- The model can enhance screening processes, reducing waiting times for cardiology appointments.
- Health professionals can use this tool for better resource allocation and patient care.
- Encourages self-awareness among individuals regarding CVD risks.

## Acknowledgements

- Team Members: Aakash Dhruva, Anubhav Nehru, Deepti Hariyani, Karthick Vel Kathirvel, Mayank Gupta, Zihao Zhu
- Dataset Source: 2021 Behavioral Risk Factor Surveillance System (BRFSS) Dataset on Kaggle
