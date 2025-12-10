# childplus-to-tsg-pipeline
Python pipeline for cleaning, validating, and merging ChildPlus and TSG datasets.
# ChildPlus → TSG Data Integration Pipeline

This project demonstrates how I clean, validate, and prepare raw exports from **ChildPlus** and **Teaching Strategies GOLD (TSG)** so they can be accurately merged for reporting and analysis.  
The focus is on building a repeatable and reliable pipeline for Early Childhood Education program data.

---

## 📌 Project Purpose

ChildPlus and TSG store child-level data separately, and their exports often:

- Use different column names  
- Store dates in different formats  
- Contain inconsistencies in child IDs  
- Require restructuring before analysis  

This notebook shows how I standardize both systems’ outputs so they can be combined and used for progress reporting, compliance checks, and classroom-level insights.

---

## 🧹 What the Pipeline Does

### ✔ 1. Import raw TSG export  
Reads the Teaching Strategies GOLD CSV export and prepares it for cleaning.

### ✔ 2. Rename and standardize columns  
Applies consistent, analysis-friendly column names.

### ✔ 3. Clean data types  
Handles:
- Dates  
- Numeric fields  
- Text normalization  
- Trimmed / missing values  

### ✔ 4. Validate child identifiers  
Ensures that IDs are valid and can be matched with ChildPlus records.

### ✔ 5. Handle missing or inconsistent values  
Detects and corrects common data issues found in raw TSG exports.

### ✔ 6. Prepare a clean, ready-to-merge dataset  
Final output can be joined with ChildPlus data for reporting or dashboards.

---

## 📂 Repository Contents

- `childplus_tsg_pipeline.ipynb`  
  Cleaned notebook (outputs removed) containing all data cleaning and preparation steps.

- `.gitignore`  
- `README.md`  

No real program data is included in this repository.

---

## 🔒 Data Privacy

This project originally worked with real ChildPlus and TSG data, but **all sensitive data has been removed**.  
The notebook includes **only code and structure**, with no outputs or identifying information.

