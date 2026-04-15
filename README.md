# A-Study-on-Customer-Churn-Analysis-in-Internet-Service-Providers
Customer satisfaction and churn analysis of Airtel, Jio, and BSNL users using primary survey data, Python, and Excel to identify switching behavior, loyalty trends, and key service factors influencing retention.
# Telecom Customer Satisfaction and Churn Analysis

## Overview
This project analyzes customer satisfaction and churn behavior in the telecom industry using survey-based primary data. The study focuses on understanding how service quality, pricing, customer support, and demographic factors influence customer churn.

The project uses Exploratory Data Analysis (EDA), ANOVA, and Logistic Regression to identify the key drivers of churn and provide actionable business recommendations.

---

## Objectives
- Analyze customer churn distribution
- Identify major reasons behind churn
- Study the relationship between service quality and churn
- Compare satisfaction levels across telecom operators
- Predict churn using Logistic Regression
- Provide business recommendations to improve customer retention

---

## Dataset
The dataset contains customer responses related to:
- Telecom operator used
- Age group
- Occupation
- Network coverage
- Internet speed
- Pricing
- Customer support
- Call quality
- Value for money
- Recommendation behavior
- Churn status

---

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Project Workflow

### 1. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Standardized column names
- Created target variable for churn

### 2. Exploratory Data Analysis
- Churn distribution
- Operator-wise customer distribution
- Top reasons for churn
- Recommendation vs churn
- Satisfaction factor analysis
- Age group analysis

### 3. Statistical Analysis
- One-Way ANOVA to compare pricing satisfaction across telecom operators

### 4. Predictive Modeling
- Logistic Regression model for churn prediction
- Train-test split
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

### 5. Feature Importance
Key churn drivers identified:
- Customers facing issues with their operator
- Younger age group (18–24)
- Recommendation behavior
- Telecom operator used
- Customer experience factors

---

## Key Findings
- Around 31% of customers showed churn behavior
- Service quality is the strongest driver of churn
- Poor internet speed, call quality, and customer support increase churn risk
- Pricing differences across operators are not statistically significant
- Younger customers are more likely to switch operators
- Customers who would not recommend their operator are more likely to churn

---

## Model Performance
- Accuracy: 75%
- Precision for churn: 1.00
- Recall for churn: 0.38
- F1-score for churn: 0.55

The model performs reasonably well overall, but misses some actual churners. This suggests that future improvements can be made using larger datasets or advanced machine learning models.

---

## Business Recommendations
- Improve network quality and internet speed
- Strengthen customer support services
- Focus on customer complaint resolution
- Develop targeted retention strategies for younger customers
- Use predictive analytics to identify high-risk customers

---

## Conclusion
The analysis shows that customer churn is mainly influenced by service quality and customer experience rather than pricing. Telecom operators can reduce churn by improving support services, network performance, and proactive customer engagement.
