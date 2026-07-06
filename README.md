# 📊 Telco Customer Churn Analysis

> An Exploratory Data Analysis (EDA) project that investigates the factors influencing customer churn in a telecommunications company using Python.

---

## Executive Summary

Customer retention remains one of the biggest challenges in the telecommunications industry. While attracting new customers requires significant marketing investment, retaining existing customers is often more cost-effective and contributes directly to long-term profitability.

In this project, I performed an end-to-end Exploratory Data Analysis (EDA) on a telecom customer dataset to understand customer behavior, identify churn patterns, and uncover the key factors associated with customer attrition.

The findings provide actionable business insights that can help improve customer retention strategies and support data-driven decision-making.

---

## Business Problem

Customer churn represents a significant business challenge for telecommunication companies. Every customer lost not only reduces recurring revenue but also increases the cost of acquiring replacement customers.

Although the company collects extensive customer information, it lacks a clear understanding of the characteristics and behaviors that contribute most to churn.

This project aims to bridge that gap by exploring customer demographics, subscription details, billing information, and service usage to identify the primary drivers of customer churn.

---

## Project Objectives

The objectives of this analysis were to:

- Understand customer demographics and service usage
- Explore customer behavior patterns
- Identify variables associated with customer churn
- Discover relationships between customer characteristics
- Generate actionable recommendations for improving customer retention

---

## Dataset Information

The dataset contains customer information from a telecommunications company.

### Key Features

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Contract Type
- Internet Service
- Payment Method
- Monthly Charges
- Total Charges
- Churn (Target Variable)

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

```
Business Problem

        ↓

Data Understanding

        ↓

Data Cleaning

        ↓

Exploratory Data Analysis

        ↓

Univariate Analysis

        ↓

Bivariate Analysis

        ↓

Multivariate Analysis

        ↓

Business Insights

        ↓

Recommendations
```

---

## Data Cleaning & Preparation

Before conducting the analysis, the dataset was prepared through several preprocessing steps:

- Checked dataset dimensions and data types
- Identified missing values
- Converted data into appropriate formats
- Examined numerical and categorical variables
- Verified data quality before visualization

---

## Exploratory Data Analysis

The analysis focused on understanding customer characteristics and their relationship with churn through:

### Univariate Analysis

- Customer churn distribution
- Gender distribution
- Contract type distribution
- Internet service distribution
- Payment methods
- Tenure distribution
- Monthly charges
- Total charges

### Bivariate Analysis

Relationships between customer churn and:

- Gender
- Contract type
- Internet service
- Payment method

### Multivariate Analysis

- Correlation analysis of numerical variables
- Identification of relationships between tenure, monthly charges, and total charges


---

## Key Insights

The analysis revealed several important business findings:

- Customers on month-to-month contracts are significantly more likely to churn than customers on one-year or two-year contracts.

- Customers using fiber optic internet services exhibit the highest churn rate, making them an important segment for retention efforts.

- Customers who pay using electronic checks are more likely to leave compared to customers using automatic payment methods.

- Gender does not appear to have a meaningful influence on customer churn, with similar churn patterns observed across both male and female customers.

- Tenure is strongly associated with customer loyalty, as customers with longer relationships tend to remain with the company.

- A strong positive relationship exists between tenure and total charges, indicating that long-term customers naturally contribute higher lifetime value.

---

## Business Recommendations

Based on the findings, the following recommendations were made:

- Encourage customers to migrate from month-to-month contracts to long-term subscription plans through loyalty incentives and promotional offers.

- Investigate customer satisfaction among fiber optic users to identify service issues contributing to higher churn.

- Promote automatic payment methods by offering discounts or rewards to customers who enroll.

- Implement targeted onboarding and engagement programs for new customers to improve early retention.

- Review pricing strategies for premium service packages to ensure customers perceive sufficient value.

---

## Conclusion

This analysis demonstrates that customer churn is influenced more by service-related and contractual factors than by demographic characteristics.

Contract type, internet service, payment method, and customer tenure emerged as the strongest indicators associated with churn.

These insights can help decision-makers prioritize customer retention initiatives, improve service offerings, and reduce revenue loss through targeted intervention strategies.

---

## Repository Structure

```
Telco-Customer-Churn-Analysis/

│── Customer_Churn_Analysis.ipynb
│── README.md
│── requirements.txt
│── dataset/
│── images/
```

---

## How to Run

Clone the repository

```bash
git clone https://github.com/Halimoh-cpu/Telco-Customer-Churn-Analysis.git
```

Navigate into the project

```bash
cd Telco-Customer-Churn-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Customer_Churn_Analysis.ipynb
```

---

## Future Improvements

This project focuses on exploratory data analysis.

Possible future enhancements include:

- Building predictive machine learning models for churn prediction
- Feature engineering
- Model evaluation and comparison
- Interactive dashboards using Power BI or Tableau
- Customer segmentation for targeted retention campaigns

---

## About Me

**Halimoh Olatunji**

Forestry and Wildlife Management Graduate | Aspiring Data Analyst

Passionate about transforming data into meaningful insights that support informed business decisions.

- LinkedIn: *https://www.linkedin.com/in/halimoh-temidayo*
- GitHub: *https://github.com/Halimoh-cpu*

---

## License

This project is available under the MIT License.
