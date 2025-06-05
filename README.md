# 🏦 Bank Loan Financial Insights Dashboard – Power BI

## 📊 Overview

Welcome to the **Bank Loan Financial Insights Dashboard**, a powerful, enterprise-grade analytics solution purpose-built for banks, lending institutions, and financial partners. This Power BI report offers a **360° view** into loan application trends, funding activity, repayment behavior, and credit risk evaluation. With dynamic KPIs, MoM performance trends, and region-specific insights, this tool empowers banks to make **data-driven lending decisions** and minimize default risk.

---

## 🧠 Key Features

- **3 Interactive Dashboards**
  - ✅ **Summary View**: MTD KPIs, Good vs. Bad Loan segmentation, portfolio health metrics
  - 🌎 **Overview Dashboard**: Trends by issue date, geography, loan term, home ownership, purpose, and employment data
  - 🔍 **Detailed Loan Explorer**: A granular view of each loan with borrower and financial metadata

- **Live KPIs for Bank Decision-Making**
  - Total Loan Applications (MTD, MoM)
  - Funded Amount & Amount Received
  - Average Interest Rate & Debt-to-Income Ratio
  - Good vs. Bad Loan Distributions

- **Advanced Visuals & Data Models**
  - MoM % Change Metrics (via DAX)
  - Regional Maps, Donut & Bar Charts, Tree Maps
  - SQL-driven backend metrics and date intelligence logic

---

## 💼 Why This Dashboard Matters for Banks

> Built for **Credit Risk Teams, Financial Analysts, and Loan Portfolio Managers**, this solution delivers insights into borrower behavior, creditworthiness, and revenue generation.

### 📈 Business Benefits
- **Optimize Lending Strategies**: Understand loan performance by segment (region, employment, purpose)
- **Identify High-Risk Areas**: Real-time Good vs. Bad loan ratio tracking
- **Support Compliance & Audit**: Structured data classification and tracking for every loan
- **Boost Recovery Rates**: Pinpoint areas of delayed or partial payments and initiate action
- **Forecast Trends**: Leverage MoM analytics for portfolio growth prediction

---

## 📷 Dashboard Snapshots

### 🔹 Summary Page
![Loan Summary Dashboard](https://raw.githubusercontent.com/NIKHILG15/Bank-Loan-Financial-Report/main/screenshots/Loan_report_summarypg_screenshot.jpg)

### 🔹 Overview Page
![Loan Overview Dashboard](https://raw.githubusercontent.com/NIKHILG15/Bank-Loan-Financial-Report/main/screenshots/Loan_report_overviewpg_screenshot.jpg)

### 🔹 Details Page
![Loan Details Dashboard](https://raw.githubusercontent.com/NIKHILG15/Bank-Loan-Financial-Report/main/screenshots/Loan_report_detailspg_screenshot.jpg)

---

## 🧮 DAX Measures & SQL Integration

> The project includes robust DAX measures and SQL queries to support time-based and performance-based metrics.

### 📐 Key DAX Measures
- `Total Funded Amount`, `Avg Interest Rate`, `Avg DTI`
- `MoM % Change in Funded Amount`, `Good/Bad Loan Percentage`
- `MTD Loan Applications`, `MTD Received Amount`

➡️ Full List: [📄 DAX_Measures_Bank_Loan_Report.docx](./DAX_Measures_Bank_Loan_Report.docx)

### 💾 SQL Queries
Comprehensive T-SQL queries power the backend including:
- Application count by month
- Good vs. Bad loan segmentation
- Regional analytics by `Address State`
- Risk evaluation using `Loan_Status`, `DTI`, and `Int_Rate`

➡️ View all queries here: [📄 Bank_Loan_Report_Queries.docx](./Bank_Loan_Report_Queries.docx)

---

## 🧠 Data Dictionary

Each column has been categorized with business-use explanations to help banking professionals understand its significance.

Example:
- `Loan Status`: Indicates current loan standing (Current, Fully Paid, Charged Off)
- `Purpose`: Explains the reason for loan application (Education, Home, Medical)
- `DTI`: Debt-to-Income Ratio – critical for assessing borrower's repayment ability

➡️ Full data glossary: [📄 BANK LOAN REPORT.docx](./BANK%20LOAN%20REPORT.docx)

---

## ⚙️ Technical Stack

| Tool/Language | Purpose |
|---------------|---------|
| **Power BI Desktop** | Report authoring & visual design |
| **DAX** | Calculated measures & KPIs |
| **T-SQL** | Data aggregation & backend logic |
| **Excel/CSV** | Source data processing |
| **Power Query** | Data transformation pipeline |

---

## 🏁 How to Use

1. Download the `.pbix` file: [📦 BANK LOAN FINANCIAL REPORT.pbix](./BANK%20LOAN%20FINANCIAL%20REPORT.pbix)
2. Open in **Power BI Desktop**
3. Connect to your database or load the demo dataset
4. Navigate through the dashboards using the bottom tabs
5. Apply slicers (term, region, date) to customize your view

---

## 🏢 Tailored for Banks and Lending Institutions

Whether you're an underwriter, analyst, or financial executive, this tool is designed with **banking-grade precision**, allowing your team to:

- Monitor performance
- Reduce loan default risk
- Improve disbursement strategies
- Enhance transparency with internal and external stakeholders

---

## 📬 Contact

Developed by **Nikhil Prashant Garse**  
📧 [Email](mailto:nikhilprashantgarse@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/nikhil-garse)  
📍 Tennessee, USA

---

## 📄 License

This project is shared for **educational and demonstration** purposes. For enterprise licensing and implementation consultation, feel free to reach out.

---

## ⭐ Star this Repository

If you find this project insightful, don’t forget to **star** ⭐ the repository and share it with professionals in the banking and finance industry.

---
