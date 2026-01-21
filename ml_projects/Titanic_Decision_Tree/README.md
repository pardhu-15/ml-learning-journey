# Titanic Survival Prediction using Decision Tree Classifier

This project predicts whether a passenger survived the Titanic disaster using a Decision Tree Algorithm.  
It includes data preprocessing, feature encoding, model training, evaluation, and saving the trained model.

---

## Problem Statement
Given passenger details such as Pclass, Sex, Age, Fare, SibSp, Parch, Embarked, the goal is to predict:

Survived (1) or  Not Survived (0)

---

##  Dataset
Dataset used: Titanic - Machine Learning from Disaster (Kaggle)

Files:
- Titanic-Dataset.csv

---

##  Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

##  ML Algorithm
Decision Tree Classifier

---

##  Data Preprocessing
- Dropped unnecessary columns: 'PassengerId', 'Name', 'Ticket', 'Cabin'
- Filled missing values:
  - 'Age' filled with median
  - 'Embarked' filled with mode
- Encoded categorical features:
  - 'Sex' mapped to 0/1
  - 'Embarked' one-hot encoded

---

##  Model Evaluation
Metrics used:
- Accuracy Score
- Confusion Matrix
- Classification Report
- Feature Importance

Achieved Accuracy: 82% 

---

## Model Saving
Trained model is saved as:
- 'models/decision_tree_model.pkl'


