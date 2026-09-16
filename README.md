# Snowflake Assignment

## Overview

This repository contains the practical implementation of a **Snowflake Tutorial Assignment**.

The assignment demonstrates Snowflake environment setup, database objects, data loading, Time Travel, and data recovery.

## Questions Covered

1. **Question 1 & Question 2** – SnowSQL Login and Connection + Creation of Snowflake Objects  
   - Both Question 1 and Question 2 are completed in the **same SQL file**.
2. **Question 3** – Data Loading Using SnowSQL
3. **Question 4** – Snowflake Time Travel
4. **Question 5** – Data Recovery Using Time Travel

## Tools and Technologies

- Snowflake
- Snowflake SQL
- Snowflake Notebooks
- SQL
- SnowSQL concepts
- Snowflake Time Travel

---

## Question 1 & Question 2 – Login, Connection and Snowflake Objects

**Question 1 and Question 2 are implemented together in the same SQL file.**

### Question 1 – SnowSQL Login and Connection

The Snowflake environment was accessed and the connection was verified using:

- Current User
- Current Role
- Current Warehouse
- Current Database
- Current Schema

Example:

```sql
SELECT
    CURRENT_USER() AS CURRENT_USER,
    CURRENT_ROLE() AS CURRENT_ROLE,
    CURRENT_WAREHOUSE() AS CURRENT_WAREHOUSE,
    CURRENT_DATABASE() AS CURRENT_DATABASE,
    CURRENT_SCHEMA() AS CURRENT_SCHEMA;
