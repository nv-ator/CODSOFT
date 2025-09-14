# Titanic Survival Prediction 🚢

## Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning.  
The dataset includes passenger details such as age, gender, ticket class, and fare.  

## Dataset
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
- Columns: Passenger details (Age, Sex, Pclass, Fare, Embarked, etc.)  
- Target: **Survived** (0 = No, 1 = Yes)  

## Workflow
1. Data preprocessing (missing values, encoding categorical variables)  
2. Splitting into train and test sets  
3. Training multiple models:
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - SVM  
   - KNN  
4. Model evaluation using Accuracy, F1-score, Confusion Matrix  
5. Best model selection and sample predictions  

## Results
- Achieved ~80–82% accuracy on the test set.  
- The model predicts deaths more accurately than survivals (due to class imbalance).  

## Sample Prediction
