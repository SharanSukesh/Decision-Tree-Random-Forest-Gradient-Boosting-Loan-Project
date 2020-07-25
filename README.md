# Loan Repayment Prediction using Decision Tree, Random-Forest and Gradient-Boosting models

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Dataset used](#dataset-used)
* [Built on](#built-on)
* [Models](#models)
* [Model Training and Testing Steps](#model-training-and-testing-steps)
* [Ackowledgements](#ackowledgements)
* [Author](#author)


## About the Project 
Exploratory Data Analysis of LendingClub dataset to fit various tree-based models and answer the problem statement.</br></br>
The python notebook __"02-Decision Trees and Random Forest Project"__ contains an initial EDA of data from the LendingClub and analyzes how different features impact the probability of a customer defaulting a loan payment. 

We fit various tree-based models on our data and see how well they perform. We will then compare their accuracy scores and other metrics to see which models performed the best. Our goal is to use Decision trees, Random Forests and Gradient boosting algorithms to predict Loan repayment probability but more so to compare how well they perform against each other.

## Libraries used 
* Numpy
* Pandas
* Matplotlib
* Seaborn
* sklearn

```bashimport numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
%matplotlib inline
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import classification_report,confusion_matrix 
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import RandomizedSearchCV
from sklearn.model_selection import GridSearchCV
from sklearn.ensemble import GradientBoostingClassifier
```

## Dataset used 
* __LendingClub__ - Loans Dataset

## Built with
* Jupyter Notebook

## Models:
1. Decision Tree
2. Random Forest
3. Gradient Boosting

## Models Training and Testing Steps
1. Training the Models
2. Predicting the Test Data
3. Evaluating the Model using various metrics

## Ackowledgements
* <a href='http://www.lendingclub.com'>Lending Club</a> - Dataset

## Author - Sharan Sukesh
