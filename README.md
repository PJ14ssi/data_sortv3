# data_sortv3

This script was an attempt tp learn how to process data from CSV and Excel files using a tkinter-based grpahical user interface (GUI).

It allows you to select three inputs files: a "red" CSV file, a "green" CSV file and a "Excel" file. The script performs various data processing operations and saves the filtered data to a new Excel file. 


Prerequisites
- Python 3.x
- tkinter library
- pandas library
- openpyxsl library

Usage:
1. Install the required libraries: pip install pandas openpyxl
2. Run the script: python script.py
3. The tkinter GUI window. Use the provided buttons to select the input files:

- Select Green File
- Select Red File
- Select Paste File

4. After inputting all the files necessary in your directgory, click the "Run" button to start the data processing.
5. The script will load the relevant CSV and Excel files, extract releant dat to be pasted into an Excel file named "filtered_data.xlsx."
6. After the script completes, a success message will be shown as a pop-up window.
7. To exit the application, click the "Exit" button.

Debug:
To enable debug.. set the debug variable to True (debug = True)

Notes:
- Make sure you have the input files (.csv for both Red and Green, and .xlsx for your Blank/Paste template)
- Make sure your "paste.xlsx" sheet has a "PCred" on it. Modify accordingly if there's a different name.
- Make sure Python is installed before running a script.




