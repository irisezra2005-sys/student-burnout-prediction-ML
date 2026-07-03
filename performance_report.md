## Project Title
Impact of AI on Students - Machine Learning Model Evaluation

## Objective
The Objective of this project was to build and evaluate machine learning models to predict the Burnout Risk Level of students using the preprocessed AI Student Impact dataset

## Models Used
- Logistic Regression
- Decision Tree Classifier
- Tuned Decision Tree(GridSearchCV)

## Performance Comparision
# Model
- Logestic Regression
. Accuracy:- 0.5112
. Precision:- 0.5306280724421037
. Recall:-  0.5112
. F1-Score:-  0.5113716134269911

- Decision Tree
. Accuracy:- 0.4324
. Precision:-  0.4323864944127819
. Recall:- 0.4324
. F1-Score:-  0.43238876064700205

- Tuned Decision Tree
. Accuracy:- 0.5236
. Precision:-  0.5431349056889571
. Recall:-  0.5236
. F1-Score:- 0.5210295657186985

## Hyperparameter Tuning
GridSearchCV was applied to the Decision Tree Classifier to identify the optimal hyperparameters. The tuned model showed improved performance compared to the baseline model
- Best Parameters:
. Criterion:- Gini
. Max Depth:- 5 
. Min Samples Split:- 2

## Conclusion
The machine learning models were successfully trained and evaluated using Accuracy, Precision, Recall, and F1-Score. After hyperparameter tuning, the Decision Tree model achieved improved performance and 
was selected as the final model for predicting students Burnout Risk Level. The results demonstrate that machine learning techniques can effictively classify burnout risk based on student related features

  
