# 🏥 Medical Insurance Cost Prediction using Regression Models

Predicting medical insurance charges using **Linear Regression**, **Ridge Regression**, and **Lasso Regression**.

---

## 📌 Project Overview

The objective of this project is to predict **medical insurance charges** based on demographic and health-related factors. The project includes data preprocessing, exploratory data analysis (EDA), model building, and performance comparison of three regression algorithms.

---

## 🎯 Objectives

- Analyze factors affecting insurance charges.
- Build a baseline Linear Regression model.
- Apply Ridge and Lasso Regression to reduce overfitting.
- Compare model performance using evaluation metrics.
- Identify the most influential features affecting insurance costs.

---

## 📂 Dataset

The dataset contains **1,338 records** with the following features:

| Feature | Description |
|---------|-------------|
| Age | Age of the beneficiary |
| Sex | Gender of the beneficiary |
| BMI | Body Mass Index |
| Children | Number of dependents |
| Smoker | Smoking status |
| Region | Residential region |
| Charges | Medical insurance charges (Target Variable) |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Missing Value Check
- Statistical Summary
- Distribution of Insurance Charges
- Correlation Heatmap
- Feature Relationships

---

## ⚙️ Data Preprocessing

- One-Hot Encoding
- Train-Test Split (80:20)
- Feature Scaling using StandardScaler

---

## 🤖 Machine Learning Models

### 1️⃣ Linear Regression

- Baseline regression model.
- Predicts insurance charges using all input features.

### 2️⃣ Ridge Regression

- Uses **L2 Regularization**.
- Reduces overfitting by shrinking coefficient values.

### 3️⃣ Lasso Regression

- Uses **L1 Regularization**.
- Performs automatic feature selection by shrinking less important coefficients to zero.

---

## 📊 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 📈 Key Insights

- 🚬 Smoking status is the strongest predictor of insurance charges.
- 👤 Older individuals tend to have higher insurance costs.
- ⚖️ Higher BMI is associated with increased medical expenses.
- 👨‍👩‍👧‍👦 The number of children has a relatively small impact.
- 📉 Ridge Regression improves model stability through regularization.
- ✂️ Lasso Regression simplifies the model by reducing less important coefficients.

---

## 📷 Visualizations

The notebook includes:

- Distribution of Charges
- Correlation Heatmap
- Actual vs Predicted Charges
- Model Comparison
- Feature Importance

---

## 📁 Project Structure

```
Medical-Insurance-Cost-Prediction/
│
├── Medical_Insurance_Cost_Prediction.ipynb
├── insurance.csv
├── requirements.txt
├── README.md
└── images/
```

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/Souri-Sarkar/Medical-Insurance-Cost-Prediction.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📌 Conclusion

This project demonstrates how regression techniques can effectively predict medical insurance charges. Among the factors analyzed, **smoking status**, **age**, and **BMI** were found to have the greatest influence on insurance costs. The comparison of Linear Regression, Ridge Regression, and Lasso Regression highlights the benefits of regularization in improving model stability and reducing overfitting.

---

## 👤 Author

**Souri Sarkar**

- GitHub: https://github.com/Souri-Sarkar
