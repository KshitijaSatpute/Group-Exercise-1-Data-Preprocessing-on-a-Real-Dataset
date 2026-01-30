# Group-Exercise-1-Data-Preprocessing-on-a-Real-Dataset

Project Description  
This project focuses on applying basic data preprocessing techniques to a real
dataset. The aim is to understand how raw data is cleaned and prepared before it
can be used for machine learning.

Dataset Information  
Dataset Name: Adult Census Income Dataset  
Source: UCI Machine Learning Repository  
https://archive.ics.uci.edu/ml/datasets/adult  

Description:  
The Adult dataset contains information about people such as age, education,
occupation, and working hours. The task is to predict whether a person earns
more than 50K USD per year using numerical and categorical features.

Group Members and Contributions  

Janvi Mahapadi  
Handled the main implementation of the project. Responsible for loading the
dataset, handling missing values, scaling numerical features, handling noise,
and integrating the complete notebook.

Devendra Ghawat  
Worked on detecting and handling outliers using the Z-score method and capping
extreme values.

Kshitija satpute

Worked on feature selection using correlation and helped with documentation
and final review of the project.

Tasks Performed  
Missing values were handled using mode imputation.  
Numerical features were scaled using Z-score standardization and Min–Max
normalization.  
Artificial noise was added to one feature and smoothed using a rolling mean.  
Outliers were detected using Z-score and handled using capping.  
Feature selection was performed using a filter-based correlation method.
