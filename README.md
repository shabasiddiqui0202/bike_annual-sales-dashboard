# Bike Buyers – Excel Data Analysis Project

## 📌 Project Overview
This project analyzes a **Bike Buyers dataset** to understand what customer characteristics influence whether a person purchases a bike. The workbook combines raw data, a cleaned working dataset, PivotTables, and a summary dashboard to present clear, actionable insights.

The analysis was built entirely in **Microsoft Excel**, using PivotTables, PivotCharts, and Slicers to explore the relationship between demographics (income, gender, age, commute distance) and bike purchase behavior.

---

## 🗂️ Workbook Structure
The Excel file contains **4 sheets**:

| Sheet Name | Description |
|---|---|
| `dashboard` | Visual summary report titled **"Bike Annual Sales Report"** with charts and slicers for interactive filtering |
| `pivot table` | Three PivotTables analyzing income, commute distance, and age group vs. purchase decision |
| `bike_buyers` | Raw/original dataset as received |
| `working data set` | Cleaned version of the raw data used for analysis |

---

## 📊 Dataset Description
The dataset contains **1,026 customer records** with **14 attributes** per customer:

| Column | Description |
|---|---|
| ID | Unique customer identifier |
| Marital Status | Single / Married |
| Gender | Male / Female |
| Income | Annual income |
| Children | Number of children |
| Education | Highest education level (High School, Partial College, Bachelors, Graduate Degree, etc.) |
| Occupation | Job category (Manual, Skilled Manual, Clerical, Professional, Management) |
| Home Owner | Yes / No |
| Cars | Number of cars owned |
| Commute Distance | Distance range to work (0–1, 1–2, 2–5, 5–10, 10+ miles) |
| Region | Pacific, North America, or Europe |
| Age | Customer age |
| Age Group | Adolescence, Adult, Older |
| Purchased Bike | Target variable — Yes / No |

---

## 🧹 Data Cleaning
Before analysis, the raw data (`bike_buyers`) was cleaned into the `working data set` sheet by:
- Standardizing inconsistent category labels (e.g., text formatting errors in categorical fields)
- Correcting spelling and formatting of column headers
- Ensuring consistent capitalization across Yes/No and category values

---

## 📈 Key Analysis (PivotTables)

**1. Average Income vs. Gender vs. Bike Purchase**
- Compares average income of buyers and non-buyers, split by gender.
- Insight: Both male and female customers with **higher average income tend to purchase bikes** more often.

**2. Total Income vs. Commute Distance vs. Bike Purchase**
- Examines how commute distance relates to total income and purchase decisions.
- Insight: Customers with a **short commute (0–1 miles)** show the highest purchase rate, while those with **very long commutes (10+ miles)** are least likely to buy.

**3. Bike Purchases by Age Group**
- Breaks down purchases across Adolescence, Adult, and Older groups.
- Insight: **Adults** make up the largest share of both buyers and non-buyers, representing the core customer segment.

---

## 📊 Dashboard
The `dashboard` sheet presents a consolidated **"Bike Annual Sales Report"**, combining:
- PivotCharts visualizing the trends above
- Interactive **slicers** to filter by Region, Gender, and other attributes
- A clean, presentation-ready summary for stakeholders

---


### Dashboard View
<!-- Paste your dashboard screenshot here -->
![Dashboard Screenshot](<img width="850" height="512" alt="Screenshot 2026-09-05 104621" src="https://github.com/user-attachments/assets/ecc065c5-1f81-4a2f-a8d6-0910b3e022e6" />
)


## 🛠️ Tools Used
- Microsoft Excel
  - PivotTables & PivotCharts
  - Slicers for interactive filtering
  - Data cleaning and formatting functions

---

## 🎯 Conclusion
The analysis shows that **income level, commute distance, and age group** are strong indicators of whether a customer is likely to purchase a bike. These insights can help a bike company target marketing efforts toward high-income adults with shorter commutes, who represent the most promising customer segment.

---


## 📁 Files
- `1788585412902_Excel_Project_Dataset.xlsx` — Full workbook with raw data, cleaned data, pivot tables, and dashboard
- `README.md` — Project documentation (this file)

