📚 Online Bookstore Database System

A fully designed and implemented relational database system for managing an online bookstore. This project demonstrates real-world database design principles including normalization, relationships, transactions, triggers, and automation.

📌 Project Overview

The Online Bookstore Database is built to efficiently manage:

📖 Books & Inventory
👤 Users (Customers)
🧑‍💼 Authors & Publishers
🛒 Orders & Order Items
💳 Payments
⭐ Reviews & Ratings

It provides a strong foundation for scalable e-commerce systems with optimized data handling and reporting capabilities.

📄 Detailed documentation:

SQL Queries & Use Cases →
Full Design Presentation →
Project Abstract →
🧱 Database Architecture

The system follows a normalized relational schema ensuring:

Data consistency
Minimal redundancy
High performance
🗂️ Key Entities
Users – Customer details
Books – Book catalog & stock
Authors / Publishers / Genres – Metadata
Orders – Customer purchases
Order_Items – Many-to-many relationship
Payments – Transaction tracking
Reviews – User feedback
🔗 Entity Relationships
One user ➝ many orders
One order ➝ many books (via Order_Items)
One book ➝ one author, genre, publisher
One order ➝ one payment
Users ➝ reviews on books
⚙️ Features
🛍️ Core Functionalities
Browse books by title, author, genre
Place and manage orders
Track order status (Pending → Shipped → Delivered)
Manage inventory in real-time
Store and retrieve user reviews
📊 Advanced SQL Capabilities
Complex joins & aggregations
Sales analytics & reporting
Revenue calculation per category
Customer spending insights
Best-selling books detection

(Example queries available in )

🔄 Automation & Database Logic

This project includes advanced database features:

⚡ Triggers
Auto-update stock after order placement
Prevent negative inventory
Maintain accurate order totals
🔁 Stored Procedures
Restrict orders if previous payments are pending (>30 days)
🧾 Views
Customer order summary
Category-wise revenue
⏰ Events
Daily low-stock alerts
Monthly sales summary generation
🧪 Sample Business Queries
📌 Top 5 best-selling books
📌 Customers with highest spending
📌 Books with low stock
📌 Monthly sales trends
📌 Authors with highest sales
🛠️ Tech Stack
Database: MySQL
Language: SQL
Tools: MySQL Workbench / DBDiagram
Concepts Used:
Normalization (3NF)
Joins & Subqueries
Indexing
Constraints
Transactions
Triggers & Events
🚀 Getting Started
1️⃣ Clone Repository
git clone https://github.com/your-username/online-bookstore-db.git
cd online-bookstore-db
2️⃣ Setup Database
CREATE DATABASE bookstore_db;
USE bookstore_db;
3️⃣ Run SQL Script

Import:

OnlineBookstoreDB.sql
4️⃣ Execute Queries

Run queries from:

sql_queries_with_questions.pdf
📈 Workflow

As shown in your documentation (page 4):

User Registration/Login
Browse/Search Books
Place Order
Payment Processing
Order Fulfillment
Reporting & Analytics
🎯 Key Highlights

✔ Fully normalized database design
✔ Real-world e-commerce use case
✔ Advanced SQL (Triggers, Views, Events)
✔ Scalable and modular structure
✔ Covers both OLTP + analytical queries

📊 Benefits
📦 Efficient inventory management
💡 Data-driven insights
⚡ Automated operations
😊 Improved customer experience

(Explained in detail on page 10 of your presentation )

🔮 Future Enhancements
Recommendation system
AI-based analytics
Integration with backend APIs (Spring Boot)
Full-stack implementation (React + Java)
👨‍💻 Author

Pathakota Charan
📘 Full Stack Engineering (FSE)
