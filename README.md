# HRVitals_Predictive-People-Analytics-for-Clinics

A data-driven project focused on understanding and predicting employee well-being and turnover at FAU Clinic. Using real-world HR datasets, this project applies machine learning and statistical techniques to uncover insights and support better people management decisions in a clinical setting.

---

## 🧠 Project Overview

This project explores two key HR challenges in healthcare:

- **Employee Well-Being**: Analyzing factors that influence work-life balance and stress levels.
- **Employee Turnover**: Predicting which employees are likely to leave and understanding why.

Through data preprocessing, visualization, and predictive modeling, this project demonstrates the power of **People Analytics** in improving organizational outcomes.

---

## 📂 Project Structure

## 📊 Datasets

- `fau_clinic_employee_wellbeing.csv`  
  Contains data on stress levels, time for hobbies, awards, and more — all factors contributing to **Work-Life Balance**.

- `fau_clinic_turnover_data.csv`  
  Includes job satisfaction, salary levels, patient load, and other metrics linked to **employee turnover**.


## 🛠️ Technologies Used

- Python 🐍
- pandas, numpy
- seaborn, matplotlib
- scikit-learn
- statsmodels

---

## 🤖 Machine Learning Models

- **Linear Regression** for predicting **Work-Life Balance Score**
- **Random Forest Classifier** for predicting **Employee Turnover**

Both models achieved strong performance:
- `R² score for Well-Being Prediction`: **0.85**
- `Random Forest Accuracy for Turnover`: **99%**, with high precision & recall

---

## 📈 Key Insights

- **Well-Being**: 
  - Stress is higher among middle-aged employees.
  - Males spend slightly more time on hobbies than females.
  - Achievement and task completion are highly correlated with better Work-Life Balance.

- **Turnover**:
  - Low job satisfaction is the strongest predictor of employee exit.
  - Overload (patients * working hours) is another key driver of attrition.
  - Most employees who leave do so within 4 years.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/HRVitals.git
   cd HRVitals
