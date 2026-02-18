# ML-Student-Exam-Score-Prediction-System
Predict, analyze, and visualize student performance using Random Forest &amp; Streamlit — from data to deployment.
# 🎓 Student Exam Score Prediction System

## 📌 Project Overview

This project predicts student performance (Low, Middle, High) based on academic and engagement factors such as:

- `raisedhands`  
- `VisITedResources`  
- `AnnouncementsView`  
- `Discussion`  
- Attendance, Grade, and other personal factors  

The goal is to help educators and students understand which factors most significantly impact academic performance.

---

## 🛠️ Features Implemented

1. **End-to-End ML Pipeline**
   - Data cleaning and handling duplicates
   - Exploratory Data Analysis (EDA) with visualizations
   - Feature encoding and selection

2. **Machine Learning Models**
   - Logistic Regression (baseline)
   - Random Forest Classifier (final model)
   - Model evaluation using Accuracy, Classification Report, Confusion Matrix

3. **Feature Importance**
   - Identified top predictors of student performance
   - Visualized the importance of engagement features

4. **Deployment**
   - Saved model with `pickle`
   - Interactive web app using **Streamlit**
   - Real-time predictions based on user input

---

## 📊 Exploratory Data Analysis (EDA)

- Checked class distribution: `Low`, `Middle`, `High`
- Analyzed categorical features like `Gender`, `StageID`, `GradeID`, `Topic`, etc.
- Visualized numeric features (`raisedhands`, `VisITedResources`, etc.) using histograms and boxplots
- Studied correlations and feature interactions
- Removed duplicates and handled missing values

---

## 🧠 Technology Stack

- Python 3.x
- Pandas & NumPy
- Scikit-learn (Logistic Regression, Random Forest)
- Matplotlib & Seaborn (EDA visualization)
- Streamlit (web app)
- Pickle (model serialization)

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone (https://github.com/thatboyremo/ML-Student-Exam-Score-Prediction-System)
cd student-exam-score-prediction
