# Sales_Prediction-Rossmann_Store

## Problem Description

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.
You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.

## Approach and Presentation. 
Final Notebook - https://github.com/yagnik99/Sales_Prediction-Rossmann_Store/blob/main/Team_4_Capstone_Project_2.ipynb

Presentation - https://github.com/yagnik99/Sales_Prediction-Rossmann_Store/blob/main/Project%20Presentation.pdf

## Important Works/ Conclusion : 

Worked to Forecast Sales for a major drug store chain (Rossmann Store), and built a Machine Learning solution with Meta Regressor in the stacked ensembles model as XG Boost on base models such as Random Forest, Light GBM, and Decision Trees giving the lowest RMSPE of 9.2% as the final solution.

Engineered features include - days since the last promotion, days to next holiday, lag of sales, lag of customers among others, and applied isolation forest to treat outliers helping clean and prepare data for further modeling by scaling it.

Utilized analytical and visual expertise to provide insights and proposals to support sales improvement include Time Series Analysis.

Used unsupervised learning using PCA for dimensionality reduction of highly correalted features and used Bayesian Optimization to tune the hyperparameters.
