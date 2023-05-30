# Excel---Vrinda-Store-Data-Analysis
This repository contains a dashboard created for the company Vrinda Stores' annual report for the year 2022. The objective of this project is to understand and analyze the sales performance of Vrinda Store's sales data from 2022 and provide an annual report to help improve the business in 2023.

# Objectives
To understand and analyze the sales performance of Vrinda Store's sales data from 2022.
To provide an annual report to help improve the business in 2023.
Things I Worked On
**Data Cleaning:**

Imported the CSV file into Excel and performed various activities such as removing duplicates, fixing typo errors, and transforming the data into a format that can be easily analyzed.

Step-by-Step Guide: Data Cleaning Process

Replace 'W' with 'Women' and 'M' with 'Men' in the Gender column:

Open the dataset or spreadsheet containing the data.
Locate the column labeled "Gender" (assuming it is column W).
Select the entire column W or the specific range of cells containing the gender data.
Use the "Find and Replace" function (usually found under the "Home" or "Editing" tab in Excel).
In the "Find" field, enter 'W' (without quotes).
In the "Replace" field, enter 'Women' (without quotes).
Click on the "Replace All" button to replace all occurrences of 'W' with 'Women'.
Repeat the same steps to replace 'M' with 'Men' in the Gender column.
Create an Age Group column:

Identify the column where you want to create the Age Group column (assuming it is column F).
Label the new column as "Age Group" or any suitable name.
In the first cell of the Age Group column (assuming it is F2), enter the following formula:
=IF(E2>50, "Senior", IF(E2>30, "Adult", "Youth"))
Copy the formula down to apply it to all the cells in the Age Group column, corresponding to each individual's age.
Create a Month column and extract month from the given date:

Determine the column where you want to create the Month column (assuming it is column H).
Label the new column as "Month" or any desired name.
In the first cell of the Month column (assuming it is H2), enter the following formula:
=TEXT(G2, "mmmm")
This formula extracts the month from the given date in column G and displays it in a full month name format.
Copy the formula down to apply it to all the cells in the Month column, corresponding to each date.
Replace 'One' with '1' and 'Two' with '2' in the Qty column:

Locate the column labeled "Qty" (assuming it is column C).
Select the entire column C or the specific range of cells containing the quantity data.
Use the "Find and Replace" function (usually found under the "Home" or "Editing" tab in Excel).
In the "Find" field, enter 'One' (without quotes).
In the "Replace" field, enter '1' (without quotes).
Click on the "Replace All" button to replace all occurrences of 'One' with '1'.
Repeat the same steps to replace 'Two' with '2' in the Qty column.
Insert a table:

Select the entire dataset or the range of cells containing the cleaned data.
Under the "Insert" tab in Excel, click on the "Table" option.
Excel will detect the range of cells automatically, make sure the "My table has headers" option is checked if your dataset has column headers.
Click on the "OK" button to insert the table.
Excel will convert the selected range into a formatted table, allowing for easier data manipulation and analysis.
Following these steps will help you perform the data cleaning process as described.

**Data Processing:**

Created an "Age group" column to categorize the "Age" column into "Senior" (>=50), "Adult" (>30), and "Teenagers" using the IF() function. The formula used was =IF(E2>=50,"senior",IF(E2>30,"adult","teeneger")).
Created a "Month" column to get the month-wise data using the function =TEXT(G2,"mmm").
Data Analysis using Pivot table:

Created a Clustered combo-Line chart to analyze Orders vs Sales for each month.
Created a Pie chart to analyze the shopping percentage of men and women.
Created a Bar chart to show the top 5 states with the highest sales.
Created a Pie Chart to understand the order status of the customers.
Created a Column Chart to know the age-wise purchasing pattern between men and women.
Created a Pie Chart to determine the percentage share of each distribution channel.

# Insights Drawn
Based on the analysis of the data, the following insights were drawn:

Women aged between 30-49 years are placing more orders from states like Maharashtra, Karnataka, Tamil Nadu, Uttar Pradesh, and Telangana.
Business Decisions
The following business decisions were made based on the insights:

Target women customers in the age group of 30-49 years living in the states of Maharashtra, Karnataka, and Uttar Pradesh.
Focus on advertising and offering discounts, coupons, and exclusive deals on platforms like Amazon, Flipkart, and Myntra.
Provide attractive discounts and exclusive deals to encourage both online and offline purchases.

# Additional Insights
Here are some additional insights from the sales report:

The month of March had the highest number of sales and orders.
Women made more purchases compared to men in 2022.
The different order statuses in 2022 include Delivered, Refunded, Cancelled, and Returned.
The top 5 states contributing to sales are Maharashtra, Karnataka, Telangana, Tamil Nadu, and Kerala.
Women adults above the age of 30 made the highest number of orders.
The channel contributing the highest sales is Amazon, followed by Flipkart.
Final Conclusions to Improve Vrinda Store Sales
To improve Vrinda Store's sales, the following recommendations are provided:

Target women customers in the age group of 30-49 years living in the states of Maharashtra, Karnataka, and Uttar Pradesh by showing ads/offers/coupons available on platforms like Amazon and Flipkart.
