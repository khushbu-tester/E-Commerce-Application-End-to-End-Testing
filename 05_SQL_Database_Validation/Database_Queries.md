# SQL Database Validation - E-Commerce Data Integrity

Testing the backend database ensures that every action on the UI (like placing an order) is correctly recorded in the system.

### 1. Order Confirmation Check
**Scenario:** To verify if a new order is correctly saved in the 'orders' table.
```sql
SELECT order_id, customer_name, total_amount, status 
FROM orders 
WHERE customer_email = 'testuser@example.com' 
ORDER BY order_date DESC LIMIT 1;

### 2. Stock Inventory Validation (JOINS)
**Scenario:** To identify products that are marked as 'In Stock' on UI but have 0 quantity in the database.
```sql
SELECT p.product_name, i.stock_count 
FROM products p 
JOIN inventory i ON p.product_id = i.product_id 
WHERE i.stock_count <= 0;
Duplicate Account Prevention
Scenario: To ensure the system doesn't allow two users with the same email.
SQL
SELECT email, COUNT(email) 
FROM users 
GROUP BY email 
HAVING COUNT(email) > 1;
