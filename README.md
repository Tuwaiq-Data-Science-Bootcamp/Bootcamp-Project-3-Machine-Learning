# Bootcamp-Project-3-Machine-Learning

Based on what you’ve learned until now, use numpy, pandas, matplotlib, seaborn and scikit-learn to create a project of your choosing. This project must at least satisfy the following minimum requirements:

- Choose a public dataset that needs to clean and preprocess.
- EDA
  - Apply the essential EDA steps: head, shape, info, describe, missing values
  - Display different charts that give an overview of  your data.
- Use two splitting methods (train-test split and cross-validation split).
- Choose three proper ML Algorithms.
- Report appropriate evaluation metrics for each model.
- Create a chart that compares the final results of your selected models.
- Write a final conclusion and recommendations (your interpretation of the results).
- Report your final conclusion and findings in one page (readme markdown file).
  - Team members.
  - Introduction (problem or your goal).
  - Dataset Overview and Source.
  - A table represents the final results of ML models.
- **[Nice to have - Optional]** Create an interactive dashboard using plotly.
- Due Date: Sun, 13 Nov, at 12:00 p.m.
- The Final presentation will be on Sunday (10 min for each group).

### Final Deliverables:
- Notebook file(.ipynb).
- Dataset file.
- README.md file.

# Stroke predection 
- I've built 3 machine learning model to try and predict if a person would get a stroke or not, What I observed was that all of the three prediction models had an unusual high predection and unusual similarity when it comes to specialy the KNN and the SVM models. 

- My recommendation is that the logistic regression could be the best fit for now.

# Dataset describtion
- Attribute Information
- 1) id: unique identifier
- 2) gender: "Male", "Female" or "Other"
- 3) age: age of the patient
- 4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- 5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- 6) ever_married: "No" or "Yes"
- 7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- 8) Residence_type: "Rural" or "Urban"
- 9) avg_glucose_level: average glucose level in blood
- 10) bmi: body mass index
- 11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
- 12) stroke: 1 if the patient had a stroke or 0 if not
- *Note: "Unknown" in smoking_status means that the information is unavailable for this patient
- https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

