A Machine Learning based Heart Disease Risk Prediction Web Application that analyzes patient clinical data and estimates the probability of heart disease using medical indicators.

This project combines Machine Learning concepts with an interactive web interface to provide a simple tool for understanding heart disease risk factors.

📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection of risk factors can help in taking preventive medical actions.

This project predicts the probability of heart disease based on various medical parameters such as:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Maximum heart rate

Exercise-induced angina

ECG results

ST depression

Major blood vessels

Thalassemia condition

The system calculates a risk score and probability of heart disease using a Logistic Regression–style scoring model inspired by the UCI Heart Disease Dataset.

🚀 Features

Interactive web interface

Real-time heart disease risk prediction

Visual risk probability bar

Feature contribution indicators

Clinical risk factor evaluation

Responsive UI design

Smooth animations and modern styling

🧠 Model Concept

The prediction engine uses a weighted scoring system similar to Logistic Regression, where different clinical factors contribute to the final risk score.

Key influencing factors include:

Age

Cholesterol level

Blood pressure

Maximum heart rate

Exercise-induced angina

Number of blocked vessels

ST depression level

The final probability is calculated using a sigmoid function to convert the score into a percentage risk.

🛠️ Technologies Used
Frontend

HTML5

CSS3

JavaScript

Data Science Concepts

Logistic Regression

Clinical Risk Scoring

Probability Estimation

Medical Feature Analysis

Dataset

UCI Heart Disease Dataset

📊 Input Parameters

The system accepts the following medical attributes:

Feature	Description
Age	Patient age
Sex	Male / Female
Chest Pain Type	Type of chest pain experienced
Resting Blood Pressure	Blood pressure at rest
Cholesterol	Serum cholesterol level
Fasting Blood Sugar	Blood sugar level after fasting
Rest ECG	Resting electrocardiographic results
Max Heart Rate	Maximum heart rate achieved
Exercise Angina	Chest pain during exercise
ST Depression	Depression induced by exercise
Slope	Slope of peak exercise ST segment
Major Vessels	Number of blocked vessels
Thalassemia	Blood disorder indicator
📈 Output

The system provides:

Heart disease risk prediction

Probability score

Risk visualization bar

Feature health indicators

⚠️ Disclaimer

This project is built for educational and research purposes only.

It should not be used as a medical diagnosis tool. Always consult a qualified medical professional for proper health evaluation.

📂 Project Structure
Heart-Disease-Predictor
│
├── index.html
├── style.css
├── script.js
└── README.md
💡 Future Improvements

Integrate real Machine Learning model

Add Flask or FastAPI backend

Deploy as a full ML web application

Add SHAP explainability

Connect to real patient datasets
