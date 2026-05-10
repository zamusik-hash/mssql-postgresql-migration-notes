# PostgreSQL Commands

## Database list

\l

## Table list

\dt

## User list

\du

## Example query

CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    name TEXT
);

SELECT * FROM users;
