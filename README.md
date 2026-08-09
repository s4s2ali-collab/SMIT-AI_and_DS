# SMIT-AI_and_DS
This is my first repository that I have created.
<br>
It is regarding SMIT Course Artificial Intelligence and Data Science.
<br>
Assignment No. 11

# California Housing Price Prediction

## Project Overview
This project builds a machine learning model to predict California housing prices
using the California Housing Dataset with 20,640 records.

## Dataset
- File: housing.csv
- Records: 20,640
- Features: 10 (including target)
- Target: median_house_value

## Steps Performed
1. Exploratory Data Analysis (EDA)
2. Missing Value Handling (Median Imputation)
3. Feature Engineering (3 new ratio features)
4. One-Hot Encoding (ocean_proximity)
5. Feature Scaling (StandardScaler)
6. Six Regression Models trained and compared
7. 5-Fold Cross Validation
8. Hyperparameter Tuning with GridSearchCV

## Models Compared
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree
- Random Forest (WINNER)
- Gradient Boosting

## Best Model
Tuned Random Forest — highest R² Score

## How to Run
1. Place housing.csv in the same folder
2. Open Regression_Assignment.ipynb
3. Run Kernel > Restart & Run All

## Requirements
pandas, numpy, matplotlib, seaborn, scikit-learn
Install: pip install pandas numpy matplotlib seaborn scikit-learn

------------------------------------------------------------------------------------------------

Assignment No. 12

# Framingham Heart Disease — 10-Year CHD Risk Prediction

## Overview
**Framingham Heart Study** dataset — cardiovascular disease prediction.  
Features include age, gender, smoking habits, blood pressure, cholesterol, and more.  
Target: `TenYearCHD` — whether the patient develops coronary heart disease in 10 years.

## Dataset
- File   : framingham.csv
- Records: 4,238
- Target : TenYearCHD — 10-Year Coronary Heart Disease Risk (0=No, 1=Yes)

## Models Applied
Logistic Regression, KNN, Naive Bayes, Decision Tree,
Random Forest, Gradient Boosting, SVM

## Best Model
Tuned Random Forest (GridSearchCV optimized)

## Steps Performed
1. EDA
2. Missing Values
3. Encoding
4. Feature Scaling
5. SMOTE
6. 7 Models
7. Confusion Matrix
8. ROC Curves
9. Cross Validation
10. Hyperparameter Tuning

## Requirements
pip install pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

## How to Run
1. Place framingham.csv in the same folder
2. Open Assignment_1_Framingham_CHD.ipynb
3. Run Kernel > Restart & Run All

------------------------------------------------------------------------------------------------

Assignment No. 13

# Heart Disease Prediction (UCI Dataset)

## Overview
**UCI Heart Disease Dataset** — classifying presence of heart disease.  
Features include age, sex, chest pain type (cp), resting BP (trestbps), cholesterol (chol), max heart rate (thalach), and more.  
Target: `target` — 0=No heart disease, 1=Heart disease present.

## Dataset
- File   : heart.csv
- Records: 1,025
- Target : target — Heart Disease Presence (0=No Disease, 1=Disease)

## Models Applied
Logistic Regression, KNN, Naive Bayes, Decision Tree, Random Forest, Gradient Boosting, SVM

## Best Model
Tuned Random Forest (GridSearchCV optimized)

## Steps Performed
1. EDA
2. Missing Values
3. Encoding
4. Feature Scaling
5. SMOTE
6. 7 Models
7. Confusion Matrix
8. ROC Curves
9. Cross Validation
10. Hyperparameter Tuning

## Requirements
pip install pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

## How to Run
1. Place heart.csv in the same folder
2. Open Assignment_2_Heart_Disease.ipynb
3. Run Kernel > Restart & Run All
