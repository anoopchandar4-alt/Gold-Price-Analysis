# Gold-Price-Analysis
Gold price analysis using correlation and heatmap(Random Forest Regressor)

## 📌 Project Overview
This project analyzes the relationship between gold prices (GLD) and various financial indicators using data analysis and machine learning techniques.

The goal is to understand key factors affecting gold prices and build a model to predict them.

---

## 📊 Dataset Description
The dataset contains the following features:

- **Date** → Time of observation  
- **SPX** → Stock Market Index  
- **GLD** → Gold Price (Target Variable)  
- **USO** → Oil Price  
- **SLV** → Silver Price  
- **EUR/USD** → Currency Exchange Rate  

---

## 🧹 Data Preprocessing
- Removed non-numeric column (`Date`) for correlation analysis  
- Checked for missing values  
- Prepared dataset for machine learning  

---

## 📈 Correlation Heatmap

![Heatmap](GLD-images/heatmap.png)

---

## 🤖 Machine Learning Model
A regression model was used to predict gold prices based on other financial features.

### Steps:
- Split data into training and testing sets  
- Trained model on training data  
- Predicted gold prices on test data  

---

## 📊 Actual vs Predicted Graph

![Actual vs Predicted](GLD-images/actual_vs_predicted.png)

---

## 🔍 Key Insights
- Gold (GLD) shows **strong positive correlation with Silver (SLV)**  
- Weak negative correlation between **GLD and SPX**  
- Oil prices (USO) have **moderate influence** on gold  
- The model predictions closely follow actual values, showing good performance  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

## 📁 Project Structure

Gold-Price-Analysis/
│── GLD-images/
│ ├── heatmap.png
│ ├── actual_vs_predicted.png
│
│── gld_price_data.csv
│── goldpriceprediction.ipynb
│── README.md


## 🚀 Conclusion
This project demonstrates how data analysis and machine learning can be used to understand and predict gold price movements.

---

## 🔮 Future Improvements
- Use advanced models (Random Forest, XGBoost)  
- Perform feature engineering  
- Improve prediction accuracy  

---






---

## 📁 Project Structure
