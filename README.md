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

![Correlation Heatmap](images/correlation_heatmap.png)

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

![Pairplot](images/pairplot.png)

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

