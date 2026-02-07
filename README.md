# Crop Yield Prediction using Machine Learning

## Problem Statement
This project predicts agricultural crop yield in Indian states using climate and agricultural input factors such as rainfall, fertilizer usage, pesticide usage, cultivated area, and seasonal patterns.

## Dataset
The dataset used is the publicly available **Agricultural Crop Yield in Indian States** dataset.

### Columns Used
- Crop
- Crop_Year
- Season
- State
- Area
- Annual_Rainfall
- Fertilizer
- Pesticide
- Yield (Target)

## Methodology
- Extracted dataset from ZIP format
- Performed data cleaning and preprocessing
- Encoded categorical variables
- Scaled numerical features
- Trained Linear Regression and Random Forest models

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Key Insights
- Fertilizer and pesticide usage significantly impact crop yield.
- Random Forest captures nonlinear relationships better than Linear Regression.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Google Colab

## Author
Priya Nandini Vaka
