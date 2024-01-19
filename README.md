# Uber Fare Prediction Project

## Overview

This project involves predicting the fare amount for Uber transactions using machine learning techniques. The dataset contains information such as pickup and dropoff locations, passenger count, and timestamps. The predictive model is built using the XGBoost algorithm.

## Project Structure

- **Data Exploration and Analysis:**
  - Visualizes the distribution of fare amounts.
  - Checks correlation between numerical features.
  - Generates pairwise scatter plots and box plots for insights.

- **Data Pre-processing:**
  - Converts pickup date and time to datetime format.
  - Extracts additional features from datetime.
  - Handles missing values.

- **Feature Selection/Extraction:**
  - Encodes categorical columns, specifically the pickup date.

- **Predictive Modeling (XGBoost):**
  - Splits data into training and testing sets.
  - Builds an XGBoost regressor for fare prediction.
  - Evaluates model performance using Root Mean Squared Error (RMSE).

- **Feature Importance:**
  - Plots the top 10 features influencing fare predictions.

## Usage

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
