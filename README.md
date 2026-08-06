# Supply Chain Delivery Performance Analysis & Late Delivery Prediction

An end-to-end data analytics and machine learning project that investigates delivery performance for a global e-commerce supply chain. The project identifies operational bottlenecks, quantifies the financial impact of late deliveries, performs root cause analysis, and develops a predictive model to identify high-risk shipments.

---

## Dataset

**Dataset:** [DataCo Smart Supply Chain Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

---

## Project Overview

This project analyzes **172,765** e-commerce orders collected between **2015 and 2018** to answer key business questions related to delivery performance and profitability.

The analysis follows a complete analytics workflow:

- Data Cleaning & Feature Engineering
- Business KPI Analysis
- Exploratory Data Analysis (EDA)
- Profitability Analysis
- Bottleneck Detection
- Root Cause Analysis
- Time-based Trend Analysis
- Machine Learning Prediction
- Business Recommendations

---

## Business Problem

Late deliveries reduce customer satisfaction and directly impact profitability. The objective of this project is to identify the operational drivers behind delayed shipments and build a predictive model capable of identifying orders at risk before shipment.

---

## Dataset

- **Industry:** E-commerce / Supply Chain
- **Orders:** 172,765
- **Time Period:** Jan 2015 – Jan 2018

The dataset includes information such as:

- Customer Segment
- Order Region
- Shipping Mode
- Department
- Product Category
- Order Status
- Delivery Delay
- Scheduled Shipment Days
- Order Profit

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## Analysis Performed

### Business KPIs

- Total Orders
- Late Delivery Rate
- On-Time Delivery Rate
- Total Profit
- Profit at Risk
- Average Order Profit
- 90th Percentile Delivery Delay

---

### Profitability Analysis

- Profitability Distribution
- Delay Distribution
- Profit vs Delay Analysis

---

### Bottleneck Detection

Delay performance was analyzed across multiple operational dimensions:

- Order Region
- Customer Segment
- Shipping Mode
- Department
- Order Status
- Order Type

---

### Root Cause Analysis

A detailed investigation was performed for the region with the highest delay rate to identify the strongest operational drivers contributing to late deliveries.

---

### Time-Based Analysis

Delivery trends were analyzed by:

- Month
- Day of Week
- Hour of Day

---

### Machine Learning

A Random Forest classifier was developed to predict whether an order would be delivered late.

Model pipeline:

- Feature Engineering
- Frequency Encoding
- Train-Test Split
- SMOTE for Class Balancing
- Random Forest Classification
- Model Evaluation

---

## Model Performance

| Metric | Score |
|---------|--------|
| Accuracy | 74% |
| Precision | 74% |
| Recall | 74% |
| F1 Score | 74% |

---

## Key Insights

- More than half of all analyzed orders were delivered late.
- Shipping mode was identified as the strongest operational bottleneck.
- Delivery delays were consistent across regions, indicating a systemic operational issue rather than a regional problem.
- Seasonal demand spikes contributed to increased delay rates.
- The predictive model successfully identifies high-risk shipments with approximately **74% accuracy**.

---

## Future Improvements

- Hyperparameter tuning
- XGBoost / LightGBM comparison
- Model deployment using Flask or FastAPI
- Interactive Power BI dashboard
- Real-time prediction API
