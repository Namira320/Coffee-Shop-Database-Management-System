# Coffee Shop Database Management System ☕

A comprehensive relational database system designed to manage multi-branch coffee shop operations, inventory, customer data, and transaction processing. Built and managed using MySQL.

---

## 📌 Project Overview
 
Effective data management is crucial for modern cafe businesses to enhance order accuracy, optimize inventory, and streamline multi-branch operations. This project implements a fully normalized relational database (`cafe_management_db`) equipped with advanced database features such as Views, Stored Procedures, Triggers, and Full-Text Search to support robust business intelligence and efficient daily operations.

---

## 🛠️ Database Architecture & Design

### Database Specifications (`cafe_management_db`)
* **Tables (10):** Profile Cafe, Cabang Cafe, Menus, Status Menu Cabang, Customers, Transactions, Details Transaction, Suppliers, Reservations, and Tables.
* **Views (5):**
  * `vw_menu_per_cabang`: Tracks available menus and pricing per branch.
  * `vw_customer_orders`: Comprehensive history of customer orders and reservations.
  * `vw_stock_per_menu`: Real-time inventory tracking across branches.
  * `vw_daily_sales`: Daily revenue aggregation per branch.
  * `vw_top_customers`: Identifies top loyal customers based on total spending.
* **Stored Procedures (3):** Handles automated transaction logging, stock replenishment, and dynamic menu price updates.
* **Triggers (4):** Ensures data integrity, stock validation, and automated rollback/cascade handling during order cancellations and deletions.
* **Full-Text Indexes (2):** Optimized search performance across menu items and customer contacts.

