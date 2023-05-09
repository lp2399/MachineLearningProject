# MachineLearningProject
# Powerlifting Performance Analysis and Prediction:


This project focuses on analyzing and predicting powerlifting performance based on features such as age, sex, equipment, body weight, and weight class. We have used the open powerlifting dataset from [Kaggle Open Powerlifting](https://www.kaggle.com/datasets/open-powerlifting/powerlifting-database?select=openpowerlifting.csv), which contains powerlifting competition data from across the world. In this project, we performed exploratory data analysis, visualize some data features, and build machine learning models to predict a lift total of a powerlifter based on the previously listed features.
## How to run
There are a few ways to run the experiments and reproduce the results, you can follow any of the provided steps below:
Clone the repository:
```
git clone https://github.com/b2529361/MachineLearningProject.git
```
Install the required dependencies:
```
pip install -r dependencies.txt
```
Run the Jupyter Notebook or Python script containing the experiments:
```
jupyter notebook MachineLearningProject.ipynb
```
or
Use Google Collab [→](https://colab.research.google.com/drive/1ZtSMBYVzAlmgiSA6xc2KVjrpta1XtVOv?usp=sharing)


## Overview
Powerlifting is a strength sport consisting of three main lifts: squat, bench press, and deadlift. The goal is to lift as much weight as possible in each of these lifts. The dataset used is obtained from Openpowerlifting.org and includes various information such as the sex of the lifter, age, weight, the event they participated in, and the equipment they used.
## Project Goals
The primary goal of this project is to provide a baseline weight goal for a powerlifter to aim for during competition and to identify key trends and patterns in powerlifting.
## Data Cleaning and Preprocessing
The data cleaning process involves removing irrelevant data, converting column data to numeric data, and dropping duplicate rows and null values. The dataset is also filtered to include only raw and wraps as equipment. In the second part of data cleaning, a new data frame is created by keeping only the necessary columns and dealing with null values using imputation.
## Preliminary Data Exploration
The dataset contains many missing values and duplicate data points. Preliminary data exploration suggests that the sex and weight of a competitor is a crucial features in determining the total lift.
## Data Analysis
The data is split into training, testing, and validation sets. We look at the male and female subsets of the dataset. Descriptive statistics are utilized, and the data is visualized using Matplotlib and Seaborn. 
## Model Implementation
Three machine learning models are implemented: Linear Regression, K-Nearest-Neighbor, and Multi-layer Perceptron. These models are selected for their ability to capture complex relationships between features and the target variable.
## Training and Fine-tuning
Model performance is evaluated using mean absolute error, mean squared error, and r-squared. The K-Nearest Neighbor algorithm trained on the alternative data cleaning and processing approach performed the best.
## Results and Conclusion
The K-Nearest Neighbor model had the highest r-squared value and the lowest error rates, indicating the best performance among the three models. This model can be used to provide a baseline weight goal for powerlifters to aim for during a competition, and with further work, it can help identify key trends and patterns in powerlifting.
## Future Work
Future work could involve trying different data cleaning and processing methods, exploring other machine learning models, feature engineering, or fine-tuning the existing models further.

This page uses data from the OpenPowerlifting project, https://www.openpowerlifting.org.
You may download a copy of the data at https://data.openpowerlifting.org.
