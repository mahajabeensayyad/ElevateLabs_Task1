# **Task 1 : Retail Store Sales Data**

## **👨‍💻Dataset Overview:**

Retail Store Sales Dataset representing sales transactions from a retail store. Customer_ID and Transaction_ID are the Unique field columns in the dataset. This data has several uncleaned and missing data like:

• Column Headers are not in inconsistent format

• Few columns have missing data in it like columns Category_Item, Price_Per_Unit, Quantity, Total_spent and Discount_Applied

• Data formatting is not consistent for value columns like Price_per_item and Total_Spent

• There are few columns where we need to do some deducing to get the data like columns Category_Item, Price_per_Unit, Quantity and Total_Spent

## **🛠️Tools Used:**
• Advanced MS Excel and Pivot

## **📚Cleaning Steps Followed:**

### **Header Standardization and Data Formatting:**

• Used ‘Proper’ function formula to standardize the header (=Proper (Cell ref))

• Header alignment to Centre, Bold Font and Header Colour.

• Increased the font size to differentiate the header from other rows.

• Changed column header names for “Category” to “Product_Category” and “Item” to “Category_Item” for better understanding.

• Columns Price_per_Unit and Total_Spent changed to Number format with 2 decimals. All text columns into Text format and Data column to Date format (dd-mm-yyyy).

### **Handling Missing Values:**

• Total Spent = Quantity * Price per Unit

• Price per Unit = Total spent \Quantity

• Where Quantity and Total Spent values are missing = 0

• Column “Discount Applied” for blank cells = None

• Each “Product_Category” has 25 “Category_Items” and each “Category_Item” has price per Unit as same. By deducting we can find out the missing values for columns Item, Price Per Unit, Quantity and Total spent.
Example: For ‘Beverage’, ‘Item_1_BEV’ has unit price as ‘5’. In order to fill the missing “Category Item” column, sorted the data by “Product Category” first then “Price per Item” and then “Category Item” and used Ctrl+D from visible blanks to fill the missing details.

