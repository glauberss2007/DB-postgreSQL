# GFT-postgresql
![image](https://user-images.githubusercontent.com/22028539/123992699-39a55d00-d9a2-11eb-9731-533ebe786f6a.png)

PostgreSQL also known as Postgres, is a free and open-source relational database management system (RDBMS) emphasizing extensibility and SQL compliance. It was originally named POSTGRES, referring to its origins as a successor to the Ingres database developed at the University of California, Berkeley. In 1996, the project was renamed to PostgreSQL to reflect its support for SQL. After a review in 2007, the development team decided to keep the name PostgreSQL and the alias Postgres.[16]

PostgreSQL features transactions with Atomicity, Consistency, Isolation, Durability (ACID) properties, automatically updatable views, materialized views, triggers, foreign keys, and stored procedures.It is designed to handle a range of workloads, from single machines to data warehouses or Web services with many concurrent users. It is the default database for macOS Server and is also available for Windows, Linux, FreeBSD, and OpenBSD.

## Introduction to PostgreSQL Database
- [Database Basics](https://www.postgresqltutorial.com/what-is-postgresql/)
- [Installing PostgreSQL on Linux](https://www.postgresqltutorial.com/install-postgresql-linux/)
- [Installing PostgreSQL on MAC](https://www.postgresqltutorial.com/install-postgresql-macos/)
- [Installing PostgreSQL on Windows](https://www.postgresqltutorial.com/install-postgresql/)

Confirm instalation using "SQL Shell" and command 

    SELECT version();

## PostgreSQL Objects and Datatypes
- [What is the postgresql.conf file](https://www.postgresql.org/docs/9.3/config-setting.html)
- [Get to know the PGAdmin tool](https://www.pgadmin.org/docs/pgadmin4/development/index.html)  
- [How to administer users in the database](https://www.davidpashley.com/articles/postgresql-user-administration/)
- [Database Objects and Commands](https://gist.github.com/Kartones/dd3ff5ec5ea238d4c546)

## Fundamentals of Structured Query Language (SQL)
- DDL - Data Definition Language - Data Definition Language.
        These are the commands that interact with database objects.
        These are DDL commands: CREATE, ALTER and DROP

- DML - Data Manipulation Language - Data Manipulation Language.
        These are the commands that interact with data within tables.
        These are DML commands: INSERT, DELETE and UPDATE

- DQL - Data Query Language - Data Query Language.
        These are the query commands.
        These are DQL commands: SELECT (it is the query command)

- DTL - Data Transaction Language - Data Transaction Language.
        These are the commands for transaction control.
        These are DTL commands: BEGIN TRANSACTION, COMMIT AND ROLLBACK

- DCL - Data Control Language - Data Control Language.
        These are the commands to control the security part of the database.
        These are DCL commands: GRANT, REVOKE and DENY.

- [Aggregate Functions in PostgreSQL](https://www.postgresql.org/docs/9.5/functions-aggregate.html)
- [Working with JOINs](https://www.postgresqltutorial.com/postgresql-joins/)
- [CTE (Common Table Expressions)](https://www.postgresqltutorial.com/postgresql-cte/)

## Advanced Structured Query Language (SQL) Commands
- [How views help access the database](https://www.postgresql.org/docs/9.2/sql-createview.html)
- [Get to know one of the main database concepts: transactions](https://www.postgresql.org/docs/8.3/tutorial-transactions.html)
- [Functions that can be created by the developer inside postgree](https://www.postgresql.org/docs/9.1/sql-createfunction.html)
- [Using procedural languages inside postgress](https://www.postgresql.org/docs/13/external-pl.html)

## References
[Kartones](https://gist.github.com/Kartones/dd3ff5ec5ea238d4c546)
[DIO](https://web.digitalinnovation.one/course/conceitos-e-melhores-praticas-com-bancos-de-dados-postgresql)
[Documentations](https://www.postgresql.org/docs/)
