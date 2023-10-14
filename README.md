# SevenCode-Titanic Survival Prediction

# Titanic Survival Prediction

This repository contains code and resources for predicting the survival of passengers on the Titanic using machine learning. The dataset includes 12 features, and we utilize Python and various machine learning algorithms to determine the survival status of individuals who were aboard the Titanic.

## Table of Contents
- [1. Introduction]
- [2. Steps Followed]
  - [2.1 Importing Libraries]
  - [2.2 Descriptive Data Analysis]
  - [2.3 Cleaning Dataset]
  - [2.4 Exploratory Data Analysis]
  - [2.5 Model Training]
  - [2.6 Data Visualization]
  - [2.7 Analysis Conclusion]
- [3. Getting Started]
- [4. Usage]

## 1. Introduction

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, the Titanic sank after colliding with an iceberg, resulting in the deaths of a significant number of passengers and crew. This project aims to predict the survival of individuals on the Titanic based on various features such as age, gender, ticket class, and more.

## 2. Steps Followed

### 2.1 Importing Libraries

In this initial step, we import necessary Python libraries including NumPy, Pandas, and Seaborn to assist with data manipulation, analysis, and visualization.

### 2.2 Descriptive Data Analysis

This step involves exploring the dataset with functions like `info`, `head`, `describe`, and `dtypes` to gain insights into the data's structure and characteristics.

### 2.3 Cleaning Dataset

Here, we clean the dataset by removing unused columns like name, cabin, and ticket numbers. We also identify and handle null values. The 'cabin' column, with a majority of missing values, is dropped.

### 2.4 Exploratory Data Analysis

Exploratory Data Analysis (EDA) is a crucial phase in understanding the relationships between various features. It involves a blend of data visualization and analysis to highlight correlations, patterns, and insights within the dataset.

### 2.5 Model Training

In this step, we employ various machine learning models to train the dataset. The data is split into training and testing sets, and these models are used to predict the survival outcomes of passengers.

### 2.6 Data Visualization

Data visualization is employed to summarize the model performance. A bar plot is used to display the accuracy of different models, aiding in the comparison of their performance.

### 2.7 Analysis Conclusion

The analysis concludes with insights drawn from the modeling results. It is determined that the Decision Tree Classifier model achieved the highest accuracy at 78%.

## 3. Getting Started

To get started with this project, you will need Python and the following libraries installed:

- NumPy
- Pandas
- Seaborn
- Scikit-Learn

## 4. Usage

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook in Google Colab or any other compatible environment.
3. Execute each cell in the notebook to reproduce the analysis.

Feel free to use this repository to explore the Titanic survival prediction analysis and adapt it for your own projects. 
If you have any questions or suggestions, please don't hesitate to reach out.

Happy analyzing!
