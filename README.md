# 🏥 Smart Health Monitoring and Sleep Analysis System

An AI-powered Smart Health Monitoring and Sleep Analysis System developed using **Python, Streamlit, and Machine Learning**. The application analyzes a user's health and lifestyle data to predict **Sleep Quality** and **Sleep Disorders**, while providing personalized health insights, recommendations, and downloadable reports.

---

## 📌 Project Overview

This project helps users understand their sleep health by analyzing lifestyle and physiological parameters. It uses Machine Learning models trained on a sleep health dataset to predict sleep quality and identify possible sleep disorders.

The application also provides a health dashboard, personalized suggestions, weekly health plans, and downloadable PDF reports.

---

## ✨ Features

- 🔐 User Login Interface
- 📝 Health Data Input Form
- 🤖 Machine Learning-Based Predictions
- 😴 Sleep Quality Prediction
- 🩺 Sleep Disorder Classification
- 📊 Health Dashboard
- 📈 Interactive Health Charts
- 💡 Personalized Health Suggestions
- 🥗 Food Recommendations
- 📅 Weekly Health Plan
- 📄 Downloadable PDF Health Reports

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Joblib
- Jupyter Notebook

---

## 🤖 Machine Learning Models

### Regression Model
- Predicts Sleep Quality Score

### Classification Model
- Predicts Sleep Disorders:
  - No Disorder
  - Insomnia
  - Sleep Apnea

---

## 📊 Dataset

**Dataset:** Sleep Health and Lifestyle Dataset

The dataset contains information related to:

- Gender
- Age
- Occupation
- Sleep Duration
- Physical Activity
- Stress Level
- BMI Category
- Heart Rate
- Daily Steps
- Blood Pressure
- Sleep Disorder

---

## 📁 Project Structure

```
Smart-health-monitoring-and-Sleep-analysis-system/
│
├── app.py
├── main.ipynb
├── requirements.txt
├── README.md
├── Sleep_health_and_lifestyle_dataset.csv
│
├── models/
│   ├── sleep_quality_model.pkl
│   ├── sleep_disorder_model.pkl
│   ├── scaler_regression.pkl
│   ├── scaler_classification.pkl
│   ├── regression_columns.pkl
│   └── classification_columns.pkl
│
└── reports/
    ├── comparison_classification.png
    ├── comparison_regression.png
    ├── feature_importance_classification.png
    ├── feature_importance_regression.png
    └── EDA graphs
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/iamprithuhs/Smart-health-monitoring-and-Sleep-analysis-system.git
```

Move into the project directory:

```bash
cd Smart-health-monitoring-and-Sleep-analysis-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## 📈 Project Workflow

1. User enters health and lifestyle information.
2. Data is preprocessed.
3. Machine Learning models analyze the data.
4. Sleep Quality and Sleep Disorder are predicted.
5. Results are displayed on the dashboard.
6. Personalized recommendations are generated.
7. Users can download health reports.

---

## 📊 Visualizations

The project includes:

- Sleep Disorder Distribution
- Sleep Duration Distribution
- Correlation Heatmap
- Stress vs Sleep Quality
- Physical Activity vs Sleep Quality
- Age vs Sleep Quality
- Feature Importance
- Model Comparison Charts

---

## 🔮 Future Enhancements

- Deep Learning Models
- Real-Time Health Monitoring
- Wearable Device Integration
- Cloud Deployment
- Doctor Recommendation System
- Multi-language Support

---

## 👨‍💻 Author

**Prithu H S**

Computer Science Engineer

GitHub:
https://github.com/iamprithuhs

---

## ⭐ If you found this project useful, please consider giving it a Star.
