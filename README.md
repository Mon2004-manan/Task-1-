# Task-1-
Excel Basics: Data Cleaning &amp; Formatting
📌 Objective

The objective of this task is to clean and standardize a real-world dataset using Microsoft Excel, identify data quality issues, and prepare a clean dataset ready for analysis.

📂 Dataset Used

Netflix Movies and TV Shows Dataset

Source: Kaggle

Format: CSV

Rows: ~8,800

Columns: 12

The dataset contains missing values, duplicates, inconsistent text formats, and date issues, making it suitable for data cleaning practice.

🛠 Tools Used

Microsoft Excel

CSV & XLSX file formats

🔄 Steps Performed
1️⃣ Data Import

Downloaded the dataset from Kaggle

Opened the CSV file in Excel

Verified column headers and delimiter

2️⃣ Data Exploration

Froze the header row using Freeze Panes

Applied filters to all columns for easy analysis

3️⃣ Handling Missing Values

Identified missing values using column filters

Decisions made based on column context:

Director, Cast → Left blank (optional information)

Rating → Standardized where required

Added observations in Data_Quality_Notes

4️⃣ Removing Duplicates

Created a backup copy of raw data

Removed duplicate records using:

show_id

title

5️⃣ Text Cleaning & Standardization

Removed extra spaces using TRIM()

Standardized text case using PROPER() and UPPER()

Fixed inconsistent naming patterns

6️⃣ Data Type Validation

Corrected date formats to YYYY-MM-DD

Ensured numeric columns had no symbols

Verified categorical columns for spelling consistency

7️⃣ Cleaned Dataset Creation

Created a separate worksheet named Cleaned_Data

Copied only cleaned and validated records

Maintained raw data separately for integrity

8️⃣ Data Quality Documentation

Added a column named Data_Quality_Notes

Included short notes such as:

“Missing director names present”

“Date format corrected”

“Duplicates removed safely”

9️⃣ Final Output Files

Raw_Data.xlsx

Cleaned_dataset.xlsx

cleaned_dataset.csv

📈 Final Outcome

Learned hands-on Excel data cleaning techniques

Improved understanding of data quality issues

Created a structured and analysis-ready dataset

Followed professional data handling practices

📌 Interview Questions Covered

Difference between deleting vs imputing missing data

Risks of incorrect duplicate removal

Role of TRIM and CLEAN functions

Importance of validating data types

Why raw and cleaned data should be kept separately
