# Data-Transformation-10

# Objective : 

Your objective in this exercise was to prepare a worksheet for analysis by completing the following tasks:

⦁ Address instances of missing values.

⦁ Clean columns by changing data types as required.

⦁ Replace values where required.

⦁ Address inconsistencies in data.

⦁ Dropping records with errors.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Steps Involved

# 1. Load the Workbook

     Import the SalesFile.xlsx dataset using Power BI's Get Data feature.

             ⦁ Home > Data > Get Data > Select SalesFile.xlsx

# 2. Open Power Query Editor

     Open the Power Query Editor to begin editing the data.

             ⦁ Home > Queries > Transform Data
              
# 3. Address Missing Values

     Replace all null values in the Units Sold, Sale Price, Sales, and Profit columns with 0.

            ⦁ Select the column.
            ⦁ Transform > Replace Values.
            ⦁ Replace null with 0.
             
# 4. Clean Manufacturing Price and Sale Price Columns

     Change the data type of Manufacturing Price and Sale Price to Decimal Number.

            ⦁ Select the column header.
            ⦁ Change the data type to Decimal Number.
              
# 5. Clean Discount Band Column

      Replace instances of the value 1 with None and change the data type to Text.

             ⦁ Replace Values: 1 → None.
             ⦁ Change the data type to Text.
              
# 6. Clean Units Sold Column

      Replace the text value "six hundred" with the numeric value 600 and change the column’s data type to Whole Number.

             ⦁ Replace Values: six hundred → 600.
             ⦁ Change data type to Whole Number.
              
# 7. Address Date Column Inconsistencies

      Replace empty values in the Date column with a default date of 03 March 2023, and change the data type to Date.

             ⦁ Replace Values: Empty → 03/03/2023. (or any current date of your system)
             ⦁ Change data type to Date.

# 8. Drop Records with Errors
      
      Remove rows with errors in the Manufacturing Price, Sales, and Profit columns.

             ⦁ Select the column.
             ⦁ Remove Rows > Remove Errors.

# 9. Remove Duplicate Rows
      
      Remove duplicate rows from the dataset.

             ⦁ Home > Remove Rows > Remove Duplicates.
              
# 10. Apply the Data Transformations

      After cleaning, click Close & Apply to apply all transformations to the dataset.

# Conclusion

In this exercise, we applied various data cleaning and transformation techniques in Power Query Editor to prepare the dataset for analysis. The transformations included replacing missing values, correcting data types, handling inconsistent entries, removing duplicates, and eliminating erroneous rows.
