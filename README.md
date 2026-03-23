# 🏦 Housing Finance Loan Approval Prediction

![R](https://img.shields.io/badge/Language-R-blue?style=for-the-badge\&logo=r)
![Machine Learning](https://img.shields.io/badge/Model-Logistic%20Regression-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-74%25-brightgreen?style=for-the-badge)

---

## 📌 Overview

This project predicts whether a housing loan application will be **approved or rejected** using Logistic Regression.
It leverages financial and demographic data to help financial institutions make **data-driven decisions**.

---

## 🎯 Objectives

* Analyze housing finance dataset
* Perform data preprocessing & feature engineering
* Build Logistic Regression model
* Evaluate model using accuracy & ROC curve

---

## 📊 Dataset Features

The dataset includes key attributes such as:

* 💰 Income to Asset Ratio (IAR)
* 📉 Loan to Value Ratio (LTV)
* 📊 Fixed Obligation to Income Ratio (FOIR)
* 🏢 Employer Type
* 🏦 Bank Savings
* 💍 Marital Status
* 🎯 Loan Decision (Target Variable)

---

## 🛠️ Tools & Technologies

* **Language:** R
* **IDE:** RStudio
* **Libraries:**

  * fastDummies
  * corrplot
  * caTools
  * car
  * ROCR

---
## Dataset
https://1drv.ms/x/c/f483042b9735aab9/IQCcLU9hPxEoSKeUcyso96AtAXgJrAD9s0hlR95DtLMv7L4?e=NLESkm

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Converted categorical variables into numerical format
* Used label encoding & dummy variables

### 2️⃣ Feature Engineering

* Correlation analysis to detect relationships & multicollinearity

### 3️⃣ Train-Test Split

* 70% Training Data
* 30% Testing Data

### 4️⃣ Model Building

* Built Logistic Regression using `glm()` function

### 5️⃣ Model Evaluation

* Confusion Matrix
* ROC Curve
* Accuracy Score

---

## 📈 Results

* ✅ Achieved **~74% accuracy**
* 📊 Key influencing features:

  * Income to Asset Ratio
  * Loan to Value Ratio
  * FOIR
  * Employer Type
  * Bank Savings

---

## 📷 Visualizations
* Correlation Matrix
* <img width="621" height="540" alt="image" src="https://github.com/user-attachments/assets/7222ea28-8d15-4587-b223-aa364f9a6837" />

* Confusion Matrix
* <img width="940" height="206" alt="image" src="https://github.com/user-attachments/assets/eef2fdab-681b-435a-83d4-a768fb75ce3b" />

* ROC Curve
* <img width="940" height="832" alt="image" src="https://github.com/user-attachments/assets/609885e6-a8dd-4034-afd3-6f88f3255908" />
---

## 🚀 How to Run

```r
# Install required libraries
install.packages(c("fastDummies","corrplot","caTools","car","ROCR"))

# Load dataset
data <- read.csv("your_dataset.csv")

# Run model (example)
model <- glm(Decision ~ ., data=data, family=binomial)
summary(model)
```
Can also use this R file
https://1drv.ms/u/c/f483042b9735aab9/IQCoIaLp1xnLSpKp9u3DH53DATKkz6ZvZk8x2qu98uoli0E?e=zp0not
---

## 📌 Key Insights

* Logistic Regression effectively predicts loan approval decisions
* Financial ratios play a major role in decision-making
* Machine learning improves accuracy and reduces manual effort

---

## 🔮 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy as a web app (Shiny)
* Improve accuracy with feature selection

---

## 🙌 Author

**Dhathri Narne**
📊 Data Analyst | Machine Learning Enthusiast

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
