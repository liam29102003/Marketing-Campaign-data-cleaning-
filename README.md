# 🧹 Data Cleaning & Preprocessing Notebook (Python)

## 📌 Project Overview
This project demonstrates **real-world data cleaning and preprocessing techniques** using Python.  
The notebook focuses on identifying and fixing common data quality issues that frequently appear in raw datasets before analysis or machine learning.

The goal is to transform **messy, inconsistent data** into a **clean, reliable, and analysis-ready dataset**.

---

## 🎯 Objectives
- Clean inconsistent column headers
- Convert incorrect data types
- Fix currency and numeric formatting issues
- Handle categorical typos using fuzzy matching
- Normalize mixed boolean values
- Parse and validate date columns
- Enforce logical data integrity rules
- Detect and handle outliers
- Extract useful features from text columns

---

## 🧰 Tools & Libraries Used
- **Python 3**
- **Pandas**
- **NumPy**
- **FuzzyWuzzy / RapidFuzz** (for categorical typo correction)
- **Datetime utilities**

---

## 📒 Notebook Structure
The notebook is organized into clear, well-defined sections:

### 1️⃣ Header Cleaning
- Standardizing column names
- Removing spaces, special characters, and inconsistencies

### 2️⃣ Type Conversion & Currency Cleaning
- Converting strings to numeric values
- Cleaning currency symbols and formatting issues

### 3️⃣ Categorical Typos (Fuzzy Logic)
- Fixing misspelled category values
- Mapping similar text values to standardized labels

### 4️⃣ Handling Mixed Booleans
- Normalizing values like `Yes / No`, `True / False`, `1 / 0`

### 5️⃣ Date Parsing
- Converting string dates into datetime format
- Handling invalid or inconsistent date entries

### 6️⃣ Logical Integrity Checks
- **Clicks vs Impressions** validation
- Preventing logically impossible values

### 7️⃣ Time-Based Logical Integrity
- Detecting time-travel issues (future dates, invalid sequences)

### 8️⃣ Outlier Handling
- Identifying extreme values
- Applying appropriate treatment strategies

### 9️⃣ String Parsing & Feature Extraction
- Extracting structured information from text fields
- Creating new meaningful features

---

## 📊 Key Skills Demonstrated
- Practical **data cleaning workflows**
- Defensive data validation techniques
- Feature engineering from raw text
- Preparing data for **analytics or machine learning**
- Writing readable and well-structured notebooks

---

## 🚀 How to Run the Notebook
1. Clone this repository
2. Install required dependencies
   ```bash
   pip install pandas numpy rapidfuzz
