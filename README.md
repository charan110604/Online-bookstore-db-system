📚 Online Bookstore Database System

A fully designed relational database system for managing an online bookstore. This project demonstrates real-world database concepts like normalization, relationships, transactions, triggers, and automation.

📌 Project Overview

The system is designed to efficiently manage:

📖 Books & Inventory
👤 Users (Customers)
🧑‍💼 Authors & Publishers
🛒 Orders & Order Items
💳 Payments
⭐ Reviews

📄 Supporting Documents:

SQL Queries →
Project Design PPT →
Abstract →
🧱 Database Schema

The database follows 3rd Normal Form (3NF) ensuring:

✔ Data consistency
✔ Reduced redundancy
✔ Efficient querying

🗂️ Tables
Users
Books
Authors
Publishers
Genres
Orders
Order_Items
Payments
Reviews
🔗 Relationships
One user → many orders
One order → many books
One book → one author, genre, publisher
One order → one payment
Users → reviews on books
⚙️ Features
🛍️ Core Features
Browse and search books
Place and manage orders
Track order status
Manage inventory
Add reviews and ratings
📊 Advanced SQL
Complex joins
Aggregations
Revenue analysis
Customer insights
Best-selling books
🔄 Automation & Logic
⚡ Triggers
Auto-update stock
Prevent negative inventory
Update order totals
🔁 Stored Procedures
Block orders for pending payments (>30 days)
🧾 Views
Customer summary
Revenue per category
⏰ Events
Daily stock alerts
Monthly sales reports
🧪 Sample Queries
-- Top 5 best-selling books
SELECT b.title, SUM(oi.quantity * oi.price) AS revenue
FROM Order_Items oi
JOIN Books b ON oi.book_id = b.book_id
GROUP BY b.title
ORDER BY revenue DESC
LIMIT 5;

More queries → sql_queries_with_questions.pdf

🛠️ Tech Stack
Database: MySQL
Language: SQL
Tools: MySQL Workbench, dbdiagram.io
🚀 Getting Started
1️⃣ Clone Repo
git clone https://github.com/charan110604/Library-management-Database.git
cd Library-management-Database
2️⃣ Setup Database
CREATE DATABASE bookstore_db;
USE bookstore_db;
3️⃣ Import SQL File

Run:

OnlineBookstoreDB.sql
📈 Workflow
User Registration/Login
Browse Books
Place Order
Payment
Delivery
Reports & Analytics
🎯 Highlights

✔ Real-world database design
✔ Covers OLTP + analytics
✔ Includes triggers, views, events
✔ Interview-ready project

🔮 Future Improvements
🔗 Spring Boot backend integration
⚛️ React frontend
🤖 Recommendation system
📊 Advanced analytics dashboard
👨‍💻 Author

Charan Pathakota
📘 Full Stack Engineering
