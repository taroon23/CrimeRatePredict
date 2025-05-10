# 📊 Crime Rate Prediction with Regularized Regression and Boosting

This repository contains a complete pipeline for predicting violent crime rates in U.S. communities using socioeconomic and demographic data. The project demonstrates the application of feature engineering, dimensionality reduction, and regularized regression techniques to extract insights from real-world data.

---

## 🧠 Project Overview

We use the [Communities and Crime dataset](https://archive.ics.uci.edu/ml/datasets/communities+and+crime) to model the relationship between community-level attributes (e.g., population stats, education levels, law enforcement presence) and the violent crime rate. The pipeline involves:

- **Data imputation** for missing values
- **Feature selection** using Coefficient of Variation
- **Dimensionality reduction** with Principal Component Analysis (PCA)
- **Model training** and evaluation using:
  - Ordinary Least Squares (OLS)
  - Ridge Regression
  - LASSO Regression
  - Principal Component Regression (PCR)
  - XGBoost (L1-penalized gradient boosting)

---

## 📁 Repository Structure

```
.
├── notebook/
│   └── CrimeRatePredict.ipynb     # Full analysis notebook
│
├── data/
│   ├── communities.data           # Main dataset (crime and features)
│   ├── communities.names          # Feature descriptions
│   ├── diagnosis.data             # Dataset used for decision tree modeling
│   └── diagnosis.names            # Feature descriptions for diagnosis data
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/crime-rate-prediction.git
cd crime-rate-prediction
```

### 2. Install Requirements
Make sure you have Python 3.7+ installed. Then install the required packages:
```bash
pip install -r requirements.txt
```

---

## 📈 Results

- LASSO regression enabled **sparse and interpretable** feature selection.
- XGBoost delivered **superior test accuracy** and generalization across high-dimensional inputs.
- The project highlights how **ensemble methods and regularization** can drive robust forecasting from noisy, real-world datasets.

---

## 🏁 Conclusion

This project demonstrates a practical application of modern regression techniques for public policy analysis, showcasing how interpretable and scalable models can assist in understanding community-level crime dynamics.

---

## 📚 References

- [Communities and Crime Dataset - UCI](https://archive.ics.uci.edu/ml/datasets/communities+and+crime)
- [Diagnosis of Acute Inflammations Dataset - UCI](https://archive.ics.uci.edu/ml/datasets/Acute+Inflammations)
- Scikit-learn, NumPy, pandas, XGBoost

---

## ✍️ Author

Taroon Ganesh  
Graduate Student, Data Science  
University of Southern California  
