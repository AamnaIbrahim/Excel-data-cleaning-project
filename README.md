# US Presidents Data Cleaning Project

This repository contains a comprehensive data cleaning project focused on standardizing and structuring a messy dataset of US Presidents. The goal was to transform raw, inconsistent data into a polished, analysis-ready format using data cleaning best practices.

## Dataset Overview

The project utilizes two main files:
* **`Raw Data.xlsx`**: The original dataset containing inconsistent text casing, extra spacing, hidden characters, duplicates, and unformatted columns (e.g., prior roles mixed with names, irregular party names).
* **`Cleaned Data.xlsx`**: The final output after applying various data cleaning techniques, featuring standardized columns, uniform formatting, and validated data types.


## Data Cleaning Steps & Transformation Log

The following issues were identified and resolved during the data cleaning process:

1. **Text Standardization (Casing):** Fixed inconsistent naming (e.g., converting `john adams` and `JAMES MONROE` to proper title case: `John Adams`, `James Monroe`).
2. **Whitespace & Character Trimming:** Removed accidental double spaces and trailing whitespaces in names, political parties, and vice president columns (e.g., `Democratic-  Republican` fixed to `Democratic-Republican`).
3. **Handling Duplicates:** Identified and removed duplicate entries for presidents (e.g., removing typos or repeated rows like the duplicate entries for Woodrow Wilson with typos like `Demorcatic`).
4. **Column Restructuring:** Separated or dropped irrelevant metadata (like the messy `prior` career column) to focus exclusively on essential presidential details: `S.No.`, `President`, `Party`, `Vice President`, `Salary`, and system dates.
5. **Data Type and Currency Alignment:** Formatted numerical values such as `Salary` into clean numeric strings/integers for seamless mathematical computations.


