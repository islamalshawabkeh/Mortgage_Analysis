# Mortgage_Analysis
# 📊 Mortgage Trading Analysis in Power BI

## 🔍 Project Overview

This Power BI report analyzes the trading performance and risk profile of a mortgage loan portfolio. It brings together multiple datasets to support decision-making in secondary mortgage markets, highlighting loan statuses, bid activity, bond pricing, and borrower credit data.

The goal is to enable institutions or analysts to:
- Evaluate loan sale readiness
- Compare bids across institutions
- Monitor loan status through processing stages
- Benchmark loans against UMBS bond prices
- Assess borrower and property risk indicators

---

## 📁 Data Model

The report integrates five datasets with relationships based on `loan_id`:

### 1. **Loan Balances**
- Loan payment progress, interest rates, balances

### 2. **Loan Status**
- Key dates in the mortgage file lifecycle (audit, custodian, etc.)

### 3. **Loan Bids**
- Competitive bid values from multiple institutions

### 4. **UMBS Prices**
- Bond data to evaluate mortgage-backed securities pricing

### 5. **Loan Data**
- Full mortgage metadata: credit score, LTV, DTI, location, occupancy, loan type, etc.

---

## 📊 Report Structure

| Page | Description |
|------|-------------|
| **Overview** | Portfolio KPIs: Total Loans, Avg Rate, Total Balance |
| **Loan Performance** | Remaining balance, delinquency detection, interest heatmaps |
| **Loan Status Tracker** | Process pipeline: closing → audit → custodian |
| **Institutional Bidding** | Highest bids, bid spreads, top bidders |
| **Bond Price Comparison** | Loan rate vs. UMBS bond price/coupon |
| **Borrower Risk Profiles** | Credit score, debt-to-income, LTV, property type |

---

## 🛠 Tools & Techniques

- **Power BI Desktop**
- **DAX Measures** for custom calculations (e.g., Remaining Term, LTV Ratio)
- **Power Query** for data shaping and transformation
- **Relationships** built on `loan_id` as primary key

---

## ✅ Outcomes

- Clear visibility into loan portfolio quality
- Identification of high-value loans based on bids
- Risk segmentation by borrower, property, and geography
- Alignment of loan pricing with secondary bond markets
- Operational monitoring of loan processing stages

---

## 🧠 Usage Instructions

1. Open the Power BI `.pbix` file.
2. Use slicers to filter by state, institution, or loan status.
3. Navigate across the report tabs to view insights.
4. Hover over visuals for detailed tooltips.
5. For quick overview : open pdf file .
---

## 📬 Contact

For questions or project details, contact:

**[Islam_AlShawabkeh]**  
Email: [islamshawabkeh12@gmail.com]  
LinkedIn: [www.linkedin.com/in/islamalshawabkeh]  

---

