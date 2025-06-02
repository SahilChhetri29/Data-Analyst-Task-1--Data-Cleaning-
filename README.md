---

## Internship Task – Data Analyst Role

# Task 1: Data Cleaning & Preprocessing

This task focused on cleaning and preparing a raw dataset using **Microsoft Excel**. The goal was to detect and correct common data issues such as missing values, duplicate records, inconsistent formatting, and poorly structured column names.

---

## Dataset Overview

* **Dataset:** [marketing\_campaign.xlsx](https://github.com/user-attachments/files/20553251/marketing_campaign.xlsx)
* **Source:** *Customer Personality Analysis* from Kaggle

---

## Data Cleaning Steps in Excel

### 1. Missing Values

* Identified **24 missing entries** in the `Income` column.
* Replaced all missing values with the **average income**: `52,247.25`.

### 2. Duplicate Records

* Used Excel’s *Remove Duplicates* tool.
* No duplicates were found in the dataset.

### 3. Text Standardization

* Cleaned up categorical fields such as `Education` and `Marital_Status`:

  * Trimmed extra spaces
  * Formatted values using *Proper Case* for consistency

### 4. Date Formatting

* Converted all entries in the `Dt_Customer` column to a standard `YYYY-MM-DD` format.

### 5. Column Header Cleanup

* Renamed all column headers:

  * Used lowercase text
  * Replaced spaces with underscores (`_`) for uniformity

---

## Final Deliverables

Cleaned version of the dataset:
[marketing\_campaign\_cleaned.xlsx](https://github.com/user-attachments/files/20553232/marketing_campaign_cleaned.xlsx)

---

## Repository Overview

| File Name                               | Description                        |
| --------------------------------------- | ---------------------------------- |
| `marketing_campaign.xlsx`               | Original dataset                   |
| `marketing_campaign_cleaned_filled.csv` | Cleaned and processed version      |
| `README.md`                             | Task description and documentation |

---

## Tools Utilized

* **Microsoft Excel**

---
