# 🏥 Medical Insurance Cost Prediction using Regression Models

## 📌 Project Overview

This project predicts medical insurance charges based on demographic and health-related factors using machine learning regression models.

The objective is to compare the performance of:

- Linear Regression
- Ridge Regression
- Lasso Regression

---

## 📂 Dataset

The dataset contains information about insurance beneficiaries, including:

- Age
- Sex
- BMI
- Number of Children
- Smoking Status
- Region
- Medical Insurance Charges (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Missing value check
- Statistical summary
- Distribution of insurance charges
- Correlation heatmap
- Feature relationships

---

## ⚙️ Data Preprocessing

- One-Hot Encoding
- Train-Test Split
- Feature Scaling using StandardScaler

---

## 🤖 Models Implemented

### 1. Linear Regression

A baseline regression model for predicting insurance charges.

### 2. Ridge Regression

Uses L2 regularization to reduce overfitting.

### 3. Lasso Regression

Uses L1 regularization and performs feature selection.

---

## 📈 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 📌 Key Findings

- Smoking status is the strongest predictor of insurance charges.
- Age and BMI significantly influence medical costs.
- Ridge Regression improves model stability.
- Lasso Regression performs feature selection by shrinking less important coefficients.
- The regression models provide reliable predictions for insurance charges.

---

## 📷 Sample Visualizations

- Distribution of Charges
- Correlation Heatmap
- Actual vs Predicted Charges
- Model Comparison
- Feature Importance

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Medical-Insurance-Cost-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

4. Run all cells.

---

## 📁 Repository Structure

```
Medical-Insurance-Cost-Prediction
│
├── Medical_Insurance_Cost_Prediction.ipynb
├── insurance.csv
├── requirements.txt
├── README.md
└── images/
```

---

## 👤 Author

**Souri Sarkar**

