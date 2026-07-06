# 💰 Finance Analytics Dashboard | Power BI

An interactive Business Intelligence dashboard built using **Microsoft Power BI** to analyze financial transactions, customer behavior, account information, and product performance.

---

# 📊 Project Overview

This project analyzes a banking/finance dataset and transforms raw data into meaningful business insights using Power BI.

The dashboard is divided into three interactive pages:

- 📈 Executive Dashboard
- 💳 Transaction Analysis
- 👥 Customer Analysis

Users can explore transaction trends, customer distribution, account performance, product categories, and regional transaction analysis through interactive visuals and slicers.

---

# 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft Excel
- Kaggle Dataset

---

# 📂 Dataset

**Source:** Kaggle Banking/Finance Dataset

The project follows a **Star Schema** data model consisting of one Fact table and multiple Dimension tables.

### Fact Table
- FactTransaction

### Dimension Tables
- DimCustomer
- DimAccount
- DimProduct
- DimProductCategory
- DimProductSubCategory

The dataset contains:

- Customer Details
- Account Information
- Product Categories
- Product Subcategories
- Transaction Records
- Transaction Types
- Transaction Channels
- Registration Dates
- Geographic Regions

---

# 📊 Dashboard 1 – Executive Dashboard

This page provides a quick overview of important business KPIs.

### KPIs

- Total Accounts
- Total Transaction Amount
- Total Transactions
- Total Customers

### Visuals

- Monthly & Yearly Transaction Trend
- Year Filter (Slicer)

### Key Insight

Provides a quick summary of overall business performance.

---

# 📊 Dashboard 2 – Transaction Analysis

This page focuses on transaction performance across different dimensions.

### Visuals

- Transaction Amount by Product Category & Subcategory
- Transaction Count by Transaction Type
- Transaction Amount by Channel
- Monthly Registration Trend
- Year Filter

### Key Insights

- Compare transaction amount across product categories.
- Analyze contribution of each product subcategory.
- Compare transaction channels (ATM, Mobile, Web).
- Identify monthly transaction trends.

---

# 📊 Dashboard 3 – Customer Analysis

This page analyzes customer behavior and account information.

### Visuals

- Customer Distribution by Gender
- Balance by Account Type
- Top 5 Customers
- Transaction Amount by Region (Map)
- Transaction Amount by Account Type
- Year, Quarter & Month Filter

### Key Insights

- Analyze customer demographics.
- Compare balances across account types.
- Identify highest-value customers.
- Analyze regional transaction distribution.
- Explore customer transactions interactively.

---

# 📸 Dashboard Screenshots

## Dashboard 1 – Executive Dashboard

![Dashboard 1](Images/Dashboard.1.png)

---

## Dashboard 2 – Transaction Analysis

![Dashboard 2](Images/Dashboard.2.png)

---

## Dashboard 3 – Customer Analysis

![Dashboard 3](Images/Dashboard.3.png)

---

# 📈 Business Insights

- Total transaction amount exceeded **5 Million**.
- More than **10,000 transactions** were analyzed.
- Mobile channel generated the highest transaction amount.
- Product categories contribute differently to total transactions.
- Savings and Checking accounts hold the highest balances.
- Female customers slightly outnumber male customers.
- Top customers contribute a significant portion of total transaction value.
- Transaction activity varies across different regions.

---

# 📚 Learning Outcomes

This project helped me learn:

- Data Cleaning using Power Query
- Data Modeling (Star Schema)
- Creating DAX Measures
- Interactive Dashboard Design
- KPI Cards
- Maps & Geographical Analysis
- Business Intelligence Reporting
- Data Visualization Best Practices

---

# 📁 Project Structure

```
Finance-Analytics-Dashboard
│
├── README.md
├── Finance Dashboard.pbix
├── Finance Dataset.xlsx
│
└── Images
    ├── Dashboard.1.png
    ├── Dashboard.2.png
    └── Dashboard.3.png
```

---

# 🚀 How to Use

1. Clone this repository.
2. Open **Finance Dashboard.pbix** in Microsoft Power BI Desktop.
3. Refresh the dataset if required.
4. Explore the dashboards using slicers and filters.

---

# 👩‍💻 Author

**Tanvi Pandey**

🎓 BCA (Data Science & Artificial Intelligence)

📊 Aspiring Data Analyst

---

⭐ If you found this project helpful, consider giving it a Star!
