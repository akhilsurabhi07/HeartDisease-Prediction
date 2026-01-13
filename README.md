# HeartDisease-Prediction

# ❤️ Heart Disease Prediction using Machine Learning

This project implements a **Heart Disease Prediction System** using **Logistic Regression**.  
The model predicts whether a person has heart disease based on medical attributes such as age, cholesterol level, blood pressure, and ECG results.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can significantly improve treatment outcomes.  
This project uses **machine learning** to classify patients as having heart disease or no heart disease using clinical data.

- **Algorithm Used:** Logistic Regression  
- **Dataset Size:** 303 samples  
- **Features:** 13 medical attributes  
- **Target Variable:**  
  - `1` → Heart Disease  
  - `0` → Healthy Heart  

---

## 🧠 Machine Learning Workflow

1. Import required dependencies  
2. Load and explore the dataset  
3. Perform data preprocessing  
4. Split data into training and testing sets  
5. Train Logistic Regression model  
6. Evaluate model performance  
7. Build a predictive system for new input data  

---

## 🧪 Dataset Description

The dataset contains the following features:

| Feature | Description |
|-------|------------|
| age | Age of the patient |
| sex | Gender (1 = male, 0 = female) |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression |
| slope | Slope of peak exercise ST segment |
| ca | Major vessels colored by fluoroscopy |
| thal | Thalassemia |
| target | 1 = Heart Disease, 0 = Healthy |

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

---

## 📊 Model Performance

| Dataset | Accuracy |
|-------|----------|
| Training Data | **85.12%** |
| Testing Data | **81.96%** |

---

## 🔮 Predictive System

The trained model can predict heart disease for new patient data.

### Example Input
```python
input_data = (62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2)

## output
The Person does not have a Heart Disease
