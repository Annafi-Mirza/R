# Overview

The purpose of the project is to create multiple, multiple-regression models that each predict HDL cholesterol using a test dataset and determining which model performs best through root mean squared error.

This is for the ASA South Florida Data Challenge.

# Description

- Project completed for the 2026 ASA South Florida Student Data Challenge
- Challenge was to predict HDL-cholesterol levels mg/dL in test dataset
- Project completed in R and RStudio
- Training dataset included 1000 observations with 95 possible predictors from the NHANES
- Predictors included numerical data like nutritional stats and also categorical data like income levels
- Created, trained, & evaluated linear, ridge, lasso, elastic net, and random forest regression models
- Conducted permutation testing to determine most accurate random forest model based on random seed distribution
- Finalized random forest regression model with RMSE (error rate) of ~4.78 mg/dL on test dataset
- Final model achieved RMSE of ~4.56 mg/dL compared to SD in test dataset of 8.99 mg/dL
- Final model’s predictions were, on average, within 4.56 mg/dL of the real HDL-cholesterol levels
- Determined model’s most influential predictors included gender, BMI, waist circumference, alcohol levels, and age
- Model’s performance was in the top 20% of competitors