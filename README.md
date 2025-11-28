# NBA-EDA-and-Model-Tuning

## Overview
This project performs **Exploratory Data Analysis (EDA)** and **Machine Learning Model Tuning** on NBA player data to predict the number of single-game (PTS). We will make these predictions based on the numerical metrics in the dataset. The dataset is provided on Kaggle and was created by Eduardo Palmieri. The dataset can be found [here](https://www.kaggle.com/datasets/eduardopalmieri/nba-player-stats-season-2425/data).

This repository includes two Jupyter notebooks:
- Exploratory_Data_Analysis.ipynb
- model_and_model_tuning.ipynb

## Project Goal
- Understand the statisical relationship between NBA player features and total points scored
- Use regression techniques to **predict points** based on **numerical features**
- Tune advanced models to improve accuracy
- Evalute model performance using standard scoring metrics 

## Exploratory Data Analysis
The Exploratory Data Analysis section of this project contains features like a clean, structured EDA notebook, correlation heatmaps and descriptive statisics, along with feature engineering and data preprocessing. 

**EDA Steps**
- 1. Basic Analysis - Read the CSV file: Get the shape of the dataset, use the 'head()' function to see some data in the dataset, and see the dtypes in the dataset.
- 2. Data Cleaning - Handle missing values, seperating the numerical and categorical columns 
- 3. Data Visualization - Created histograms to see distribution of numerical values, create correlation heatmap to see correlation to points 
- 4. Create numerical dataset 

### Visualizations in EDA:
![alt text](image.png) ![alt text](image-1.png)