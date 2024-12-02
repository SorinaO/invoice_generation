Python Script to Generate PDF Invoices from Excel Data

This Python script automates the process of generating professional-looking PDF invoices from Excel spreadsheets. It leverages the fpdf library to create custom PDF documents and pandas to read and process Excel data.

Key Features:

Reads Excel Data: Reads data from Excel spreadsheets using pandas.
Generates PDF Invoices: Creates PDF invoices with a clear and organized layout.
Customizable Formatting: Allows for customization of font styles, sizes, and colors.
Dynamic Content: Populates the PDF with data from the Excel spreadsheet, including product information, quantities, prices, and totals.
Professional Appearance: Includes a header with invoice number and date, a table for product details, and a total amount.
Error Handling: Incorporates error handling to gracefully handle potential issues.
How to Use:

Install Required Libraries: Ensure you have fpdf and pandas installed in your Python environment.
Prepare Excel Data: Create Excel files with the following columns: product_id, product_name, amount_purchased, price_per_unit, and total_price.
Run the Script: Execute the Python script. It will process each Excel file in the specified directory and generate a corresponding PDF invoice.
Customization:

Modify the font styles, sizes, and colors to match your preferences.
Adjust the table layout and column widths to fit your specific needs.
Add more fields or sections to the invoice as required.
Implement error handling to gracefully handle exceptions.
By leveraging this script, you can streamline your invoice generation process and create professional-looking documents efficiently.