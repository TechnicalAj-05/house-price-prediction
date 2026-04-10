# 🏠 House Price Prediction

## 📌 Overview
This project is a Machine Learning-based web application that predicts house prices based on various features such as area, number of bedrooms, bathrooms, and furnishing status.

It uses Linear Regression to estimate prices and provides a simple user interface using Streamlit.

---

## 🚀 Features
- Predict house prices instantly
- User-friendly Streamlit interface
- Real-time input prediction
- Clean and simple ML pipeline

---

## 📊 Dataset Features
- area  
- bedrooms  
- bathrooms  
- stories  
- parking  
- mainroad  
- guestroom  
- basement  
- hotwaterheating  
- airconditioning  
- prefarea  
- furnishingstatus  

---

## ⚙️ Data Preprocessing
- Converted categorical values (yes/no → 0/1)
- Applied one-hot encoding for furnishing status
- Cleaned dataset for better training

---

## 🧠 Model Used
- Linear Regression

---

## 📈 Performance
- R² Score: ~0.61

---

## 🛠 Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  

---

## ▶️ How to Run

```bash
git clone https://github.com/TechnicalAj-05/house-price-prediction.git
cd house-price-prediction
pip install -r requirements.txt
streamlit run app.py
