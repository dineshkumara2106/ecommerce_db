# Ecommerce Database

This project contains a basic SQL schema for an Ecommerce system. It includes tables to manage customers, products, orders, and payments.

## Tables Included

- **Customers**: Stores customer details like name, phone number, email, and address.
- **Products**: Stores product information such as name, price, and available stock.
- **Orders**: Records orders placed by customers, including product, quantity, and order date.
- **Payments** *(optional)*: Tracks payment details for each order, including payment method and status.

## SQL Features Used

- `PRIMARY KEY`, `FOREIGN KEY` relationships
- `AUTO_INCREMENT` for unique IDs
- Data types like `VARCHAR`, `DECIMAL`, `DATE`
- Constraints like `NOT NULL`, `CHECK`, and `UNIQUE`

## How to Use

1. Import the SQL schema into your database (e.g., MySQL).
2. Add data using `INSERT` queries.
3. Run `SELECT` queries to retrieve customer orders, product lists, etc.

## Example Query

```sql
SELECT * FROM orders WHERE Customer_id = 1;
