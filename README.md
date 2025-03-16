# Insurance Claim Analysis - SQL Capstone Project
# Overview

This project is a SQL-based capstone project focused on analyzing insurance claims data. It was completed as part of a LinkedIn Learning course. The project covers database schema creation, data population, analytical queries, optimization techniques, and role-based access control.

# Project Structure

## Task 1: Database Schema Creation

Designed a relational database for an insurance claims system.

Created tables: Customers, Policies, Claims, and PolicyTypes.

Key fields include:

CustomerID, PolicyID, ClaimID, PolicyTypeID, ClaimAmount, ClaimDate

PolicyStartDate, PolicyEndDate, etc.

## Task 2: Data Population

Inserted realistic sample data to reflect diverse insurance scenarios.

Included various policy types, claim amounts, and customer profiles.

## Task 3: Analytical Queries

Wrote SQL queries for insights and reporting:

Calculated the total number of claims per policy type.

Used analytical functions to determine:

Monthly claim frequency.

Average claim amount per policy type.

## Task 4: Query Optimization

Implemented indexing strategies to enhance query performance.

Added indexes on frequently used columns in WHERE clauses and join keys.

## Task 5: Roles and Permissions

Defined user roles to ensure secure data access:

ClaimsAnalyst: Read-only access to claims and policies.

ClaimsManager: Full access to claims and the ability to update policies.

Technologies Used

Database: MSQL / PostgreSQL / SQL Server

SQL Concepts: Joins, Aggregations, Window Functions, Indexing, Role Management

## How to Use

### Clone the repository
git clone https://github.com/akulkarni5208/SQL-PROJECT-INSURANCE-DATA-ANALYSIS.git


### License

This project is open-source and available under the MIT License.

### Author

Abhishek Kulkarni
