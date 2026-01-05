# EPL Team Style Analysis & Match Prediction System

## 📌 Project Overview
This project applies unsupervised machine learning (KMeans clustering) to identify playing style patterns among English Premier League teams based on match-level performance statistics.

## 🔍 Methodology
- Feature engineering from match-level data
- Team-level aggregation of performance metrics
- Standardization and KMeans clustering
- Cluster interpretation and style labeling
- PCA-based visualization for cluster validation

## 📊 Key Insights
- Teams naturally cluster into four playing styles:
  - Attacking
  - Balanced
  - Aggressive
  - Struggling / Passive
- PCA visualization explains ~87% of variance, showing clear separation between styles.
- High attacking output is relatively rare across the league.

## 📁 Project Structure

```

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

```

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## 📁 Files
- `EPL Team Style Analysis & Match Prediction System.ipynb`: Main analysis notebook

## 🚀 Future Improvements
- Multi-season data integration
- Tactical features (pressing intensity, pass networks)
- Match outcome prediction models

---
