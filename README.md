# 🚴‍♂️ Dataline Bike Company - Power BI Capstone Project

This repository contains the Power BI report developed as part of my graduation project for the Udemy course ([Link]([url](https://www.udemy.com/share/105uTi3@ZN9ZaH1nOzgyXLCcYBhhGPGK6O3qHQYEuLS-2HVTFjyQGOCrbfQc6JnLekV-KqyGew==/))). The goal was to transform raw sales and product data into meaningful business insights for **Dataline Bike Company**, a global manufacturer of bikes and accessories. Find all project files/reports/snapshots/recordings on Google Drive Link - [here](https://drive.google.com/drive/folders/1ZPlOFFj4LS0I9Es19IfMZebNmJc6-FEM?usp=drive_link).

## Project Objective

To replace static PDF and Excel reports with a fully interactive, visually appealing, and insight-rich **Power BI Dashboard** tailored for two main user groups:

- **CEO & Managers**
- **Marketing & Product Team**

---

## Data Sources

- `Sales_2017.csv` to `Sales_2020.csv`: Sales data over four years
- `ProductData.xlsx`: Multiple sheets containing product, customer, and category data

---

## Business Questions Answered

### CEO Dashboard
- Which products are generating the most **profit or loss** across countries?
- How is **revenue** evolving over time?
- What’s the **profit breakdown** by product categories and subcategories?

### Marketing & Product Dashboard
- What is the **Year-to-Date (YTD) sales and profit**?
- How does **profit compare to the previous year**?
- Who are the **top customers by revenue**?
- What is the **average profit per customer**, and how has it changed?
- How has **category revenue** and **profit margin** evolved over time?
- Drillthrough details: Orders by product, quantity, revenue, profit, country, and date

---

## Features & Techniques Used

- Data Cleaning & Transformation using **Power Query**
- **Star Schema** data model with relationships
- DAX Measures:
  - Revenue = `Order Quantity * Unit Price`
  - Profit = `Order Quantity * (Unit Price – Standard Cost)`
  - YTD Sales/Profit, Previous Year Profit, Profit Difference, Profit Margin, etc.
- Custom Date Dimension built in Power Query
- Conditional formatting with data bars and tooltips
- Drillthrough for detailed order insights
- Interactive visuals: matrix, map, bar/line/area charts, KPIs

---

## PowerBI Dashboard Screenshots

![ceo](https://github.com/user-attachments/assets/53f4e99d-bbac-4854-beae-d357ca61c619)


![marketing and products team](https://github.com/user-attachments/assets/3e82ef69-5d5f-4212-847b-62fd0d2acab8)


![drillthrough via category - order details](https://github.com/user-attachments/assets/1d57b7f3-f8ed-40d4-9078-3f15d2efd892)


---

## 📁 View Project Files

Google Drive Link - ([Click Here](https://drive.google.com/drive/folders/1ZPlOFFj4LS0I9Es19IfMZebNmJc6-FEM?usp=drive_link))

---
