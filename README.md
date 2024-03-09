# Data Analysis on Uber 

## Overview

This project involves predicting the fare amount for Uber transactions using machine learning techniques. The dataset contains information such as pickup and dropoff locations, passenger count, and timestamps.

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

- **Feature Importance:**
  - Plots the top 10 features influencing fare predictions.

## Usage

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
