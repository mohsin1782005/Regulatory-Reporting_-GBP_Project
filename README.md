# Regulatory Reporting & Data Distribution Project (GBP)

## 📌 Project Overview
This project focuses on a financial case study for a client requiring high-accuracy **Regulatory Reporting** in GBP. The core challenge involved cleaning a raw financial dataset and implementing specific business logic to distribute data into two distinct regulatory portions: **R1** and **R3**.

## 🎯 Business Case
The client needed to separate financial records based on specific regulatory criteria (R1/R3) to comply with reporting standards. The project demonstrates the full data lifecycle: from raw data ingestion and SQL transformation to executive-level visualization.

## 🛠️ Tech Stack
* **Data Cleaning:** Excel / SQL
* **Database Logic:** PostgreSQL (Methodology for R1/R3 Splitting)
* **Visualization:** Tableau (3 Key Dashboards)
* **Documentation:** Microsoft Word & PowerPoint 

## 📊 Methodology & SQL Logic
To ensure the data was distributed correctly between **R1** and **R3**, I applied the following logic:
1.  **Data Auditing:** Identified nulls and currency inconsistencies in Excel.
2.  **Transformation:** Imported data into SQL to handle complex filtering.
3.  **R1/R3 Distribution:** Created specific views to partition data.

> **Note:** Detailed SQL methodology, including joins and filtering logic, can be found in the [SQL logic document](./SQL%20logic/methodology_logic.docx).

## 📈 Key Visuals
The Tableau workbook includes three primary dashboards:
1.  **Portfolio Overview:** A high-level view of total GBP volume.
2.  **R1 vs. R3 Distribution:** A comparative analysis of the two data portions.
3.  **Compliance Audit:** Identifying trends and anomalies within the reporting period.

![Dashboard Preview](./visuals/R1%20UK%20Cross%20Currency.png)

## 📁 Project Contents
* [data](./data): Contains the raw and processed datasets.
* [SQL logic](./SQL%20logic): Documentation of the SQL scripts and data distribution rules.
* [visuals](./visuals): The Tableau workbook and dashboard previews.
* [reports](./reports): The final Case Study presentation and PDF report for stakeholders.

