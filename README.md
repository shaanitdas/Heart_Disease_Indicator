# Heart_Disease_Indicator

🫀 Heart Disease Prediction using Random Forest
📌 Project Overview

This project is a machine learning classification system that predicts whether a patient is at risk of developing heart disease based on lifestyle, medical history, and demographic features.

Using a dataset containing health-related factors such as BMI, smoking habits, alcohol consumption, physical/mental health scores, and chronic conditions, the model identifies patterns that are strongly associated with heart disease.

The goal is to support early diagnosis and preventive healthcare using machine learning.

🔬 Model Used: Random Forest Classifier

The core model used in this project is the Random Forest Classifier, an ensemble method widely used for classification tasks.

🌲 What is Random Forest?

Random Forest is an ensemble of decision trees, where each tree is trained on a random subset of data and features.

Final predictions are made using majority voting across all trees.

This approach reduces overfitting and provides robust, stable predictions.

✅ Why Random Forest?

Handles both categorical (yes/no, race, sex) and numerical features (BMI, sleep time, age category, physical health, etc.) effectively.

Works well with imbalanced and noisy datasets.

Provides feature importance, helping identify which health factors contribute most to heart disease risk.

Resistant to overfitting compared to a single decision tree.

📂 Dataset Details

The dataset includes the following features:
BMI 
Smoking
AlcoholDrinking 
Stroke 
PhysicalHealth 
MentalHealth 
DiffWalking 
Sex
AgeCategory
Race
Diabetic
PhysicalActivity
GenHealth
SleepTime
Asthma
KidneyDisease
SkinCancer 
Target Variable: Presence of heart disease (Yes/No).
