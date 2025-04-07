# kylelnfo-data-analysis


KyleInfo Customer Service manages the customer service of a well-known e-commerce site. Rising complaints have become very concerning for e-commerce so they asked KyleInfo to do a Pareto analysis and find priority concerns that they can work on to reduce customer complaints.

The goal is to analyze the available data, focusing on key product categories, and key complaint drivers, and provide actionable recommendations to optimize operations and improve customer experience.

Download this CSV file and analyze the data to provide recommendations.

https://raw.githubusercontent.com/Invact-Abhay/DOE/refs/heads/main/ComplaintsTable.csv

Set Up Colab environment for Python

Import Pandas and matplotlib.pyplot libraries

Read the CSV file and create a data frame named Kyleinfo

Task 1

Show the top 5 rows of data frame ‘Kyleinfo’

Task 2

Create a table to show the total number of complaints for each product category as shown in the screenshot below. 

Assign the result to a variable named: total_complaints

Task 3

Sort the above table in descending order.

Assign the result to a variable named: sorted_complaints

Task 4

Calculate the cumulative sum of complaints from the above sorted_complaints table

Assign the result to a variable named: cumulative_sum

Task 5

Calculate the percentage of complaint count of  each product out of the total complaint counts  from the above cumulative_sum table

Assign the result to a variable named:  cumulative_percentage.

Task 6

Plot the bar chart for individual product categories from cumulative_percentage DataFrame then plot a line chart for cumulative percentage on a secondary y-axis

Task 7

Filter the top 4 products category (in terms of complaints count) from df DataFrame and Assign the result to a variable named:  Top4

Task 8

Create a table to find the complaints count table by complaints reason from Top4 DataFrame, Sort the table in descending order.

Assign it to a variable named sorted_returns1.

Task 9

Calculate the cumulative percentage from the sorted_returns1 DataFrame.

Assign it to a variable named: cumulative_reason_percentage.

Task 10

Plot the bar chart for individual complaint reason

Plot cumulative percentage on a secondary y-axis and 

Display the plot
