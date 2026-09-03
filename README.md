💰 Finance Analysis Dashboard

An end-to-end Finance Analytics project analyzing 50,069 financial transactions from 5,000 customers across India, using Power BI to uncover transaction performance, customer segments, channel usage, fraud risk, and actionable business insights.

📌 Project Overview

This project analyzes financial transaction and customer data to understand overall transaction performance, customer demographics, transaction behavior, channel adoption, fraud patterns, risk levels, and pending transactions.

The project transforms raw financial data into an interactive Power BI dashboard designed to support data-driven business decisions.

📊 Dashboard Preview

Executive Summary



Finance & Risk Analysis



🔄 Project Workflow

CSV Data → Data Preparation → Power BI → Dashboard → Insights & Recommendations

🗂️ Dataset

The project uses two datasets covering customers and financial transactions.

Customer Dataset

Customers: 5,000

Geographical coverage: India

Customer segments: Retail, Premium, SME, Corporate, Wealth

Transaction Dataset

Transactions: 50,069

Transaction types: 10

Transaction channels: 7

Key Areas Analyzed

Category

Areas

Customer

Customer segments, Occupation, State

Transactions

Transaction type, Transaction amount

Channels

Branch, UPI, ATM, Net Banking, POS, Auto Debit, Mobile App

Risk

Risk Score, Risk Category

Fraud

Fraud Transactions, Fraud Rate

Status

Successful, Pending and other transaction statuses

Finance

Transaction Volume, Fees, Average Transaction Value

🧹 Data Preparation & Quality

The analysis identified several data-quality issues in the source data:

Channel inconsistencies – Different naming conventions were identified in channel values.

Currency inconsistency – Currency values contained case differences such as INR and inr.

Column naming issue – The fisrt_name column contains a spelling error.

Pending transactions – 2,036 transactions require further investigation.

📊 Power BI Dashboard

Finance_Analysis_Dashboard.pbix is an interactive Power BI dashboard covering financial performance, customers, transactions, risk, fraud, and business recommendations.

Dashboard Features

Executive financial KPIs

Customer segment analysis

State-wise customer distribution

Transaction type analysis

Transaction channel analysis

Fraud and risk assessment

Pending transaction monitoring

Business recommendations

Key KPIs

KPI

Value

Transaction Volume

₹456 Cr

Total Transactions

50,069

Customers

5,000

Transaction Success Rate

85.7%

Fraud Rate

1.26%

Average Transaction

₹9,110

Fraud Transactions

632

Pending Transactions

2,036

Average Risk Score

36.1 / 100

👥 Customer Analysis

The dashboard analyzes 5,000 customers across different customer segments and Indian states.

Customer Segments

Segment

Customers

Share

Retail

2,703

54.1%

Premium

895

17.9%

SME

780

15.6%

Corporate

374

7.5%

Wealth

248

5.0%

Top States by Customer Count

Maharashtra — 747

Gujarat — 541

Karnataka — 534

Uttar Pradesh — 492

Tamil Nadu — 482

Madhya Pradesh — 479

💳 Transaction Analysis

The project analyzes 50,069 transactions across 10 transaction types and 7 channels.

Top Transaction Types

Transaction Type

Transactions

Loan EMI

9,140

Transfer

8,479

Card Payment

5,329

Deposit

4,970

Bill Payment

4,310

Withdrawal

4,279

Transaction Channels

Channel

Transactions

Branch

7,236

UPI

7,206

ATM

7,185

Net Banking

7,125

POS

7,119

Auto Debit

7,084

Mobile App

6,344

🛡️ Risk & Fraud Analysis

The dashboard provides a dedicated assessment of financial risk and fraudulent transactions.

Fraud Transactions: 632

Fraud Rate: 1.26%

Clean Transactions: 49,437

Clean Transaction Rate: 98.74%

Average Risk Score: 36.1 / 100

Pending Transactions: 2,036

Risk Score Distribution

Risk Level

Distribution

Low (1–25)

25%

Medium (26–50)

50%

High (51–75)

15%

Critical (76–100)

10%

🔑 Key Insights

Strong transaction volume: ₹456 Cr in transaction volume across 50,069 transactions.

Diverse customer base: Retail customers represent the largest segment at 54.1%.

Diversified channel usage: Transaction activity is distributed across seven channels.

Loan EMI leadership: Loan EMI is the highest-volume transaction type with 9,140 transactions.

Low fraud rate: 632 transactions are classified as fraudulent, representing 1.26% of total transactions.

Pending transaction opportunity: 2,036 transactions (4.1%) require investigation.

Data quality opportunity: Channel naming, currency formatting, and column naming inconsistencies were identified.

Growth opportunity: Premium and Wealth segments provide potential opportunities for targeted financial products.

Mobile adoption opportunity: Mobile App transactions are lower than the other major transaction channels.

💡 Business Recommendations

1. Resolve Pending Transactions

Investigate the 2,036 pending transactions and introduce improved retry mechanisms and alerting processes to reduce transaction backlogs.

2. Improve Data Quality

Standardize channel names, normalize currency values to INR, and correct column naming inconsistencies.

3. Target High-Value Customer Segments

Develop targeted financial products and services for Premium and Wealth customers.

4. Increase Mobile App Adoption

Launch targeted campaigns to improve Mobile App adoption and reduce dependency on physical branches.

🛠️ Tech Stack

Tool

Purpose

Power BI

Interactive dashboard & visualization

Power Query

Data preparation & transformation

DAX

KPI calculations & business metrics

CSV

Source datasets

PowerPoint

Project presentation

📁 Repository Structure

├── customers.csv
├── finance_transactions.csv
├── Finance_Analysis_Dashboard.pbix
├── Finance_Analysis_Presentation.pptx
├── screenshots/
│   ├── dashboard-1.png
│   └── dashboard-2.png
└── README.md

🚀 How to Reproduce

Clone the repository.

Download/open the provided CSV datasets.

Open Finance_Analysis_Dashboard.pbix using Power BI Desktop.

If required, update the dataset file paths in Power Query.

Refresh the data.

Explore the dashboard using the available visuals and filters.

Review Finance_Analysis_Presentation.pptx for the project summary and recommendations.

📄 Project Presentation

The repository includes Finance_Analysis_Presentation.pptx, covering:

Executive Summary

Customer Base

Transaction Analysis

Risk & Fraud Assessment

Data Quality Issues

Business Recommendations

🎯 Project Outcome

This project demonstrates the ability to transform financial transaction data into a business-focused Power BI dashboard and communicate insights through KPIs, visualizations, customer segmentation, risk analysis, and actionable recommendations.

Skills Demonstrated

Data Analysis

Power BI Dashboard Development

Power Query

DAX

KPI Development

Customer Segmentation

Fraud & Risk Analysis

Data Visualization

Business Intelligence

Business Reporting
