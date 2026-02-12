# EPL Team Style Analysis & Match Prediction System

![AWS](https://img.shields.io/badge/AWS-Database%20Projects-232F3E?logo=amazonaws&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Relational%20Database-4479A1?logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-DDL%20%7C%20DML-CC2927)
![ER Modeling](https://img.shields.io/badge/ER-Modeling-0A66C2)
![Normalization](https://img.shields.io/badge/3NF-Normalization-6A1B9A)
![Relational Design](https://img.shields.io/badge/Relational-Design-1E88E5)
![Schema Architecture](https://img.shields.io/badge/Schema-Architecture-2E7D32)
![PK/FK Constraints](https://img.shields.io/badge/PK%2FFK-Constraints-795548)
![Junction Tables](https://img.shields.io/badge/Many--to--Many-Junction%20Tables-00897B)
![Data Modeling](https://img.shields.io/badge/Data-Modeling-FF7043)

![EPL Team Styles PCA](screenshot/epl_pca_team_styles.png)

This project applies unsupervised machine learning (KMeans clustering)
to identify playing style patterns among English Premier League teams
based on match-level performance statistics.

---

## 📌 Project Overview
This project applies unsupervised machine learning (KMeans clustering) to identify playing style patterns among English Premier League teams based on match-level performance statistics, supporting data-driven tactical analysis and team profiling.

---

## 🔍 Methodology
- Feature engineering from match-level data
- Team-level aggregation of performance metrics
- Standardization and KMeans clustering
- Cluster interpretation and style labeling
- PCA-based visualization for cluster validation

---

## 📊 Key Insights
- Teams naturally cluster into four playing styles:
  - Attacking
  - Balanced
  - Aggressive
  - Struggling / Passive
- PCA visualization explains ~87% of variance, showing clear separation between styles.
- High attacking output is relatively rare across the league.

---

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## 📁 Files
- `EPL Team Style Analysis & Match Prediction System.ipynb`: Main analysis notebook
- `README.md`: Project documentation

---

## 🚀 Future Improvements
- Multi-season data integration
- Tactical features (pressing intensity, pass networks)
- Match outcome prediction models

---

## 📁 Project Structure

```

project/
├── data/                 # Raw & processed EPL datasets
├── notebooks/            # EDA, clustering, modeling notebooks
├── dashboard/            # Tableau or Streamlit dashboards
└── README.md             # Project documentation

```
