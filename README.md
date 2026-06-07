# 🍷 Wine Quality Analysis

Exploratory Data Analysis (EDA) of the Wine Quality Dataset using Python, Pandas, Matplotlib, and Seaborn.

---

## 📌 Project Overview

This project investigates the physicochemical properties of red wine samples and their relationship with wine quality scores.

The analysis includes:

- Data cleaning
- Duplicate removal
- Statistical exploration
- Feature distribution analysis
- Correlation analysis
- Outlier detection
- Relationship visualization

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Feature Distributions


The distributions reveal:

- Residual sugar and sulfur dioxide are highly right-skewed.
- Density follows an approximately normal distribution.
- Wine quality is concentrated around scores 5 and 6.

---

## 🔥 Correlation Heatmap
<img width="1048" height="814" alt="Heatmap" src="https://github.com/user-attachments/assets/c2e92a0d-7ca7-497c-8a6b-0eb2f87f23e7" />


### Key Findings

| Feature | Correlation with Quality |
|----------|----------|
| Alcohol | +0.48 |
| Sulphates | +0.26 |
| Citric Acid | +0.24 |
| Volatile Acidity | -0.41 |

Observations:

- Higher alcohol content tends to increase wine quality.
- Higher volatile acidity tends to reduce wine quality.
- Sulphates show a moderate positive relationship with quality.

---

## 📈 Pairplot Analysis
<img width="1224" height="918" alt="Feature Distributions" src="https://github.com/user-attachments/assets/68bf4829-8a4a-4321-ac79-1c6b548cee61" />


Pairwise visualizations help identify:

- Feature interactions
- Cluster patterns
- Potential separation between quality groups

---

## 🚀 How to Run

```bash
git clone https://github.com/USERNAME/wine-quality-analysis.git

cd wine-quality-analysis

pip install -r requirements.txt

jupyter notebook
```

---

## 📚 Dataset

Wine Quality Dataset (WineQT)

Source:
https://www.kaggle.com/datasets/yasserh/wine-quality-dataset

---

## 🎯 Future Improvements

- Machine Learning Models
- Quality Prediction
- Feature Importance Analysis
- Model Comparison
- Hyperparameter Tuning

