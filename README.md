# machine_learning_project-supervised-learning

## Project Outcomes
- Supervised Learning: use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.
-
## Project Execution
#### exploratory data analysis
- created visualizations to see correlations, outliers and better understand the dataset

#### preprocessing and feature engineering
- Replacing zero values with mean of the columns for all the predictor variable column.
 - Scaled data in the predictor variable column.

#### training a machine learning model

Trained model through both logistic regression and Gradient Boosting Classifier.
Evaluated both models using various metrics that include accuracy, precision, Recall, F1-score and ROC_AUC.
Compareed both models on the results of the evaluation metrics

## Conclusion 
Both models have their strengths and weaknesses:
-Logistic Regression has a higher accuracy, precision, and ROC-AUC score, indicating better overall performance in terms of correctly predicting positive cases and distinguishing between classes.
-Gradient Boosting has a slightly higher recall, meaning it's slightly better at identifying actual positive cases, but it sacrifices some precision compared to Logistic Regression.

## Future Goals
- Explore more models to find a better fit
- Hypertunning dataset for better modelling
