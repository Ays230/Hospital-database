# 🏥 Hospital Database Project

## Overview
The **Hospital Database Project** is a relational database system designed to efficiently manage hospital operations — including data about **departments, doctors, patients, and appointments**.  
It was developed using **PostgreSQL** as part of a personal learning project focused on **SQL, PL/SQL, and Data Analytics**.

---

## Objectives
The main goal of this project is to:
- Design a **normalized relational database** suitable for a medium-sized hospital  
- Demonstrate **realistic data relationships** between departments, doctors, and patients  
- Practice **SQL queries** for data analysis and reporting  
- Provide a foundation for future **data visualization** or **ETL (Extract-Transform-Load)** projects

---

## Database Structure

| Table Name      | Description |
|-----------------|--------------|
| **departments** | Stores details of hospital departments (e.g., Cardiology, Neurology) |
| **doctors**     | Contains information about doctors, their specialization, and department affiliation |
| **patients**    | Holds patient demographic and contact details |
| **appointments**| Tracks appointments, including date, diagnosis, and assigned doctor |

---

## Relationships
- One **department** → many **doctors**  
- One **doctor** → many **appointments**  
- One **patient** → many **appointments**
