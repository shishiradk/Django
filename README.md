
# Wine Quality Prediction

This repository contains a Jupyter Notebook for building a machine learning model to predict wine quality based on various features of the wine dataset.

## Overview

The project utilizes a dataset of red wine characteristics to analyze and predict wine quality. It employs Python libraries for data analysis, visualization, and machine learning to create a classification model.

## Dataset

The dataset used in this project is the **Red Wine Quality Dataset**, which includes 1,599 samples of red wine with the following features:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

## Features

- **Data Analysis and Visualization**: Statistical summaries and visualizations of the dataset are provided to understand the data distribution and relationships among features.
- **Data Preprocessing**: Includes handling missing values and preparing the dataset for training and testing.
- **Machine Learning**: A Random Forest Classifier is used to predict wine quality based on the input features.
- **Evaluation**: The accuracy of the model is measured using evaluation metrics like accuracy score.

## Prerequisites

Before running the notebook, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

You can install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
Usage
Clone the repository:
bash
git clone https://github.com/shishiradk/wine_quality_prediction.ipynb.git
Open the Jupyter Notebook:
bash
jupyter notebook wine_quality_prediction.ipynb
Follow the steps in the notebook to:
Load the dataset
Analyze the data
Train the model
Evaluate the results
Results
The model achieves an accuracy score based on the test dataset, allowing for the prediction of wine quality with a reasonable level of accuracy.

Acknowledgments
The dataset is publicly available on the UCI Machine Learning Repository.
The project uses open-source Python libraries for machine learning and data visualization.
License
This project is licensed under the MIT License. See the LICENSE file for details.
