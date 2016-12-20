# Chapter 1. Getting Started with Doctrine 2
The Doctrine project is a collection of libraries providing utilities to ease data persistence in PHP applications. It makes it possible to create complex model layers in no time that will be compatible with popular DBMS, including SQLite, MySQL, and PostgreSQL. To discover and understand Doctrine, we will create a small blog from scratch throughout this book that will mainly use the following Doctrine components:

> **Common** provides utilities that are not in the PHP standard library including a class autoloader, an annotations parser, collections structures, and a cache system.
>
> **Database Abstraction Layer (DBAL)** exposes a unique interface to access popular DBMS. Its API is similar to PDO (and PDO is used when possible). The DBAL component is also able to execute the same SQL query on different DBMS by internally rewriting the query to use specific constructs and emulate missing features.
>
> **Object Relational Mapper (ORM)** allows accessing and managing relational database tables and rows through an object-oriented API. Thanks to it, we will directly manipulate PHP objects, and it will transparently generate SQL queries to populate, persist, update, and delete them. It is built on top of DBAL and will be the main topic of this book.

> ### Note
For more information on PHP Data Objects and the data-access abstraction layer provided by PHP, refer to the following link: http://php.net/manual/en/book.pdo.php
