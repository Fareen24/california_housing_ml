

# Regression Practice with California Housing Dataset

## Overview

This project is a practice exercise to help me  understand regression techniques within supervised learning. The goal is to explore, analyze, and build regression models using the California Housing dataset available in scikit-learn. This dataset is used to predict housing prices based on various features.

## Objectives

- **Exploratory Data Analysis (EDA):** Understand the dataset, its structure, and relationships between different features.
- **Linear Regression:** Learn how to implement and interpret linear regression for predicting continuous outcomes.


## Dataset

The California Housing dataset is sourced from the `sklearn.datasets` module. It consists of several features such as:
- **MedInc:** Median income in block group
- **HouseAge:** Median house age in block group
- **AveRooms:** Average number of rooms per household
- **AveBedrms:** Average number of bedrooms per household
- **Population:** Block group population
- **AveOccup:** Average household size
- **Latitude:** Block group latitude
- **Longitude:** Block group longitude

The target variable is `MedianHouseValue`, representing the median house value in each block group.

## Steps and Workflow

1. **Data Loading:** Fetch the California Housing dataset using scikit-learn.
2. **Data Preparation:** Organize the data into a pandas DataFrame for easy manipulation.
3. **Exploratory Data Analysis (EDA):** 
   - Check for missing values.
   - Generate descriptive statistics.
   - Visualize feature distributions and relationships using histograms, scatter plots,  and correlation matrices.
4. **Linear Regression:**
   - Split the data into training and testing sets.
   - Train a linear regression model to predict `MedianHouseValue`.
   - Evaluate the model using metrics such as Mean Squared Error (MSE) and R-squared score.


## Tools and Libraries

- **Python**: The primary programming language used for this project.
- **Jupyter Notebook**: An interactive environment for running Python code and visualizations.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib and Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning algorithms and model evaluation.

## Purpose

This project is created solely for **learning purposes**. It aims to provide hands-on experience in applying regression techniques and understanding their application in supervised learning. The California Housing dataset helped me have a practical example to explore these concepts in the context of real-world data.

## How to Use

1. Clone this repository.
2. Install the necessary Python libraries listed above.
3. Open the Jupyter Notebook and follow along with the code and explanations provided.


## Link to the dataset 

https://scikit-learn.org/stable/datasets/real_world.html
