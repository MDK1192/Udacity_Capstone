# Udacity_Capstone
A Repository for the Capstone project of the Udacity Data Scientist Nanodegree



# Project Motivation
The motivation of this project is based on a Udacity-Nanodegree project. Task is to write a Blogpost on the results of a Datamining process. In my case I choose the Cross Industry Standart Process for Data Mining (CRISP-DM). Furthermore, I choose a Dataset which contains poll-data from Stackoverflow users form 2017. The general goal behind my analysis is to characterize the average user of Stackoverflow using most frequent observation of features that give insights to the persona.

A Blogpost can be describing my findings, can be found [here](https://medium.com/@mdk_57697/efforts-made-in-creating-a-generalized-classifier-for-cardiovascular-diseases-1927c1c6952)

# Installations
This project was initialized in a Jupyter Notebook using Python 3. Dependencies are implemented within the Notebook itself. 
Further Notebook-external dependencies are non existant and hence will not be covered.

- pandas 
- matplotlib.pyplot 
- seaborn 
numpy
scipy
sklearn.preprocessing: StandardScaler
sklearn.model_selection: train_test_split
sklearn.linear_model: LogisticRegression
sklearn.neighbors: KNeighborsClassifier
sklearn.tree: DecisionTreeClassifier
sklearn.svm: SVC
sklearn.ensemble: RandomForestClassifier
sklearn.neural_network: MLPClassifier
sklearn.metrics import: accuracy_score
sklearn.metrics import: recall_score, precision_score
sklearn.model_selection: cross_validate, RepeatedKFold
sklearn.model_selection: GridSearchCV
sklearn.model_selection: RandomizedSearchCV

# File Descriptions

Dataset.rar: compressed folder with the Dataset used for this analysis in .csv format, as well as a description of the questions behind the given columns.

Udacity_Create_a_Blogpost.ipynb: Jupyter Noptebook in Python, that was used for analysing the dataset using the process of CRISP-DM.

# How to interact with the repositories content

For further working on the Jupyter Notebook, you can either download it and work locally with it, or use the Python Notebook from within the online version of [Jupyter](https://jupyter.org/try).

You furthermore can extract the Datasets I used from the Dataset.rar file within this repository.

## Author
The Author of this Notebook is the GitHub User MDK1192, usage for own interests of my files is granted.

## Acknowledgements
I would like to thank Udacity for giving an introduction into the topics needed to create this repositories content, as well as Stackoverflow/Kaggle for making the poll data openly accessible for usage.



