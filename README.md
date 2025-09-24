# Credit Card Financial Dashboard

This project is an **interactive financial dashboard** built in **Power BI** to analyze weekly credit card transactions and customer data from a **PostgreSQL database**.

---

## 📊 Dashboard Preview
<!-- Add a screenshot of your dashboard here -->

---

## 🔑 Key Performance Indicators (KPIs)

The dashboard tracks critical financial and customer metrics, including:

- **Total Revenue:** $55.4M  
- **Total Interest:** $7.9M  
- **Total Transactions:** 657K  
- **Key Insight:** A **28.8% revenue increase** was identified in the final week's analysis.  
- **Top Drivers:** Blue & Silver cards account for **93% of transactions**, with TX, NY, & CA contributing **68% of revenue**.  

---

## 🛠 Technology Stack
- **Data Visualization:** Power BI  
- **Database:** PostgreSQL (SQL)  
- **Data Transformation:** DAX  

---

## 🚀 How to Use

1. **Set up the Database:** Create a new PostgreSQL database.  
2. **Create Tables:** Run the `Financial Dashboard Data.sql` script to create the necessary tables.  
3. **Import Data:** In the `.sql` script, update the file paths in the `COPY` commands to point to your local `.csv` files and execute the script.  
4. **Connect Power BI:** Open the Power BI file and connect it to your PostgreSQL database to load the data and view the dashboard.  

---

## 📂 Project Structure
- `Financial Dashboard Data.sql` → SQL script to create tables and load data.  
- `CreditCardDashboard.pbix` → Power BI dashboard file.  
- `data/` → Folder containing CSV datasets.  

---

## 📈 Insights
This dashboard helps track and analyze **revenue growth, customer behavior, and transaction trends** to support data-driven financial decision-making.  

---
