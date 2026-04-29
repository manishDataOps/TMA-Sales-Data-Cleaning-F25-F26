# TMA-Sales-Data-Cleaning-F25-F26
Cleaned and transformed cross-tabular TMA dataset (F25–F26) into analysis-ready format by combining manufacturer groups (MM, EIC, ESC). Suitable for Power BI, SQL, and business analytics projects.
# 📊 TMA Sales Data Analysis (F25–F26)

## 📁 Project Overview

This project focuses on transforming and analyzing a cross-tabular TMA dataset for the financial years F25 and F26. The original dataset contained complex manufacturer segmentation and wide-format structure, which was cleaned and converted into a structured, analysis-ready format.

---

## 🔄 Data Transformation Process

### 1. Handling Cross-Tabular Format

* Original dataset was in wide (cross-tabular) format
* Converted into **long/tabular format** using unpivoting
* Improved usability for tools like Power BI and SQL

---

### 2. Manufacturer Grouping

Multiple manufacturers were merged into logical groups:

| Original Manufacturers | New Group |
| ---------------------- | --------- |
| MM + PTL               | MM(G)     |
| EIC + TAFE             | EIC(G)    |
| ESC + Kubota           | ESC(G)    |

👉 This helped in simplifying analysis and improving comparability.

---

### 3. Data Cleaning

* Removed duplicate and unnecessary columns
* Standardized column names
* Ensured consistency across F25 and F26 datasets
* Combined both datasets into a single unified dataset

---

## 📊 Final Dataset Features

* Month-wise data (F25 & F26)
* State-wise performance
* Manufacturer group segmentation
* Category (HP range) classification
* Structured tabular format

---

## 📂 Files Included

* `TMA Clean Data.xlsx` → Final cleaned dataset

---

## 🛠️ Tools & Technologies

* Microsoft Excel (Power Query(M) (Data Cleaning & Transformation)
* Power BI (Visualization – optional)
* SQL (Data Analysis – optional)

---

## 📈 Use Cases

* Sales trend analysis
* Regional performance comparison
* Manufacturer group analysis
* Business decision-making insights

---

## 🎯 Key Learning Outcomes

* Data cleaning and preprocessing
* Cross-tabular to tabular transformation
* Data modeling for analytics
* Business data interpretation

---

## 📍 Author

Manish Kr Mandal
