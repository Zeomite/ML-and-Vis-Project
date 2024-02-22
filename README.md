# ML-and-Vis-Project

# Self-Harm and Substance Abuse Deaths Worldwide

This repository contains Python code to analyze and visualize data on self-harm and substance abuse deaths worldwide. The dataset used in this analysis is sourced from Kaggle, specifically from the [Self-Harm and Substance Abuse Deaths Worldwide](https://www.kaggle.com/datasets/thomaseltonau/self-harm-and-substance-abuse-deaths-worldwide/data) dataset.

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

The analysis provided here offers insights into the patterns and factors associated with self-harm and substance abuse deaths worldwide.
