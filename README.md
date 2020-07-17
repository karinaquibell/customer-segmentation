# Arvato Customer Segmentation and Acquisition

This project is the capstone project for the Udacity Machine Learning Nanodegree in partnership with Arvato Financial Solutions, a Bertelsmann subsidiary.

## Project Overview
In this project, we are given general German population data as well customer population data for a mail order company in Germany. Each row in the datasets represent an individual and provides information about them, their household, their building and their neighborhood. 

Our first task was to use these two datasets and unsupervised learning techniques to describe which people in the general population are most like the customer base of the company.This insight can be used to develop a marketing strategy tailored to the companies’ target audience.

Our second task was to use a training dataset and supervised learning techniques to predict which individuals in a testing dataset are likely to respond to the marketing campaign and become customers. This would ensure that marketing campaigns are only sent to individuals who are most likely to respond in order to improve the ROI of the campaign.


## Datasets
The datasets are not publicly available. They were provided by Arvato Financial services subject to terms and conditions stating that it may only be used to complete the project and not for any other purpose.

## Notebook

The project is detailed in the ```Arvato Project Notebook.ipynb``` Python3 notebook.

The following libraries need to be imported:

- pandas
- numpy
- matplotlib
- seaborn
- os
- time
- pickle
- sklearn
- xgboost
- sys

To install xgboost in a notebook instance use either one of the below.

Using conda:
```python
!conda install --yes --prefix {sys.prefix} xgboost 
```
Using pip:
```python
!{sys.executable} -m pip install xgboost
```

#### Part 0: Get to Know the Data
This section covers importing the data, exploring the data and preprocessing it.

#### Part 1: Customer Segmentation Report
This section covers dimensionality reduction using PCA and clustering to determine which parts of the general population are most like the cusotomer population.

#### Part 2: Unsupervised Learning Model
This section covers training a base model and exploring the ROC AUC scores of different base classifiers as well as the selection, tuning of parameters and refinement of chosen model.

#### Part 3: Kaggle Competition
This section covers the creation of a Kaggle submission file from the predictions on the test data.

### Report
The final report, labelled ```Report.pdf``` gives detailed information about the techniques, methodologies and results of the project.

## License
[MIT](https://choosealicense.com/licenses/mit/)