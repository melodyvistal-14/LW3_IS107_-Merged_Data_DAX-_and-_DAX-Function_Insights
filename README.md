# LW3_IS107_-Merged_Data_DAX-_and-_DAX-Function_Insights


Google Slide : https://docs.google.com/presentation/d/1JcQWsLQPycuKXqBcMYpu9b3JUS5_GJa78fTqXx-pU9A/edit?usp=sharing


Part 1:

Guide Questions

1. Is the dataset in flat-table format?
   - Yes, the dataset is in a flat-table format because each row represents a single sales record and each column contains one type of information.
2. Which columns describe customers?
     - The columns that describe customers are CustomerName and Region.
3. Which columns represent transactions?
     - The columns that represent transactions are OrderID, OrderDate, Product, Quantity, and SalesAmount.


PART 2

1. Why must dimension tables contain unique keys?
   - Dimension tables must contain unique keys so each record can be identified distinctly
2. What problems occur if duplicates exist in DimCustomer?
   - If duplicates exist in DimCustomer, aggregations and relationships can produce incorrect results.

PART 3

Guide Questions
1. What is a primary key?
   - A primary key is a column that uniquely identifies each record in a table.
2. Why is CustomerID a foreign key in FactSales?
   - CustomerID is a foreign key in FactSales to link each sale to a specific customer.

PART 4

1. Why should relationships flow from dimension to fact?
   - Relationships should flow from dimension to fact to ensure proper filtering and aggregation.
2. What happens if the relationship is Many-to-Many?
   - If relationships were missing, totals would not match customers correctly.

PART 5

1. Did sales aggregate correctly per customer?
   - Yes, if relationships are properly set, Power BI will automatically group and sum the SalesAmount per CustomerName.
2. What would happen if relationships were missing?
   - If relationships were missing, totals would not match customers correctly.


Introduction to DAX

1. What is a DAX measure?
   - A DAX measure is a calculation evaluated dynamically in visuals.
2. Difference between SUM and AVERAGE?
   - SUM adds values together, while AVERAGE calculates their mean.
3. Why use measures instead of calculated columns?
   - Measures are preferred over calculated columns because they are dynamic and use less memory.

DAX Function

1. What is time intelligence in DAX?
   - Time intelligence in DAX allows calculations based on dates, like YTD, MTD, or comparisons over periods.
2. Why is a date table required?
   - A date table is required to properly perform time-based calculations.
5. How does PREVIOUSMONTH help analyze trends?
   - PREVIOUSMONTH helps analyze trends by comparing values to the prior month.
7. What insights can YTD Sales provide?
    - YTD Sales provides insight into total sales accumulated since the start of the year.
