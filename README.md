# 🏥 MedCost_Predictor using Linear Regression

A Python-based machine learning project to predict **medical insurance costs** using linear regression. This notebook performs exploratory data analysis, feature visualization, and regression modeling on real-world healthcare data.

---

## 📌 Project Objectives

- Understand how different factors like age, BMI, and smoking habits affect medical insurance charges.
- Visualize key relationships using interactive and static charts.
- Implement linear regression from scratch to model healthcare cost predictions.
- Evaluate model performance using error metrics.

---

## 📊 Dataset

The dataset [medical.csv](https://github.com/fatimazafarrizvi/Machine-Learning/blob/main/medical.csv) contains the following columns:

- `age`: Age of the individual
- `sex`: Gender (`male`, `female`)
- `bmi`: Body Mass Index
- `children`: Number of dependents
- `smoker`: Smoking status (`yes`, `no`)
- `region`: Residential area in the US
- `charges`: Medical insurance cost (target variable)

---

## 🛠️ Tools & Technologies

- Python 3
- NumPy, Pandas
- Matplotlib, Seaborn, Plotly
- scikit-learn
- Jupyter Notebook

---

## 📈 Key Features

- 🔍 **Data Exploration**: Summary statistics and categorical analysis
- 📊 **Visualizations**:
  - Age vs Charges
  - BMI vs Charges
  - 
  - Smoker vs Non-Smoker cost comparison
  - Correlation Heatmap
  - <img width="766" height="534" alt="image" src="https://github.com/user-attachments/assets/238d58d0-e2e8-44e9-9734-4e727b45f434" />

- 📐 **Linear Regression Model**:
  - Implementation (without and with using `LinearRegression` from sklearn seperately)
  - Cost vs Age prediction for non-smokers
  - Model performance evaluation using MSE

---
- 🧮 **RMSE Evaluation**:
  - **Non-Smokers**: RMSE =  4662.505766636395
  - <img width="882" height="533" alt="image" src="https://github.com/user-attachments/assets/e31cef0c-a5b0-474d-9033-d42e88e9b59b" />
  - **Smokers**: RMSE = 24338.502872599212
  - <img width="882" height="533" alt="image" src="https://github.com/user-attachments/assets/335c4211-8385-4d96-ba72-cc27bb3762cd" />
  - Calculated using `LinearRegression` 
  
---


## 👩‍💻 Author

**Fatima Zafar Rizvi**  
🔗 [GitHub Profile](https://github.com/fatimazafarrizvi)  
📬 Feel free to star ⭐ the repo if you found it useful!

---

> “Learning by doing is the best way to truly understand ML algorithms.”

