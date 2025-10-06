# 🏦 Bank Loan Analysis — Power BI + SQL Project  

## 📘 Project Overview  
This project analyzes a bank’s loan portfolio to uncover key performance trends, lending patterns, and borrower profiles. Using **real-world data** with **38,577 records and 24 columns**, the analysis delivers insights into **funding, repayments, borrower risk, and portfolio health** through interactive Power BI dashboards.  

The goal is to empower stakeholders to make data-driven decisions around credit risk, portfolio management, and regional growth.

---

## 🧠 Business Problem  
The bank needed a unified analytical view to answer:  
- How are loan applications trending month-to-month (MTD, PMTD)?  
- What percentage of loans are classified as **Good vs. Bad**?  
- Which regions, purposes, and borrower types drive the most activity?  
- How do **employment length** and **home ownership** influence loan applications?  

---

## 🧩 Dataset Summary  
- **Rows:** 38,577  
- **Columns:** 24  
- **Data Source:** Real loan portfolio dataset (confidential)  
- **Key Fields:**  
  `issue_date`, `loan_amount`, `loan_status`, `term`, `purpose`,  
  `emp_length`, `home_ownership`, `funded_amount`, `amount_received`,  
  `interest_rate`, `dti`

---

## ⚙️ Tools & Technologies  
| Tool | Purpose |
|------|----------|
| **MS SQL Server 19** | Data storage, transformation, and KPI computation |
| **Power BI (June 2023)** | Visualization, DAX modeling, and interactive dashboards |
| **Power Query** | Data transformation and relationship management |
| **Excel 2021** | Initial data validation and checks |

---

## 🧹 Data Preparation  
Data cleaning and preprocessing included:  
- Standardizing `issue_date` to **YYYY-MM-DD** for time-based analysis.  
- Validating and correcting **data types** (dates, decimals, text).  
- Grouping loans into **Good vs. Bad** categories.  
- Creating DAX measures for **funded amount**, **received amount**, **MTD**, **PMTD**, and **MoM** comparisons.  

---

## 📈 Key Performance Indicators (KPIs)  
1. **Total Loan Applications**  
2. **Total Funded Amount**  
3. **Total Amount Received**  
4. **Average Interest Rate**  
5. **Average Debt-to-Income (DTI) Ratio**  

Each KPI is analyzed with **Month-to-Date (MTD)** and **Month-over-Month (MoM)** performance measures.

---

## 📊 Dashboard Highlights  

### 🧾 Dashboard 1: Summary  
- Displays **Total Applications, Funded Amount, Amount Received, Avg. Interest Rate, Avg. DTI**.  
- Segmentation by **Good vs. Bad Loans** with MTD & MoM comparisons.  
- Snapshot view of portfolio health.

### 🌎 Dashboard 2: Overview  
- **Monthly Trend:** Loan applications steadily increase month-over-month.  
- **Loan Term Distribution:** 73.8% of loans have a **36-month term**.  
- **Employment Length:** Borrowers with longer employment apply more often.  
- **Loan Purpose:** “Debt Consolidation” dominates.  
- **Home Ownership:** Borrowers who rent and those with mortgages are equally represented.  
- **Regional Map:** Highlights states with high lending activity.  

### 📋 Dashboard 3: Details View  
- Comprehensive grid displaying **loan-level details** (funded amount, received amount, DTI, status, etc.).  
- Interactive filters for **region**, **purpose**, and **term** for detailed analysis.  

---

## 💡 Key Insights  
- 📈 **Loan applications are increasing month-over-month**, showing portfolio growth.  
- 💰 **36-month loans dominate (73.8%)**, suggesting shorter-term loan preference.  
- 👔 **Borrowers with longer employment histories** tend to apply for larger loans.  
- 💳 **Debt consolidation** is the leading loan purpose.  
- 🏠 **Homeowners with mortgages and renters** are almost equally represented.  
- ⚖️ **Good loans outweigh bad loans**, indicating effective credit evaluation.  
- 🌍 **Regional analysis** highlights states with high-performing lending activity.

---

## 🧮 Business Impact  
This analysis helps stakeholders:  
- Monitor **loan performance** and **repayment efficiency**.  
- Identify **risk patterns** within the portfolio.  
- Prioritize **regions and borrower segments** for strategic growth.  
- Build a foundation for **predictive risk modeling** and automation.  

---

## 🎓 Learning Outcomes  
- Integrated **SQL Server** with **Power BI** for live analytics.  
- Mastered **DAX time intelligence** (MTD, PMTD, MoM).  
- Developed **interactive dashboards** focused on financial decision-making.  
- Enhanced storytelling through **data-driven visuals** for stakeholders.

---

## 📁 Project Flow  
SQL Server → Data Cleaning & Queries → Power BI Connection → DAX Measures → Dashboard → Insights


---

## 🧭 Future Enhancements  
- Add **machine learning** models to predict loan defaults.  
- Automate **data refresh** using Power BI Gateway.  
- Apply **RFM segmentation** for borrower profiling.  

---

## 👤 Author  
**Ramkumar N**  
Business Intelligence Analyst | Executive PG in Data Analytics (IIT Roorkee)  
📧 [ramkumar.nagaraju92@gmail.com](mailto:ramkumar.nagaraju92@gmail.com)  
🔗 [LinkedIn](linkedin.com/in/ramkumar-n-a8a817388) | [Portfolio](https://marked-unicorn-aef.notion.site/Ramkumar-Data-Analyst-Portfolio-27179b3fd86d80c6a194e9debe65e193)

---

## 📸 Dashboard Previews  
*[https://app.powerbi.com/view?r=eyJrIjoiOTljZWFhYzYtN2IzNC00Y2JmLThhZmEtODU1OGJiMmZhMTAzIiwidCI6IjI1Y2UwMjYxLWJiZDYtNDljZC1hMWUyLTU0MjYwODg2ZDE1OSJ9]*  
