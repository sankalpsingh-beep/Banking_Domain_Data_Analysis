# 📊 Banking Domain Data Analysis & Power BI Dashboard

## 📌 Overview
This project focuses on **Banking Domain Data Analysis** to develop a basic understanding of **risk analytics in banking and financial services**.  
The analysis demonstrates how customer data can be used to evaluate loan risk and support better lending decisions.

The project involves:
- Data loading and analysis using **Python**
- Data cleaning and feature engineering
- Building an **interactive Power BI dashboard** for insights

---

## 📂 Dataset
The dataset contains banking and client-related information distributed across multiple interlinked tables.

### Key Tables
- Clients – Banking  
- Banking Relationship  
- Gender  
- Investment Advisor  
- Period  

These tables are connected using **primary and foreign keys** to enable meaningful analysis.

### Data Includes
- Client demographics  
- Loan details (Bank Loan, Business Lending, Credit Cards)  
- Deposit details  
- Engagement duration  
- Income and nationality  

---

## 🛠️ Tools & Technologies
- **Python**
  - Pandas
  - NumPy
  - Matplotlib / Seaborn
- **Power BI**
  - Data modeling
  - DAX calculations
  - Interactive dashboards
- **SQL**
  - Conceptual knowledge only (not implemented in this version)

---

## 🔍 Project Steps

### 1️⃣ Data Loading
- Loaded CSV datasets into Python using Pandas.
- Checked data types, null values, and structure.

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed loan, deposit, and engagement distributions.
- Identified missing values and data inconsistencies.
- Studied customer behavior patterns.

### 3️⃣ Data Cleaning & Feature Engineering
The following transformations were applied:

- Created **Engagement Timeframe** to track client duration.
- Created **Engagement Days** using joining date.
- Created **Income Band**:
  - Low: Income < 100,000  
  - Mid: Income < 300,000
- Created **Processing Fees** based on fee structure.

---

## 📊 Power BI Dashboard

### Dashboards Included
- Home Dashboard  
- Loan Analysis  
- Deposit Analysis  
- Summary Dashboard  

### Key KPIs
- Total Clients  
- Total Loan  
- Total Deposit  
- Total Fees  
- Total Credit Card Amount  
- Engagement Length  

### DAX Functions Used
- `SUM`
- `DISTINCTCOUNT`
- `SUMX`
- `SWITCH`
- `DATEDIFF`

---

## 📈 Results & Insights
- Identified customer segments with higher loan exposure.
- Analyzed deposits vs loans across investors.
- Observed income bands contributing most to bank loans.
- Evaluated customer engagement duration.
- Enabled data-driven decision-making for loan approvals.

---

## ▶️ How to Run the Project

### Python Analysis
Install required libraries:

- pip install pandas, numpy, matplotlib seaborn

- Run the Python scripts or notebooks for analysis.

- Power BI Dashboard

- Open the .pbix file in Power BI Desktop.

- Refresh the dataset if required.

- Explore dashboards using filters and visuals.

🚀 Future Enhancements

- Implement SQL queries using MySQL / SQL Server.

- Add automated data pipelines.

- Build predictive risk analytics models.

- Enhance dashboards with real-time data.

📚 References

YouTube Tutorial:
(https://youtu.be/qlYT2VIyaaY?si=1IbRSr79Pj4tUfZ_)
