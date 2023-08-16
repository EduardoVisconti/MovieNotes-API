# Overview

**server.js**: This is the main entry point of the application. It starts the server using the Express.js framework, which is designed for building web applications and APIs.

## Routes and Controllers

Routes are the endpoints of the application, accessible via URLs. Controllers are functions that handle requests and send responses.

### HTTP Verbs

- **GET**: Retrieve a resource.
- **POST**: Create a resource.
- **PUT**: Update a resource.
- **DELETE**: Delete a resource.
- **PATCH**: Partially update a resource.

## Middleware

Middleware functions have access to request and response objects. They perform actions and pass data to the next middleware. They can also send responses to clients.

## SQL and CRUD

SQL (Structured Query Language) accesses and manipulates databases. CRUD stands for Create, Read, Update, Delete.

- **CREATE**: SQL INSERT
- **READ**: SQL SELECT
- **UPDATE**: SQL UPDATE
- **DELETE**: SQL DELETE

## knex.js and Migrations

Knex.js is a versatile SQL query builder for various databases. Migrations are a way to modify database schema consistently. Migrations have UP (alter table) and DOWN (revert UP) methods.

## Primary and Foreign Keys

Primary keys uniquely identify rows; they're unique and non-null. Foreign keys establish relationships between tables.

## Cardinality

Cardinality refers to the number of relationships between tables: one-to-one, one-to-many, or many-to-many.

## npm vs npx

**npm**: Node.js package manager for installing and managing packages.

**npx**: Executes packages without global installation. Useful for one-off commands and tools.
