# 📈 ApexPlanet Data Analytics Internship – Task 4

## 🎯 Project Overview
This repository contains **Task 4 – Advanced Analytics** completed as part of the **ApexPlanet Data Analytics Internship**.

Using the **Superstore Sales** dataset, this project applies statistical analysis, time series forecasting, customer segmentation, and machine learning techniques to extract actionable business insights and build predictive models.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **SciPy** – Statistical hypothesis testing
- **Scikit-learn** – K-Means Clustering, PCA & Logistic Regression
- **Statsmodels** – Time Series Analysis
- **Matplotlib & Seaborn** – Data Visualization

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `notebooks/04_task.ipynb` | Complete notebook containing statistical analysis, forecasting, clustering, and predictive modeling |
| `reports/png/10_timeseries_decomposition.png` | Trend, seasonality and residual components |
| `reports/png/11_moving_average_forecast.png` | 3-Month Moving Average Forecast |
| `reports/png/12_elbow_method.png` | Optimal number of clusters using Elbow Method |
| `reports/png/13_pca_cluster_visualization.png` | Customer Segmentation using PCA |
| `reports/png/14_confusion_matrix.png` | Logistic Regression model evaluation |
| `reports/png/15_feature_importance.png` | Feature importance visualization |

---

## 📊 Statistical Analysis

### Descriptive Statistics

Computed key statistical measures including:

- Mean
- Median
- Mode
- Standard Deviation
- Skewness

for all numerical features.

### Hypothesis Testing

Performed:

- Independent **T-Test** (Discounted vs Non-Discounted Orders)
- **Chi-Square Test** (Region vs Category)
- **95% Confidence Interval** for Profit Margin

---

## 📈 Time Series Analysis

Analyzed **48 months** of sales data to identify long-term patterns.

### Performed

- Time Series Decomposition
- Trend Analysis
- Seasonality Analysis
- Residual Analysis
- 3-Month Moving Average Forecast

---

## 👥 Customer Segmentation

Implemented **K-Means Clustering** to identify customer groups.

### Process

- Data Scaling
- Elbow Method
- K-Means Clustering
- PCA Visualization

### Customer Segments

| Cluster | Segment | Business Strategy |
|----------|----------|------------------|
| 0 | Champions | Loyalty rewards & premium engagement |
| 1 | Loyal / High Potential | Upselling & cross-selling |
| 2 | Developing | Targeted promotions |
| 3 | At-Risk | Re-engagement campaigns |

---

## 🤖 Predictive Modeling

Built a **Logistic Regression** model to predict whether an order would be profitable.

### Model Configuration

- Binary Classification
- Train-Test Split: **80/20**
- Logistic Regression

### Model Performance

| Metric | Score |
|--------|-------:|
| Accuracy | **94.38%** |
| Precision | **94.48%** |
| Recall | **99.76%** |

---

## 💡 Business Insights

- Identified statistically significant relationships between discount and profitability.
- Forecasted future sales trends using historical sales data.
- Segmented customers into four actionable business groups.
- Built a predictive model capable of identifying profitable orders with high accuracy.
- Enabled data-driven decision-making through statistical and machine learning techniques.

---

## 🚀 Skills Demonstrated

- Statistical Analysis
- Hypothesis Testing
- Time Series Forecasting
- Customer Segmentation
- K-Means Clustering
- Principal Component Analysis (PCA)
- Logistic Regression
- Machine Learning
- Predictive Analytics
- Python
- Scikit-learn
- SciPy
- Statsmodels

---

## 🚀 How to Run

```bash
pip install pandas numpy scipy scikit-learn statsmodels matplotlib seaborn

jupyter notebook notebooks/04_task.ipynb
```

---

## 📊 Dataset

**Dataset:** Superstore Sales

The dataset contains retail sales transactions including customer information, products, sales, profit, discounts, quantity, region, and category details.

---
