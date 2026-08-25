# 🐟 Fish Weight Prediction

**Predicting fish weight based on physical measurements (species, height, width, length) using linear regression.**

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-ML-F7931E.svg)](https://scikit-learn.org/)
[![License MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

---

## 🎯 Problem Statement

Predicting fish weight based on physical measurements (species, height, width, length) using linear regression.

---

## 📊 What I Built

A simple ML regression pipeline: load data, train/test split (70/30), Linear Regression, evaluate with MAE and R².

### Key Results

| Metric | Value |
|---|---|
| **Model** | Linear Regression |
| **Train Size** | 70% |
| **Test Size** | 30% |
| **Evaluation** | mean_absolute_error, r2_score |

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| **Language** | Python 3.8+ |
| **Data Processing** | Pandas |
| **ML Framework** | Scikit-Learn |
| **Model** | Linear Regression |

---

## 📁 Project Structure

```
Fish_Weight_Prediction/
├── *.ipynb                          # Main notebook with full pipeline
├── ml_evaluation_utils.py           # Evaluation utilities (CV, confidence intervals)
├── README.md
└── LICENSE
```

---

## 🔧 How to Run

```bash
# Install dependencies
pip install pandas scikit-learn jupyter

# Run the notebook
jupyter notebook *.ipynb
```

---

## 🧪 Engineering Decisions

| Decision | Rationale |
|---|---|
| **Linear Regression** | Chosen as baseline model for this problem type |
| **70/30 Split** | Standard split ratio for small-medium datasets |
| **Random State 2529** | Fixed random state ensures reproducibility |

---

## ⚠️ Limitations

- **No cross-validation**
- **No feature scaling**
- **Simple model (Linear Regression may not capture non-linear relationships)**
- **No confidence intervals**

---

## ⚠️ Disclaimer

This is an educational project for learning ML concepts. It is not intended for production use.

---

*Built as part of MSc Data Science coursework — demonstrating fundamental ML pipeline.*
