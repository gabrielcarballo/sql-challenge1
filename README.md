# SQL Challenges Project

## Project Overview

This project consists of a series of SQL challenges of varying complexity levels, each to be solved in its own file. The main goal is to enhance SQL skills by solving real-world data querying scenarios.

## Development
### Technologies
 - SQL

## Project Structure
The project is structured around multiple SQL files, each serving a specific function:
desafioN.sql: Each file contains the SQL code for the corresponding challenge, where N is the challenge number.

## Project Requirements

<details>
<summary>Challenge List</summary>

1. Display only the names of the products in the products table.
2. Display the data from all columns in the products table.
3. Write a query that displays the values of the column that represents the primary key of the products table.
4. Count how many records exist in the product_name column of the products table.
5. Construct a query that displays the data from the products table starting from the fourth record up to the thirteenth.
6. Display the data from the product_name and id columns of the products table in such a way that the results are in alphabetical order of the names.
7. Show only the ids of the last 5 records of the products table (the ordering should be based on the id column).
8. Make a query that returns three columns, respectively, with the names 'A', 'Trybe' and 'eh', and with values referring to the sum of '5 + 6', the string 'de', the sum of '2 + 8'.
9. Show all values of notes from the purchase_orders table that are not null.
10. Show all data from the purchase_orders table in descending order, sorted by created_by where created_by is greater than or equal to 3. Also sort the results by id in ascending order, as a tie-breaker for the ordering.
11. Display the data from the notes column of the purchase_orders table where its Purchase generated based on Order value is greater than or equal to 30 and less than or equal to 39.
12. Show the submitted_date of purchase_orders where the submitted_date is April 26, 2006.
13. Show the supplier_id of the purchase_orders where the supplier_id is 1 or 3.
14. Show the results of the supplier_id column of the purchase_orders table where the supplier_id is greater than or equal to 1 and less than or equal to 3.
15. Show only the hours (without the minutes and seconds) of the submitted_date column of all records in the purchase_orders table. In the result, the hour extracted from the submitted_date column should be called submitted_hour.
16. Display the submitted_date of the purchase_orders that are between 2006-01-26 00:00:00 and 2006-03-31 23:59:59.
17. Show the records of the id and supplier_id columns of the purchase_orders where the supplier_ids are either 1, or 3, or 5, or 7.
18. Show all records of purchase_orders that have supplier_id equal to 3 and status_id equal to 2.
19. Show the number of orders that were made in the orders table by the employee_id equal to 5 or 6, and that were sent through the method (column) shipper_id equal to 2. In the result, the column that contains the count of orders should be called orders_count.
20. Add to the order_details table a record with order_id: 69, product_id: 80, quantity: 15.0000, unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL and inventory_id: 129.
21. Add with a single INSERT, two rows to the order_details table with the same data as requirement 20.
22. Update all data in the discount column, in the order_details table, to 15.
23. Update the data in the discount column of the order_details table to 30, where the value in the unit_price column is less than 10.0000.
24. Update the data in the discount column of the order_details table to 45, where the value in the unit_price column is greater than 10.0000 and the id is a number between 30 and 40.
25. Delete all data where the unit_price of the order_details table is less than 10.0000.
26. Delete all data where the unit_price of the order_details table is greater than 10.0000.
27. Delete all data from the order_details table.

</details>

- **SQL Queries**: Creation of SQL queries to find the expected information for each challenge.
- **File Structure**: Each challenge is solved in its own file, named desafioN.sql, where N is the challenge number.
- **Code Annotations**
Each SQL file contains a single SQL query that solves the corresponding challenge. For example, the file desafio1.sql might contain a query like this:
```sql
SELECT product_name FROM products;
```
This query selects the names of all products from the products table.

## Feedback
Your feedback is invaluable! Please share your thoughts and suggestions regarding the project. I am eager to incorporate any insights you may have.

## Portfolio
Check out my [portfolio](my-folio-weld.vercel.app/) for more of my work!