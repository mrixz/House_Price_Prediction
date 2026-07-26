# 🏠 House Price Prediction using Multiple Linear Regression

## 📖 Overview

This project predicts house prices using **Multiple Linear Regression**, one of the fundamental supervised machine learning algorithms.

The project demonstrates the complete machine learning pipeline, from downloading the dataset using the Kaggle API to preprocessing, feature engineering, model training, prediction, and evaluation.

This project is part of my **Machine Learning Learning Series**, where I learn ML concepts by building practical projects.

---

## 🎯 Objectives

- Learn Multiple Linear Regression
- Understand data preprocessing techniques
- Perform feature engineering
- Train and evaluate a regression model
- Interpret regression metrics

---

## 🚀 Features

- 📥 Dataset downloaded automatically using Kaggle API
- 📊 Exploratory Data Analysis (EDA)
- 🧹 Missing Value Handling
- 🔤 One-Hot Encoding
- ⚙️ Feature Engineering
- 📏 Feature Scaling using StandardScaler
- ✂️ Train-Test Split
- 📈 Multiple Linear Regression Model
- 📉 Model Evaluation
- 📋 Feature Coefficient Analysis
- 🔍 Actual vs Predicted Price Comparison

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Kaggle API

---

## 📂 Project Structure

```
House_Price_Prediction/
│
├── House_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 📊 Machine Learning Workflow

1. Install and configure Kaggle API
2. Download dataset
3. Load dataset
4. Explore dataset
5. Handle missing values
6. Encode categorical variables
7. Perform feature engineering
8. Scale features
9. Split dataset into training and testing sets
10. Train Multiple Linear Regression model
11. Predict house prices
12. Evaluate model performance

---

## 📈 Model Performance

| Metric | Value |
|---------|-------|
| Mean Absolute Error (MAE) | **970,043.40** |
| Mean Squared Error (MSE) | **1,754,318,687,330.67** |
| Root Mean Squared Error (RMSE) | **1,324,506.96** |
| R² Score | **0.6529** |

### 📌 Model Fit

The Multiple Linear Regression model achieved an **R² Score of 0.6529**, meaning it explains approximately **65.3% of the variance** in house prices.

> **Note:** Regression models do not use "Accuracy" as an evaluation metric. The R² Score is the standard metric used to evaluate regression performance.

---

## 📚 Concepts Learned

- Multiple Linear Regression
- Data Cleaning
- Handling Missing Values
- One-Hot Encoding
- Feature Engineering
- Feature Scaling
- Train-Test Split
- Model Training
- Model Prediction
- Regression Evaluation Metrics

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/House_Price_Prediction.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Download Kaggle API Key

- Log in to Kaggle.
- Go to **Account**.
- Click **Create New API Token**.
- A `kaggle.json` file will be downloaded.

### 4. Run the notebook

Open `House_Price_Prediction.ipynb` in **Google Colab** or **Jupyter Notebook**.

The notebook will:

- Configure the Kaggle API
- Download the dataset automatically
- Train the model
- Evaluate the model

---

## 📌 Dataset

The dataset is downloaded directly using the **Kaggle API** at runtime.

No manual dataset download is required.

---

## 🔮 Future Improvements

- Polynomial Regression
- Decision Tree Regression
- Random Forest Regression
- XGBoost Regression
- Hyperparameter Tuning
- Model Deployment using Flask or Streamlit

---

## 👨‍💻 Author

**T S Mridul Narayanan**

Computer Science Engineering Student

Machine Learning Learning Series

Project 2: House Price Prediction using Multiple Linear Regression

---

## ⭐ If you found this project useful

Give this repository a ⭐ on GitHub if you found it helpful or learned something from it!
