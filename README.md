# About

This Notebook was part of a challenge, the capstone project of Summer Analytics, a primer course on Data Science, conducted by the Consulting and Analytics Club of IIT Guwahati in the summers.

DeltaX provided the dataset is the pioneering cross-channel digital advertising platform. The cloud-based platform leverages big data, user behaviour, and machine learning algorithms to improve performance across the business funnel of advertisers.

The goal was to predict the revenue from Test data with a low RMSE score.

The published notebook can be found [here](https://aiplanet.com/notebooks/1931/abhishek_roy/capstone-project-advertisement-10206).

## Problem Statement
To predict an ad's future performance (revenue) between March 1st and March 15th.

## Data Description
- date: the date on which the ad was made live
- campaign: campaign number
- adgroup: adgroup number
- ad: ad number
- impressions - Number of time the ad was shown
- clicks - Number of time the ad clicked shown
- cost - Amount spent to show ad
- conversions - Number of transactions received
- revenue: revenue generated from the ad

## Summary
I utilized Python as the primary programming language, employing libraries such as Pandas, Numpy, Matplotlib, Seaborn, and Sklearn for comprehensive data analysis and machine learning.

The notebook began with an in-depth Exploratory Data Analysis (EDA) to assess the dataset, identify key patterns, visualize distributions, and uncover insights that would guide the modelling process. Data preprocessing steps were meticulously executed, normalizing data, and encoding categorical variables to ensure the dataset was in optimal shape for analysis.

I employed feature engineering techniques to develop additional variables that could enhance the predictive power of the model. Following this, a regression tree model was implemented to predict revenue. The modelling process included careful tuning and hyperparameter optimization, leading to the final model achieving a Root Mean Squared Error (RMSE) score of 106.65 on the testing dataset. This result demonstrates the model's effectiveness and accuracy in making revenue predictions.

The entire workflow is documented in the Google Colab, detailing each step taken and the insights gained throughout the competition.

![image](https://github.com/user-attachments/assets/a1e32651-b9d1-44ec-b535-f5435c2c5547)
