# 🌞 **Solar Power Output Prediction using Machine Learning**  
**🚀 AICTE Internship Project**  

## 📌 Overview  
This project focuses on predicting **solar power generation** using machine learning models. By leveraging historical weather and solar data, we aim to build accurate models that estimate **generated power (kW)** based on environmental conditions.  

✅ **Project Type**: Regression  
✅ **Technologies Used**: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  
✅ **Internship**: AICTE Virtual Internship - CYCLE 3  

---

## 📂 Dataset & Features  
The dataset contains historical solar energy generation data, including:  
- **Temperature (°C)**  
- **Solar Irradiance (W/m²)**  
- **Humidity (%)**  
- **Wind Speed (m/s)**  
- **Generated Power (kW) [Target Variable]**  

---

## 🛠️ Machine Learning Models Used  
The following **regression models** were implemented and compared:  

| Model | Mean Absolute Error (MAE) |
|--------|----------------------|
| 🔹 **Linear Regression** | 389.2865516698178 kW |
| 🌳 **Decision Tree Regressor** | 331.9375076712652 kW |
| 🌲 **Random Forest Regressor** | 297.5932548504351 kW |
| 📈 **Support Vector Regressor (SVR)** | 321.046302630519 kW |

---

## 📊 Data Preprocessing & Feature Engineering  
- **Exploratory Data Analysis (EDA)**: Heatmaps, scatter plots, correlation analysis  
- **Outlier Detection & Handling**: Imputed using median values  
- **Feature Scaling**: StandardScaler applied after train-test split  
- **Model Training & Evaluation**: Used MAE (Mean Absolute Error) as the performance metric  

---

## 📜 Results & Observations  
- **Linear Regression** provided the best generalization among all models, making it a strong baseline.  
- **Random Forest Regressor** performed better than SVR but was still prone to overfitting.  
- **Support Vector Regressor (SVR)** struggled slightly more than Random Forest but captured some non-linear trends.  
- **Decision Tree Regressor** had the highest error, indicating severe overfitting. 

### **🔹 Final Model Performance (MAE Ranking - Lower is Better)**  
1️⃣ **Linear Regression** (Lowest Error)  
2️⃣ **Random Forest Regressor**  
3️⃣ **Support Vector Regressor**  
4️⃣ **Decision Tree Regressor** (Highest Error, Overfitting) 

From these observations, **Linear Regression** turned out to be the most reliable model, while **Decision Tree Regressor** suffered from overfitting due to deep splits. Further **hyperparameter tuning** or **ensemble learning** (e.g., Gradient Boosting, XGBoost) can help improve performance.

---

## 📌 Key Learnings & Challenges  
✅ Importance of **data preprocessing** (outlier handling, feature scaling)  
✅ Impact of **overfitting in Decision Trees** and how **hyperparameter tuning helps**  
✅ **SVR's effectiveness** with **non-linear relationships** in solar power prediction  

---

## 📌 Future Improvements  
- 🚀 Implement **XGBoost** for better performance  
- 📊 Collect more real-time **weather & solar energy data** for enhanced accuracy  
- 🌐 Deploy the model as a **web application** for real-time predictions  

---



Thank you for checking out this project! 😊
