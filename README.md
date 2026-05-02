# 🪙 Gold Price Prediction & Analysis

## 📌 Project Overview

This project analyzes and predicts gold prices (GLD) using financial indicators such as stock index, oil prices, silver prices, and currency exchange rates.

The goal is to understand relationships between variables and build a machine learning model to predict gold prices.

---

## 📊 Dataset

The dataset includes:

* **Date** → Time series data
* **SPX** → Stock Market Index
* **GLD** → Gold Price (Target Variable)
* **USO** → Oil Price
* **SLV** → Silver Price
* **EUR/USD** → Currency Exchange Rate

---

## 🧹 Data Preprocessing

* Removed `Date` column for correlation analysis
* Selected only numeric features
* Checked for missing values

---

## 📈 Correlation Heatmap

![Heatmap](https://raw.githubusercontent.com/anoopchandar4-alt/Gold-Price-Analysis/main/GLD-images/correlationofGLD.png)

---

## 🤖 Machine Learning Model

A regression model was used to predict gold prices.

### Steps:

* Split data into training and testing sets
* Trained model on financial features
* Predicted GLD values

---

## 📊 Actual vs Predicted Graph

![Actual vs Predicted](https://raw.githubusercontent.com/anoopchandar4-alt/Gold-Price-Analysis/main/GLD-images/ActualVsPredictedValue.png)

---

## 🔍 Key Insights

* **GLD and SLV** show strong positive correlation
* **SPX and GLD** show weak negative correlation
* **USO** has moderate influence on gold prices
* The model predictions closely follow actual values

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

Gold-Price-Analysis/
│── GLD-images/
│   ├── heatmap.png
│   ├── actual_vs_predicted.png
│
│── gld_price_data.csv
│── goldpriceprediction.ipynb
│── README.md

---

## 🚀 Conclusion

This project demonstrates how data analysis and machine learning can be used to understand and predict gold price movements.

---

## 🔮 Future Improvements

* Apply advanced models (Random Forest, XGBoost)
* Improve feature engineering
* Evaluate model performance using metrics

---



## 📊 Model Performance
- R² Score: (write your value here)
R squared error : 0.989326643295551
---

## 📌 How to Run
1. Open the notebook
2. Run all cells step by step
