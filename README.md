# 🧪 Clinical Trial Data Wrangling & Analysis — Auralin vs Novodra

## 🚀 Project Overview
This project performs **end-to-end data wrangling and exploratory analysis** on a simulated Phase II clinical trial dataset for a new oral insulin drug **Auralin**, compared with **Novodra**.

The dataset simulates real-world healthcare data challenges such as:
- Missing values
- Inconsistent formats
- Duplicate records
- Multi-table relational complexity

The goal is to transform raw data into a **clean, structured dataset** and extract insights on treatment effectiveness and safety.

---

## 🎯 Problem Statement
Clinical datasets are often messy and fragmented, leading to:
- Incorrect analysis results  
- Poor medical decisions  
- Data inconsistency  

This project builds a **robust data cleaning and integration pipeline** to solve these issues.

---

## 📂 Dataset Description

| File | Description |
|------|------------|
| `patients.csv` | Patient demographics and baseline data |
| `treatments.csv` | Treatment details and dosage |
| `adverse_reactions.csv` | Side effects and reactions |

> ⚠️ Note: This dataset is synthetic and created for educational purposes.

---

## 🧠 Methodology

```mermaid
flowchart TD
    A[Raw Data] --> B[Data Assessment]
    B --> C[Data Cleaning]
    C --> D[Data Tidiness]
    D --> E[Data Integration]
    E --> F[Feature Engineering]
    F --> G[Exploratory Data Analysis]
    G --> H[Insights]
