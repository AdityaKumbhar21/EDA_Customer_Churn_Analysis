# Customer Churn Analysis (EDA)

## Overview
This project explores **customer churn** through **Exploratory Data Analysis (EDA)**.  
The goal is to uncover patterns and insights into what factors contribute most to customers leaving.
---
A detailed summary report/PPT of the project: [Click here](https://www.canva.com/design/DAGqxrdv3eY/kfacleE_9h_KqdHxgHdu4A/view?utm_content=DAGqxrdv3eY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=ha3f93a78ab)

## 📂 Dataset
- **Features**:
  - `customerID`: Unique customer identifier
  - `tenure`: Number of months with the company
  - `MonthlyCharges`: Monthly payment amount
  - `Contract`: Customer’s contract type
  - `Churn`: Target variable (`Yes` or `No`)
  - Other demographic and service-specific features

---

## Data Cleaning
- Checked and handled missing or duplicate values.
- Converted categorical variables into appropriate types.
- Created new features as needed (e.g. tenure groups).

---

## Exploratory Data Analysis
Key analyses performed:
- **Univariate Analysis**:  
  Examined distributions of important features (`tenure`, `MonthlyCharges`, etc.).
- **Bivariate Analysis**:  
  Studied relationships between features and `Churn`.
- **Key Insights**:
  - Customers with **monthly charges between $70–$110** have higher churn rates.
  - Customers with **longer tenure** tend to have lower churn rates.
  - Customers on **month-to-month contracts** are most likely to churn.

---

## Recommendations
Consider retention offers for customers with higher monthly charges.  
Encourage customers to switch to longer-term contracts.  
Target retention campaigns at customers who fit high-risk profiles.

---

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

##  Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-eda.git
