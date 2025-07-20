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
   <img width="943" height="454" alt="image" src="https://github.com/user-attachments/assets/66c85522-6630-44a8-88bf-af3218cff582" />

  - BMI vs Charges
   <img width="944" height="452" alt="image" src="https://github.com/user-attachments/assets/a59ee318-2483-4e71-8e6f-b169d1074eca" />

  - Smoker vs Non-Smoker cost comparison
   <img width="942" height="456" alt="image" src="https://github.com/user-attachments/assets/746a3866-f98d-4850-ba17-50ecc0dd6b25" />

  - Correlation Heatmap
   <img width="771" height="536" alt="image" src="https://github.com/user-attachments/assets/4c8d1f02-8048-4d30-bbaf-563c29a16288" />


- 📐 **Linear Regression Model**:
  - Implementation (without and with using `LinearRegression` from sklearn seperately)
  - Cost vs Age prediction for non-smokers
  - Model performance evaluation using MSE

---
- 🧮 **RMSE Evaluation**:
  - **Non-Smokers**: RMSE =  4662.505766636395
   <img width="883" height="536" alt="image" src="https://github.com/user-attachments/assets/9e665d62-271c-4523-82eb-1c27618e37a6" />

  - **Smokers**: RMSE = 24338.502872599212
   <img width="888" height="536" alt="image" src="https://github.com/user-attachments/assets/b4654356-427d-4cab-9e0b-97e58e1dcad5" />

  - Calculated using `LinearRegression` 
  
---


## 👩‍💻 Author

**Fatima Zafar Rizvi**  
🔗 [GitHub Profile](https://github.com/fatimazafarrizvi)  
📬 Feel free to star ⭐ the repo if you found it useful!

---

> “Learning by doing is the best way to truly understand ML algorithms.”

