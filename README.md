# 💼 Salary Prediction Based on Country and Race


This project involves predicting salaries using a dataset that includes features like **country** and **race**. It uses machine learning techniques to understand how these demographic features might influence salary levels and aims to build a predictive model with reasonable accuracy.

![image](https://github.com/user-attachments/assets/3b478959-d9c0-4a56-a7d8-c0896bf3a13c)

---

## 📁 Project Structure

- `Salary Prediction.ipynb` — Jupyter notebook containing all the code for:
  - Exploratory Data Analysis (EDA)
  - Data preprocessing
  - Model training and evaluation
- `Salary_Data_Based_country_and_race.csv` — Dataset containing salary records based on demographic details.

---

## 🔍 Problem Statement

To predict an individual's salary based on attributes like country, race, education level, and years of experience using machine learning models.

---

## 🧠 Technologies & Libraries Used

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models and preprocessing
- **Jupyter Notebook** – Interactive development environment

---

## 📊 Workflow Summary

1. **Data Loading & Exploration**  
   Basic understanding of dataset shape, missing values, and feature types.

2. **Data Cleaning & Preprocessing**  
   Encoding categorical features, handling nulls, scaling numerical values.

3. **Model Building**  
   Training regression models such as:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor

4. **Evaluation**  
   Using metrics like MAE, MSE, and R² to evaluate model performance.

---

## ✅ Results

The final model shows promising performance in estimating salaries based on available demographic features. Further enhancements can be made by adding more contextual data or using ensemble and deep learning techniques.

---

## 📌 Future Improvements

- Add more features (e.g., job title, company, location within country)
- Hyperparameter tuning for better accuracy
- Model deployment as a web API using Flask/FastAPI

---

## 📎 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/salary-prediction.git
   cd salary-prediction
2. Install required packages:
   ```bash
   pip install -r requirements.txt
3.Launch the notebook:
  ```bash
   jupyter notebook Salary\ Prediction.ipynb

