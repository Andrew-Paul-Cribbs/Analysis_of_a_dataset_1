# Analysis_of_a_dataset_1
Analysis of a dataset
This is my first analysis of a real world dataset

## Overview

Objective: Predicting employee attrition in the workplace using the IBM HR employee dataset. The goal is to identify employees likely to leave so that companies can provide incentives to retain them, thereby saving significant training and resource costs.
Data Handling:
Reading in the data from a CSV file.
Evaluating and cleaning the data frame, noting that there were no missing or duplicate values.
Reducing the data frame to the top 1000 rows and selecting specific columns for analysis.
Regression Analysis:
Initially, performing a regression analysis using 'Age,' 'Total Working Years,' 'Years at Company,' and 'Years in Current Role' to predict 'Daily Rate.' You noted that these predictors were not good indicators for daily rate.
Logistic Regression for Attrition Prediction:
Dropping unnecessary columns and partitioning the data.
Running a logistic regression model to predict attrition, using predictors such as 'Age,' 'Total Working Years,' 'Years at Company,' 'Years in Current Role,' 'Years Since Last Promotion,' and 'Years with Current Manager.'
Evaluation:
The model was able to accurately predict employees who would leave 83% of the time based on the confusion matrix.
The AUC score was 0.7.
However, precision and recall for positive values were not predicted, which might indicate challenges in correctly identifying all actual attrition cases despite high overall accuracy.
Conclusion/Recommendation: The project concludes that logistic regression can accurately predict attrition, and you recommend that companies use these predictions to target at-risk employees with incentives to improve retention and save resources.
