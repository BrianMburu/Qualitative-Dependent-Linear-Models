## Comparison of Three Qualitative Dependent Models on Diabetes Dataset

This Jupyter notebook compares the performance of three qualitative dependent models on the diabetes dataset downloaded from Kaggle. The three models are the linear probability model, the logic model, and the probit model. The following metrics are used to investigate the performance of the three models:

1. Accuracy
2. Precision
3. Recall
4. F1-Score
5. Area under the Receiver Operating Characteristic Curve (AUC-ROC)

## Dataset

The diabetes dataset used in this analysis contains medical information about patients and their diabetes status. It has 768 observations and 9 features including age, BMI, blood pressure, and glucose levels.

## Models

The three models used in this analysis are:

1. Linear probability model - A simple model that predicts a binary outcome using a linear combination of the independent variables.
2. Logic model - A model that uses logical rules to predict a binary outcome.
3. Probit model - A model that predicts a binary outcome using a probit function, which is a cumulative distribution function of a normal random variable.

## Performance Evaluation

The performance of the three models is evaluated using the following metrics:

- Accuracy - The proportion of correctly classified cases out of the total number of cases.
- Precision - The proportion of true positives out of the total number of positive predictions.
- Recall - The proportion of true positives out of the total number of actual positives.
- F1-Score - A weighted average of precision and recall that takes both false positives and false negatives into account.
- AUC-ROC - A measure of the overall performance of a binary classifier.

## Conclusion

This notebook provides a comparison of the performance of three qualitative dependent models on the diabetes dataset. The results of the analysis can be used to inform the selection of the most appropriate model for predicting diabetes status in future studies.
