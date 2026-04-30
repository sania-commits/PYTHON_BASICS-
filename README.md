# PYTHON_BASICS-
I generated complete Python workflow in this repository. 

# 🚢 Titanic Data Analysis & Preprocessing

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) and data preprocessing on the Titanic dataset. The goal is to understand the dataset, handle missing values, and prepare the data for further machine learning tasks.

---

## 📊 Dataset

The dataset used in this project is the Titanic dataset, which contains information about passengers such as age, gender, ticket class, fare, and survival status.

* Source: Public dataset (loaded via URL)
* Rows: ~891
* Columns: Multiple features including numerical and categorical data

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* VS Code (WSL)

---

## 🔍 Tasks Performed

* Loaded dataset directly from a URL using Pandas
* Explored dataset structure using `.head()`, `.info()`, `.describe()`
* Identified missing values
* Handled missing values using:

  * Mean imputation (for numerical columns like Age)
  * Dropping columns with excessive missing values (like Cabin)
* Basic data cleaning

---

## 📈 Key Insights

* Some columns like `Age` and `Cabin` contain missing values
* `Cabin` has a large number of missing entries
* Data contains both categorical and numerical features

---

## 🧹 Data Preprocessing Steps

* Filled missing values in `Age` using mean
* Dropped or handled columns with too many missing values
* Checked data types and structure

---

## 🚀 Future Work

* Perform data visualization
* Feature engineering
* Build a machine learning model to predict survival

---

## 📂 How to Run

```python
import pandas as pd

url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
df = pd.read_csv(url)
print(df.head())
```

---

## 🤝 Author

[Open Titanic Notebook](./Titanic%20Data%20Analysis%20%26%20Preprocessing.ipynb)


Sania Anjum
Aspiring Data Scientist

