# Udacity_Capstone
A Repository for the Capstone project of the Udacity Data Scientist Nanodegree

# Project Motivation
The motivation of this project is based on a Udacity-Nanodegree project. The task is to develop a Data Science project based on ones own preference and to write a Blogpost on the results of said Data Science project. 

I choose a dataset which contains observations on various habits and health-metrics as well as the presence or absence of a cardiovascular disease (CVD) available on Kaggle. The general goal behind my project is to experiment on whether based on very commonly available data, it is possible to build a somehow trustworthy classifier for detecting risk-patients that currently or likely will encounter a CVD in near future.

A Blogpost can be describing my findings, can be found [here](https://medium.com/@mdk_57697/efforts-made-in-creating-a-generalized-classifier-for-cardiovascular-diseases-1927c1c6952)

# Installations
This project was initialized in a Jupyter Notebook using Python 3. Dependencies are implemented within the Notebook itself. 
Further Notebook-external dependencies are non existant and hence will not be covered.

- pandas 
- matplotlib.pyplot 
- seaborn 
- numpy
- scipy
- sklearn.preprocessing: StandardScaler
- sklearn.model_selection: train_test_split
- sklearn.linear_model: LogisticRegression
- sklearn.neighbors: KNeighborsClassifier
- sklearn.tree: DecisionTreeClassifier
- sklearn.svm: SVC
- sklearn.ensemble: RandomForestClassifier
- sklearn.neural_network: MLPClassifier
- sklearn.metrics import: accuracy_score
- sklearn.metrics import: recall_score, precision_score
- sklearn.model_selection: cross_validate, RepeatedKFold
- sklearn.model_selection: GridSearchCV
- sklearn.model_selection: RandomizedSearchCV

# File Descriptions

cardio_train.csv: Dataset used for this project in .csv format.

Udacity_Capstone.ipynb: Jupyter Noptebook in Python, that was used for analysing the dataset using the process of CRISP-DM.

# How to interact with the repositories content

For further working on the Jupyter Notebook, you can either download it and work locally with it, or use the Python Notebook from within the online version of [Jupyter](https://jupyter.org/try).

You furthermore can extract the Datasets I used from the .csv file within this repository.

## Author
The Author of this Notebook is the GitHub User MDK1192, usage for own interests of my files is granted.

## Acknowledgements
I would like to thank Udacity for giving an introduction into the topics needed to create this repositories content, as well as Kaggle for making the data openly accessible for usage.



