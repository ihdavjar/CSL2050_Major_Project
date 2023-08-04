## Problem Statement

This study aimed to construct a supervised learning model for classifying medical subjects into two groups based on their Parkinson's disease status. The dataset comprises a variety of audio parameters extracted from voice recordings of patients. The dataset is skewed, as 23 of the total 31 patients in the recording are positive. As a result, we used both accuracy and the F1 score as measures. We've employed dimensionality reduction and feature selection techniques and then trained multiple models on them.

## Machine Learning Pipeline
<p align="center">
   <img width="562" alt="image22" src="https://github.com/ihdavjar/CSL2050_Minor_Project/assets/95899338/62bc558e-7ecd-4fc7-a6c6-d929b0834f0a">
</p>

## Result and Discussion
Current problem is a clustering problem. Several clustering algorithms were imployed on PCA data and the original data and their outputs were compared. It was evident that PCA doesn't bring any notable changes to the clustering problem.

&rarr; [Report.pdf](https://github.com/ihdavjar/CSL2050_Minor_Project/blob/b9b0829c6594c0f99f119708bcacf8a74df04473/Report.pdf) contains detailed explaination of this project along with various visualisation.

&rarr; [minor_project.ipynb](https://github.com/ihdavjar/CSL2050_Minor_Project/blob/b9b0829c6594c0f99f119708bcacf8a74df04473/minor_project.ipynb) contains the implementation of the above discussed clustering.
