# Bike Buyers Demographics & Purchase Analysis (Excel)

## 📌 Project Overview
Why do certain customers buy bicycles while others pass? This project explores customer demographic data to uncover the driving factors behind bicycle purchases. Utilizing a raw dataset of 1,000 prospective buyers, I executed a complete data pipeline inside Microsoft Excel—from structural cleaning to pivot aggregation, culminating in a dynamic, user-facing executive dashboard.

## 🗂️ Workbook Architecture
The project is structurally separated across four dedicated layers within `Excel Project Dataset.xlsx`:
* **`bike_buyers`**: The raw, unformatted demographic data layer.
* **`working sheet`**: The staging environment where all data cleaning, structural updates, and logic testing occurred.
* **`pivot table`**: The back-end calculation layer used to aggregate and cross-reference key performance metrics.
* **`dashboard`**: The final interactive user interface containing dynamic charts and functional data filters.

## 🛠️ Data Cleaning & Engineering (Working Sheet)
Before building visuals, the raw data was prepared using the following techniques:
* **Standardization:** Cleaned single-letter codes in the `Marital Status` (M/S) and `Gender` (M/F) columns to explicit values (*Married/Single*, *Male/Female*) using Find & Replace.
* **Currency Formatting:** Converted the `Income` column to standard currency formatting for financial accuracy.
* **Age Segmentation:** Created a custom nested `IF` logic statement to group ages into explicit brackets (*Middle Age, Adolescent, Old*) to allow for granular cohort analysis.
* **Duplicate Elimination:** Filtered and removed duplicate records to protect data integrity.

## 📊 Dynamic Dashboard Preview
Below is the final interactive dashboard built to present these insights clearly to stakeholders.

![Interactive Excel Dashboard](excel_dashboard.png)

## 📈 Core Insights Discovered
* **The Income Threshold:** Customers who purchased a bicycle had a noticeably higher average income across both genders compared to non-buyers.
* **The Age Sweet Spot:** The *Middle Age* cohort represented the vast majority of bicycle purchases, marking them as the primary target demographic.
* **Commute Distance Factor:** Customers with shorter commutes (0-1 miles) showed a much higher propensity to purchase bicycles than those commuting long distances.

## ⚙️ Features Demonstrated
* Nested logical functions (`IF`)
* Pivot Tables & Pivot Charts
* Dashboard Slicers (Interactive filtering for Region, Education, and Occupation)
* Data Type casting and structural formatting
