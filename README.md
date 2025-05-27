# OLA Driver Attrition Analysis 🚗

## Problem Statement
Recruiting and retaining drivers is a critical challenge for Ola. High driver churn impacts organizational morale and makes acquisition more expensive than retention. This analysis predicts driver attrition using ensemble learning to provide actionable retention strategies.

## Dataset Overview
- **Period**: Monthly driver data (2019-2020)
- **Features**: Demographics (age, gender, city, education), performance metrics (quarterly rating, business value, grade), and tenure information
- **Target**: Predict whether a driver will leave the company

## Key Findings
- **Attrition Rate**: 67.9% (critical retention problem)
- **Top Predictors**: Last Quarterly Rating, Business Value, Rating Improvement
- **Best Model**: Decision Tree (87.3% F1-score, 82.2% accuracy)
- **Key Insight**: Performance matters more than demographics for retention

## Recommendations
1. **Priority**: Income growth programs (93% retention when income increases)
2. Improve quarterly rating systems
3. Target Grade 1 drivers (80% attrition rate)
4. Deploy ML-based early warning system

## Technologies Used
Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn
