# 👗 Women's Clothing Customer Analytics

## 📌 Project Overview

This project analyzes women's clothing e-commerce reviews to understand customer satisfaction, recommendation behavior, age patterns, department performance, and product popularity.

The project combines **Python, Machine Learning, and Power BI** to generate useful customer and product insights.

## 🎯 Objectives

- Analyze customer ratings
- Study recommendation behavior
- Understand customer age patterns
- Compare department performance
- Identify popular clothing categories
- Analyze positive feedback
- Build a recommendation prediction model
- Present insights using Power BI

## 📊 Key Analysis

### Customer Ratings
Analyzes the distribution of customer ratings and overall satisfaction.

### Recommendation Analysis
Measures how many customers recommend products and identifies factors associated with recommendations.

### Department Performance
Compares departments using review count and average rating.

### Clothing Class Analysis
Identifies the most frequently reviewed clothing categories.

### Customer Age Analysis
Examines the age distribution of customers.

## 🤖 Machine Learning

A **Decision Tree Classifier** is used to predict whether a customer will recommend a product.

Features used:

- Age
- Rating
- Positive Feedback Count

The original capstone run recorded approximately **93% test accuracy**.

## 📈 Original Analysis Results

The original project analysis contained approximately:

- **23,472 cleaned reviews**
- Average Rating: **4.20**
- Recommendation Rate: **82.23%**
- `Tops` as the department with the largest review volume
- `Dresses` and `Knits` among the most frequently reviewed clothing classes

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Power BI

## 📁 Repository Files

- `01_Womens_Clothing_Customer_Analysis.ipynb` — Python analysis and ML notebook
- `Womens_Clothing_Customer_Analytics.pbix` — Power BI dashboard
- `requirements.txt` — Python dependencies
- `.gitignore` — Git configuration

## ▶️ How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
