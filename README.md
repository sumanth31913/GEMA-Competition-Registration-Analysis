# GEMA Competition Registration Performance Analysis 📊

## Project Overview

This project analyzes GEMA Education's competition registration data to understand how registrations are performing in 2026 compared with the same period in 2025.

The project focuses on cleaning and preparing the registration data, performing year-over-year analysis, identifying competition-level performance and trends, and presenting the findings through an interactive Power BI dashboard.

The main objective is to convert raw registration data into clear business insights that can help GEMA management understand registration performance and make better decisions.

---

## 🎯 Business Problem

GEMA Education conducts multiple student competitions throughout the year.

Management wants to understand:

- How many students registered in 2025 and 2026?
- How much have registrations grown year over year?
- Which competitions are growing the fastest?
- Which competitions are growing slowly?
- How are registrations changing over time?
- Which competitions may require additional attention or promotion?

To ensure a fair comparison, 2026 registrations are compared with the **same time period in 2025**.

---

## 📅 Comparison Period

The analysis uses the same period for both years:

**January 1 – September 4**

- 2025: January 1 – September 4, 2025
- 2026: January 1 – September 4, 2026

Using the same period avoids comparing a partial year against a longer period.

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- **Power Query**
- **Power BI**
- **DAX**
- **Data Cleaning**
- **Data Analysis**
- **Data Visualization**
- **Business Intelligence**

---

## 📂 Dataset

The project uses two registration datasets:

- 2025 Competition Registrations
- 2026 Competition Registrations

### Main Fields

The datasets contain registration-level information such as:

- Registration ID
- Registration Date
- Competition
- Student Name
- School
- Grade
- City
- Country
- Registration Source

---

## 🧹 Data Cleaning & Preparation

Before performing the analysis, the datasets were cleaned and standardized.

### Cleaning steps performed

- Removed duplicate registration records
- Checked and handled missing/blank values
- Standardized inconsistent competition names
- Standardized inconsistent school names where required
- Corrected inconsistent date formats
- Identified and handled obvious invalid/test records
- Created Year fields
- Created Month fields for trend analysis
- Filtered the datasets to the comparable period
- Combined the cleaned datasets for analysis

### Data Quality Checks

The following checks were performed:

- Duplicate Registration IDs
- Missing values
- Date validity
- Competition name consistency
- School name consistency
- Registration period

---

## 📊 Key Performance Indicators

The dashboard tracks the following KPIs:

| KPI | Value |
|---|---:|
| 2025 Registrations | 1,800 |
| 2026 Registrations | 2,150 |
| Absolute Change | +350 |
| YoY Growth | +19.44% |

### YoY Growth Calculation

```text
YoY Growth % =
(2026 Registrations - 2025 Registrations)
÷ 2025 Registrations × 100
