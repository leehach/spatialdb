Meeting:

* Thursday 5:30-8pm, Gladfelter 341

Instructor Info:

* Prof. Lee Hachadoorian
* 104 Gladfelter Hall – In GIS Studio, enter 103A
* [Lee.Hachadoorian@temple.edu](mailto:Lee.Hachadoorian@temple.edu)
* Office Hours:
    * Monday 2:30-3:30pm (virtual only)
    * Tuesday 2:30-3:30 (office + virtual)
    * Thursday 2:30-3:30

# Overview

## Purpose of the Course

This course is an introduction to the design and management of spatial databases. The relational database model underlies most modern databases. Because of increasing demand to store, analyze, and display geographic data, many major RDBMSes have added spatial features. The course will begin with (nonspatial) database theory and practice, including SQL (Structured Query Language, the language specification that underlies most RDBMSes), the database design process, normalization, and entity-relationship diagramming. It will then move on to spatial data types, spatial indexing, and spatial querying. Specific issues related to spatial data storage, including denormalization, will be addressed.

The course will use PostGIS, a spatial extension to the open source PostgreSQL RDBMS. SQL and the SQL/MM Spatial extension, moreso than other programming languages, are widely adopted standards, and the use of any particular implementation will introduce skills that will be directly portable to other implementations, including Oracle, SQL Server, and SpatiaLite/SQLite.

At the end of the course students are expected to know how to design relational and object-relational schemas for GIS databases, implement database designs in spatial database management systems (RDBMS), and retrieve and manage spatial data in a GIS database. If time permits, we will also discuss recent trends such as unstructured data and column-oriented databases.

## Prerequisites

* Fundamentals of GIS (GUS 5062) or equivalent
* A laptop on which you can install software and data

## Text

* [PostGIS in Action, 3e](https://www.manning.com/books/postgis-in-action-third-edition), by Obe & Hsu
* [Relational Database Design and Implementation, 4e](https://www.elsevier.com/books/relational-database-design-and-implementation/harrington/978-0-12-804399-8), by Harrington
* The official [PostgreSQL Documentation](https://www.postgresql.org/docs/current/index.html)
* The official [PostGIS Documentation](https://postgis.net/docs/)

*PostGIS in Action* is available directly from the publisher at the link above. The publisher regularly runs sales. If you sign up for their Deal of the Day email far enough in advance, ***there is a good chance you will be able to purchase the text at 40%-50% off***. This is a very hands-on book, with many code examples and implementation recommendations, and you are required to purchase a physical copy. I expect that you will get significant use out of it even after the conclusion of the course.

*Relational Database Design and Implementation* is available to read online for free for the Temple community. Use one of the links from the Temple Library page for this book: <https://librarysearch.temple.edu/catalog/991037042739803811>. However, we will be reading most of the book, so purchasing a physical copy is probably a good idea. The publisher sells a print-on-demand version and often runs sales near the beginning of the semester. Use the link above to the publisher's book page.

The PostgreSQL Documentation is an excellent example of clear, readable software documentation. Since Postgres strives to be a standards-compliant implementation of SQL, the docs, in addition to providing instruction on how to use Postgres, make clear what the standard requires and where and why Postgres SQL sometimes diverges from it. I will be assigning sections from the documentation to read, but you should become familiar with it beyond the specifically assigned sections, as you will refer back to it over and over in your use of Postgres and PostGIS.

## Schedule in Brief

* Week 1
    * Introduction and Basic Queries
* Week 2
    * SQL Functions and Spatial Data
* Week 3
    * Aggregate Queries
    * Term Project: Milestone 1 Due
* Week 4
    * Table Joins
* Week 5
    * Data Modification Language (DML) and Keys
    * Assignment 0 (Practice ERD) Due
* Week 6
    * Data Definition Language (DDL) and Database Normalization
    * Assignment 1 (Basic ERD) Due
* Week 7
    * Spatial Relationships
    * Assignment 2 (Normalizing the Open Source Shakespeare Database) Due
* Week 8
    * Proximity Analysis
    * Term Project: Milestone 2 Due
* Week 9
    * Storage Strategies and Performance Tuning
    * Assignment 3 (ETL Processes) Due
* Week 10
    * Student-Led Tutorials
    * Term Project: Milestone 3 Due
* Week 11
    * Student-Led Tutorials
    * Term Project: Milestone 4 Due
* Week 12
    * Student-Led Tutorials
* Week 13
    * Student-Led Tutorials
* Week 14
    * Student-Led Tutorials
* Finals
    * Term Project: Milestone 5 (Final Report) Due

## Assignments in Brief

You will earn points along several **tracks**. Each track is worth up to 100 points. Your must progress along ***ALL*** tracks to be successful in this course. Your final grade is based on the ***lowest*** score earned along any track.

The tracks and points associated with each assignment in the track are as follows:

Attendance
: 0-100 points. Your attendance score is a straight percentage of the class sessions you are present for.

SQL Quizzes (8)
: 34 base score.
: 10 points each for quizzes 1 through 5.
: 3 points each for quizzes 6 through 8.
: Exercises (8): ½ bonus point each (4 max).
: DataCamp (2): 1 bonus point each (2 max).

Database Design Assignments (3)
: 69 base score
: Ungraded - Practice ERD
: 10 points - Basic ERD with LucidChart
: 10 points - Normalizing the Open Source Shakespeare Database
: 10 points - ETL Processes

Student-Led Tutorial
: 70-100 points. The tutorial is a skills workshop developed and presented by teams of 3-4 students based on topics discussed in class. The tutorial is awarded up to 30 points based on written materials (a workbook) and presentation..

Term Project
: 50 base score
: 5 points Milestone 1: Proof of Concept
: 10 points Milestone 2: Normalization Plan
: 10 points Milestone 3: Normalization Scripts
: 10 points Milestone 4: Analysis and Optimization
: 15 points Milestone 5: Final Report


