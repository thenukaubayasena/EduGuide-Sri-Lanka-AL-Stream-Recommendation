### 🎓 EduGuide Sri Lanka – A/L Stream Recommendation (Machine Learning Model)

This repository contains the machine learning model and datasets used for predicting the most suitable A/L (Advanced Level) stream for students in Sri Lanka, based on their O/L results, favorite subjects, and career interests.

#### 📌 Features:
- A stacking ensemble model combining **Random Forest**, **XGBoost**, and **Logistic Regression**
- Trained on real survey data collected from past Sri Lankan school students
- Text preprocessing pipeline to extract features from student preferences
- Subject & career keyword classification for intelligent feature engineering
- Includes model training script, evaluation metrics, and prediction interface

#### 📂 Contents:
- `Survey for AL stream model.csv` – Real survey data from past Sri Lankan school students
- `Data Preparation.ipynb` – Preprocessed notebook
- `updated_dataset.csv` – Cleaned and preprocessed student dataset
- `AL Stream Recommendation.ipynb` – Full model training and evaluation notebook
- `model.pkl` – Serialized model for deployment

#### 🧠 Objective:
To support students in making informed decisions about their A/L stream by analyzing their academic performance and personal interests using machine learning.
