# Data analysis, visualization and Classification model for income predicting of Adult or Census Income dataset
- Exploratory data analysis and visualization for the [Adult or Census Income dataset](https://archive.ics.uci.edu/ml/datasets/adult) from UCI Machine Learning Repository.
- Preprocessing, Training and evaluate classification machine learning models to predict income from test and train dataset.
  
## Python Packages:

* Scikit-learn
* Pandas
* Numpy
* matplotlib
* seaborn

## Classification Models Used:

* Gradient Boosting
* Support Vector Machine
* Random Forests
* Logistic Regressions
* k-Nearest Neighbours


## Performance Analysis

### Overall Performance Metrics
Model: Logistic Regression
              precision    recall  f1-score   support

           0       0.92      0.85      0.88     12434
           1       0.61      0.77      0.68      3846

    accuracy                           0.83     16280
   macro avg       0.77      0.81      0.78     16280
weighted avg       0.85      0.83      0.84     16280


 Model: Random Forest
              precision    recall  f1-score   support

           0       0.88      0.93      0.90     12434
           1       0.72      0.61      0.66      3846

    accuracy                           0.85     16280
   macro avg       0.80      0.77      0.78     16280
weighted avg       0.84      0.85      0.85     16280


 Model: SVM
              precision    recall  f1-score   support

           0       0.88      0.94      0.91     12434
           1       0.76      0.58      0.66      3846

    accuracy                           0.86     16280
   macro avg       0.82      0.76      0.78     16280
weighted avg       0.85      0.86      0.85     16280


 Model: KNN
              precision    recall  f1-score   support

           0       0.88      0.91      0.89     12434
           1       0.66      0.60      0.63      3846

    accuracy                           0.83     16280
   macro avg       0.77      0.75      0.76     16280
weighted avg       0.83      0.83      0.83     16280


 Model: Gradient Boosting
              precision    recall  f1-score   support

           0       0.89      0.95      0.92     12434
           1       0.79      0.60      0.69      3846

    accuracy                           0.87     16280
   macro avg       0.84      0.78      0.80     16280
weighted avg       0.86      0.87      0.86     16280


### Models accuracy comparation
![](<img width="691" height="541" alt="image" src="https://github.com/user-attachments/assets/2a33b532-dba6-4fe1-9171-e6b7f98cc6d8" />
)
