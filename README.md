# income-classification
Machine learning comparison of Decision Trees, Random Forest, and Logistic Regression for classifying high-income individuals using the UCI Adult Income dataset.

# Adult Income Classification Project (Machine Learning)
 
## Project Overview
This project compares multiple machine learning models to classify individuals earning more than $50K per year using the UCI Adult Income dataset.
The goal is to identify high-income individuals while minimizing false positives, making precision the primary evaluation metric.
Models evaluated include:
- Decision Trees
- Random Forest
- Logistic Regression

## Dataset
The dataset comes from the UCI Machine Learning Repository:
Adult Census Income Dataset
It contains demographic and employment variables including:
- Age
- Education
- Occupation
- Marital Status
- Hours Worked Per Week
- Capital Gain / Loss
- Relationship Status

The target variable is:
- Income > $50K

## Modeling Approach
Each model was evaluated using:
- Predicted probabilities
- Threshold-based class predictions
- Confusion matrices
- Precision
- Recall
- F1 Score
- Accuracy

Because the business objective was to minimize false positives, precision was used as the primary evaluation metric.

## Model Performance
Model	Precision	Recall	F1	Accuracy
Random Forest	0.859	0.449	0.589	0.852
Decision Tree	0.755	0.506	0.606	0.845
Full Logistic Regression	0.729	0.599	0.657	0.853
Logistic Regression	0.590	0.256	0.357	0.782

## Key Findings
Random Forest achieved the highest precision (85.9%), making it the best model for minimizing false positives.
Full Logistic Regression produced the strongest F1 score, indicating a more balanced tradeoff between precision and recall.
Decision Trees performed well but were less precise than Random Forest.
Given the project's objective, Random Forest was selected as the preferred model.
