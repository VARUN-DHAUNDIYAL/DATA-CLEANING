Cleaning Data in SQL
This project involves cleaning and preprocessing real estate data from Nashville using SQL. The script applies various data cleaning techniques to improve data quality and prepare it for analysis.

Key Cleaning Steps:
Standardizing Date Format – Converts the SaleDate column into a standardized Date format.
Populating Missing Property Addresses – Fills missing PropertyAddress values using available data for matching ParcelIDs.
Splitting Address into Components – Extracts Street Address, City, and State from PropertyAddress and OwnerAddress.
Normalizing Categorical Data – Converts SoldAsVacant values from 'Y'/'N' to 'Yes'/'No' for better readability.
Removing Duplicates – Uses a Common Table Expression (CTE) to identify and remove duplicate records based on key attributes.
Dropping Unnecessary Columns – Removes columns like OwnerAddress, TaxDistrict, PropertyAddress, and SaleDate to optimize the dataset.
Bulk Data Import (Optional) – Provides SQL scripts for importing data using OPENROWSET and BULK INSERT.
Usage:
Run each section of the script in sequence to clean and prepare the dataset for further analysis.
