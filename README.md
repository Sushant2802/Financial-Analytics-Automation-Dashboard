# 📊 Financial Analysis Project

This project demonstrates **end-to-end financial analytics automation and visualization** using **Power BI, Power Query, Python, and Google Cloud Platform (GCP)**.  
It solves **real-world business problems** by automating data ingestion, cleaning, transformation, and building interactive dashboards.

---

## 🚀 Project Overview

- **Client**: US Government  
- **Workflow Challenge**:  
  Each day ~25 data files were received via email (~3 PM) from a distributed survey team, and the dashboard had to be built & delivered by 8 PM.  
  The manual process was **time-consuming, error-prone, and costly ($12,000/month)**.

- **Objective**:  
  - Automate the data pipeline (Email → Power BI)  
  - Reduce turnaround time  
  - Minimize errors  
  - Cut costs & improve efficiency  

---

## ⚡ Workflow Automation

The automated pipeline:

```
Email → Power Automate → Google Drive → GCP API → Python Script → Power BI
```

### Steps:
1. **Email Rule Setup**: Outlook mail rule filters relevant analytics emails into a dedicated folder.  
2. **Power Automate**: Automatically transfers attachments to Google Drive.  
3. **Google Drive API**: Secure access to only the "Financial Project" folder.  
4. **Python Script (Power BI Desktop)**: Fetches & concatenates all files.  
5. **Power Query**: Cleans and preprocesses data for dashboarding.  

---

## 🧹 Data Cleaning Process (Power Query)

Key transformations:
- Handled missing/invalid values (`No Information`, `Data Missing`)  
- Fixed outliers in **Age, Bank Accounts, Credit Cards, Interest Rate**  
- Created new features like **monthly_in_hand_salary**, **credit history in months**, and **age bins**  
- Processed **loan types** into structured data  

---

## 📈 Business Problems Solved

### ✅ Problem Statements (Highlights)
1. Automating file ingestion from emails to Power BI.  
2. Calculating **average annual income, monthly balance, payment delays, credit utilization**.  
3. Analyzing **age vs. credit limit changes**.  
4. Visualizing **age demographics**.  
5. Credit score distribution across **age groups (Teen, Young Adult, etc.)**.  
6. Payment behavior analysis for different **credit mix categories**.  
7. Identifying potential loan customers by age group.  
8. Filtering **loan inquiries > 7.5** to refine target customers.  
9. Calculating **LTV (Lifetime Value) scores** and assigning promotions.  
10. Analyzing **credit card ownership trends by age**.  
11. Counting **types of loans dispersed** to find popular loan products.  

---

## 📊 Dashboard

The interactive **Power BI Dashboard** presents:
- Customer demographics  
- Credit utilization trends  
- Loan distribution insights  
- LTV-based promotions  
- Age-group-based financial behaviors  

🔗 **Live Power BI Report**:  
[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiN2IwYTY5NmEtMDk2NC00NTcyLWI2YmItOTNkNmVmYTc0OTQxIiwidCI6ImNhZWFiMzBhLTJjODUtNDc3Ny1iYjgwLTM1ZWQwNmU0ODFkZSJ9)  

---

## 🛠️ Tech Stack

- **Power BI Desktop & Power BI Service**  
- **Power Query** for data transformation  
- **Python** for file ingestion (Power BI script)  
- **Microsoft Outlook** (Email rules)  
- **Power Automate** for workflow automation  
- **Google Cloud Platform (GCP)** – Drive API integration  

---

## 📌 Key Insights
- Automated workflow reduced **daily manual work by 80%**.  
- Eliminated **$12,000/month manual labor costs**.  
- Increased accuracy & reduced human errors.  
- Improved delivery time from **5 hours → <1 hour**.  
- Provided actionable insights for **targeted marketing, promotions, and loan strategies**.  

---

## 👨‍💻 Author

**Sushant Mane**  
[LinkedIn](#) | [GitHub](#)  
