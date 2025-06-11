# UPI Transactions Analysis 📊

An in-depth analysis of a Unified Payments Interface (UPI) transaction dataset to uncover trends, user behavior, and key patterns in the digital payments landscape. This project leverages Python for data processing and analysis and conceptualizes an interactive Power BI dashboard for business intelligence.

---

### ► Data Source

The analysis is performed on the `UPI+Transactions.xlsx` dataset, which contains 20,000 anonymized records of UPI transactions. Each record includes various features such as transaction amount, status, bank names, merchant details, customer demographics, and transaction purpose.

---

### ► Project Components

This repository is structured into two main analytical components:

#### 1. Jupyter Notebook Analysis (`UPI_Transactions_Analysis.ipynb`)

The core of this project is a Jupyter Notebook that performs exploratory data analysis (EDA) using tables to derive insights. Using the **Pandas** library, the notebook conducts several tabular analyses:

-   **Data Loading and Inspection**: The dataset is loaded and its structure is examined using `.head()` to preview the data.
-   **Data Integrity Check**: A check for missing values is performed across all columns using `.isnull().sum()`.
-   **Descriptive Statistics**: A statistical summary is generated with `.describe(include='all')` to understand the distributions and ranges of all data fields.
-   **Top Transaction Identification**: The data is sorted by `Amount` in descending order to create a table of the top 10 highest-value transactions.
-   **Frequent Merchant Analysis**: The `value_counts()` function is used to produce a table of the most frequent merchants in the dataset.

#### 2. Power BI Dashboard

To extend the analysis, this project includes a conceptual design for a dynamic Power BI dashboard. This business intelligence tool would provide a user-friendly, interactive interface for exploring the data and deriving actionable insights.

**General Info & Key Capabilities:**

-   **UPI Transactions Summary**: The dashboard would offer a high-level, aggregated view of key performance indicators, including total transaction volume, total monetary value, and overall success rates.

-   **UPI Transactions Trends**: It would provide the ability to analyze transaction patterns over time. Users could identify trends on a monthly, weekly, or daily basis to understand peak activity periods.

-   **Bank and City-Level Details**: The dashboard would allow for a deep dive into performance by specific entities. This includes a comparative analysis of transaction volumes across different banks and a geospatial analysis of transaction activity by city to identify regional behavior.

-   **Remaining Balance Analysis**: It would provide general insights into customer account balances after transactions, helping to understand the financial state and spending power of the user base.

-   **Interactive Filtering**: The entire dashboard would be designed with interactive filters. Users could dynamically segment the data by dimensions such as date range, city, specific banks, and merchants to conduct focused analysis.

---

### ► Technologies Used

-   **Data Analysis**: `Python`
-   **Python Libraries**: `Pandas`, `NumPy`, `Plotly`, `Seaborn`
-   **IDE**: `Jupyter Notebook`
-   **BI & Visualization**: `Microsoft Power BI`, `Microsoft Excel`

---
