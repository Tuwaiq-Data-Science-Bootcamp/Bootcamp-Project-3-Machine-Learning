
# Project 3

# Introduction (problem or your goal):
 Airlines prioritize customer satisfaction at all times. Customers who are dissatisfied or disengaged naturally result in fewer passengers and less revenue. It is important that customers have a positive experience every time they travel. Flights that are on time, have good in-flight entertainment, and provide good food and drinks  are obvious contributors to a positive experience and enhanced loyalty. our goal is to predict airlines passenger satisfaction and identify what factors that affect the  satisfaction the most.
 
# Team members: 
- Ghadah Alabduljabbar
- Shahad Alsaif
- Asma Almalki

# Dataset Overview and Source:
 The dataset contains an airline passenger satisfaction survey, and it shows What factors are highly correlated to a satisfied (or dissatisfied) passenger.
## Source : https://www.kaggle.com/datasets/johndddddd/customer-satisfaction



# ML Result (A table represents the final results of ML models):

|                             |   K-Nearest Neighbors |   Decision Tree |   Naive Bayes |   Random Forest |   Logistic Regression |
|:----------------------------|----------------------:|----------------:|--------------:|----------------:|----------------------:|
| train_test_split            |               73.455  |         93.281  |       81.4778 |         95.1173 |               82.6853 |
| cross_val                   |               69.3702 |         71.7132 |       75.6188 |         73.6931 |               75.8043 |
| train_test_split_Normalized |               91.7924 |         93.2925 |       81.737  |         95.0942 |               82.6853 |
| cross_val_Normalized        |               71.436  |         71.456  |       75.6188 |         73.6896 |               75.8024 |
