# DRW - Crypto Market Prediction

This repository contains our solution to the **DRW Crypto Market Prediction** challenge. The objective of the competition is to forecast cryptocurrency market behavior using historical trading data. Participants develop machine learning models to predict future market movements, aiming to improve trading decisions.

> 📊 **Current [Leaderboard](https://www.kaggle.com/competitions/drw-crypto-market-prediction/leaderboard#) Standing:** 353 (subject to change)

---

## 📂 Project Contents

- `DRW.ipynb` – Jupyter Notebook with data loading, EDA, feature engineering, and modeling.
- `README.md` – This file.

---

## 🚀 Approach Summary

### 🧹 Data Preprocessing
- Data cleaning and formatting
- Missing value handling
- Feature engineering from timestamp and price data

### 📊 Exploratory Data Analysis (EDA)
- Univariate and bivariate visualizations
- Volatility and liquidity exploration
- Correlation analysis

> **Note:** Some EDA techniques and visualizations were adapted from another contributor's notebook. The original source is credited [here](https://www.kaggle.com/code/nadiatriki/deep-eda-guide-for-drw-crypto-market).

### 🤖 Modeling
- XGBoost
- Evaluation using `rmse` and `pearson metric`
- Feature importance analysis

---

## 🛠️ Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 🙏 Acknowledgments

- Special credit to the author of the EDA reference [notebook](https://www.kaggle.com/code/nadiatriki/deep-eda-guide-for-drw-crypto-market).

---

## 📄 License

This project is open-source and intended for educational or research purposes. Attribution is appreciated.
