# ml-01 
# California House Price Prediction

## Author
David Rodriguez-Mayorquin 
[github.com/drodmay1](https://github.com/drodmay1)

## Overview
This project uses the **California Housing Dataset** to build a **Linear Regression Model** that predicts **median house value** based on features such as **median income** and **average number of rooms**.

## Goal
The goal is to predict **median house values** (`MedHouseVal`) based on various features like:

- Median Income (`MedInc`)
- Average Number of Rooms (`AveRooms`)
- House Age
- Population
- Location (Latitude & Longitude)

## Dataset 
Dataset: **California Housing Dataset**
- Source: Scikit-learn's built-in dataset
- Rows: 20,640
- Features: 8 numerical predictors + 1 target

## ML Workflow Overview
1. Load and explore data
2. Visualize feature distributions
3. Select features
4. Split data into training and test sets
5. Train a Linear Regression model
6. Evaluate performance using R², MAE, RMSE
---

## Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook / VS Code

## Project Outline
Machine learning projects follow a structured approach.
We will use this approach throughout the course. 

### Section 1. Load and Explore the Data
- 1.1 Load the dataset and display the first 10 rows.
- 1.2 Check for missing values and display summary statistics.

### Section 2. Visualize Feature Distributions
- 2.1 Create histograms, boxplots, and scatterplots.
- 2.2 Identify patterns or anomalies in feature distributions.

### Section 3. Feature Selection and Justification
- 3.1 Choose two input features for predicting the target.
- 3.2 Justify your selection with reasoning.

### Section 4. Train a Linear Regression Model
- 4.1 Define X (features) and y (target).
- 4.2 Train a Linear Regression model using Scikit-Learn.
- 4.3 Report R^2, MAE, RMSE.


