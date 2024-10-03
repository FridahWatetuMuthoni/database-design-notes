# Databases Notes

## Database Introduction

We use a database management system to manipute data in a database.
We do these using SQL which is a database language that is used to define (data-defination-language:DDL) and (data-manipulation-language:DML) manipulate data.

## Data Defination Language

Data defination language includes defining the columns and the fields of the database.

## Data Manipulation Language

Data manipulation language includes data insertion, update, delete, search etc

## Database Design

What to consider when designing a database:

1. conceptual=>database defination
2. logical=> parent , child relationships
3. physical=> access etc

## Data Integrity

Its basically having the correct data in your database, no broken relationships between tables, duplicate different rows in a database.
Types of data integrity:

1. Entity Integrity => users e.g. caleb etc
2. Referential Integrity => relationships between tables
3. Domain Integrity => when a number's field only contains numbers and not strings.

## Database Terms

1. An Entity is anything we store data about e.g. a user, comments, sales.
2. Attributes. an atribute are the fields in an entity e.g. with a comment entity we have the comment, user who commented it, the comment ID e.t.c.
3. Relation is another name of a table
4. Tuple. a tuple is basically a row in a table.
5. Rows and Columns make up the table
6. File another name for a table
7. Record another name for a row
8. Field another name for a column
9. value is information put into a specific column
10. Normalization
11. Schema
12. keys


## The stages of database design

### Determine the purpose of your database

1. Mission Statement
   The purpose of the e-commerce inventory database is to maintain the product data and supply information to our customers and management services.

2. Mission Objectives
   i. Maintain complete product inventory
   ii. Keep Track of product inventory
   iii. Produce product and corresponding sub-product information

### Establish the requirements

Acquire data by studying existing systems, interviews and other data gathering techniques.

1. What queries will the user need to perform
   a. Return a list of all products
   b. Return a list of products by category
   c. Return a list of products by product attribute
   d. Return a list of products on promotion
   e. Return a list of new products
   f. Sort list of products by dates
   g. Sort a list of products bt price
   h. Return a single product
   i. Add a review for product

2. What queries will the business user need to perform?
   a. Add, update or delete new products
   b. Add, return or update details related to product stock levels
   c. Report: Return a list of total products sold per product
   d. Report: Return a list of newly added products for a given timeframe
   e. Description: Return a list of low or not in stock products.

3. System Requirements
   a. Return product data and images
   b. Retur a single product and associated sub-product

### Establish a preliminary set of fields

### Establish an initial set of tables

### Resolve fields and table anomalies

### Refine fields and table names

### Establish field specifications

### Determining and establishing table relationships

### Establishing business rules.
