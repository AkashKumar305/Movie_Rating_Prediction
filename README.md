# Movie Rating Prediction Project

## Overview
This project aims to build a predictive model that estimates the rating of Indian movies based on various features such as genre, director, and actors. The dataset used for this project is pulled from IMDb.com and contains information about Indian movies available on the platform. By analyzing historical movie data and leveraging regression techniques, the objective is to develop a model that accurately predicts the rating given to a movie by users or critics.

## Dataset
The dataset used for this project is sourced from IMDb.com and includes information about Indian movies. Prior to building the predictive model, the dataset undergoes a data cleaning process to handle missing values. This involves either removing missing values or imputing them with average values to ensure the dataset is ready for exploratory data analysis (EDA) and modeling.

## Objective
The main objective of this project is to develop a predictive model that estimates the rating of a movie based on various features. The model will utilize regression techniques to analyze the relationship between the movie's rating and its associated features such as genre, director, and actors. By accurately predicting movie ratings, this project aims to provide insights into the factors influencing movie ratings and enable better understanding of audience preferences.

## Key Steps
1. Data Collection: Obtain the dataset from IMDb.com containing information about Indian movies.
2. Data Cleaning: Clean the dataset by handling missing values through removal or imputation with average values.
3. Exploratory Data Analysis (EDA): Explore the dataset to gain insights into the distribution of features and their relationship with movie ratings.
4. Feature Engineering: Select relevant features and perform feature engineering to prepare the data for modeling.
5. Model Building: Develop a regression model using machine learning techniques to predict movie ratings based on selected features.
6. Model Evaluation: Evaluate the performance of the model using appropriate metrics and assess its ability to accurately predict movie ratings.
7. Interpretation: Analyze the model results to understand the factors influencing movie ratings and derive insights from the predictive model.

## Repository Structure
- `Movie dataset.csv`: Contains the dataset used for the project.
- `Movie Rating Prediction.ipynb`: Jupyter notebooks documenting the data cleaning, EDA, and modeling process.
- `final_model.joblib`: Model saved as Joblib type.
- `README.md`: Provides an overview of the project, its objectives, and key steps.

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Usage
1. Clone the repository to your local machine.
2. Navigate to the directory and run the Jupyter notebooks to execute the data cleaning, EDA, and modeling steps.
