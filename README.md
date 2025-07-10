# 🚢 Task 2 – Data Cleaning & EDA on Titanic Dataset

This project is part of my **Data Science Internship** at **Prodigy Infotech**.

The goal of this task was to perform **data cleaning** and **exploratory data analysis (EDA)** on the **Titanic dataset** from Kaggle, identifying patterns such as survival trends based on gender, age, and class.

---

## 📂 Dataset
- Source: [Titanic Dataset – Kaggle](https://www.kaggle.com/c/titanic/data)
- Format: CSV
- Target Variable: `Survived` (1 = Yes, 0 = No)

---

## 🧹 Data Cleaning Performed
- Filled missing `Age` values using the median
- Filled missing `Embarked` values with the mode
- Dropped the `Cabin` column due to too many missing values
- Converted categorical variables like `Sex` and `Embarked` into proper types

---

## 📊 Exploratory Data Analysis
- Survival counts and survival by gender
- Distribution of age
- Survival rate by passenger class
- Correlation heatmap between numeric features

---

## 📈 Key Visuals
Included: Bar charts, histograms, and heatmaps showing survival patterns.

---

## 🧰 Tools & Libraries
- Python
- pandas
- seaborn
- matplotlib

---

## 🛠 How to Run
1. Open `PRODIGY_DS_02.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run all cells
3. View visualizations inline

---

## 🔗 Repository Link
[🔗 GitHub Repo](https://github.com/ashraful2512/PRODIGY_DS_02)
