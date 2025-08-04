# task1_titanic-data-preprocessing

# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

This project is part of my AI & ML Internship Task 1.  
The objective was to clean and preprocess the Titanic dataset to make it ready for machine learning models.

---

## ✅ What I Did

### 1. Imported Dataset
- Loaded the Titanic dataset using Pandas.

### 2. Explored the Data
- Checked the number of rows/columns, data types, and missing values.
- Used `.info()`, `.describe()`, and `.isnull().sum()`.

### 3. Handled Missing Values
- Filled missing `Age` values with **median**.
- Filled missing `Embarked` values with **ffill**.
- Dropped `Cabin` column due to too many null values.

### 4. Encoded Categorical Features
- Applied **One-Hot Encoding** on `Sex` and `Embarked` columns using `pd.get_dummies()`.

### 5. Scaled Numerical Features
- Used **StandardScaler** to standardize features like `Age`, `Fare`, `SibSp`, and `Parch`.

### 6. Detected & Removed Outliers
- Visualized outliers using **boxplots**.
- Removed them using **IQR (Interquartile Range)** method.

---

## 🧰 Tools Used
- Python
- Pandas
- NumPy
- Seaborn / Matplotlib
- Scikit-learn

---

## 📁 Files Included
- `task1_cleaning.ipynb` — main code file
- `cleaned_titanic.csv` — final cleaned dataset
- `README.md` — this file

---

## 📌 Dataset Source
[📊 Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🚀 Output
A clean, preprocessed dataset ready for use in building machine learning models.

