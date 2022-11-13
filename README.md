# Bootcamp Project 3
## Team Member:
- Njood Ebraheem Aljuraid
- Arwa Saleh AlThiyab
- Yara khalid alrabah

## Introduction
 In this project we will explore and analysis then visualize dataset for bank customers in order to understand the relationship 
 between the customers and their loan payment difficulties, but our dataset needs cleaning because it have (unknown) data that's refer to 
 null values in specific columns. Then, we need to clarify the values in certain columns such as Gender to "Female","Male" instead of "F","M".After that,  data will be vislize in varity charts to presents the relationship and drive the important insights. Finally, we will build different models to train and predict the loan payment difficulties.


## Dataset Overview
dataset used in this project (loan dataset) from (Kaggle) https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter?select=application_data.csv
contains:
1.  CODE_GENDER
2.   FLAG_OWN_CAR
3.   FLAG_OWN_REALTY
4.   DAYS_EMPLOYED
5.   ORGANIZATION_TYPE
6.   NAME_CONTRACT_TYPE
7.   OCCUPATION_TYPE
8.   CNT_FAM_MEMBERS
9.   NAME_INCOME_TYPE
10.  REGION_POPULATION_RELATIVE
11.  NAME_HOUSING_TYPE
12.  NAME_FAMILY_STATUS
13.  NAME_EDUCATION_TYPE
14.  CNT_CHILDREN
15.  AMT_INCOME_TOTAL
16.  AMT_GOODS_PRICE
17.  AMT_CREDIT
18.  TARGET 
## final results of ML models
| Model          | Accuracy | Confusion Matrix               |
|----------------|----------|--------------------------------|
| Logistic Model | 0.91     |[[57764, 0], [ 5506 ,0]] |
| Decision Tree  | 0.82    |  [[51636 ,6152], [ 4690, 792]] |
| Random Forest  | 0.91     | [[57744 ,20], [ 5499 ,7]]   |