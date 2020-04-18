This project is part of the Udacity Nanodegree Programm. It analysis the famous Titanic Data set, which can be found under

https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html

The motivation of the project is to predict on certain factors, if somebody is going to die on the Titanic or not. 

The following libaries are used:

pandas for data analysis
matplotlib for plotting
sklearn for statistical analysis

The following import statements are used:

import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.metrics import confusion_matrix
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier
from sklearn import svm
from sklearn.metrics import average_precision_score
from sklearn.metrics import recall_score
from sklearn.metrics import f1_score

The analysis follows the CRISP-DM process

Business Understanding: What is the understanding behind. 

RMS Titanic was a British passenger liner operated by the White Star Line that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after striking an iceberg during her maiden voyage from Southampton to New York City. Of the estimated 2,224 passengers and crew aboard, more than 1,500 died, making the sinking one of modern history's deadliest peacetime commercial marine disasters. (https://en.wikipedia.org/wiki/RMS_Titanic)

The goal of the project is to estimate the dead of a person based on a data set of the passenges with serveral attributes. 


Data Understanding

Due the fact, that the data are already prepared, the data quality is very high. There are no n/a values and not so much outliers. 


Data Preparation

Data Preparation is mainly done by creating dummy variables.

Modeling

There are 3 methods of modelling used: SVM, Linear regression and Random Forrests. 

Evaluation

For Evaluation the F1 metric is used.


Deployment

See the data science blog articel on medium. 



















