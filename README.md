# Learning Regression Models using Python

This guide will take you from an absolute beginner to an intermediate user in building Regression models using Python. We'll start with the basics and move towards more advanced topics.

## Table of Contents
1. Setting up the environment
2. Importing libraries and loading dataset
3. Exploratory Data Analysis (EDA)
4. Understanding the assumptions of regression
5. Preprocessing the data
6. Building a Simple Linear Regression model
7. Building a Multiple Linear Regression model
8. Validating the assumptions of regression
9. Evaluating the model

## Setting up the environment
First, install Python, Jupyter Notebook or an Integrated Development Environment (IDE) like PyCharm or Visual Studio Code. 
Then, create a virtual environment for managing dependencies.


'''
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score
'''