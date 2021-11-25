# ML-Final-Project
Final Project Machine Learning


## Problem Statement
The main idea of the project is to classify whether a statement is sexist, not sexist or neutral. The main motivation is to identify the sexist statements
that are commonly observed in workspaces. In the project we are trying to classify these statements using various ML algorithm and parallely comparing which algorithm
gives the best accuracy.

## Dataset
The dataset is obtained from kaggle and contains classified data on sexist and not sexist statementsf

## Preprocessing
In the preprocessing step we cleaned the data and removed missing values. Then we used BOW(bag of words) and TF-IDF(Term frequency inverse document frequence) for 
feature extraction and finally trained models on the obtained preprocessed data.

## Models
1. Logistic Regression on BOW and TF-IDF
3. Naive Bayes on TF-IDF Data
2. Random Fprest on TF-IDF Data
3. SVM with various kernels on TF-IDF Data

## Requirments
1. pandas
2. matplotlib
3. nltk
4. scikit-learn

## How to Run
Download the ipynb file and load the dataset folder. Then run each cell to obtain output
