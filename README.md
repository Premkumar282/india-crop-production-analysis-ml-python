# AQI Pollution Recovery Analysis using Machine Learning

## 📌 Overview
This project analyzes Air Quality Index (AQI) trends across Indian states and cities using real-world government data. The goal is to understand pollution patterns and evaluate how effectively regions recover after pollution spikes.

The project combines Exploratory Data Analysis (EDA), visualization, and machine learning models to generate insights into air quality behavior.

---

## 📊 Dataset
- Source: Government of India Open Data Portal (data.gov.in)
- Organization: CPCB (Central Pollution Control Board)
- Time Period: 2022–2025
- Records: 2,35,785+
- Coverage: 32 States, 291 Cities

---

## 🔍 Objectives
- Analyze AQI trends across time and regions  
- Identify high pollution areas  
- Understand seasonal variation in AQI  
- Build models to predict AQI and classify pollution levels  

---

## 🛠️ Project Workflow

### 1. Data Cleaning
- Converted date column to datetime  
- Removed duplicates  
- Dropped unnecessary columns (unit, note)  

### 2. Exploratory Data Analysis (EDA)
- Analyzed dataset structure and statistics  
- Identified missing values and patterns  

### 3. Data Visualization
- AQI distribution analysis  
- City-wise pollution comparison  
- Seasonal and time-based trends  
- Correlation analysis  

### 4. Feature Engineering
- Extracted month and year from date  
- Created pollution category and binary flag  

### 5. Machine Learning Models

#### 🔹 Linear Regression
- Purpose: Predict AQI values  
- Evaluation:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - R² Score  
- Result: Moderate performance (R² ≈ 0.21)

#### 🔹 Logistic Regression
- Purpose: Classify AQI as polluted or not  
- Evaluation:
  - Accuracy
  - Precision
  - Recall
  - F1 Score  
- Result: Moderate classification performance (~68% accuracy)

---

## 📊 Key Insights
- AQI values are right-skewed, indicating frequent high pollution events  
- Winter months show higher pollution levels  
- Certain cities consistently experience higher AQI  
- Models capture general trends but not full variability  
- External factors like weather significantly influence AQI  

---

## 🧠 Conclusion
AQI prediction is a complex problem influenced by multiple environmental factors. While machine learning models provide useful insights, accurate prediction requires additional data such as weather and emission sources.

---

## 🧾 Technologies Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔗 Project Link
GitHub Repository: [Paste your repo link here]

---

## 📌 Author
Prem Kumar