# Machine-Learning-Trading-Bot
This code is creating a machine learning algorithm that will create trading signals based on the inputs that are coded into it. We can use whatever machine learning model we want, but here I am using a Logistic Regression model, but it would not be difficult to change these models up and use a different one.

## Technologies
In this code, I am using Pandas, Numpy, Pathlib, Hvplot, Matplotlib, and Sklearn.

## Installation Guide
import pandas as pd,
import numpy as np,
from pathlib import Path,
import hvplot.pandas,
import matplotlib.pyplot as plt,
from sklearn import svm,
from sklearn.preprocessing import StandardScaler,
from pandas.tseries.offsets import DateOffset,
from sklearn.linear_model import LogisticRegression,
from sklearn.metrics import classification_report

## Usage
This can be used to aid in trading, as it will alert the user based on the signal that it is fed. This bot can be connected to an API, which would allow for the bot to automatically make trades for the user. This is a great tool, because you can also plot the charts, showing how machine learning model predicts.

## Contributors
I am the main contributor for this code.
