# 💳 Credit Card Customer Analysis & Risk Dashboard

## 📌 Project Overview

This project presents an interactive **Credit Card Customer Analysis Dashboard built using Microsoft Power BI**.

The objective of this project is to analyze customer demographics, credit utilization, spending behavior, transaction patterns, delinquency, and customer risk segments. The dashboard converts raw customer and credit card data into meaningful business insights that can help organizations improve **risk monitoring, customer segmentation, retention, and marketing strategies**.

The analysis was performed using **Microsoft Power BI**, with **Power Query** for data preparation, **DAX** for calculated measures and KPIs, and interactive Power BI visualizations for business analysis.

---

## 🎯 Business Objectives

The main objectives of this project are:

- Analyze the overall credit card customer base.
- Understand customer demographics and characteristics.
- Analyze credit utilization and outstanding balances.
- Identify high-risk and delinquent customers.
- Analyze customer spending behavior.
- Identify the highest spending categories.
- Compare spending across different occupations.
- Analyze customer segmentation based on credit risk.
- Identify patterns that can support targeted customer strategies.
- Provide actionable business recommendations.

---

## 📂 Dataset

The project uses two datasets:

### 1. Credit Card Dataset

**File:** `credit_card.csv`

The dataset contains **10,108 records and 18 columns** related to credit card usage and financial activity.

Some important attributes include:

- Card Category
- Annual Fees
- Customer Acquisition Cost
- Credit Limit
- Total Revolving Balance
- Total Transaction Amount
- Total Transaction Volume
- Average Utilization Ratio
- Expense Type
- Interest Earned
- Delinquency indicators

### 2. Customer Dataset

**File:** `customer.csv`

The dataset contains **10,108 customer records and 15 columns**.

Important attributes include:

- Customer Age
- Gender
- Dependent Count
- Education Level
- Marital Status
- State
- Car Ownership
- House Ownership
- Personal Loan
- Contact Type
- Customer Job
- Income
- Customer Satisfaction Score

---

## 🛠️ Technologies Used

- **Microsoft Power BI**
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated measures and KPIs
- **Data Modeling** – Combining customer and credit card information
- **Power BI Visualizations** – Charts, KPI cards, slicers, and interactive analysis
- **CSV** – Source data

---

# 📊 Dashboard Pages

## 1. Credit Utilization & Risk

This page focuses on how customers use their available credit and where potential credit risk exists.

### Key KPIs

- **Average Utilization:** 27.5%
- **Total Revolving Balance:** 12M
- **Delinquency Rate:** 6.07%
- **Delinquent Customers:** 614

### Visualizations

- Credit Limit vs Outstanding Balance
- Customers by Credit Utilization
- Delinquency Rate by Occupation
- Interactive filters for Gender, Card Category, Marital Status, and Customer Job

### Key Insights

- A large proportion of customers fall into the low-utilization segment.
- **70.11% of customers are classified as Low Risk.**
- **23.81% of customers have High Utilization**, making this an important segment for risk monitoring.
- The overall **6.07% delinquency rate** indicates the need for proactive payment and credit-risk management.

---

## 2. Credit Card Customer Analytics

This page provides an overall view of the customer base and its financial profile.

### Key KPIs

- **Total Customers:** 10K
- **Total Spending:** 45M
- **Total Credit Limit:** 87.29M
- **Delinquency Rate:** 6.07%
- **Average Utilization:** 27.5%

### Visualizations

- Customer Distribution by Age Group
- Customers by Occupation
- Customer Distribution by Card Category

### Key Insights

- Customers aged **45–54** represent the largest age group.
- **Self-employed** customers form the largest occupational group.
- The **Blue card category dominates the portfolio**, representing approximately **91.16%** of customers.
- The dashboard provides a combined view of customer demographics and financial performance.

---

## 3. Customer Segmentation & Recommendations

This page focuses on customer risk segmentation and understanding income and spending behavior.

### Risk Segments

Customers are categorized into:

- Low Risk
- High Utilization
- Delinquent
- High Risk

### Key Insights

- **70.11% of customers are Low Risk**, indicating a generally healthy customer base.
- **23.81% have High Credit Utilization**, making this an important risk segment.
- The overall delinquency rate is **6.07%**.
- Income and spending patterns can help identify different customer segments and create personalized strategies.

### Recommendations

- Prioritize high-utilization and delinquent customers for proactive monitoring.
- Provide personalized repayment or credit-management support to higher-risk customers.
- Use customer income and spending patterns to create targeted offers and rewards.
- Develop differentiated credit strategies based on customer risk profiles.

---

## 4. Spending Behavior

This page analyzes where customers spend their money and how spending changes throughout the year.

### Key KPIs

- **Total Spending:** 45M
- **Average Spending:** 4.40K
- **Total Transaction Volume:** 656K

### Visualizations

- Total Spending by Expense Category
- Average Spending by Occupation
- Spending Trend Over Time

### Key Insights

- **Bills are the largest spending category.**
- **Businessmen have the highest average spending** among the analyzed occupations.
- Spending shows noticeable fluctuations throughout the year.
- Higher spending periods can be used to design targeted promotional campaigns and customer engagement strategies.

---

# 📈 Dashboard Highlights

The dashboard provides interactive analysis through slicers for:

- Gender
- Card Category
- Marital Status
- Customer Job

Users can apply these filters to analyze specific customer segments and understand how their spending, utilization, and risk characteristics change.

---

# 💡 Key Business Insights

Some of the major insights obtained from the analysis include:

- **70.11% of customers are classified as Low Risk**, indicating that most customers have relatively healthy credit behavior.
- **23.81% of customers fall into the High Utilization segment**, making them an important group for proactive monitoring.
- The overall **delinquency rate is 6.07%**, highlighting the importance of payment-risk management.
- The portfolio has approximately **87.29M in total credit limit** and **45M in total spending**.
- The **Blue card category accounts for approximately 91.16%** of customers.
- Customers aged **45–54** represent the largest age group.
- **Self-employed customers** form the largest occupational group.
- **Bills contribute the highest total spending** among expense categories.
- **Businessmen have the highest average spending** among occupations.
- Customer income, spending, utilization, and risk patterns can be combined to create targeted customer segments.

---

# 💼 Business Recommendations

### 1. Monitor High-Utilization Customers

Customers with high credit utilization should be monitored closely to identify potential increases in credit risk.

### 2. Target Delinquent Customers

Personalized communication and repayment-support strategies can help improve payment behavior and reduce delinquency.

### 3. Improve Customer Segmentation

Income, occupation, spending, satisfaction, and credit utilization can be combined to create more meaningful customer segments.

### 4. Personalize Offers and Rewards

Customer spending behavior can be used to provide targeted offers, rewards, and promotional campaigns.

### 5. Strengthen Credit Risk Monitoring

Regularly monitoring utilization and delinquency KPIs can help identify changes in customer risk behavior at an early stage.

---

# 📁 Project Structure

```text
credit-card-analysis-powerbi/
│
├── credit_card_PBI_dataset/
│   ├── credit_card.csv
│   └── customer.csv
│
├── Credit_card_dashboard/
│   └── Credit_Card_Analysis.pbix
│
├── Screenshots/
│   ├── credit_utilization_risk.png
│   ├── customer_financial_overview.png
│   ├── customer_segmentation_recommendations.png
│   └── spending_behavior.png
│
├── README.md

