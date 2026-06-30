# 🏠 House Price Prediction using Regression

An end-to-end Machine Learning regression project that analyzes various factors affecting house prices and predicts house prices using Linear Regression and Regularized Regression techniques.

---

## 📌 Project Overview

The goal of this project is to analyze the housing dataset, identify the factors that influence house prices, and build regression models capable of accurately predicting house prices.

This project follows a complete Machine Learning workflow, from data exploration to model evaluation.

---

# 🎯 Problem Statement

The objective is to build a regression model that can predict the selling price of a house based on its characteristics such as:

- Area
- Number of Bedrooms
- Bathrooms
- Stories
- Parking
- Air Conditioning
- Furnishing Status
- Basement
- Preferred Area
- and other housing features.

---

# 📂 Dataset Information

- **Total Records:** 545 Houses
- **Features:** 13
- **Target Variable:** Price

### Features

| Feature | Description |
|----------|-------------|
| area | Area of the house |
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| stories | Number of floors |
| mainroad | Connected to main road |
| guestroom | Guest room available |
| basement | Basement available |
| hotwaterheating | Hot water heating |
| airconditioning | Air conditioning |
| parking | Parking spaces |
| prefarea | Preferred residential area |
| furnishingstatus | Furnishing level |
| price | Target Variable |

---

# 🚀 Project Workflow

```text
Dataset
    │
    ▼
Data Understanding
    │
    ▼
Exploratory Data Analysis (EDA)
    │
    ▼
Data Cleaning
    │
    ▼
Outlier Treatment
    │
    ▼
Feature Encoding
    │
    ▼
Train-Test Split
    │
    ▼
Linear Regression (Baseline)
    │
    ▼
Regularized Regression Models
    │
    ▼
Model Evaluation
```

---

# 📊 Exploratory Data Analysis (EDA)

Several visualizations were performed to understand the dataset before training the models.

### Key Findings

### 📈 Price Distribution

- Most houses belong to the low and medium price range.
- Price distribution is positively skewed.
- Few luxury houses create outliers.

---

### 📐 Area vs Price

- Larger houses generally have higher prices.
- Strong positive relationship between area and price.

---

### 🚿 Bathrooms vs Price

- Houses with more bathrooms tend to have higher selling prices.

---

### 🛏 Bedrooms vs Price

- Selling price generally increases with the number of bedrooms.

---

### 🔥 Correlation Analysis

Strong positive correlation observed between Price and:

- Area
- Bathrooms
- Stories
- Air Conditioning

---

# 🛠 Data Preprocessing

The following preprocessing techniques were applied:

- Checked missing values
- Removed outliers using IQR
- Encoded categorical variables
- Converted binary values into numerical values
- Prepared data for regression models

---

# 🤖 Machine Learning Models

The following regression models were implemented.

## ✅ Linear Regression

- Used as the baseline model
- Evaluated using R² Score and RMSE
- Residual analysis performed

---

## ✅ Ridge Regression

- Standardized data
- Hyperparameter tuning using GridSearchCV
- Performance comparison with baseline model

---

## ✅ Lasso Regression

- Hyperparameter tuning
- Automatic feature selection capability

---

## ✅ Elastic Net Regression

- Combination of Ridge and Lasso Regularization
- Compared with previous regression models

---

# 📈 Model Performance

| Model | Test R² Score | Test RMSE |
|--------|--------------:|----------:|
| Linear Regression | 0.677 | 965432 |
| Ridge Regression | 0.674 | 968776 |
| Lasso Regression | 0.674 | 965430 |
| Elastic Net | 0.675 | 1001841 |

> **Observation:**  
> Linear Regression achieved the best overall performance on this dataset. Regularization did not significantly improve prediction accuracy, indicating that the baseline model already generalized well.

---

# 📉 Model Evaluation

The models were evaluated using:

- R² Score
- RMSE
- Actual vs Predicted Plot
- Residual Distribution
- Residual Density Plot

Residual analysis indicates that errors are approximately centered around zero, suggesting a reasonably good model fit.

---



# 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn



---

# 📌 Future Improvements

- Feature Engineering
- Cross Validation
- Pipeline Implementation
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- XGBoost Regression
- Hyperparameter Optimization
- Model Deployment using Streamlit

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Outlier Detection
- Feature Encoding
- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Model Evaluation
- Residual Analysis

---

# 👨‍💻 Author

**Keshav Sahu(KC)**

First Machine Learning Regression Project

Always learning, improving, and building real-world Data Science projects.

⭐ If you found this project interesting, feel free to star the repository.