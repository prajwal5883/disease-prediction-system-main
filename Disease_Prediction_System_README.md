# 🏥 Disease Prediction System

An advanced Machine Learning-based healthcare application that predicts diseases using patient symptoms and medical parameters. The project provides an interactive dashboard built with Streamlit for healthcare analytics and patient report generation.

---

## 📌 Project Overview

The Disease Prediction System analyzes patient information such as:

- Age and Gender
- Vital signs (Blood Pressure, Sugar Level, Cholesterol, Heart Rate, Oxygen Level, BMI)
- Symptoms (Fever, Cough, Headache, Fatigue, Chest Pain, etc.)

Using a trained machine learning model, the system predicts the most likely disease, calculates a confidence score, assigns a risk level, and provides recommendations.

The application is implemented in Streamlit and supports patient history storage and report downloads. fileciteturn1file0

---

## 🚀 Features

- Patient data entry form
- Disease prediction using Machine Learning
- Confidence score calculation
- Risk level analysis (Low, Medium, High)
- Personalized medical recommendations
- Downloadable patient reports (CSV)
- Patient history tracking
- Interactive charts and analytics dashboard

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- Pickle
- CSV Datasets

---

## 📂 Project Structure

```text
disease-prediction-system/
│── app.py
│── Disease prediction system.ipynb
│── strong_disease_model.pkl
│── strong_disease_dataset.csv
│── healthcare_disease_dataset_3000.csv
│── patient_history.csv
│── README.md
```

---

## ⚙️ How the System Works

### 1. Patient Input
The user enters:
- Personal details
- Medical parameters
- Symptoms

### 2. Data Preprocessing
Yes/No symptom responses are converted into numerical values.

### 3. Disease Prediction
The trained model predicts the disease based on the provided data.

### 4. Confidence Score
The system calculates the prediction probability.

### 5. Risk Assessment
Risk levels are categorized as:
- 🔴 High Risk
- 🟡 Medium Risk
- 🟢 Low Risk

### 6. Recommendation
A medical recommendation is generated automatically.

### 7. History Storage
Each prediction is saved to `patient_history.csv`.

### 8. Report Download
Users can download the patient report in CSV format.

---

## 🧠 Predicted Diseases

The model can predict diseases such as:

- Diabetes
- Hypertension
- Asthma
- Heart Disease
- Pneumonia
- Dengue
- Kidney Disease
- Viral Fever
- Common Cold

---

## ▶️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/disease-prediction-system.git
cd disease-prediction-system
```

### 2. Install Dependencies

```bash
pip install streamlit pandas scikit-learn
```

### 3. Run the Application

```bash
streamlit run app.py
```

---

## 🖥️ Usage

1. Open the Streamlit application.
2. Enter patient details and symptoms.
3. Click **Predict Disease**.
4. View:
   - Predicted Disease
   - Confidence Score
   - Risk Level
   - Recommendation
5. Download the report if needed.

---

## 📊 Dashboard Tabs

### 📝 Patient Input
Enter all patient data and symptoms.

### 📋 Prediction Report
Shows disease, confidence, risk level, and recommendations.

### 📈 Patient History
Displays previous predictions and charts.

### ℹ️ About Project
Provides information about the system and technologies used.

---

## 📸 Sample Output

```text
Predicted Disease: Diabetes
Confidence Score: 84.6%
Risk Level: Medium
Recommendation: Schedule clinical checkup
```

---

## 🔮 Future Enhancements

- PDF report generation
- User authentication
- Database integration
- Doctor appointment booking
- Cloud deployment
- Mobile-friendly UI

---

## 👨‍💻 Developed By

**Prajwal Yaranal**

---

## 📄 License

This project is developed for educational and academic purposes.

---

## 🙌 Acknowledgements

- Streamlit
- Scikit-learn
- Pandas
- Python Community
