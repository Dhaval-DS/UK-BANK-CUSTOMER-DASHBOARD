# 🏦 UK Bank Customer Insights Dashboard

A dynamic and interactive Power BI dashboard designed to analyze the demographics, regional distribution, and financial standing of 4,014 UK bank customers.

### Short Description / Purpose

This dashboard provides a comprehensive visual analysis of a UK bank's customer base. It is designed to help bank managers, financial analysts, and marketing teams identify key customer segments, understand regional performance, and make data-driven decisions to improve customer targeting and services.

### Tech Stack

The dashboard was built using the following tools:
* 📊 **Power BI Desktop** – Main data visualization and report creation platform.
* 📂 **Power Query** – Used for data cleaning, transformation, and preparation.
* 🧠 **DAX (Data Analysis Expressions)** – Implemented for creating key measures such as total customer count, sum of balance, and average age.
* 📝 **Data Modeling** – Established relationships between data tables to enable interactive cross-filtering across all visuals.

### Data Source
The analysis is based on a customer dataset for a UK bank. The dataset includes columns such as `Customer ID`, `Region`, `Job Classification`, `Gender`, `Age`, `Date Joined`, and `Balance`.

---

## Features / Highlights

### Business Problem
Financial institutions need a clear and consolidated view of their customer portfolio to drive growth and improve service delivery. Without an effective visualization tool, answering critical questions is difficult. For instance:
* Which region holds the highest customer base and total balance?
* What is the financial profile of different customer job segments?
* Which demographic groups (age, gender) have the highest average balance?
* How does customer activity vary across different quarters?

### Goal of the Dashboard
To create an intuitive, interactive tool that allows stakeholders to:
* Quickly identify and understand the key characteristics of the customer base.
* Filter and segment customers by region, job type, gender, and age.
* Uncover insights related to customer balance and demographics to support strategic planning.

### Walkthrough of Key Visuals

* **Key KPIs & Filters (Top Row)**
    * **Total Customers:** The report analyzes a total of `4.014K` customers.
    * **Interactive Slicers:** The dashboard can be filtered by `Region`, `Job Classification`, `Gender`, `Age Group`, `Quarter`, and `Balance` range.

* **Customer & Balance Distribution by Region**
    * **Count of Customer ID by Region (Pie Chart):** `England` accounts for the majority of customers with `2.16K` individuals, representing `53.79%` of the total base.
    * **Sum of Balance by Region (Donut Chart):** Similarly, `England` contributes the highest portion of the balance with `£84.83M`, which is `53.15%` of the total.

* **Quarterly Customer Analysis**
    * **Count of Customer ID by Quarter (Column Chart):** Customer count is highest in `Qtr 4` (`1613` customers) and lowest in `Qtr 1` (`123` customers), indicating significant activity towards the end of the year.

* **Job Classification & Demographic Insights**
    * **Sum of Balance by Job Classification (Bar Chart):** `White Collar` customers hold the largest total balance at `£78.87M`, followed by `Blue Collar` customers at `£41.33M`.
    * **Average of Balance by Age Group (Bar Chart):** The `26 to 35` and `36 to 55` age groups maintain the highest average balances, generally around `£39K-£40K`.
    * **Average of Age by Job Classification (Bar Chart):** The average age for `White Collar` customers (`35.28`) is notably lower than for `Blue Collar` (`41.87`) and `Other` (`41.68`) job classifications.

### Business Impact & Insights
* **Market Focus:** With over 53% of both the customer count and total balance originating from England, it is clearly the bank's most critical market.
* **High-Value Segment:** `White Collar` customers represent the most significant segment by total balance, making them a primary audience for investment and premium financial products.
* **Demographic Targeting:** `White Collar` customers are, on average, younger than other job segments. This insight can be used to tailor marketing campaigns and digital banking solutions to a younger, high-balance demographic.

### Screenshots / Demos
[![UK Bank Customer Dashboard](https://github.com/Dhaval-DS/UK-BANK-CUSTOMER-DASHBOARD/blob/86481083d0a431ca2a886f7fb7434369704011f6/Uk-BankCustomer-Dashboard.png)
