# 📊 Bank Customer Churn Analysis - Power BI Project 🏦

## 📝 Project Overview

The main objective of this project is to analyze the bank's customer data to identify customers who are likely to churn (leave the bank). Through this Power BI dashboard, we aim to understand the key drivers behind churn and provide data-driven insights that can help the bank improve its customer retention strategies.

## ❓ Problem Statement

Bank customer churn is a significant problem that impacts a bank's revenue and growth. Retaining existing customers is more cost-effective than acquiring new ones. The goals of this project are:
* 📉 To track the customer churn rate.
* 🎯 To identify customer segments with the highest churn rates.
* 🤔 To determine the key factors influencing churn, such as customer age, tenure, bank balance, and service usage.
* 💡 To help the bank develop effective retention strategies.

## 💾 Dataset

A standard bank customer dataset was used for this analysis. It includes customer information such as their demographics, account details, and their relationship tenure with the bank.

**Key Columns:**
* CustomerID
* Surname
* CreditScore
* Geography
* Gender
* Age
* Tenure
* Balance
* NumOfProducts
* HasCrCard
* IsActiveMember
* EstimatedSalary
* Exited (Customer churned or not - this is our target variable)

## 🛠️ Tools Used

* **Microsoft Power BI:** For importing, transforming, modeling, and visualizing data.
* **DAX (Data Analysis Expressions):** For creating necessary calculations and new measures.

## 🖥️ Dashboard Overview

This Power BI report is divided into several interactive pages:

1.  **Summary Dashboard:**
    * Key KPIs for Total Customers, Churned Customers, and Churn Rate.
    * Churn breakdown by Gender, Geography, and Age Group.
    * Analysis of churn based on Customer Tenure and Bank Balance.

2.  **Customer Demographics Analysis:**
    * In-depth analysis of churn patterns across different age groups and genders.
    * Comparison of churn rates based on Geography.

3.  **Product and Service Usage Analysis:**
    * The impact of the number of bank products and customer activity on churn.
    * Difference in churn rate between credit card holders and active members.

## 💡 Key Insights

* **Geography:** Customers in Germany 🇩🇪 have a higher churn rate compared to those in France 🇫🇷 and Spain 🇪🇸.
* **Age:** Customers over the age of 50 show a higher tendency to churn.
* **Balance:** Customers with a higher bank balance are more likely to churn.
* **Number of Products:** Customers using more than two bank products also have an increased churn rate.

## 🚀 How to Use

1.  Clone this repository to your local machine.
2.  Open the `Bank Customer Churn.pbix` file in Microsoft Power BI Desktop.
3.  You can refresh the data if you want to connect a new data source.
4.  Use the various filters and slicers to interact with the dashboard.

## 👨‍💻 Author

* **Kalpesh Baria**
* **LinkedIn:** [https://www.linkedin.com/feed/](https://www.linkedin.com/feed/)
