# EPL-Team-Style-Analysis-Match-Prediction-System

A comprehensive analysis and prediction system for English Premier League data, showcasing end-to-end data preprocessing, team style profiling, machine learning modeling, and final visualization dashboards.

---

## 📌 Project Overview
This project analyzes English Premier League (EPL) team playing styles and predicts match outcomes using machine learning.  
The workflow includes data preprocessing, exploratory analysis, clustering, dimensionality reduction (PCA/MDS), and predictive modeling.

---

## ⚽ Key Features

### 🔹 Team Style Profiling
- K-Means clustering  
- PCA / MDS visualizations  
- Offensive vs defensive team signatures  
- Similarity analysis between teams

### 🔹 Match Prediction Model
- Logistic Regression / Random Forest / XGBoost  
- Home & away features  
- Feature engineering  
- Evaluation (accuracy, F1-score, confusion matrix)

### 🔹 Dashboards & Visualization
- Tableau team-style dashboard  
- Python interactive dashboard (Plotly / Streamlit)

---

## 📁 Project Structure

```text
project/
├── data/                 # Raw & processed EPL datasets
├── notebooks/            # EDA, clustering, modeling notebooks
├── src/                  # Python scripts
│   ├── preprocessing.py
│   ├── clustering.py
│   ├── modeling.py
│   └── visualization.py
├── dashboard/            # Tableau or Streamlit dashboards
└── README.md             # Project documentation
