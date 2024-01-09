# House Price Prediction

## Overview

This project focuses on predicting house prices using machine learning regression models. The dataset used for training and testing the models is loaded from a CSV file named 'data.csv'. The code involves data cleaning, preprocessing, visualization, and model training.

## Prerequisites

Before running the code, make sure you have the following libraries installed:

- pandas
- numpy
- plotly
- seaborn
- matplotlib
- scipy
- scikit-learn

You can install these libraries using the following command:

```bash
pip install pandas numpy plotly seaborn matplotlib scipy scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone <repository_url>
cd <repository_directory>
```

2. Ensure your dataset is in the root directory and named 'data.csv'.

3. Run the 'house_price_prediction.ipynb' notebook or the Python script.

## File Structure

- **house_price_prediction.ipynb**: Jupyter Notebook containing the code.
- **house_price_prediction.py**: Python script with the same functionality as the notebook.
- **data.csv**: Dataset containing house-related information.
- **README.md**: This file.

## Data Cleaning and Preprocessing

The dataset is loaded using pandas, and missing values are handled appropriately. Outliers are removed using z-scores. Categorical variables are encoded, and unnecessary columns are dropped. The dataset is then split into training and testing sets.

## Exploratory Data Analysis (EDA)

EDA is performed using Plotly Express for visualizations. Bar plots, scatter plots, and pie charts are used to explore the relationships between different features and the target variable (house prices).

## Model Training

Three regression models are trained:
- Linear Regression
- Support Vector Regression (SVR)
- Random Forest Regression

Data is standardized using StandardScaler, and the models are trained with the training set.

## Model Evaluation

Model performance is evaluated using R-squared (R2) scores and Mean Squared Error (MSE) on both the training and testing sets.

## Results

The results of each model, including R2 scores and MSE, are printed to the console.

## Acknowledgments

This project is for educational purposes and was created as part of a machine learning course. The dataset used is fictional and for demonstration purposes only.

---
