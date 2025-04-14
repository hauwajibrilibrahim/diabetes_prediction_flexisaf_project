# 💉 Diabetes Prediction Model

A simple supervised machine learning project that predicts whether a patient is diabetic based on medical diagnostic measurements.  
This project uses **Logistic Regression** — a classification algorithm — trained on the popular **Diabetes Dataset** from Kaggle.

---

## 📊 Dataset

Dataset sourced from Kaggle:  
👉 [Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

It contains medical measurements from women of Pima Indian heritage, including:

- Number of Pregnancies
- Plasma Glucose Concentration
- Diastolic Blood Pressure
- Triceps Skinfold Thickness
- Serum Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age  
- **Outcome** (0 = Non-Diabetic, 1 = Diabetic)

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- Scikit-learn
- Logistic Regression Classifier

---
## 🧠 Problem Statement
Diabetes is one of the most common chronic diseases worldwide, often developing silently until serious complications arise. In many cases, early signs of diabetes go unnoticed due to limited access to routine health screenings, especially in resource-constrained environments. This leads to delayed diagnosis, expensive medical treatments, and an increased risk of long-term health issues such as kidney failure, vision loss, and cardiovascular disease.

This project aims to address this problem by creating a machine learning-based predictive model that uses basic health indicators — such as glucose level, BMI, age, and insulin levels — to predict the likelihood of diabetes. By offering a simple and accessible prediction tool, this project supports early detection and encourages timely medical consultation, potentially reducing healthcare costs and improving patient outcomes.

## 🚀 Getting Started

### 1️⃣ Clone this repository:
```bash
git clone https://github.com/hauwajibrilibrahim/diabetes_prediction_flexisaf_project
cd diabetes-prediction
```

### 2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the program:
```bash
python diabetes_model.py
```

---

## 💡 Features

- Cleaned and preprocessed dataset.
- Model training using `LogisticRegression`.
- Model evaluation with `Accuracy Score` and `Classification Report`.
- 🎯 **Interactive User Input Mode:**  
  When you run the script, you can enter real health measurements manually, like this:

```
--- Diabetes Prediction ---
Enter number of pregnancies: 3
Enter glucose level: 120
Enter diastolic blood pressure: 70
Enter skin thickness: 22
Enter insulin level: 85
Enter BMI: 24.5
Enter Diabetes Pedigree Function: 0.5
Enter age: 32

Prediction Result: Not Diabetic
```

---

## 📈 Sample Output

```
Accuracy Score: 0.79
Classification Report:
              precision    recall  f1-score   support
           0       0.82      0.87      0.84       150
           1       0.74      0.66      0.70        74
```

---