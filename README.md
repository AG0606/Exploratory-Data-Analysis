# Customer Behavior Analysis: Exploratory Data Analysis (EDA)

This repository contains a comprehensive Exploratory Data Analysis (EDA) of a customer dataset aimed at extracting actionable insights from demographic, transactional, and behavioral attributes of 100,000 customers.

---

## 📁 Dataset Description

The dataset consists of 100,000 rows and 11 features after preprocessing. The features can be broadly classified as follows:

### 🧾 Feature Overview

| Feature               | Type        | Description                                                        |
|-----------------------|-------------|--------------------------------------------------------------------|
| `age`                 | Numeric     | Age of the customer                                                |
| `gender`              | Categorical | Gender of the customer (e.g., Male, Female)                        |
| `income`              | Numeric     | Annual income of the customer                                      |
| `education`           | Categorical | Educational qualification (High School, Graduate, etc.)           |
| `region`              | Categorical | Region of residence                                                |
| `loyalty_status`      | Categorical | Loyalty tier (Bronze, Silver, Gold)                                |
| `purchase_frequency`  | Categorical | Frequency of purchases (Low, Medium, High)                         |
| `purchase_amount`     | Numeric     | Total purchase amount                                              |
| `product_category`    | Categorical | Preferred product category                                         |
| `promotion_usage`     | Binary      | Indicator for promotion usage (0 = No, 1 = Yes)                    |
| `satisfaction_score`  | Numeric     | Customer satisfaction score on a scale from 0 to 10               |

### 📊 Dataset Statistics

- **Total entries**: 100,000  
- **Missing values**: None  
- **Categorical columns**: 6  
- **Numerical columns**: 5  
- **Unique values**:
  - `gender`: 2
  - `education`: 4
  - `region`: 4
  - `loyalty_status`: 3
  - `purchase_frequency`: 3
  - `product_category`: 7

---

## 🔍 EDA Objectives

- Identify key customer segments.
- Analyze behavior patterns across demographics.
- Evaluate correlation between promotional activity and purchasing trends.
- Understand the relationship between satisfaction scores and other features.

---

## ✅ Key Insights

- **Income and Purchase Amount**: Higher income correlates positively with purchase amount, though not strictly linear.
- **Loyalty Status vs. Satisfaction**: Gold members exhibit higher satisfaction scores; likely due to incentives and personalized offers.
- **Promotion Impact**: Promotion usage is linked with increased purchase frequency and amount.
- **Age Distribution**: Predominantly young to middle-aged customer base, indicating potential for long-term engagement strategies.
- **Regional Patterns**: Variance in product category preferences across regions suggests potential for regionalized marketing.

---

## 🧠 Potential Applications

### 1. Customer Segmentation  
Cluster analysis can be applied post-EDA to segment customers for personalized marketing.

### 2. Recommendation Systems  
Feature distributions and preferences can inform collaborative filtering or content-based recommendation engines.

### 3. Predictive Modeling  
Build models for:
- Churn prediction
- Satisfaction forecasting
- Promotion response modeling

### 4. Business Intelligence Dashboards  
EDA outputs (visualizations, metrics) can be embedded into BI tools for real-time insights.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, plotly

### Installation

```bash
git clone https://github.com/AG0606/Exploratory-Data-Analysis.git
cd customer-eda
jupyter notebook
```

### Dependecies
```bash
pip install -r requirements.txt
```
---

### Project Structure
```bash
customer-eda/
│
├── EDA_CustomerData.ipynb      # Main analysis notebook
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies
```
---

## 📌 Future Work

- Feature engineering for ML models.
- Deployment of insights into an interactive dashboard (e.g., Streamlit, Dash).
- Integration with real-time customer data pipelines.
