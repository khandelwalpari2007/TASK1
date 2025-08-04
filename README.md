# TASK1
# Sales Data Cleaning and Analysis
This dataset contains weekly sales data for a variety of health and wellness supplements from January 2020 to April 2025. The data includes products in categories like Protein, Vitamins, Omega, and Amino Acids, among others, and covers multiple e-commerce platforms such as Amazon, Walmart, and iHerb. The dataset also tracks sales in several locations including the USA, UK, and Canada.


## Files Included

- `cleaned_sales_data.xlsx`: Final cleaned version of the dataset.
- Supplement_Sales_Weekly_Expanded.csv
- `data/`: Folder for structured uploads by month or category.

---

##  Data Columns

| Column Name      | Description                                              |
|------------------|----------------------------------------------------------|
| Date             | Date of sale in `DD-MM-YYYY` format                      |
| Product Name     | Name of the product sold                                 |
| Category         | Product category (e.g., Protein, Vitamin, Omega)         |
| Units Sold       | Number of units sold                                     |
| Price (INR)      | Price per unit, formatted in INR                         |
| Revenue (INR)    | Total revenue                                            |
| Discount (%)     | Discount as a decimal (e.g., `0.03` = 3%)                |
| Units Returned   | Number of returned units                                 |
| Location         | Sale location (e.g., USA, UK, Canada)                    |
| Platform         | Platform of sale (e.g., Offline, Online, Instagram)      |



#  Cleaning Steps Performed
- Converted all dates to a consistent `DD-MM-YYYY` format
- Standardized INR currency formatting for price and revenue
- Ensured all numerical columns are correctly typed
- Reformatted discount as decimals (e.g., `0.03` = 3%)
- Removed duplicate entries (if any)
- Checked for missing values and handled them appropriately
- Unified category names and corrected spelling inconsistencies



# Tools Used
- Microsoft Excel
  
