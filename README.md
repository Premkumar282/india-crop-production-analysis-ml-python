# 🌾 Crop Production Analysis using Machine Learning

This project focuses on analyzing agricultural crop production across India using data science and machine learning techniques. The goal is to understand key factors influencing production and build predictive models for better insights.

---

## 📌 Project Overview

Agriculture plays a vital role in the economy, but production patterns vary due to multiple factors such as area, crop type, season, and region.

This project explores:
- What drives crop production?
- Can machine learning accurately predict production?
- How do different factors influence agricultural output?

---

## 📊 Dataset

- Source: Government of India Open Data Portal (data.gov.in)
- Contains data on:
  - States
  - Crops
  - Seasons
  - Area under cultivation
  - Production

---

## 🛠️ Workflow

### 🔹 Data Preprocessing
- Removed missing values
- Filtered invalid entries (zero/negative values)
- Cleaned dataset for analysis

### 🔹 Feature Engineering
- Created new feature: **Yield (Production / Area)**
- Applied **log transformation** to handle skewed data

### 🔹 Exploratory Data Analysis (EDA)
- Distribution analysis of production
- Area vs production relationship
- Top crops analysis
- Seasonal variation analysis
- Correlation heatmap

---

## 🤖 Machine Learning Models

### 📈 Regression Models
- **Linear Regression**
  - Captures general trend
  - Moderate performance

- **Random Forest Regressor (Main Model)**
  - Captures complex patterns
  - Best performing model

### 📊 Classification Model
- **Logistic Regression**
  - Categorizes production into:
    - Low
    - Medium
    - High

---

## 📊 Model Performance

| Model | Metric |
|------|--------|
| Linear Regression | Moderate R² |
| Random Forest | High R² (Strong Performance) |
| Logistic Regression | ~78% Accuracy |

---

## 📈 Key Insights

- Crop production is **strongly influenced by cultivated area**
- A few crops dominate total agricultural output
- Production varies significantly across seasons
- Agricultural data is highly skewed → transformation improves analysis
- Machine learning effectively captures production patterns

---

## 📊 Visualizations

The project includes:
- Production distribution (log scale)
- Area vs Production scatter plot
- Top crops bar chart
- Season-wise boxplot
- Correlation heatmap
- Confusion matrix

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---


---

## 🎯 Conclusion

This project demonstrates how data science and machine learning can be applied to agricultural data to uncover meaningful insights and build predictive models. Random Forest proved to be the most effective model for this dataset.

---

## 🔗 Connect

If you found this project interesting or have suggestions, feel free to connect or share your feedback!