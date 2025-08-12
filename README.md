**Data Cleaning & Preprocessing – Excel Workflow (No Pandas)

==>  Overview
This project demonstrates how to clean a raw dataset using "Excel", without any Python dependencies. The goal was to transform a messy dataset into a consistent, analysis-ready format. Key tasks included handling missing values, deduplicating rows, standardizing date formats, fixing inconsistent naming, and renaming columns.

==> Files in This Repository
=>Data cleaning.xlsx: The cleaned version after applying all transformations.
=>README.md`: This documentation outlining the cleaning steps and summary of changes.

---

==> Data Cleaning Steps (Excel)

1. Fill Missing Values  
   - Replaced blank or empty cells with `"NA"` using Excel’s Find & Replace or formula (`=IF(cell="", "NA", cell)`).

2. Remove Duplicate Rows  
   - Used Data → Remove Duplicates to drop exact duplicate entries.

3. Standardize Text Values  
   - Cleaned inconsistent text data (e.g., names, Region values) using:
     - TRIM() to remove extra spaces  
     - UPPER() / PROPER() to unify casing  
     - FIND & REPLACE for manual corrections 

4. Convert Date Formats  
   - Selected date columns and set formats via "Format Cells"(ctr+1) → Date → DD-MM-YYYY.

5. Rename Column Headers  
   - Edited column names directly in the header row to be lowercase, space-free, and underscore-separated.

