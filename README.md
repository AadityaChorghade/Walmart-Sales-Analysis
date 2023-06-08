# Walmart-Sales-Analysis

Description:

This code performs a comprehensive analysis of Walmart sales data using Python and various libraries. It aims to gain insights into sales patterns, trends, shipping efficiency, product performance, and customer behavior.

The code begins by importing the necessary libraries, including pandas and matplotlib, followed by loading the Walmart sales data from an Excel file. Descriptive statistics are then calculated for the sales, quantity, and profit variables using the describe() function and printed to the console.

Next, box and whisker plots are created for the sales, quantity, and profit variables using the boxplot() function from matplotlib. Each boxplot visualizes the distribution of the corresponding variable, displaying the quartiles, median, and outliers.

The code then focuses on trend analysis by extracting the month from the 'Order_Date' column and grouping the data by month to count the number of orders placed each month. A line chart is plotted to visualize the month-over-month trend in the number of orders, providing insights into the impact of events like Thanksgiving and Black Friday on sales.

Shipping efficiency is analyzed by calculating the average time taken to ship an order. The code creates a new column for the order month, groups the data by month, and calculates the mean shipping time for each month. A line chart is plotted to visualize the average ship time month over month, enabling the identification of any variations or trends in the company's shipping process.

Product analysis is conducted by grouping the data by category and product name to determine the number of orders for each category and the top 20 most ordered products. Bar charts are plotted to visualize the distribution of orders across different categories and highlight the most popular products.

Customer analysis is performed by grouping the data by customer name and aggregating the number of orders, total sales, and total profits for each customer. The code identifies the top 10 customers by number of orders, sales, and profits and plots bar charts to visualize their contributions to the business.

This code provides valuable insights into sales patterns, trends, shipping efficiency, product performance, and customer behavior. The visualizations aid in understanding the data and making data-driven decisions to improve business strategies, customer satisfaction, and overall performance
