# MYSQL - QUERYING DATA
A comprehensive MySQL database project covering database setup, Data Definition Language (DDL), Data Manipulation Language (DML), data aggregation, and table join operations (INNER JOIN, LEFT JOIN, RIGHT JOIN).
# Project Overview
This repository contains the complete SQL script for creating and querying an employee management database system. It demonstrates step-by-step SQL data manipulation and relational analytics, including filtering, grouping, aggregation, and multi-table joins.
# Database Schema
The database consists of three interconnected tables:
1. Employees: Stores core employee demographic details, designation, salary, department references, and location IDs.
2. Departments: Stores department IDs and department names.
3. Locations: Stores location IDs and geographic workplace locations.

# Key Features & Query Tasks Covered
1. Database & Table Setup: Database initialization using USE employee; and structured table creation with Primary Key constraints.
2. Basic Aggregations: Grouping and filtering aggregated metrics using GROUP BY and HAVING clauses (e.g., department employee counts and salary averages).

3. Inner Joins:
* Joining employees and locations on location_id to map employee names to their assigned locations.
* Joining employees and departments with WHERE filtering to analyze specific departments (e.g., Design, Marketing).

4. Left Join:
* Displaying all departments along with total employee counts, including departments with zero assigned employees.

5. Right Join:
* Displaying all locations alongside employee names, returning NULL for locations with no assigned staff.

# How to Run
* Clone the Repository
* Open in MySQL Workbench
* Execute the Script
