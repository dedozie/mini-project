# Mini Project – Express.js + PostgreSQL CRUD API

## Overview
This project is a simple RESTful API built with Express.js and PostgreSQL to demonstrate basic CRUD operations on a 'users' table.

## Prerequisites
- Node.js
- PostgreSQL

## Setup Instructions

1. Create a PostgreSQL database.
2. Create the users table with:

```sql
CREATE TABLE users (
  id SERIAL PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100),
  age INTEGER
);
