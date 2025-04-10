# Predicting Customer Churn in the Credit Card Industry

## Project Overview
This project addresses a key challenge faced by financial institutions: **customer churn**. Using machine learning, we developed a predictive model that determines whether a customer is likely to attrite (cancel their credit card account). By identifying at-risk customers, banks and credit card providers can take proactive steps to improve retention, reduce revenue loss, and better serve their clientele.

---

## Stakeholders

This project is designed to support decision-makers across various departments within a financial institution:

| **Stakeholder**            | **Interest**                                                                 |
|----------------------------|------------------------------------------------------------------------------|
| Marketing Team             | Target churn-prone customers with personalized retention offers             |
| Customer Success Managers  | Engage proactively with high-risk customers before they leave               |
| Product Managers           | Identify product features or services that may be contributing to attrition |
| Data Analysts              | Use model insights to develop ongoing reporting and trend analysis           |
| Executive Leadership       | Monitor churn KPIs and allocate resources to improve customer lifetime value |

---

## Stakeholder Questions

This project answers key business questions that stakeholders care about:

- **Which customers are most likely to churn?**  
  → Helps prioritize customer retention efforts.

- **What factors contribute most to customer attrition?**  
  → Enables data-driven decisions about policy and marketing strategy.

- **How can we proactively identify high-risk customers before they leave?**  
  → Supports building preventative outreach programs.

- **Can we segment customers based on their behaviors and churn risk?**  
  → Aids in tailoring offers and services to different customer groups.

- **How accurate is our ability to predict future churn based on customer data?**  
  → Builds confidence in the predictive model’s value and informs strategic planning.

---

## Objectives

- Predict whether a customer will churn based on historical behavior and account metrics  
- Achieve at least **75% classification accuracy**  
- Identify which customer features most strongly influence churn  
- Visualize insights to support data-driven decision making  

---

## Project Timeline

| **Date**       | **Milestone**                                      |
|----------------|-----------------------------------------------------|
| April 8–10     | Dataset exploration, cleaning, and EDA             |
| April 11–14    | Model training, testing, and optimization          |
| April 15–17    | Tableau dashboard creation + GitHub repo cleanup   |
| April 18–19    | Finalize README, visuals, and model results        |
| April 20       | Group presentation prep and review                 |
| **April 21**   |  **Project Due – Submit and Present**              |


---


![02885488-7135-46b2-9759-433d4f13700250](https://github.com/user-attachments/assets/6fe0eb84-3d4d-4249-beb1-08f3ee9ec5e7)


---

## Machine Learning Strategy

- **Problem Type**: Binary Classification  
- **Target Variable**: `Attrition_Flag`  
- **Algorithms Used**:
  - Logistic Regression
  - Random Forest Classifier
- **Model Performance Goal**: ≥ **75% accuracy**

---

## Dataset

- **Source**: [Gigasheet – Credit Card Customers](https://app.gigasheet.com/spreadsheet/credit-card-customers/8a7f5cd0_8522_4dd1_ad9d_4efe52507b2b)  
- **Records**: ~1,000 customers  
- **Features**:
  - Demographics (e.g., Gender, Income Category, Education Level)
  - Account Metrics (e.g., Credit Limit, Revolving Balance, Avg Open to Buy)
  - Transaction Behavior (e.g., Total Transaction Count, Total Transaction Amount)
  - `Attrition_Flag`: Indicates whether the customer churned

---

## Technologies Used

| **Technology**      | **Purpose**                                  |
|---------------------|----------------------------------------------|
| Python & Pandas     | Data cleaning and feature engineering        |
| Scikit-learn        | Machine learning modeling and evaluation     |
| Matplotlib/Seaborn  | Visualizing distributions and insights       |
| PostgreSQL          | Storing and retrieving data                  |
| Amazon AWS          | Cloud hosting or database management         |
| Tableau             | Stakeholder-friendly dashboards              |
| GitHub              | Version control and collaboration            |

---

## Model Optimization & Evaluation

Model performance was monitored and improved through:

- Iterative tuning of model hyperparameters  
- Evaluation using cross-validation  
- Feature selection and importance analysis  

Results were documented in a CSV table and within the training script.

---

## Tableau Dashboard

An interactive Tableau dashboard summarizes:

- Customer churn distribution  
- Feature impact and patterns  
- Model prediction summaries  

---

## Results Summary

- **Best model**: Random Forest Classifier  
- **Accuracy**: 75%
- **Top churn predictors**:
  - Total Transaction Count
  - Total Revolving Balance
  - Credit Limit
  - Months on Book

---

## Repository Structure

project4-churn-prediction/

│

├── data/                     # Raw and cleaned datasets

├── notebooks/                # Jupyter notebooks for EDA and modeling

├── scripts/                  # Final ML training and evaluation scripts

├── tableau/                  # Tableau workbook or screenshots

├── optimization_results.csv  # Model tuning documentation

├── README.md                 # Project documentation

└── .gitignore                # Files to exclude from version control


