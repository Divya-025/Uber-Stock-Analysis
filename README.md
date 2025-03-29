# Uber Data Analysis Project

## 📌 Project Overview
This project performs **Uber stock price analysis** using Python. It includes **data loading, visualization, and predictive modeling** using **Linear Regression**.

## 🛠️ Tech Stack
- **Python**
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn
- **Jupyter Notebook**

## 📂 Dataset
- **File:** `uber_stock_data.csv`
- **Columns:** (Assumed)
  - `Date`: Trading date
  - `Open`: Opening stock price
  - `Close`: Closing stock price
  - `Volume`: Number of shares traded

## 📑 Installation & Setup
1️⃣ Install dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn
```
2️⃣ Run the Jupyter Notebook:
```bash
jupyter notebook
```
3️⃣ Open `project_uber.ipynb` and execute the cells.

## 📊 Key Analysis & Visualizations
✅ **Load Data:** Read Uber stock data using Pandas
✅ **Data Cleaning:** Handle missing values (if any)
✅ **Visualization:** Stock price trends using Matplotlib
✅ **Predictive Modeling:** Train a **Linear Regression** model to predict stock prices

## 🔍 Sample Code
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression

# Load dataset
df = pd.read_csv("uber_stock_data.csv")
df.head()
```

## 📈 Expected Output
- **Stock Price Trends** 📉
- **Model Predictions** for future stock prices 


