## Abstract

This study aimed to construct a supervised learning model for classifying medical subjects into two groups based on their Parkinson's disease status. The dataset comprises a variety of audio parameters extracted from voice recordings of patients. The dataset is skewed, as 23 of the total 31 patients in the recording are positive. As a result, we used both accuracy and the F1 score as measures. We've employed dimensionality reduction and feature selection techniques and then trained multiple models on them.

## Introduction
In this investigation, we attempted to categorise patients as either healthy or sick using a variety of supervised learning algorithms. Initially, we employed linear discriminant analysis (LDA) to determine whether or not the data were linearly separable. Then, we utilised principal component analysis (PCA) with naive Bayes classification to determine the efficacy of this method.

Then, we attempted the sequential forward feature selection algorithm with the Naive Bayes classifier as the foundational model. 
Then, we attempted to identify the optimal feature using the sequential forward feature selection algorithm and the Decision Tree classifier as the base model. On the resulting datasets, we then evaluated the precision of various models.

## The various models used in this project are
* Gaussian NB
* Decision Tree Classifier
* Bagging with the Decision Tree Classifier as the base ensemble
* AdaBoost with the Decision Tree Classifier as the base ensemble
* Xgboost Classifier
* Neural Network 
* Support Vector Machine
* KNN Classifier


## Result and Discussion
Current problem is a clustering problem. Several clustering algorithms were imployed on PCA data and the original data and their outputs were compared. It was evident that PCA doesn't bring any notable changes to the clustering problem.

&rarr; [Report.pdf](https://github.com/ihdavjar/CSL2050_Minor_Project/blob/b9b0829c6594c0f99f119708bcacf8a74df04473/Report.pdf) contains detailed explaination of this project along with various visualisation.

&rarr; [minor_project.ipynb](https://github.com/ihdavjar/CSL2050_Minor_Project/blob/b9b0829c6594c0f99f119708bcacf8a74df04473/minor_project.ipynb) contains the implementation of the above discussed clustering.
