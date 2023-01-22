# Music-Genre
#Music Genre classification project 
steps : 
1- LOAD THE DATA 

2- DATA VISUALIZATION TO GAIN INSIGHTS : 

explore missing data ,correlations between features , Identifying outliers , distribution of a data : normal or skewed ,detect categorical features

3- DATA CLEANING :

  a) drop columns which not important 

  b) fill null values with the median using SimpleImputer

  c) handling skewness using :square root transform , cube root transform , log transform , reciprocal transform 

  d) use SMOTE to make data balanced

4- MODEL BUILDING :

in this step I use lazypredict on several algorithm to choose the one with the  highest accuracy and F1_Score 

5- FINE TUNE THE MODEL :

in this srep I  use OPTUNA to select the best hyperparameter for my algorithm

6- TRY THE MODEL ON TEST SET 

﻿

