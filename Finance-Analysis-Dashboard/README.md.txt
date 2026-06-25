# Finance Analysis Dashboard | Power BI

## Project Overview

The Finance Analysis Dashboard is an interactive Business Intelligence solution developed using Power BI to analyze financial transactions, customer behavior, fees, taxes, and transaction performance.

The dashboard provides real-time insights into transaction trends, customer segments, regional performance, profitability, and operational efficiency, enabling stakeholders to make informed business decisions.

---

## Business Requirement

A financial organization required a centralized analytics dashboard to monitor:

- Overall financial performance
- Transaction growth trends
- Monthly transaction analysis
- Customer segment contribution
- State-wise performance
- Transaction success and failure rates
- Fees and tax collection
- Customer demographic insights
- Year-over-Year (YoY) growth

The solution should provide dynamic filtering and detailed transaction-level analysis.

---

## Objectives

- Monitor key financial KPIs
- Analyze transaction performance
- Identify high-performing customer segments
- Compare state-wise financial contribution
- Evaluate transaction profitability
- Analyze customer demographics
- Track Year-over-Year growth
- Support data-driven decision making

---

# Dashboard 1 – Executive Overview

### KPI Cards

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax

Each KPI includes Previous Year comparison and YoY analysis.

---

### Interactive Filters

- Year
- Dynamic Measure
- Occupation
- Category

---

### Visualizations

#### Total Transaction by Month
- Area Chart
- Displays monthly transaction trends and seasonality.

#### Total Transaction by Transaction Status
- Donut Chart
- Success
- Failed
- Pending

#### Total Transaction by Customer Segment
- Horizontal Bar Chart

Segments:
- Retail
- Premium
- SME
- Corporate
- Wealth

#### Total Transaction by State
- Horizontal Bar Chart
- Compares transaction performance across states.

#### Transaction Type Analysis
- Matrix Heatmap

Metrics:
- Amount
- Fees
- Tax
- Transaction Count

Transaction Types:
- Bill Payment
- Card Payment
- Deposit
- Fee Charge
- Interest Credit
- Investment
- Loan EMI
- Refund
- Transfer
- Withdrawal

#### Total Transaction by Gender
- Donut Chart

Categories:
- Male
- Female

---

# Dashboard 2 – Transaction Details & Drill Down Analysis

Provides transaction-level insights through drill-down functionality.

Users can analyze detailed records including:

- Transaction ID
- Transaction Date
- Customer Name
- Transaction Type
- Transaction Status
- Gender
- Customer Segment
- State
- Amount
- Fee
- Tax

This enables users to move from high-level summaries to detailed transaction records.

---

# Data Modeling

## Calendar Table

A dedicated Date Dimension table was created for:

- Year Analysis
- Monthly Analysis
- Time Intelligence
- YoY Calculations

Relationship:

Calendar Table[Date]
↓

finance_transactions[transaction_date]

---

# DAX Measures

## Core Measures

- Total Amount
- Total Fee
- Total Tax
- Total Transaction
- Average Transaction Value

## Previous Year Measures

- PV Amount
- PV Fees
- PV Tax
- PV Transaction
- PV Avg Transaction

## Year-over-Year Measures

- YOY Amount
- YOY Fees
- YOY Tax
- YOY Transaction
- YOY Avg Transaction

## Year-over-Year Percentage Measures

- YOY% Amount
- YOY% Fees
- YOY% Tax
- YOY% Transaction
- YOY% Avg Transaction

## Dynamic Features

- Dynamic Measure Selection
- Dynamic Titles
- Interactive Slicers
- Drill Down Analysis

---

# Key Insights

- Retail customers contribute the highest transaction volume.
- Success transactions account for the majority of financial activity.
- Maharashtra and Karnataka are among the top-performing states.
- Transfer and Loan EMI transactions generate significant transaction volume.
- Customer participation is balanced across genders.
- Monthly trends help identify seasonal peaks and dips.

---

# Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Excel
- Data Modeling

---

# Skills Demonstrated

- Business Intelligence
- Data Analysis
- Data Visualization
- Dashboard Development
- DAX Calculations
- Time Intelligence
- KPI Reporting
- Data Modeling
- Financial Analytics
- Drill Down Reporting

---

# Project Outcome

Successfully developed a Finance Analytics Dashboard that provides a centralized view of financial transactions, customer behavior, profitability metrics, and operational performance.

The dashboard enables stakeholders to monitor KPIs, identify business opportunities, analyze trends, and make data-driven decisions through interactive visualizations and detailed transaction analysis.