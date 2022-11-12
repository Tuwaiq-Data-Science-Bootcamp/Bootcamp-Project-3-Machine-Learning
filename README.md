# Fraudulent Job postings
We picked a Dataset about Job listings. It centers around whether a specfic job listing is real or fake.

## Team members
Meshari Alqahtani<br />
Yasser Alomar<br />
Khalid Alghamdy<br />

## Introduction & Overview

This dataset consists of 17000+ rows and 18 columns. It contains columns such as Job title, location, salary range and employment type. It also contains the column "fraudulent" which indicates whether the job listing is fake or not, which is the target of our model.<br /><br />
<br />
Source link : https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction<br />


## Results: 

  We used 3 ML Algorithms and below are the results of each one.

![image](https://user-images.githubusercontent.com/109832303/201484671-fcc28769-82a2-443b-bb9d-b57d8e4ad1f7.png)<br />

  Random forest in this case was not ideal, and that's due to the fact that overfitting has clearly occured.
  
  Seeing as how Crossvalidating the data gives us a more broad and general model. Our choice for the best model to pick would be the Decision Tree Algorithm when
  applied to crossvalidated data.

