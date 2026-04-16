# 📚 Online Bookstore Database System

A fully designed relational database system for managing an online bookstore.  
This project demonstrates real-world database concepts like normalization, relationships, transactions, triggers, and automation.

---

## 📌 Project Overview

The system is designed to efficiently manage:

- 📖 Books & Inventory  
- 👤 Users (Customers)  
- 🧑‍💼 Authors & Publishers  
- 🛒 Orders & Order Items  
- 💳 Payments  
- ⭐ Reviews  

---

## 🧱 Database Design

The database follows **3rd Normal Form (3NF)** ensuring:

- ✔ Data consistency  
- ✔ Reduced redundancy  
- ✔ Efficient querying  

### 🗂️ Tables

- Users  
- Books  
- Authors  
- Publishers  
- Genres  
- Orders  
- Order_Items  
- Payments  
- Reviews  

---

## 🔗 Relationships

- One user → many orders  
- One order → many books  
- One book → one author, genre, publisher  
- One order → one payment  
- Users → reviews on books  

---

## ⚙️ Features

### 🛍️ Core Features
- Browse and search books  
- Place and manage orders  
- Track order status  
- Manage inventory  
- Add reviews and ratings  

### 📊 Advanced SQL
- Complex joins  
- Aggregations  
- Revenue analysis  
- Customer insights  
- Best-selling books  

---

## 🔄 Automation & Logic

### ⚡ Triggers
- Auto-update stock  
- Prevent negative inventory  
- Update order totals  

### 🔁 Stored Procedures
- Restrict orders if payment pending > 30 days  

### 🧾 Views
- Customer order summary  
- Revenue per category  

### ⏰ Events
- Daily stock alerts  
- Monthly sales reports  

---

## 🛠️ Tech Stack

- **Database:** MySQL  
- **Language:** SQL  
- **Tools:** MySQL Workbench, dbdiagram.io  

---

## 📈 Workflow

- User Registration & Login  
- Browse / Search Books  
- Add to Cart & Place Order  
- Payment Processing  
- Order Fulfillment (Shipping & Delivery)  
- Reporting & Analytics  

---

## 🎯 Key Highlights

- Fully normalized relational database (3NF)  
- Real-world e-commerce use case  
- Advanced SQL (Triggers, Views, Events)  
- Supports both transactions and analytics  
- Scalable and modular design  

---

## 🔮 Future Improvements

- Backend integration using Spring Boot  
- Frontend using React.js  
- Book recommendation system  
- Analytics dashboard  
- Role-based authentication & authorization  

---

