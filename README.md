## About this repository

This repository contains a machine learning model that detects fraudulent transactions.

The training of this model can be found in the python notebook named `model_training.ipynb`

## About the notebook

The notebook contains two parts:

* EDA (Exploratory Data Analysis): Where we perform a statistical analysis of our dataset
* Model training: We select the relevant models for our problem and optimize the hyperparameters of the model

## About the dataset

The dataset is a .csv file containing transactions made by credit cards in September 2013 by European cardholders.

It was found on the site kaggle.com, you can find it [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## How to replicate the results

The dataset is not in the repository, however, it is available in the latest release. Please ensure you have the file in the same folder as the notebook and do not change the name of the csv file.

To execute the notebook, you need Python 3 and the following libraries:

* matplotlib
* numpy
* pandas
* seaborn
* sklearn

You can install these libraries using the following command:

`pip install requirements.txt`

requirements.txt is the txt file containing the names of the necessary libraries
