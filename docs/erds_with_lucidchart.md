# ERDs with Lucidchart

Some notes on using Lucidchart ERDs for database modelling:

* Use the three-column table:
    * Primary keys, foreign keys, and indexes go in the first column.
    * Column names go in the middle column.
    * Data types go in the last column.
* Use "PK" to indicate a primary key. If you do so, when you export the SQL from Lucidchart, it will create the correct syntax for a primary key. Lucidchart will correctly handle composite primary keys–just put "PK" in each column that is part of the primary key.
* If you put any other text in the left column, Lucidchart will treat it as the name of an index on that column, and generate a CREATE INDEX statement.
* Use "FK" to indicate a foreign key. Also make sure that the relationship lines connect the related column in the primary and foreign key tables. Lucidchart *should* generate a correct `REFERENCES` line in PostgreSQL.
* I've failed in a couple of attempts at importing (auto-generating an ERD from) a PostgreSQL schema.

Lucidchart has a number of useful help pages and tutorial videos. Here are ones specifically focused on working with ERDs:

* Lucidchart Help Center Entity Relationship Diagrams: Several short step-by-step guides, with screenshots, to common actions when creating ERDs
* ERD Tutorial videos:
    * Entity Relationship Diagram (ERD) Tutorial – Part 1
    * Entity Relationship Diagram (ERD) Tutorial – Part 2
* Tutorial videos on exporting SQL DDL and importing from existing databases:
    * Lucidchart Tutorials – Export your ERD
    * Lucidchart Tutorials – Import for ERD


