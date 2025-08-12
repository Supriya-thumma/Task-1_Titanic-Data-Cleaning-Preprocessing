# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

## 📌 Overview
This project is part of my AI & ML Internship Task 1.  
The goal is to clean and preprocess the Titanic dataset to make it ready for Machine Learning.

## 📂 Dataset
- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File: `Titanic-Dataset.csv`

## 🛠 Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📊 Steps Performed
1. Imported dataset and explored data.
2. Handled missing values:
   - Age → Median
   - Embarked → Mode
   - Dropped Cabin (too many missing values)
3. Encoded categorical columns (`Sex`, `Embarked`) into numerical form.
4. Standardized numerical features (`Age`, `Fare`).
5. Detected and removed outliers using the IQR method.
6. Saved cleaned dataset as `Titanic-Dataset_cleaned.csv`.

## 📈 Output
- Final dataset: **No missing values, encoded categorical features, scaled numerical features, and outliers removed**.

---

