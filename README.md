# 🏥 Health Care Diabetes Prediction — Data Science Capstone

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-green?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-9cf?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

This is a **Data Science Capstone Project** focused on predicting the **onset of diabetes** in patients using clinical health measurements. The dataset originates from the National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK), and all patients in the dataset are females of Pima Indian heritage.

The project follows a structured, week-by-week approach covering **data analysis, cleaning, visualisation, feature engineering, and machine learning modelling**.

---

## 🗂️ Dataset Description

| Feature | Description |
|---------|-------------|
| `Pregnancies` | Number of times pregnant |
| `Glucose` | Plasma glucose concentration |
| `BloodPressure` | Diastolic blood pressure (mm Hg) |
| `SkinThickness` | Triceps skin fold thickness (mm) |
| `Insulin` | 2-hour serum insulin (mu U/ml) |
| `BMI` | Body mass index |
| `DiabetesPedigreeFunction` | Diabetes pedigree function |
| `Age` | Age in years |
| `Outcome` | Target variable — 1 (Diabetic) / 0 (Non-diabetic) |

> **Dataset:** `health care diabetes.csv` — 768 observations, 9 variables

---

## 🎯 Objectives

- Perform **Descriptive Statistical Analysis** on all clinical features
- Handle **missing values** (zero-imputation with mean substitution)
- Create **visual distributions** (histograms, heatmaps, scatter plots)
- Build and evaluate **classification models** for diabetes prediction
- Identify key features influencing diabetes diagnosis

---

## 📅 Project Workflow (Week-by-Week)

### 📌 Week 1 — Data Loading & Cleaning
- Loaded the dataset and performed `.info()` and `.describe()` analysis
- Identified that zero values in clinical columns represent missing data
- Replaced zeros in `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, and `BMI` with **column means**
- Verified missing value treatment with a **heatmap**

### 📌 Week 2 — Exploratory Data Analysis
- **Count plot** — Class distribution of Outcome (balanced dataset, no sampling needed)
- **Scatter plot (Pair Plot)** — Pairwise relationships between all features
- Correlation analysis across all variables

### 📌 Week 3+ — Modelling & Evaluation
- Feature selection and train/test split
- Classification model training and accuracy evaluation
- Model comparison and insights

---

## 🔍 Key Insights

- Dataset contains **768 records** with **9 variables** (8 features + 1 target)
- The `Outcome` classes are **balanced** — no need for SMOTE or oversampling
- **Glucose** is the strongest individual predictor of diabetes
- Missing values (stored as 0) were imputed using **column mean** — medically justified

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Plotting & charts |
| Seaborn | Statistical visualisation |
| Scikit-learn | ML modelling & evaluation |

---

## 📁 Project Structure

```
health-care/
│
├── Health Care Project Datascience Capstone.ipynb   # Full notebook
├── health care diabetes.csv                          # Dataset
├── after_week1.csv                                   # Cleaned data after Week 1
└── README.md                                         # Project documentation
```

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/homeshwarnelakurthi/health-care.git
cd health-care
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Launch the notebook
```bash
jupyter notebook "Health Care Project Datascience Capstone.ipynb"
```

---

## 👨‍💻 Author

**Homeswar Rao Nelakurthi**  
[![GitHub](https://img.shields.io/badge/GitHub-homeshwarnelakurthi-181717?style=flat&logo=github)](https://github.com/homeshwarnelakurthi)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
