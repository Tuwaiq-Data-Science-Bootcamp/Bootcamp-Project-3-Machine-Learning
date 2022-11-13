### Team Members:
1- Hadeel Aldhafiri
2- Alanoud Alrashed
3- Rawan Alhalwan


Introduction:

Problem: X of people has a plan to start his business which is phone store, He needs help to specify phone prices. Phone prices are determined based on different features, such as: Memory, screen size, battery power, ram, ..etc.

Goal: To build 3 ML models to predict phone prices based on the phone different features, such as: Memory, screen size,..etc

To Estimate or predict the prices, we use three different machine learning algorithms, which are:
		1- Logistic regression
		2- K-Nearest Neighbor Classifier 
		3- Random Forest Classifier

Also, we adopt two different splitting techniques, which are:
		1- Train-test split
		2- Cross-Validation split


Dataset: Mobile Price Prediction
Overview: The Dataset contains 21 columns and 2000 rows
Source: Kaggle 


Results:

* for Test-train split, the accuracy score for each model was as following:
1- Logistic Regression: 77.8 %
2- K-Nearest Neighbors (KNN): 91.8 %
3- Random Forest Classifier: 87.6 %

* On the other hand, Cross-validation split has achieved the following accuracy scores:
1- Logistic Regression: 77.2 %
2- K-Nearest Neighbors (KNN): 92.4 %
3- Random Forest Classifier: 88.3 %


Final Conclusion and Recommindations:

Cross Validation is an important step,
1- To prove the results.
2- Gives us much more information about our algorithm performance.
3- Discover the case when modle results are good but not real.
