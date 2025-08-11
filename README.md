# 📚 Grade Forecast – Student Marks Prediction

## 📌 Project Overview
**Grade Forecast** is a machine learning project designed to predict student marks based on the number of courses taken and the time spent studying.  
Using **Multiple Linear Regression**, the model learns from historical data to forecast marks with high accuracy.

---

## 🎯 Objectives
- Understand and implement **Supervised Learning** algorithms.
- Explore the difference between **Simple** and **Multiple Linear Regression**.
- Evaluate model performance using **R² Score** and **Mean Squared Error**.

---

## 📂 Dataset
The dataset contains three columns:
- `number_courses` → Number of courses taken by the student.
- `time_study` → Hours spent studying.
- `Marks` → Actual marks obtained.

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas 📊
- NumPy ➗
- Matplotlib 🎨
- Scikit-learn 🤖

---

## 📈 Model Performance
- **R² Score**: `0.946` → The model explains ~94.6% of the variance in marks.
- **Mean Squared Error**: `14.20` → On average, predictions are ~3.77 marks off (sqrt of MSE).

---

## 🚀 Workflow
1. **Data Loading** – Import dataset using Pandas.
2. **Data Exploration** – Check structure, summary statistics, and correlations.
3. **Feature Selection** – Choose relevant features for prediction.
4. **Train-Test Split** – Divide dataset into training and testing sets.
5. **Model Training** – Fit Multiple Linear Regression model.
6. **Prediction** – Predict marks for test data.
7. **Evaluation** – Calculate R² Score & MSE.
8. **Visualization** – Plot predictions vs actual marks.

---

## 📊 Example Prediction
| number_courses | time_study | Predicted Marks |
|---------------|------------|----------------|
| 5             | 4.5        | 88.2           |
| 3             | 2.0        | 65.4           |

---

## 🏆 Learning Outcomes
- Hands-on experience with **Multiple Linear Regression**.
- Understanding **model evaluation metrics**.
- Ability to **forecast continuous values** using machine learning.

---

## 📜 License
This project is created for learning purposes and is open to use and modify.

---
✍️ **Author**:
   Shalini Saurav
– Data Science Enthusiast 🚀
