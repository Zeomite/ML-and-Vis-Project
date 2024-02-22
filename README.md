# ML-and-Vis-Project

# Self-Harm and Substance Abuse Deaths Worldwide

This repository contains Python code to analyze and visualize data on self-harm and substance abuse deaths worldwide. The dataset used in this analysis is sourced from Kaggle, specifically from the [Self-Harm and Substance Abuse Deaths Worldwide](https://www.kaggle.com/datasets/thomaseltonau/self-harm-and-substance-abuse-deaths-worldwide/data) dataset.
Certainly! Here's a sample README you can use for your code:

---

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly

---
## Data Cleaning

The code begins by loading the dataset using pandas and performing initial data exploration:

- Removing unnecessary age ranges.
- Transforming categorical data for 'Cause' column into more concise labels.
- Filtering out unnecessary gender categories.
- Cleaning up the dataset to ensure consistency and remove any irrelevant or redundant data.

## Visualization

Following data cleaning, the code proceeds to visualize the data using both matplotlib and Plotly:

- Visualizing the number of deaths by age and sex for both self-harm and substance abuse.
- Creating a choropleth map using Plotly to visualize worldwide deaths by country.

## Machine Learning

Finally, the code demonstrates how to apply machine learning techniques to the dataset:

- One-hot encoding categorical features.
- Evaluating the performance of different machine learning models such as Linear Regression, Decision Tree, Random Forest, and K-Nearest Neighbors (KNN) on predicting the number of deaths.
- Model optimization using techniques like grid search to find the best hyperparameters for Decision Tree and KNN models.
- Feature importance analysis to understand which features contribute the most to the prediction.

## Results
The analysis provides insights into the distribution of self-harm and substance abuse deaths worldwide. Additionally, machine learning models were trained to predict the number of deaths based on different features, with performance metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared.

