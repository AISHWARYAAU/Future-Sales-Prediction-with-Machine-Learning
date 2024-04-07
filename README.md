# Future Sales Prediction with Machine Learning

## Overview

This repository contains a Python script to predict future sales based on advertising expenditure using machine learning. The primary dataset used for this prediction is "advertising.csv", which includes data on sales and advertising spending across various channels like TV, Radio, and Newspaper.

## Requirements

- pandas
- numpy
- scikit-learn
- plotly

Install the required packages using pip:

```bash
pip install pandas numpy scikit-learn plotly
```

## Data Exploration

The initial step involves loading and exploring the dataset to understand its structure and contents. We check for any missing values and visualize the relationships between sales and different advertising channels using scatter plots with trendlines.

## Data Preprocessing

Before training the machine learning model, the data is split into features (advertising expenditures on TV, Radio, and Newspaper) and the target variable (Sales). We use the `train_test_split` function from scikit-learn to split the dataset into training and testing sets.

## Model Building

A Linear Regression model is used for predicting future sales based on advertising expenditures. The model is trained on the training dataset, and its performance is evaluated using the R-squared score on the testing dataset.

## Prediction

As a demonstration, the model is used to predict sales for a given set of advertising expenditures on TV, Radio, and Newspaper (features = [[230.1, 37.8, 69.2]]). The predicted sales value is printed to the console.

## Conclusion

This project provides a basic example of how machine learning can be used to predict future sales based on advertising spending across different channels. Further improvements and optimizations can be made by exploring more complex models or incorporating additional features into the dataset.

## images
![image](https://github.com/AISHWARYAAU/Future-Sales-Prediction-with-Machine-Learning/assets/91381783/2f4ca5c7-1764-43b8-b251-359d2ea0708e)
![image](https://github.com/AISHWARYAAU/Future-Sales-Prediction-with-Machine-Learning/assets/91381783/8c28cb32-d391-4da0-8a43-947c76268a63)
![image](https://github.com/AISHWARYAAU/Future-Sales-Prediction-with-Machine-Learning/assets/91381783/c0f3b2bb-7aec-4bbc-86dc-5fb0316f6e1d)


