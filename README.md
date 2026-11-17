# 🏡 Airbnb Database Management System
A relational database management system for an Airbnb-style accommodation platform developed using MySQL.

This project was developed to demonstrate database design principles, relational modeling, SQL programming, and database implementation. It includes database creation, normalization, constraints, indexes, triggers, sample data, and SQL queries for data retrieval and analysis.
---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Learning Objectives](#-learning-objectives)
- [Features](#-features)
- [Database Tables](#-database-tables)
- [Database Design](#-database-design)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Installation Guide](#-installation-guide)
- [Sample SQL Queries](#-sample-sql-queries)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

  
## 📖 Project Overview

The Airbnb Database Management System is designed to simulate the operations of an online accommodation booking platform similar to Airbnb.

The database manages:

- Users
- Hosts
- Guests
- Property Listings
- Bookings
- Payments
- Reviews
- Messages
- Support Tickets
- Amenities
- Property Availability

The project demonstrates the use of relational database concepts, normalization, foreign keys, constraints, triggers, and SQL queries.

## 🎯 Learning Objectives

This project demonstrates:

- Relational database design
- Entity Relationship (ER) modeling
- Database normalization
- Primary and foreign key implementation
- SQL Data Definition Language (DDL)
- SQL Data Manipulation Language (DML)
- Database constraints
- Index creation
- Trigger implementation
- SQL querying and reporting

## ✨ Features

- User Management
- Host and Guest Management
- Property Listings
- Booking Management
- Payment Processing
- Review System
- Messaging System
- Friend Connections
- Support Ticket Management
- Availability Tracking
- Database Constraints
- Foreign Keys
- Triggers
- Sample Data

## 🗄️ Database Tables

The project consists of the following main tables:

| Category | Tables |
|----------|--------|
| User Management | User, Host, Guest, Admin |
| Location | Continent, Country, City, Address |
| Property | Property, Listing, Listing Photo, Listing Amenity, Amenity |
| Booking | Availability, Booking, Booking Status |
| Payments | Payment, Payment Method |
| Communication | Message, Friend Connection |
| Reviews | Review |
| Support | Support Ticket |

## 🗃️ Database Design

The database follows relational database design principles and has been normalized to reduce redundancy and improve data integrity.

The project includes:

- Primary Keys
- Foreign Keys
- Unique Constraints
- Check Constraints
- Composite Keys
- Indexes
- Triggers
- Referential Integrity

## 📊 Entity Relationship Diagram (ERD)

The Entity Relationship Diagram illustrates the relationships between the entities in the database.

> **Note:** The ER Diagram will be added to the `documentation` folder.

```
documentation/
    ER_Diagram.png
```

## 💻 Technologies Used

- MySQL 8.0
- MySQL Workbench
- SQL

## ⚙️ Installation Guide

1. Clone this repository or download the project files.
2. Open MySQL Workbench.
3. Open the SQL script located in the `sql` folder.
4. Execute the SQL script.
5. Refresh the schema.
6. Verify that all tables have been created successfully.
7. Run the sample SQL queries.

## 📂 Project Structure

```text
airbnb-database-management-system
│
├── README.md
├── sql
├── documentation
└── screenshots
```

## 🔍 Sample SQL Queries

Retrieve all bookings:

```sql
SELECT *
FROM booking;
```

Retrieve all listings:

```sql
SELECT *
FROM listing;
```

Retrieve all payments:

```sql
SELECT *
FROM payment;
```

## 🚀 Future Improvements

Possible enhancements include:

- User authentication
- Stored procedures
- Views
- Backup and recovery procedures
- Performance optimization
- Dashboard integration using Power BI
- API integration
- Cloud database deployment

## 👩‍💻 Author

**Helen Umeano**

- GitHub: https://github.com/Lightroy23

This project was developed as part of a Database Management Systems course and demonstrates practical SQL database design and implementation using MySQL.
