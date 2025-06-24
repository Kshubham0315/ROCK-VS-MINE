# ROCK-VS-MINE

**# 🎯 Sonar Object Classifier (Rock vs Mine)

This is a machine learning web app built with **Streamlit** that predicts whether an object is a **Rock** 🪨 or a **Mine** 💣 based on sonar signal features.

---

## 📊 Dataset Information

- **Source**: UCI Machine Learning Repository  
- **Features**: 60 numeric values representing sonar signal strength reflected off different angles  
- **Label**:  
  - `R` → Rock  
  - `M` → Mine

---

## 💻 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn (Logistic Regression)
- Streamlit (Web App UI)

---

## 🚀 Features

- Upload sonar dataset (.csv)
- Model trains automatically on uploaded data
- Real-time predictions with 60 input features
- Displays Training & Test Accuracy
- Interactive UI using Streamlit widgets

---

## 🔗 Live App

👉 [Click here to use the app](http://localhost:8501/)  

---

## 🧠 How It Works

1. Upload the sonar dataset (`Copy of sonar data.csv`)
2. App automatically splits data, trains a Logistic Regression model
3. Shows training & test accuracy
4. Enter 60 numerical features to get prediction
5. Get result: "Rock" or "Mine" 🚀

---

## 🧪 Sample Input Format (60 features)

**
