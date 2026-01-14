# Stroke Prediction Project 🧠🩺

This project builds a **Machine Learning classification model** to predict whether a person is at risk of **stroke** based on health and lifestyle features such as age, hypertension, glucose level, BMI, smoking status, etc.

Repository includes:
- `stroke_project.ipynb` → complete workflow notebook
- `healthcare-dataset-stroke-data.csv` → dataset used in this project  
:contentReference[oaicite:1]{index=1}

---

## Problem Statement
Stroke is a serious medical condition and early risk prediction can support timely clinical decisions.  
The goal of this project is to **predict `stroke` (0/1)** using supervised machine learning.

---

## Dataset
File: `healthcare-dataset-stroke-data.csv` :contentReference[oaicite:2]{index=2}

Typical columns include:
- `gender`, `age`
- `hypertension`, `heart_disease`
- `ever_married`, `work_type`, `Residence_type`
- `avg_glucose_level`, `bmi`, `smoking_status`
- `stroke` (Target)

---

## Workflow (Notebook)
The notebook (`stroke_project.ipynb`) covers:
1. **Importing libraries**
2. **Loading dataset**
3. **EDA (Exploratory Data Analysis)**
4. **Data cleaning**
   - Handling missing values (commonly BMI)
   - Removing/handling duplicates (if any)
5. **Feature engineering**
   - Encoding categorical variables
   - Scaling numeric features (if needed)
6. **Train/Test split**
7. **Model building**
   - Trying multiple ML algorithms (example: Logistic Regression, Decision Tree, Random Forest, etc.)
8. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix / ROC-AUC (if included)

---

## Tech Stack
- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

