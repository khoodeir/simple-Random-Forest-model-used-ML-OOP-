# 🏦 Loan Approval Prediction System (OOP + Machine Learning)

This project implements a Loan Approval Prediction System using Object-Oriented Programming (OOP) and Machine Learning.

The goal is to build a structured and reusable ML pipeline using Python classes instead of writing unorganized scripts.

---

## 📌 Project Overview

The system predicts whether a loan application will be approved or rejected based on applicant data.

This project demonstrates:
- OOP principles
- Machine Learning workflow
- Clean code structure
- Model training & evaluation

---

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn
- Random Forest Classifier

---

## 🧠 OOP Structure

The project is built using a class-based design:

### 🔹 RandomForestModel Class

Responsibilities:
- Load dataset
- Preprocess data (One-Hot Encoding)
- Split data (Train/Test)
- Train model
- Evaluate performance

---

## 🚀 How It Works

1. Load dataset from CSV
2. Convert categorical features using `pd.get_dummies`
3. Split dataset into training and testing sets
4. Train Random Forest model
5. Evaluate accuracy

---

## ▶ Example Usage

```python
RF_system=RandomForestModel(r"C:\Users\FALCON\Downloads\Credit.csv")

RF_system.load_data()
RF_system.train_data()
