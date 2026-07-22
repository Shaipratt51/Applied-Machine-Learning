# 🩺 OncoInsight – Cancer Patient Analytics Dashboard

An end-to-end **Machine Learning** and **Data Analytics** project built using **Python**, **Scikit-learn**, **Streamlit**, and **Plotly**. This interactive dashboard enables exploratory data analysis, statistical testing, predictive modeling, and real-time patient outcome prediction using a cancer patient dataset.

---

# 📌 Repository Structure

```text
├── DATASET/
│   └── cancer issue (1).csv
│
├── app.py
├── survival_model.pkl
├── recurrence_model.pkl
└── README.md
```

---

# 📖 Project Overview

This project provides a complete workflow for analyzing cancer patient data and building predictive machine learning models.

The application includes:

- 📊 Interactive Dashboard
- 📈 Exploratory Data Analysis (EDA)
- 📉 Statistical Hypothesis Testing
- 🤖 Machine Learning Models
- 🔮 Live Prediction Interface
- 💾 Model Saving and Loading

---

# 🚀 Features

## 📊 Dashboard Overview

- Total Patients
- Number of Cancer Types
- Average Survival Months
- Recurrence Rate
- Interactive Data Table

---

## 📈 Exploratory Data Analysis

- Distribution Plots
- Box Plots
- Correlation Heatmap
- Survival Analysis
- Cancer Type Comparison

Interactive visualizations are built using **Plotly**.

---

## 🔬 Statistical Analysis

Implemented hypothesis testing techniques:

- Independent T-Test
- One-Way ANOVA
- Chi-Square Test

These help identify statistically significant relationships within the dataset.

---

## 🤖 Machine Learning Models

### Regression Model

Predicts:

- Patient Survival Months

Algorithm:

- Linear Regression

Evaluation Metrics:

- R² Score
- RMSE

---

### Classification Model

Predicts:

- Cancer Recurrence Risk

Algorithm:

- Random Forest Classifier

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

---

## 🔮 Live Prediction

The Streamlit application allows users to input:

- Age
- BMI
- Tumor Size
- Cancer Type
- Stage
- Treatment Type

and predict:

- Estimated Survival Months
- Recurrence Risk

---

# 📂 Dataset

Dataset:

```text
DATASET/cancer issue (1).csv
```

The dataset contains patient medical records including:

- Age
- Gender
- Race / Ethnicity
- BMI
- Smoking Status
- Family History
- Cancer Type
- Stage
- Tumor Size
- Treatment Type
- Treatment Response
- Genetic Marker
- Survival Months
- Recurrence

---

# 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Dashboard | Streamlit |
| Data Analysis | Pandas, NumPy |
| Visualization | Plotly, Matplotlib, Seaborn |
| Statistics | SciPy |
| Machine Learning | Scikit-learn |
| Model Saving | Joblib |

---

# 🔄 Machine Learning Workflow

```text
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Statistical Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Save Model (.pkl)
      │
      ▼
Streamlit Deployment
```

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

Navigate to the project

```bash
cd <repository-name>
```

Install dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install streamlit pandas numpy scipy matplotlib seaborn plotly scikit-learn joblib
```

Run the application

```bash
streamlit run app.py
```

---

# 📊 Libraries Used

- Streamlit
- Pandas
- NumPy
- Plotly
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Joblib

---

# 🎯 Learning Outcomes

This project demonstrates:

- Data Visualization
- Statistical Testing
- Regression
- Classification
- Feature Engineering
- Model Evaluation
- Interactive Dashboard Development
- Machine Learning Deployment

---

# 🚀 Future Improvements

- XGBoost Classifier
- LightGBM
- SHAP Explainability
- Hyperparameter Tuning
- Deep Learning Models
- Survival Analysis Models
- Cloud Deployment
- User Authentication
- PDF Report Generation

---

# 📄 License

This repository is intended for educational and learning purposes.

---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.
