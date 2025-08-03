# 🚗 Used Car Price Prediction

## 📘 Project Overview
This project aims to predict the price of used cars using machine learning techniques. The scenario revolves around helping a friend, Tom, who wants to sell his car at a fair price but doesn't know how to price it. Using real-world data and multiple regression models, we help Tom determine an accurate price based on the car's characteristics.

---

## 🎯 Business Problem
Tom wants to:
- Sell his used car at the best possible price.
- Avoid overpricing, which may scare away buyers.
- Avoid underpricing, which may result in a loss.

Our goal is to build a reliable price prediction model using historical data of used cars.

---

## 📂 Dataset
- **Source**: https://drive.google.com/file/d/1No_y6dQ6bfgdlAAeQR2sx4gbS1NjCuwc/view?usp=drive_link 
- **Target variable**: `price`
- **Features**: `engine-size`, `horsepower`, `length`, `fuel-type`, `curb-weight`, etc.

---

## 🧹 Data Cleaning & Preprocessing
- Handled missing values
- Data Normalization & Data Standardization
- Converted categorical features to numeric (one-hot encoding)
- Removed irrelevant columns (if any)
- Normalized/standardized numerical features

---

## 📊 Exploratory Data Analysis (EDA)
- Visualized feature relationships with price (scatter plots, heatmaps)
- Detected and treated outliers
- Annova
- Identified most correlated features with price

---

## 🤖 Models Used
1. **Linear Regression**
2. **Ridge Regression**
3. **Random Forest Regressor**

---

## 📈 Model Evaluation

| Model                | Train R² | Test R² | RMSE     | CV R² (mean ± std)   |
|---------------------|----------|---------|----------|----------------------|
| Linear Regression   | 0.87     | 0.79    | 3316.24  | 0.80 ± 0.06          |
| Ridge Regression    | 0.86     | 0.80    | 3273.81  | 0.82 ± 0.06          |
| Random Forest       | 0.99     | 0.95    | 1533.12  | 0.91 ± 0.03          |

---

## 📌 Conclusion
- **Random Forest Regressor** performs the best in terms of R² and RMSE.
- Cross-validation confirms model stability.
- This model helps users price their used cars accurately based on key features.

---

## 💻 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

---

## 📁 Folder Structure
- data/ — contains the dataset file (e.g., auto.csv)
- powerpoint/ — contains charts, graphs, and any project visuals
- notebooks/ — contains your Jupyter notebook(s) with code and analysis
