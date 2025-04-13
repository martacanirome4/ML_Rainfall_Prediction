# 🌧️ Rainfall Prediction Classifier

This project is the final assignment for the **IBM Machine Learning with Python** course on Coursera. The goal is to build a machine learning pipeline that predicts **whether it will rain tomorrow** based on historical weather data in Australia.

---

## 🧠 Objective

As a data scientist at **WeatherTech Inc.**, your mission is to develop a classifier using real-world weather data to forecast rainfall and support decision-making in climate-aware industries.

---

## 📁 Dataset

The dataset used is the **Rain in Australia** dataset, originally from the Rattle package and available on [Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package).  
It includes daily weather observations across Australian locations, with features such as:

- Temperature (MinTemp, MaxTemp, Temp3pm)
- Humidity
- Wind speed and direction
- Rainfall
- Atmospheric pressure
- Date and location
- Rain indicators (RainToday, RainTomorrow)

---

## 🛠️ Project Structure

The project follows a full machine learning workflow:

1. **Data cleaning & preprocessing**
2. **Feature engineering** (e.g. season extraction)
3. **Categorical encoding & scaling**
4. **Pipeline creation using `Pipeline` & `ColumnTransformer`**
5. **Modeling with:**
   - Random Forest Classifier
   - Logistic Regression (for comparison)
6. **Hyperparameter tuning** with `GridSearchCV`
7. **Evaluation** using classification reports, confusion matrices, and feature importance analysis

---

## 🔍 Model Performance

Both **Random Forest** and **Logistic Regression** models were evaluated using accuracy, precision, recall, and confusion matrices. The project explores **feature importance**, class imbalance, and model interpretability.

---

## 🧪 Technologies Used

- Python 3
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Pipeline, GridSearchCV, ColumnTransformer, metrics)

---

## 📚 Course Info

This project was completed as part of the:

**Machine Learning with Python** course  
by IBM | [Coursera](https://www.coursera.org/learn/machine-learning-with-python)

---

## 📌 Author

Developed by Marta Canino as part of the Coursera IBM specialization in Data Science.

---

## 🚀 Getting Started

To run the notebook locally:
1. Clone the repo
2. Install requirements
3. Run the Jupyter notebook

```bash
pip install -r requirements.txt
jupyter notebook
