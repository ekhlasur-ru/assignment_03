# Vehicle Rental System – Database Design & SQL Queries

## Project Overview

This project demonstrates database design and SQL query skills using a simplified Vehicle Rental System.
It covers ERD design, table relationships, primary & foreign keys, and core SQL concepts such as JOIN, EXISTS, WHERE, GROUP BY and HAVING.

## Objectives

- Design an ERD with proper relationships
- Understand and apply PK & FK
- Write optimized SQL queries based on real-world scenarios

## Database Entities

The system consists of three main tables:

- Users
- Vehicles
- Bookings

### Relationships

- One User can have many Bookings (1 → Many)
- One Vehicle can have many Bookings (1 → Many)
- Each Booking connects exactly one User and one Vehicle

## Business Logic

- Each user has a unique email
- Each vehicle has a unique registration number
- Bookings store rental period, status and total cost
- Vehicles have availability status (available / rented / maintenance)

## SQL Queries Explanation

### Query 1: JOIN

Retrieves booking details along with customer name and vehicle name using INNER JOIN.

### Query 2: EXISTS

Finds vehicles that have never been booked using NOT EXISTS.

### Query 3: WHERE

Fetches available vehicles of a specific type (e.g. car).

### Query 4: GROUP BY & HAVING

Counts total bookings per vehicle and returns vehicles with more than two bookings.

## ERD

The ERD is created using Lucidchart and includes:

- Primary Keys
- Foreign Keys
- Relationship cardinality
- Status fields

## Viva Video

A short viva explanation video answering theory questions.

## 🔗 Submission Links

GitHub repository Link here:  
👉 [GitHub Repository](https://github.com/ekhlasur-ru/assignment_03)

---

Lucidchart Link here:  
👉 [ERD Link](https://lucid.app/lucidchart/201ab99a-1119-4e93-8478-674f45ec1aef/edit?view_items=g_xgyQV.P0ZW&page=0_0&invitationId=inv_7eeb2d1b-fc7c-49b4-9db4-3b247c7eab7e)

---

Viva Video Link here:  
👉 [Viva Video Link](https://drive.google.com/drive/folders/18GIhNcG80VnYk7xsVz8Bl3ggLxa7R44Z?usp=sharing)

---

**Submitted by: Md. Ekhlasur Rahaman** <br>
**Assignment 03: Vehicle Rental System - Database Design & SQL Queries**<br>
**Next Level Web development (Batch-6)**
