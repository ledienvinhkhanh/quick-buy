# quick-buy
Semester 251 major assignment of Database system course at HCMUT
# QuickBuyDB - E-Commerce Database

## 📌 Project Overview
In this project, I researched e-commerce systems, contributed to database design, and implemented business logic using SQL. I focused on defining data structures, enforcing constraints, and building triggers to automate core functionalities such as order processing and data validation.


**QuickBuyDB** is a relational database system designed for an online e-commerce platform. It manages core business operations including users, product catalogs, shopping carts, orders, and inventory across stores and warehouses.

The project focuses on designing a structured database and enforcing business rules directly at the database level using SQL.

---

## 🚀 Key Highlights

### 1. Database Design (Data Modeling)
- Designed a relational database with **29 tables** representing key entities such as users, products, orders, stores, and warehouses  
- Established relationships between entities using **primary keys and foreign keys** to maintain data consistency  
- Structured data to support core e-commerce workflows such as product browsing, ordering, and inventory management  

---

### 2. Automation with Triggers
- Implemented triggers to **automatically update TotalPrice and ItemCount** in carts and orders when items change  
- Built a **loyalty points mechanism** that updates customer points when orders are completed  
- Created logic to **auto-cancel unpaid orders after 24 hours**  

---

### 3. Data Integrity & Constraints
- Applied constraints (CHECK, FOREIGN KEY) to ensure **data validity and consistency**  
- Enforced **business rules** such as:
  - Prices must not be lower than cost  
  - Stock quantities cannot be negative  
  - Time ranges must be valid (End Time > Start Time)  
- Implemented **input validation (e.g., password format using regex)**  

---

### 4. Testable Dataset
- Provided sample data including users, products, stores, and orders  
- Enabled easy testing of triggers, constraints, and business logic  

---

## 🛠️ Tech Stack & Skills Used
- **Database:** MySQL  
- **Skills:** Database Design, SQL, Triggers, Constraints (CHECK, FOREIGN KEY), Data Validation, Business Rule Implementation  

---


## 📊 Database EERD design
![alt text](image.png)

---

## 🎨 UI design using Figma
![alt text](<QuickBuy UI.png>)