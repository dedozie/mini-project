# Mini Project – Express.js + PostgreSQL CRUD API

## Prerequisites
- Node.js
- PostgreSQL

## Setup

1. Create a database in PostgreSQL
2. Create a `users` table:

```sql
CREATE TABLE users (
  id SERIAL PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100),
  age INTEGER
);
