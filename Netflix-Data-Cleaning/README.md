# 📊 Netflix Data Cleaning Project

## 🧹 Overview

This project focuses on cleaning and preparing a raw Netflix dataset using **Python (Pandas)**.
The goal is to transform messy, incomplete data into a structured and analysis-ready dataset that can be used for dashboards, insights, or machine learning projects.

---

## 📁 Dataset

* **Input file:** `netflix1.csv`
* **Output file:** `cleaned_netflix.csv`

The dataset includes information about Netflix shows such as titles, countries, directors, genres, and date added.

---

## ⚙️ Tools & Libraries

* Python 🐍
* Pandas 📊

---

## 🔄 Data Cleaning Steps

### 1. Load Data

* Read the CSV file using `pandas`
* Display dataset structure using `.info()` and `.head()`

---

### 2. Handle Missing Values

Different strategies were used depending on the column type:

* Fill missing **director** values with `"Unknown"`
* Fill missing **country** values with the most frequent value (mode)
* Drop rows with missing **date_added** (critical field)
* Optional: Fill numeric values using mean (if applicable)
* Apply forward fill (`ffill`) for remaining gaps

---

### 3. Remove Duplicates

* Checked for duplicate rows using `.duplicated()`
* Removed all duplicate records using `.drop_duplicates()`

---

### 4. Handle Missing Rows (Advanced Filling)

* Applied **forward fill (ffill)** to propagate previous valid values
* Optional: backward fill (`bfill`) can also be used

---

### 5. Drop Unnecessary Columns

* Removed irrelevant columns such as `show_id`
* Used `errors='ignore'` to avoid errors if column doesn’t exist

---

### 6. Split Columns

* Split `listed_in` into multiple genre columns:

  * `genre_1`
  * `genre_2`
* Converted `date_added` into:

  * `year_added`
  * `month_added`

---

### 7. Text Cleaning

* Removed extra spaces using `.str.strip()`
* Standardized text to lowercase for consistency

---

### 8. Final Validation

* Rechecked dataset structure after cleaning
* Verified no major missing or duplicate issues remain

---

## 💾 Save Clean Dataset

The cleaned dataset is saved as:

```
cleaned_netflix.csv
```

---

## 🚀 Outcome

After cleaning, the dataset becomes:

* More consistent
* Free of duplicates
* Missing values handled
* Ready for analysis and visualization
