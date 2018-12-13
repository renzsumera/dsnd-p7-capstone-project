# Create a Customer Segmentation Report for Arvato Financial Solutions

There is a blog post for this project hosted in [Medium](

## Table of Contents:

1. [Installation](#installation)
2. [Summary](#summary)
3. [Data Files](#files)
4. [Instructions](#instructions)

## Installation: <a name="installation"></a>

Aside from the libraries included in the Anaconda distribution for Python versions 3.*, the following have been installed for this Jupyter notebook.

1. [progressbar](https://pypi.org/project/progressbar/)
2. [XGBRegressor](https://xgboost.readthedocs.io/en/latest/python/python_api.html)

## Summary: <a name="summary"></a>

This challenge was provided by Arvato Financial Solutions for the Udacity Data Science Nanodegree Program for Term 2. This is one of the possible capstone projects.

There were three major steps in the project:

1. **Customer Segmentation Report** - This analyzed demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. This used unsupervised learning techniques to perform customer segmentation, identifying the parts of the population that best describe the core 
customer base of the company. 

2. **Supervised Learning Model** -This used the previous analysis to build a machine learning model that predicts whether or not each individual will respond to the campaign.

3. **Kaggle Competition** - This used the chosen model to make predictions on the campaign data as part of a Kaggle Competition and see how it measures up to the other fellow students.

## Data Files: <a name="files"></a>

There were four data files provided by Arvato for this project. The last file was created by the user. As part of the terms and conditions of Arvato, the files cannot be shared in this repository. However, they can be described below.

1. `azdias.csv` - Demographics data for the general population of Germany - 891,211 persons (rows) x 366 features (columns)

2. `customers.csv` - Demographics data for customers of a mail-order company - 191,652 persons (rows) x 369 features (columns)

3. `mailout_train.csv` - Demographics data for individuals who were targets of a marketing campaign (train) - 42,982 persons (rows) x 367 (columns)

4. `mailout_test.csv` - Demographics data for individuals who were targets of a marketing campaign (test) - 42,833 persons (rows) x 366 (columns)

5. `feat_info.csv` - Contains a summary of properties for each demographics data column created by the user - 366 features (rows) x 4 (columns)

## Instructions: <a name="instructions"></a>

1. Since the data files are not available publicly, the Jupyter notebook is just for exploration. An HTML file has been provided as another means to check the notebok.

2. There are two spreadsheets provided in the workspace. `DIAS Information Levels - Attributes 2017.xlsx` is a top-level list of attributes and descriptions, organized by informational category. The other `DIAS Attributes - Values 2017.xlsx` is a detailed mapping of data values for each feature in alphabetical order.

3. The Jupyter notebook produced a file called `submissions.csv` which was submitted to Kaggle for the in-class [competition](https://www.kaggle.com/c/udacity-arvato-identify-customers).



