# Great-Energy-Predictor-III
[![npm](https://img.shields.io/badge/langage-Python-blue.svg?style=flat-square)](https://www.python.org/)

## Description ##
This project is part of a kaggle competition

## libraries ##

install the libraries manually:

* [numpy](http://www.numpy.org/): _pip install numpy_
* [matplotlib](https://matplotlib.org): _pip install matplotlib_
* [pandas](https://pandas.pydata.org/): _pip install pandas_
* [seaborn](https://seaborn.pydata.org/): _pip install seaborn
* [sklearn](http://scikit-learn.org/stable/): _pip install sklearn_
* [tensorflow](https://www.tensorflow.org/): _pip install tensorflow_
* [random](https://www.random.org/): _pip install random


## Data visualization ##

The data visualisation section of this work helps us to have a better understanding of the different datasets as well as their feautures. The dataset presented has Five datasets:

*weather_train with (139773, 9) data
*train with (202116100, 4) data
*building_metadata with (1449,6) data
*weather_test with (277243, 9)) data
*test with (41697600, 4) data

## Data preparation ## 

This part is the most important part of the project.We used data preartion techniques such as dealing with missing values and remove redundant columns.Then To facilitate our task we start by merging all tables in two datasets train and test .

## Feature engineering ##

We need to deal with categorical variables.We have to encode primary_use variable using label encoding.There are 4 types of meters: 0 = electricity, 1 = chilledwater, 2 = steam, 3 = hotwater.After identifying outliers we opt for scaling very skewed features. Concerning the target variable meter_reading we opt for the log tranformation.


## How to run ##

* Execute: jupyter notebook or collab
* In the jupyter notebook web app, open the corresponding .ipynb file.

<b>Note:</b> If you are unfamiliar with [jupyter](http://jupyter.org/) notebook, you can visit their website to learn more:
* How to install: [http://jupyter.org/install](http://jupyter.org/install).
* How to run: [https://jupyter.readthedocs.io/en/latest/running.html](https://jupyter.readthedocs.io/en/latest/running.html).
* Full documentation: [https://jupyter.org/documentation](https://jupyter.org/documentation).


## Authors ##

* Dhia Dardour
  * Github: [dhiadardour](https://github.com/dhiadardour).
  * Email: [dhia.dardour](mailto:dhia.dardour@ensi-uma.tn).
  


