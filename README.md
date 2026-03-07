# Hypertension Prediction & Risk Assessment Platform
An advanced, AI-powered cardiovascular risk assessment platform designed to predict hypertension stages and provide clinically-aligned recommendations. This application bridges the gap between machine learning insights and actionable medical advice.

## 🌟 Features
AI-Driven Classification: Uses a Logistic Regression model (logreg_model.pkl) trained on clinical datasets to predict four stages: Normal, Stage 1, Stage 2, and Hypertensive Crisis.

Professional Medical UI: A clean, responsive dashboard built for healthcare settings, featuring WCAG-compliant design and intuitive data entry.

Real-time Risk Mapping: Instant visual feedback using medical-grade color coding (Green, Amber, Orange, Red).

Actionable Clinical Recommendations: Dynamic generation of lifestyle and medical advice based on the specific risk level detected.

Robust Input Validation: Comprehensive server-side validation for 12 patient variables including demographics, symptoms, and BP readings.

## 🏗️ Project Structure
## ⚙️ Technical Implementation
### Preprocessing Pipeline
The system performs manual ordinal scaling to ensure high prediction accuracy:

Age Groups: Normalized from 4-tier categories.

Blood Pressure: Scaled ranges for Systolic and Diastolic inputs.

Symptom Severity: Encoded to match model feature weights.

### Prediction Logic
The backend includes a fail-safe Demo Mode. If the .pkl model is not present in the environment, the system gracefully switches to a simulated AI prediction mode to ensure the UI remains functional for presentations.

## 🚀 Getting Started
Clone the repository:

Install dependencies:

Run the application:

Access the dashboard:
Navigate to http://127.0.0.1:5000 in your web browser.

## 📊 System Screenshots
## 🩺 Clinical Disclaimer
This tool is for educational and demonstrative purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of a physician or other qualified health provider with any questions regarding a medical condition.

## 🛠️ Built With
Backend: Flask (Python)

ML Library: Scikit-Learn, NumPy, Joblib

Frontend: HTML5, CSS3 (Flexbox/Grid), Jinja2 templates

Design: Medical-grade UI/UX principles
