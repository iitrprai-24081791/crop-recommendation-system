# 🌱 Crop Recommendation System

## 👤 Submitted by:
**Aditya Kumar**

---

## 📌 Project Overview
Farming is one of the most important sectors in India, but farmers often face the challenge of deciding which crop to grow. Choosing the wrong crop for a particular soil and climate condition can lead to low yield and financial loss.  

This project is a **Crop Recommendation System** that helps in solving this problem.  
It suggests the most suitable crop for cultivation based on **soil nutrients and weather conditions**.  

The system uses **Machine Learning (Random Forest Classifier)** trained on a public dataset from Kaggle. It is deployed as a **Streamlit web application** where users can enter their soil and climate values to get instant recommendations.

---

## 🚀 Features
- 🌍 Easy-to-use **Streamlit web interface**  
- 🔢 Input parameters: Nitrogen (N), Phosphorus (P), Potassium (K), Temperature (°C), Humidity (%), pH value, Rainfall (mm)  
- 🌾 Output: **Top-3 recommended crops** with probability scores  
- 📊 Supports decision-making for farmers and agriculture students  
- 💻 Can run locally or on the web (Streamlit Cloud)

---

## 📊 Dataset
The dataset `Crop_recommendation.csv` was taken from Kaggle.  
It contains 8 columns:
- **Nitrogen (N)** – soil nitrogen content  
- **Phosphorus (P)** – soil phosphorus content  
- **Potassium (K)** – soil potassium content  
- **Temperature (°C)** – average temperature  
- **Humidity (%)** – average humidity  
- **pH** – acidity or alkalinity of soil  
- **Rainfall (mm)** – rainfall in mm  
- **Label** – recommended crop  

The dataset includes 22 different crops such as rice, wheat, maize, coffee, mango, etc.

---

## ⚙️ Technologies Used
- **Python** – main programming language  
- **Pandas & NumPy** – data handling  
- **Scikit-learn** – machine learning model (Random Forest Classifier)  
- **Streamlit** – web app deployment

---

## 🖥️ How to Run the Project

### 🔹 1. Install dependencies
Make sure Python is installed, then run:
```bash
pip install -r requirements.txt
