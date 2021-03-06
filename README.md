# Predicting West Nile Virus in the City of Chicago
GA-DSI Project 4
Kaggle Competition: Top Kaggle Score 0.76

Mikhail Naumov, William Peterson, Chrissy Smiley, Claudia Greco
Data Science Immersive, General Assembly, 9 March 2018

## Table of Contents

- [Repository Contents](#repository-contents) - Description of this repository's contents
- [Data Description](#data-description) - Description of dataset
- [Project Summary](#project-summary) - Summary of the project's goals
- [Analysis Explanation](#analysis-explanation) - Explanation of the project's methods and analysis
- [Project Concepts](#project-concepts) - Lists the used concepts for this project
## Repository Contents

| FILENAME |  DESCRIPTION |
|:---------:|:-----------:|
| [README](./README.md) | Project description |
| [Deprecated](./Deprecated) | Previous/Removed work |
| [Input](./input) | Input Files |
| [Model Selection_final](.Model_Selection_final.ipynb) | Notebook Gridsearched Classifers |
| [Model_Starter_RS_2](.Model_Starter_RS_2_.ipynb) | SandBox Notebook |
| [Pro_Test.csv](Pro_Test.csv) | Preprocessed Kaggle Submission Input |
| [Pro_Train.csv](Pro_Train.csv) | Preprocessed Training Inputs |
| [ProcessPipeline.py](ProcessPipeline.py) | Weather/Insect/Water Source Preprocessor |
| [allDF.pickle](AllDF.pickle) | For AWS, dataframes |


## Data Description

Weather observations from Chicago O'Hare and Chicago Midway airports for 2007-2014. 
Mosquito abatement spraying records for 2011-2013, noting where and when sprays took place.
Mosquito trap observations on a weekly basis, with trap location, the mosquito species, mosquitoes capture counts, and presence of West Nile Virus in the sample.

For more information on the datasets is available here(https://www.kaggle.com/c/predict-west-nile-virus/data).

## Project Overview

The goal of this project is to predict whether West Nile Virus will be present in the trap observation.

## Analysis Explanation



## Project Concepts

Data munging; gradient boosting; gridsearch; cross-validation; haversine distance; amazon web services; exploratory data analysis; k-nearest neighbors; unbalanced classes; random forest classifier; extra trees classifier; adaboost; feature engineering; auc-roc.
