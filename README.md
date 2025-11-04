# DataScienceCourse3_Assignment1
**Power BI Data Cleaning and Visualization — DS PGC Course 3 Assignment 1**

---

## 📘 Assignment Overview
This assignment demonstrates **data cleaning, modeling, and visualization in Microsoft Power BI Desktop**.  
It uses three datasets — **Customer**, **Product**, and **Sales** — to perform cleaning, transformation, and visual analysis.  

---

## 🧩 Tasks Summary
| Task | Topic | Objectives |
|:--|:--|:--|
| 1 | Data Cleaning | Round Price column (Product); Split Customer name into First and Last name. |
| 2 | Standardization | Convert Product Category to UPPERCASE; replace “unemployment” with “Unemployed” in Customer Profession. |
| 3 | Data Type Consistency | Ensure proper data types (Date, Decimal, Text); standardize Product Size values. |
| 4 | Modeling & Deduplication | Create relationships (CustomerID, ProductID); remove duplicates in Customer and Product. |
| 5 | Visualizations | • Bar Chart – Total Sales by Category   • Pie Chart – Sales Percentage by Category |

---

## 📂 Files Included
- `DataScienceCourse3Assignmen1Question.pdf` — Assignment brief and instructions. e3Assignment1Solution.pdf` — PDF with step-by-step Power BI screenshots and explanations.    

---

## 🧮 Key Steatasets in Power Query Editor.  
- Rounded *Price* values and split full names into two columns.  
- Formatted text columns (UPPERCASE / Capitalized values).  
- Verified and corrected data types and inconsistencies.  
- Built data model relationships (Customer–Sales and Product–Sales).  
- Created clean visualizations for total and percentage sales by category.  

---

## 🧭 Tools and Features
- **Power BI Desktop (Version ≥ 2024)**  
- Power Query Editor (Transform, Replace Values, Format)  
- Data Model Relationships (1-to-Many)  
- DAX Measure: `Total Sales := SUMX(Sales, Sales[Price] * Sales[Quantity])`  
- Visualization Formatting (Title, Labels, Colors, Legend)  

---

## 📝 How to Review
1. Open the solution PDF to see screenshots of each task and steps.  
2. Follow the steps in Power BI Desktop to replicate the results if needed.  
3. Check that each visual matches the assignment tasks (Tasks 1–5).  

---

## 👤 Author
**Utkarsh Anand**  
DS PGC Course 3 – Internshala Trainings  
