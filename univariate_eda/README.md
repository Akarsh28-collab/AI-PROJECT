# 🚢 Titanic Dataset - Univariate Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Univariate Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the distribution of individual features such as survival, age, gender, passenger class, and fare.

The goal is to extract meaningful insights from each variable independently using visualization and statistical techniques.

---

## 📂 Dataset

* Dataset used: **Titanic Dataset**
* Contains information about passengers such as:

  * Survival status
  * Age
  * Gender
  * Ticket class
  * Fare
  * Embarked location

---

## 🛠️ Tools & Libraries Used

* Python 🐍
* Pandas
* Seaborn
* Matplotlib

---

## 🔍 Steps Performed

### 1. Data Loading

* Imported dataset using Pandas
* Displayed initial rows and structure

### 2. Data Understanding

* Checked data types and structure
* Generated summary statistics

### 3. Missing Value Analysis

* Identified missing values in:

  * Age
  * Cabin
  * Embarked

### 4. Univariate Analysis

Performed analysis on individual features:

* **Survived** → Countplot
* **Sex** → Countplot
* **Pclass** → Countplot
* **Age** → Histogram + KDE + Boxplot
* **Fare** → Histogram + Boxplot
* **Embarked** → Countplot

---

## 📊 Key Insights

* Majority of passengers **did not survive**
* Dataset shows **class imbalance**
* More **male passengers** than female
* Most passengers belonged to **3rd class**
* Age distribution:

  * Majority between **20–40 years**
  * Presence of **outliers**
* Fare distribution is **highly skewed**
* Missing values exist in important columns

---

## 📈 Visualizations

The project uses:

* Count plots for categorical variables
* Histograms with KDE for numerical variables
* Boxplots to detect outliers

---

## 🚀 Future Improvements

* Perform **Bivariate Analysis** (e.g., Survival vs Gender/Class)
* Handle missing values using imputation techniques
* Feature engineering
* Build a machine learning model

---

## 📁 Project Structure

```
📦 Titanic-Univariate-EDA
 ┣ 📜 Titanic-Dataset.csv
 ┣ 📜 univariate_eda.ipynb
 ┗ 📜 README.md
```

---

## 🎯 Conclusion

This analysis provides a foundational understanding of the dataset by examining individual features. It highlights patterns, distributions, and potential issues like missing values and outliers, which are crucial for further analysis and modeling.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork it!

---
