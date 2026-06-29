


# Sales Management System

## Business Problem

Many businesses struggle to efficiently manage sales transactions, customer information, and product inventory using manual processes. This project develops a relational database that stores and analyzes sales data using SQL. By applying Common Table Expressions (CTEs) and SQL Window Functions, the system provides meaningful insights to support business decision-making.



## Database Schema

The Sales Management System consists of three related tables:

* **Customers** – Stores customer information.
* **Products** – Stores product details such as name, category, price, and stock.
* **Sales** – Records each sales transaction, including the customer, product, quantity sold, sale date, and total amount.

### Relationships

* One customer can make many purchases.
* One product can appear in many sales transactions.
* Each sale is linked to one customer and one product through foreign keys.



## ER Diagram

The ER Diagram illustrates the relationships between the Customers, Products, and Sales tables.





## CTE Implementations

This project demonstrates the following Common Table Expressions (CTEs):

### Simple CTE

Displays sales records in a simplified and readable format.

### Multiple CTEs

Combines customer and product sales information to generate business reports.

### Recursive CTE

Demonstrates recursive SQL logic by generating sequential values.

### Aggregation CTE

Calculates total sales, revenue, and quantities sold.

### CTE with JOIN

Joins Customers, Products, and Sales tables to create comprehensive sales reports.

Each implementation includes:

* SQL query
* Screenshot of the output
* Business value explanation



## Window Function Implementations

The project demonstrates the following SQL Window Functions:

### Ranking Functions

* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* PERCENT_RANK()

These functions rank products or customers according to sales performance.

### Aggregate Window Functions

* SUM() OVER()
* AVG() OVER()
* MIN() OVER()
* MAX() OVER()

These functions calculate cumulative and comparative sales statistics.

### Navigation Functions

* LAG()
* LEAD()

These functions compare current sales with previous and next sales records.

### Distribution Functions

* NTILE()
* CUME_DIST()

These functions divide sales into groups and analyze data distribution.



# Analysis and Findings

## Descriptive Analysis (What happened?)

The analysis shows that some products generated significantly higher sales than others. Certain customers made multiple purchases, contributing more to total revenue. Window functions also revealed product rankings based on sales performance and cumulative revenue trends over time.

## Diagnostic Analysis (Why did it happen?)

High-performing products likely achieved better sales because of customer demand, competitive pricing, or popularity. Customers who made repeated purchases contributed a larger share of the company's revenue, while lower-selling products may have experienced limited demand or weaker marketing.

## Prescriptive Analysis (What actions should be taken?)

The business should increase inventory for high-selling products, review pricing and promotional strategies for low-performing products, reward loyal customers through loyalty programs, and regularly monitor sales performance using SQL analytical reports to improve decision-making.



## References

* Microsoft SQL Server Documentation
* PostgreSQL Documentation
* MySQL Documentation
* W3Schools SQL Tutorial
* UNILAK Database Programming Course Materials



## Academic Integrity Statement

I declare that this assignment is my own original work. All database design, SQL scripts, analyses, and documentation were completed independently in accordance with the academic integrity policy of the University of Lay Adventists of Kigali (UNILAK).

