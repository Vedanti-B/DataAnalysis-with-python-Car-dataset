# 🚗 Car Dataset Analysis using Python (Pandas)

This project involves performing **basic data analysis and data cleaning** on a car dataset using **Python** and **Pandas**. The analysis focuses on identifying missing values, filtering based on conditions, modifying columns, and understanding distributions of specific attributes.

---

## 📌 Project Objectives

- Clean the dataset by handling missing values
- Understand the distribution of different car makes
- Filter records based on the origin of the cars
- Remove outliers or unwanted rows based on specific conditions
- Apply transformations to existing columns (e.g., MPG increase)

---

## 🧰 Tools & Libraries Used

- Python 🐍
- Pandas 📊
- Jupyter Notebook

---

## 📁 Files Included

- `car_data_analysis.ipynb` — The main notebook containing all analysis steps
- `cars.csv` — The dataset file (you may need to add or download it)
- `README.md` — Project documentation
- `LICENSE` — Open-source license (MIT)

---

## ✅ Key Steps Performed

### 🔹 Q1: Handle Missing Values
- Found null values in the dataset
- Filled all numeric columns with their respective **mean** values

### 🔹 Q2: Make-wise Car Count
- Identified all unique values in the **Make** column
- Counted the occurrence of each Make using `value_counts()`

### 🔹 Q3: Filter by Origin
- Filtered and displayed all records where **Origin** is either **Asia** or **Europe**

### 🔹 Q4: Remove Heavy Cars
- Removed all cars where **Weight > 4000**

### 🔹 Q5: Transform Column
- Increased all values in the **MPG_City** column by 3

---

