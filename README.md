# Insurance Cross-Sell Prediction & Lead Scoring Analytics

## Overview
This project develops a machine learning-based lead scoring system to identify insurance customers who are more likely to respond positively to a cross-sell offer.

## Dataset
- 381,109 customer records
- 12 original variables
- Target variable: Response

## Workflow
1. Data understanding
2. Data quality checks
3. Exploratory Data Analysis
4. Feature preprocessing
5. Logistic Regression
6. Random Forest
7. Model comparison
8. Lead scoring
9. Customer priority segmentation

## Key Insights
- Customers without previous insurance had a much higher response rate.
- Customers with prior vehicle damage showed stronger interest.
- Customers with older vehicles had higher response rates.
- Certain policy sales channels performed significantly better than others.

## Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.641 | 0.251 | 0.974 | 0.399 | 0.839 |
| Random Forest | 0.701 | 0.281 | 0.925 | 0.431 | 0.855 |

Random Forest was selected as the final model.

## Lead Scoring Results
- High Priority Response Rate: 33.25%
- Medium Priority Response Rate: 16.49%
- Low Priority Response Rate: 0.80%

## Technologies
Python, Pandas, Matplotlib, Scikit-Learn, Machine Learning
