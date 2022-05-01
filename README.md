# Credit_Risk_Analysis

## Overview of Project
&nbsp;&nbsp;&nbsp; The purpose of this project is to apply supervised machine learning to solve credit risk amongst loans.  Using the credit card dataset from LendingClub, various techniques were used to train and evalute models with unbalanced classes.  In summary, an evaluation will be done on the performance of the models to see whether or not they should be used to predict credit risk.

## Resources
&nbsp;&nbsp;&nbsp;* Data Source: LoanStats_2019Q1.csv
<br />
&nbsp;&nbsp;&nbsp;* Software: Jupyter Notebook

## Results
&nbsp;&nbsp;&nbsp; In all six machine learning models a balanced accuracy scored, confusion matrix, and imbalanced classification report were produced.  Here we see how accurate the models are at predicting credit risk.  The balanced accuracy score is used to identify the success rate of the model.  A confusion matrix is a summary of prediction results on a classification problem.  The columns that will be singled out from the imbalanced classification report will be precision(pre), recall(rec), and f1. Precision measures the model's accuracy in classifying a sample as positive.  Recall is a metric that quantifies the number of correct positive predictions made out of all positive predictions that could have been made. The F1 score is a weighted harmonic mean of precision and recall such that the best score is 1.0 and the worst is 0.0.  The results of the different machine learning models are as follows:

1) Naive Random Oversampling

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Balanced Accuracy Score: 62% success rate
<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Imbalanced Classification Report:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Precision: High Risk: 0.01/ Low Risk: 1.00
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recall:    High Risk: 0.62/ Low Risk: 0.68
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F1:        0.80
<br />
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/naive_random_oversampling/b_a_s.png" width="100%" height="200" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/naive_random_oversampling/c_m.png" width="100%" height="150" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/naive_random_oversampling/i_c_r.png" width="100%" height="275" /> 
</p>
<br />


2) SMOTE oversampling

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Balanced Accuracy Score: 64% success rate
<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Imbalanced Classification Report:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Precision: High Risk: 0.01/ Low Risk: 1.00
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recall:    High Risk: 0.63/ Low Risk: 0.66
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F1:        0.79
<br />
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/SMOTE_oversampling/b_a_s.png" width="100%" height="200" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/SMOTE_oversampling/c_m.png" width="100%" height="150" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/SMOTE_oversampling/i_c_r.png" width="100%" height="275" /> 
</p>
<br />


3) Undersampling

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Balanced Accuracy Score: 52% success rate
<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Imbalanced Classification Report:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Precision: High Risk: 0.01/ Low Risk: 1.00
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recall:    High Risk: 0.60/ Low Risk: 0.43
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F1:        0.60
<br />
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/undersampling/b_a_s.png" width="100%" height="200"" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/undersampling/c_m.png" width="100%" height="150" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/undersampling/i_c_r.png" width="100%" height="275" /> 
</p>
<br />


4) Combination (Over and Under) Sampling
                                                                                                                                          
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Balanced Accuracy Score: 62% success rate
<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Imbalanced Classification Report:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Precision: High Risk: 0.01/ Low Risk: 1.00
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recall:    High Risk: 0.68/ Low Risk: 0.57
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F1:        0.72
<br />
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/combined_sampling/b_a_s.png" width="100%" height="200" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/combined_sampling/c_m.png" width="100%" height="150" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/combined_sampling/i_c_r.png" width="100%" height="275" /> 
</p>
<br />


5) Balanced Random Forest Classifier

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Balanced Accuracy Score: 79% success rate
<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Imbalanced Classification Report:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Precision: High Risk: 0.04/ Low Risk: 1.00
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recall:    High Risk: 0.67/ Low Risk: 0.91
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F1:        0.95
<br />
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/balanced_random_forest_classifier/b_a_s.png" width="100%" height="200" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/balanced_random_forest_classifier/c_m.png" width="100%" height="150" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/balanced_random_forest_classifier/i_c_r.png" width="100%" height="275" /> 
</p>
<br />


6) Easy Ensemble AdaBoost Classifier

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Balanced Accuracy Score: 93% success rate
<br />
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Imbalanced Classification Report:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Precision: High Risk: 0.07/ Low Risk: 1.00
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recall:    High Risk: 0.91/ Low Risk: 0.94
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;F1:        0.97
<br />
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/ez_ensemble_adaboost_classifier/b_a_s.png" width="100%" height="200" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/ez_ensemble_adaboost_classifier/c_m.png" width="100%" height="150" />
  <img src="https://github.com/LaszloCravensworth/Credit_Risk_Analysis/blob/main/images/ez_ensemble_adaboost_classifier/i_c_r.png" width="100%" height="275" /> 
</p>
<br />


## Summary
&nbsp;&nbsp;&nbsp;The best performing supervised machine learning algorithm, for this project, was the Easy Esemble AdaBoost Classifier.  It has the highest success rate of 93%.  Precision and Recall scores for correctly identifying high risk loans was 7% and 91% respectively.  The F1 score was 0.97 meaning this model is nearly perfect for this project.  The worst performing model was the undersampling model. It had the lowest success rate of 52% and an F1 score of 0.60.  The recommended model to use is the Easy Esemble AdaBoost Classifier.
