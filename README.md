Excel File Processing and Analysis

This project involves processing and analyzing Excel files in a directory.
The script compares new files with older ones and updates the new files accordingly.
The updated files are saved in a new directory with a timestamp.
The name of each updated file is printed out at the end.
Project Files
•	excel_processing.py: This is the main Python script that processes the Excel files.

Project Summary

The script performs the following tasks:
1.	Creates a new directory for the processed files.
2.	Sorts the files by size (smallest to largest).
3.	Compares the old and new filenames.
4.	Loads the Excel file and converts specific columns back to numerical type.
5.	Writes the original data to the new file.
6.	Splits the data based on the conditions and writes to new sheets.
7.	Loads the older Excel file and converts specific columns back to numerical type.
8.	Creates a DataFrame with ‘Account Number’ values from the old file that meet the conditions.
9.	Creates new sheets if the criteria are met.
10.	Adds additional rows to the ‘DPD 15_60’, ‘DPD 61_90’, and ‘Delisted’ DataFrames if they’re not empty.
11.	Prints out the name of the updated file.
