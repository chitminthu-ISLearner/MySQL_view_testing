This project demonstrates my ability to design and implement database views in MySQL for an eCommerce system. The schema models a realistic business scenario with Customers, Products, Orders, and Order Items, and the assignment focuses on creating views to simplify queries, enforce security, and support analytics.

--Key Highlights
Database Setup: Designed normalized tables for customers, products, orders, and order items with proper primary and foreign keys.

Sample Data: Inserted realistic records to simulate transactions across multiple customers and product categories.

Views Created:

Customer information view (hiding sensitive fields like email).

Completed and pending orders views.

Join views combining customer and product details.

Aggregated views for total sales per order and monthly sales reports.

Security-focused views (e.g., hiding product prices).

Analytical views such as high-value orders, purchase summaries, and top 3 expensive products.

--Advanced Features:

Implemented WITH CHECK OPTION to restrict updates to completed orders.

Tested updatable views and invalid updates to understand constraints.

Used ALGORITHM = TEMPTABLE for performance testing.

Practiced view management commands (showing, defining, and dropping views).

--Learning Outcomes
Strengthened understanding of SQL Views as a tool for abstraction, security, and reporting.

Gained practical experience in JOINs, aggregations, and constraints.

Explored how views can support business intelligence in eCommerce systems.

Practiced real-world scenarios like hiding sensitive data, summarizing sales, and enforcing business rules.
