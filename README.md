Task 1: Data-Cleaning-Preprocessing
Objective
To clean and prepare a raw dataset by identifying and handling null values, duplicates, inconsistent formats, and organizing the data for further analysis.

---

Dataset Used
Netflix Movies and TV Shows  
Source: [Kaggle - Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

Tool Used
- Microsoft Excel

---

Cleaning Steps Performed

1. Removed Duplicate Rows
   - Used `Remove Duplicates` under the Data tab to eliminate exact duplicates.

2. Handled Missing Values
   - Replaced blanks in `director`, `cast`, `country`, and `rating` with `"Unknown"`.
   - Replaced missing `date_added` values with `"Not Available"`.

3. Standardized Text Columns
   - Converted values in the `type` column to lowercase (e.g., `movie`, `tv show`) using `LOWER()` function.

4. Converted Date Format
   - Converted `date_added` to a consistent `DD-MM-YYYY` format using the `TEXT()` function.

5. Renamed Column Headers
   - All column names were renamed to lowercase with underscores (e.g., `date_added`, `show_id`) for consistency.

6. Split Dataset
   - Used Excel filters to separate entries into two sheets:
     - One for Movies
     - One for TV Shows

---
---

Notes
- No advanced Excel plugins or macros were used.
- All cleaning was done using basic Excel features (filters, formulas, formatting).

---

Learning Outcome
- Improved understanding of data cleaning steps such as null handling, standardization, formatting, and dataset structuring.
- Learned how to prepare real-world data using Excel for analysis or modeling.

