# 🚗 Car Sales Prediction using PySpark

This project was developed as a **collaborative effort** with my friends **Kundan** and **Uday**.  
It focuses on analyzing, cleaning, and modeling car sales data using **Apache Spark (PySpark)**, demonstrating an end-to-end big data machine learning workflow.

---

## 📁 Project Structure
```
📁 Car_Sales_Prediction  
├─ Car_Sales_Prediction.ipynb  
├─ car_sales_data.csv  
├─ requirements.txt  
└─ README.md
```
---

## 🧠 Project Overview

The main objective of this project is to:
- Perform large-scale data preprocessing using PySpark
- Conduct exploratory data analysis (EDA)
- Build machine learning models for:
  - **Price category classification (Low / Medium / High)**
  - **Car price prediction using regression**

This project highlights the use of **big data tools** for real-world predictive analytics.

---

## 🛠️ Tech Stack

- Python  
- Apache Spark (PySpark)  
- Spark MLlib  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📊 Dataset Description

The dataset includes various attributes related to car sales, such as:
- Manufacturer
- Model
- Fuel Type
- Mileage
- Engine specifications
- Price

The raw dataset contains missing values, inconsistent formats, and outliers, which are addressed during preprocessing.

---

## 🧹 Data Cleaning & Preprocessing

Using PySpark, the following steps were performed:
- Removal of duplicate records
- Handling missing and invalid values
- Identification of numerical and categorical features
- Outlier detection using the **Interquartile Range (IQR)** method
- Feature scaling using **Z-score normalization**
- Creation of a cleaned dataset for modeling

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted using PySpark and Pandas to:
- Analyze feature distributions
- Study correlations between numerical variables
- Identify top car manufacturers
- Examine mileage vs price relationships
- Visualize outliers and price variations
- Segment car prices into tiers

---

## 🧪 Feature Engineering

- Created a **Price_Tier** feature (Low, Medium, High) using price quartiles
- Applied **One-Hot Encoding** for categorical variables
- Assembled feature vectors using `VectorAssembler`

---

## 🤖 Machine Learning Models

### 1️⃣ Classification – Price Tier Prediction
- Model: Multinomial Logistic Regression (Softmax)
- Target Variable: `Price_Tier`
- Evaluation Metrics:
  - Accuracy
  - Confusion Matrix

---

### 2️⃣ Regression – Car Price Prediction
- Model: Random Forest Regressor
- Target Variable: `Price`
- Evaluation Metrics:
  - RMSE
  - MAE
- Compared actual vs predicted prices

---

## 📈 Results

- The classification model effectively predicts car price categories.
- The regression model captures non-linear relationships between features and price.
- PySpark enables scalable and efficient processing of large datasets.

---

## 🚀 How to Run the Project

1. Open the notebook in Google Colab or a local Spark environment
2. Install dependencies:
   ```bash
   pip install pyspark
   ```

---

## 👤 Author 

**Chakradhar Peddavenkatagari** 

Aspiring AI Engineer

Masters in Computer Science

The State University of New York at Buffalo 
