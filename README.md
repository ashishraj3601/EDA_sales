# 🛍️ Retail Store Sales - Exploratory Data Analysis (EDA)

This project performs an in-depth Exploratory Data Analysis (EDA) on retail store sales data using **Python**, including **data cleaning**, **visualization**, and **insight extraction**. The goal is to identify trends, outliers, patterns, and relationships in the data to support better business decision-making.

---

## 📂 Dataset Overview

The dataset contains transactional-level retail sales data with fields such as:

- `Transaction ID`, `Customer ID`
- `Category`, `Product Name`
- `Quantity`, `Price Per Unit`, `Total Spent`
- `Payment Method`, `Discount Applied`
- `Date` and `Region`

---

## 🛠️ Technologies Used

- **Python** (Jupyter Notebook)
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for visualizations

---

## 📊 Project Workflow

### 1. **Data Cleaning & Preprocessing**
- Removed prefixes from ID columns (e.g., `TXN_`, `CUST_`)
- Converted data types where necessary
- Handled missing values using:
  - Mode imputation for categorical data
  - Mean/median/mode for numerical fields
- Outlier detection using Box Plot & IQR method (capping not applied, reason mentioned in analysis)

### 2. **Univariate Analysis**
- Distribution plots, histograms, and box plots for numeric columns
- Count plots for categorical columns
- Skewness and kurtosis measured for shape understanding

### 3. **Bivariate Analysis**
- Bar plots for:
  - `Quantity Sold` by `Product Category`
  - `Total Spent` by `Payment Method`
- Box plots for:
  - `Total Spent` vs `Region`
  - `Price per Unit` vs `Category`

---

## 📌 Key Insights

- Certain categories like `Electronics` or `Groceries` consistently show higher total spent.
- Digital payment methods were used for larger transactions on average.
- Outliers were present but retained to preserve actual transaction behaviors.
- Some categories had mor
