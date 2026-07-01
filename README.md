# T20 Batting Impact Analysis

## Project Overview

This project analyzes IPL T20 batting performance during the death overs (16–20) using Python, SQL, and Power BI. The objective is to identify high-impact finishers by calculating advanced batting metrics and presenting insights through interactive dashboards.

---

## Dataset

**Source:** Cricsheet IPL Ball-by-Ball Dataset

**Seasons Used**
- 2021
- 2022
- 2023

**Files**
- deliveries.csv
- matches.csv

---

## Project Structure

```
T20-Batting-Impact-Analysis/
│
├── data/
│   ├── raw/
│   │   ├── deliveries.csv
│   │   └── matches.csv
│   │
│   ├── processed/
│   │   ├── deliveries_2021_2023.csv
│   │   └── deliveries_clean.csv
│
├── notebooks/
│   ├── day2_data_inspection.ipynb
│   └── day3_data_cleaning.ipynb
│
├── sql/
│
├── dashboards/
│   ├── powerbi/
│   ├── tableau/
│   └── screenshots/
│
└── README.md
```

---

## Tools Used

- Python
- Pandas
- SQL (Upcoming)
- Power BI (Upcoming)
- Git & GitHub
- VS Code

---

## Progress

### Day 2 – Data Inspection

- Downloaded IPL Cricsheet datasets
- Loaded CSV files using Pandas
- Inspected dataset structure
- Checked missing values
- Filtered dataset for IPL seasons 2021–2023
- Exported processed dataset

---

### Day 3 – Data Cleaning

- Loaded filtered dataset
- Verified player names
- Verified team names
- Checked missing values
- Replaced missing values in `extras_type` with `"None"`
- Exported cleaned dataset (`deliveries_clean.csv`) for SQL import

---

## Current Status

✅ Data collection completed

✅ Data inspection completed

✅ Data cleaning completed

⏳ SQL analysis starts next

---

## Upcoming Work

- Create SQL database
- Import cleaned CSV into SQL
- Filter death overs (16–20)
- Calculate Strike Rate
- Calculate Balls Per Boundary (BPB)
- Calculate Dot Ball Percentage
- Build Impact Score
- Perform K-Means Clustering
- Build Power BI Dashboard
- Train Machine Learning model for score prediction

---

## Author

**Annadanam Hemanth Kumar**

Aspiring Data Analyst | Python | SQL | Power BI

GitHub:
https://github.com/ANNADANAMHEMANTHKUMAR

LinkedIn:
(Add your LinkedIn profile here)