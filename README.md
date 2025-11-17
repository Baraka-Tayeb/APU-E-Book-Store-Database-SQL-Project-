# E-Book-Store-Database-SQL-Project-
E-Bookstore Database System
SQL Project – Database for Data Science

This project presents a complete SQL database system designed for the APU Bookstore as it transitions into online book retailing. The goal is to build a structured, efficient, and scalable database that supports membership registration, book management, online ordering, payment processing, and customer feedback.

The project includes full database modeling, SQL implementation, and analytical SQL queries.

# 📌 Project Overview

The E-Bookstore Database System is developed to support the online operations of the APU Bookstore in Kuala Lumpur, Malaysia. As the bookstore expands into digital services, the system ensures smooth processes in:

Membership registration

Book browsing and purchasing

Inventory and stock management

Publisher order tracking

Shopping cart operations

Delivery status monitoring

Customer feedback and review submission

This project demonstrates the complete lifecycle: analysis, design, database creation, data insertion, and business-driven SQL analysis.

# 🗂️ Database Features
✔ Key Entities

The system includes the following main entities:

Publisher

Manager

Members

Book

Publisher_Order

Pub_Order_Item

Member_Order

MemberOrderItem

Shopping_Cart

Feedback

✔ What the System Supports

Unique member registration

Real-time book availability

Publisher order management

Tracking of incoming stock

Customer shopping cart functionality

Order placement and delivery updates

Ratings and reviews (1–10 scale)

Reporting for sales, inventory, and member activity

# 📝 Business Rules

Some of the main business rules implemented in the database include:

Every customer must register as a member to purchase books.

Each member must have a unique email address.

Members can add multiple books to their shopping cart.

Payment must be completed before confirming an order.

Each member may submit one review per book.

Each book must have a unique ISBN and belong to at least one genre.

The manager can place orders with publishers and record incoming stock.

Books are marked Available or Unavailable based on stock quantity.

# 🧱 Database Structure
Entity Relationship Diagram (ERD)

An ERD was designed using Chen / Crow’s Foot notation to define entities and their relationships.

# Database Diagram

Automatically generated from the DBMS to visualize tables, PK/FK relationships, and constraints.

# 🛠️ SQL Implementation
# ✔ Data Definition Language (DDL)

The DDL section includes:

Database creation

Creation of all tables

Primary key constraints

Foreign key relationships

Attribute definitions

Insertion of initial data into all tables

All tables from the project documentation are included and structured properly.

# 📊 Data Manipulation Language (DML)

The project includes several analytical SQL queries that extract insights, such as:

# 🔹 Feedback Analysis

Total number of feedback per book

Total number of feedback per member

# 🔹 Publisher & Book Insights

Number of books published per publisher

Books with quantity above average stock

Number of books in each genre

# 🔹 Order & Customer Behavior

Members with no orders

Members who made more than 2 orders (using HAVING)

Undelivered purchased books with full details

Total number of books ordered from publishers

Genre of the book with the highest stock

These queries demonstrate strong SQL knowledge in joins, aggregates, grouping, and filtering.

# 🧰 Tools & Technologies

SQL (DDL & DML)

Microsoft Visio (ERD)

MySQL / SQL Server (or any SQL-based DBMS)v
