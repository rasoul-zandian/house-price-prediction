
# 🏠 House Sales Price Prediction - Final Project (IBM Data Analyst Certificate)

## 🚀 Project Overview

This project is part of the final assignment in the **IBM Data Analyst Professional Certificate** (Course 7).  
As a Data Analyst working for a Real Estate Investment Trust, I was tasked with developing a model to **predict house prices** based on various features such as square footage, number of bedrooms, number of floors, and more.

The dataset contains **21,000+ property sales in King County, USA (including Seattle)**, sold between May 2014 and May 2015.  
The objective was to **clean, explore, and model this data** to determine how different factors influence housing prices and to build predictive models with strong generalization performance.

### 🧠 Key Skills Demonstrated

- **Data Wrangling** using Pandas  
- **Exploratory Data Analysis (EDA)** with Seaborn and Matplotlib  
- **Feature Engineering** including Polynomial Feature Expansion  
- **Model Development** using Linear and Ridge Regression (with Regularization)  
- **Performance Evaluation** using R² score  
- **Pipeline Design** for modular and reusable modeling  

This notebook serves as a **practical demonstration of my ability** to:
- Work with real-world datasets  
- Preprocess and clean data  
- Apply statistical and machine learning techniques  
- Interpret and visualize insights  
- Communicate findings effectively through code and visuals  

---

## ⚙️ How to Run the Project

### 🔗 Requirements

You’ll need the following Python packages installed:

```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
```

You can install them via pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### ▶️ Instructions

1. Clone this repository:

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

2. Launch the notebook in Jupyter:

```bash
jupyter notebook Final_Project_House_Sales.ipynb
```

3. Run the cells in sequence to:
   - Load and explore the dataset  
   - Clean the data  
   - Build and evaluate multiple regression models  
   - Interpret the results

---

## 📈 Results

- **Linear Regression with single feature (`sqft_living`)**: R² ≈ 0.49  
- **Multiple Linear Regression with 11 features**: R² ≈ 0.65  
- **Polynomial + Ridge Regression (degree=2, α=0.1)**: **R² ≈ 0.75**

The best-performing model used a combination of polynomial transformation and regularized regression, indicating strong non-linear relationships between features and house price.

---

## 💼 Why This Project Matters

This project gave me hands-on experience with the full data analysis lifecycle—from data cleaning and visualization to **model development and evaluation**.  
It reflects my practical skills in **Python-based data science workflows**, and my ability to build reproducible, readable, and interpretable machine learning solutions.

---
