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

Out of all the models implemented in this project, KNN gives the best performance with standardised data, as both F1 score and accuracy are at their maximum in that case.

# Accuracy on KNN - Classifier
![image25](https://github.com/ihdavjar/Prml_Major_Project/assets/95899338/b84bbb2f-d815-4d34-87b1-d06925a50c80)

# F1 Score on KNN - Classifier
![image20](https://github.com/ihdavjar/Prml_Major_Project/assets/95899338/a80746a7-05ab-4c2d-843c-1e687260537f)


&rarr; [Report.pdf](https://github.com/ihdavjar/Prml_Major_Project/blob/8c564acfebcda30ea10f917a2200b6ea2abb9997/Report.pdf) contains detailed explaination of this project along with various visualisation.

&rarr; [major_project.ipynb](https://github.com/ihdavjar/Prml_Major_Project/blob/8c564acfebcda30ea10f917a2200b6ea2abb9997/major_project.ipynb) contains the implementation of the above discussed clustering.
