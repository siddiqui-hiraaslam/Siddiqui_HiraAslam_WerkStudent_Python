README for WerkStudent Python Project - Siddiqui_Hira Aslam
**Overview**

This project automates the process of extracting data from invoices, compiling it into a structured Excel file, and generating a corresponding CSV file. The script specifically handles data extraction from PDF invoices, creation of an Excel file with detailed data and a pivot table, and a CSV file formatted with a semicolon as the separator. This repository supports the coding tasks required for a WerkStudent position in Python programming.

**System Requirements**

•	Python installed 

**How It Works**
**Data Extraction**

The script reads PDF files containing sample invoices and extracts specific monetary values and dates.
Excel and CSV File Creation

After running the executable file "main.exe", the script generates the following files:
•	Excel File: "invoices_with_pivot_table.xlsx"
  o	Sheet 1: Data - Lists the file names of the invoices, the dates extracted from each invoice, and the monetary values.
  o	Sheet 2: Pivot Table - Organizes and sums up the values by date and document name, providing a detailed overview of the financial data.
•	CSV File: "invoices.csv"
  o	Contains all the extracted data formatted with semicolons (;) as separators to ensure compatibility with common spreadsheet applications.
  
**Installation and Running the Code**

**Installation of Dependencies**

If you encounter library errors after running the "main.exe" file, please install the dependencies with the following command in the terminal:

pip install -r requirements.txt

**Location of Invoices**

Ensure that all sample invoice PDFs are placed in the same folder as the executable file "main.exe".

**Execution**

Run the executable file "main.exe". This will execute the script, and you will see the generated Excel and CSV files in the same folder.
Opening and Viewing Files

To access and review the contents of the Excel and CSV files:
  1.	Excel File:
    o	Navigate to the location where the script outputted the file "invoices_with_pivot_table.xlsx".
    o	Open the file with Microsoft Excel or a compatible spreadsheet viewer.
    o	Check the two sheets: "Data" for the extracted values and "Pivot Table" for summarized data.
  2.	CSV File:
    o	Open Excel, go to the "Data" tab.
    o	Choose "Get Data" > "From Text/CSV."
    o	Select the "invoices.csv" file you generated and ensure that the delimiter is set to a semicolon (;).
    o	Load the data to see it formatted correctly.

**Important Note Regarding Invoice Files**

Task Requirements Discrepancy: The task requirements specify that data should be extracted from three invoices, but only two have been provided.  If the third invoice is missing, please contact me so I can update the code accordingly.

