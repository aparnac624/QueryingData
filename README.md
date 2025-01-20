# Querying Data
This file explains the SQL operations performed on two tables, Country and Persons, in a relational database. The operations cover creating the tables, inserting data, and querying the database to retrieve information based on various conditions.

Table Structures
------------------------------------------------
1. Country Table
The Country table holds information about different countries. It includes the following fields:
   - Id: A unique identifier for each country.
   - Country_name: The name of the country.
   - Population: The population of the country.
   - Area: The area (in square kilometers) of the country.
     
2. Persons Table
The Persons table stores data about individuals. It has the following fields:
   - Id: A unique identifier for each person.
   - Fname: The first name of the person.
   - Lname: The last name of the person.
   - Population: The population of the country the person is from (Note: this field is not related to the Persons table data but is stored for reference).
   - Rating: A rating (float) representing the person’s score or review.
   - Country_Id: A foreign key linking the person to a country in the Country table.
   - Country_name: The name of the country the person belongs to.

Operations Performed
--------------------------------------------------
1. Create Tables
2. Insert Sample Data
3. SQL Queries
   - List Distinct Country Names from the Persons Table
   - Select First and Last Names with Aliases
   - Find Persons with a Rating Greater than 4.0
   - Find Countries with Population Greater than 10 Lakhs (1 Million)
   - Find Persons from 'USA' or with a Rating Greater than 4.5
   - Find Persons with NULL Country Name
   - Find Persons from 'USA', 'Canada', and 'UK'
   - Find Persons Not from 'India' and 'Australia'
   - Find Countries with Population Between 5 Lakhs and 20 Lakhs
   - Find Countries Whose Names Do Not Start with 'C'
  
Summary of Operations
----------------------------------------------------
Table Creation: Created the Country and Persons tables with appropriate data types and relationships.
Data Insertion: Inserted 10 rows into both tables for use in queries.
SQL Queries: Performed various SELECT operations, such as filtering data based on conditions, retrieving unique values, and using aliases for column names.


Conclusion
----------------------------------------------------
This project demonstrates how to structure a relational database with foreign key constraints, and how to query and filter data effectively using SQL. The queries cover a range of operations to extract meaningful insights from the data.

 
