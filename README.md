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

Use ":" before parameter names. Params are used for specific resource retrieval; query parameters for filtering. Params: http://localhost:3333/message/1/John

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

## About Me

I've built my career at Tesla with increasing responsibilities over 5 years. Studied web development for 2 years, then completed a 1-year bootcamp mastering frontend and backend. I hold over 20 certificates in frontend technologies. Passionate about exploring Java, C#, and C++. Looking for roles as a Frontend Developer to apply my skills and enthusiasm in a collaborative environment, where limitless learning drives my motivation.

## Skills

**Languages**: JavaScript, HTML5, CSS3, Java.

**Technologies**: ReactJS, Node.js, Git/Github, RESTful APIs, JSON, SQLite, MySQL, SQL.

**Frameworks**: ExpressJS, bcryptJS, Jest (Automated Testing), JWT (Authentication), Multer, CORS, Axios, Styled Components, React Icons, Swiper, React Router Dom.
