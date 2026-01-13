# HeartDisease-Prediction

This project implements a Heart Disease Prediction System using Logistic Regression.
The model predicts whether a person has heart disease based on medical attributes such as age, cholesterol level, blood pressure, and ECG results.

📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can significantly improve treatment outcomes.
This project uses machine learning to classify patients as having heart disease or no heart disease using clinical data.

Algorithm Used: Logistic Regression

Dataset Size: 303 samples

Features: 13 medical attributes

Target Variable: Heart disease presence (0 = Healthy, 1 = Diseased)

🧠 Machine Learning Workflow

Import required dependencies

Load and explore the dataset

Perform data preprocessing

Split data into training and testing sets

Train Logistic Regression model

Evaluate model performance

Build a predictive system for new input data

🧪 Dataset Description

The dataset contains the following features:

Feature	Description
age	Age of the patient
sex	Gender (1 = male, 0 = female)
cp	Chest pain type
trestbps	Resting blood pressure
chol	Serum cholesterol
fbs	Fasting blood sugar
restecg	Resting ECG results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina
oldpeak	ST depression
slope	Slope of peak exercise ST segment
ca	Major vessels colored by fluoroscopy
thal	Thalassemia
target	1 = Heart Disease, 0 = Healthy
⚙️ Technologies Used

Python

NumPy

Pandas

Scikit-learn

Jupyter Notebook

📊 Model Performance
Dataset	Accuracy
Training Data	85.12%
Testing Data	81.96%

The model shows good generalization with minimal overfitting.

🔮 Predictive System

The trained model can predict heart disease for new patient data.

Example Input
input_data = (62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2)

Output
The Person does not have a Heart Disease

🚀 How to Run the Project

Clone the repository

git clone https://github.com/akhilsurabhi07/heart-disease-prediction.git


Install dependencies

pip install numpy pandas scikit-learn


Run the Jupyter Notebook

jupyter notebook


Open the notebook and execute all cells

📌 Key Highlights

Clean and well-structured ML pipeline

Logistic Regression for binary classification

No missing values in dataset

Stratified train-test split

Real-time prediction capability

🔮 Future Enhancements

Apply feature scaling and normalization

Try advanced models (Random Forest, SVM, XGBoost)

Add ROC-AUC and confusion matrix

Deploy using Flask / FastAPI

Integrate with a web or mobile application

👤 Author

Akhil Surabhi
B.Tech – Computer Science & Engineering (AIML)
Vignan Institute of Technology and Science

GitHub: https://github.com/akhilsurabhi07

LinkedIn: https://www.linkedin.com/in/akhil-surabhi-641745255

⭐ Acknowledgements

UCI Machine Learning Repository

Scikit-learn documentation

✅ Tip before pushing to GitHub

Make sure your repo contains:

README.md

.ipynb file

Dataset (or mention dataset source if not included)
