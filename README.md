# Personal Finance Analysis Dashboard
A project that utilizes Microsoft PowerBI to analyze personal financial data and visualize expenses through an interactive dashboard.
# Problem Description
dataset contains detailed financial and demographic data, focusing on income, expenses, and potential savings across various categories. The data aims to provide insights into personal financial management and spending patterns.

# Project Goals
Here are the questions I would like the PowerBI dashboards to answer:

Monthly spending (in a given year).
How much money spent per item category.
List all expenses with comments.
How much money spent per location.
The number of purchases in various price ranges.
Quarterly and weekly spending information.
Various average costs (per week, month, day).
Comparison of food costs to restaurant costs.
Spending behavior when I'm sick.
Comparison of weekday and weekend spending.

# Data Analysis Summary
![executive_summary](https://github.com/user-attachments/assets/c50c31c3-f89e-4b5a-a3da-10802333a046)

![granular_info](https://github.com/user-attachments/assets/167f67dd-4683-43f6-8d6b-69d182210bdc)

# Hardware and Software Used

1. Python (v3.8)
2. Python Libraries: openpyxl, os
3. Windows 10 Machine
4. Microsoft PowerBI Desktop (v2.93)
5. Microsoft Excel

# Data Collection Methodology
I collected this data by keeping all purchase receipts and inputting the data manually into Excel. The information I kept track of was: Date, Item Category, Price, Location, Comment.

In order to import this data into PowerBI, it was quite the process. Since the data was contained in multiple Excel sheets in the same Excel workbook, I first had to separate the sheets into their own Excel workbook - this turned out to be the easiest avenue to importing the data.

# Data Cleaning
There was quite a bit of data cleaning to do. I had to do some basic editing of the 'Item' category column, in order to have consistent categories. For example, I had 'hair cut', 'Hair cut', 'Hair-Cut' as separate categores, and so had to standardize this into simply a 'Hair Cut' category.

There was a lot of work needed to be done with dates. Some dates were of a 'Text' type, some were a 'General' type, and still others were the 'Date' type. These had to be standardized.

Finally, only a few rows contained null entries, so I simply chose to remove these rows from the overall dataset; This would not drastically affect the variance of the overall data.

# Conclusion
Using PowerBI I was able to visualize my purchases data in an interactive way. This allowed me to drill deeper into my spending behaviour and with this information I can now be more conscientious of what I choose to spend my money on.




