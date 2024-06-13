# Assignments & Grading

This course will make use of a variant of [Specification Grading](https://sites.temple.edu/hachadoorian/specification-grading/). This means that many assignments will be graded Complete/Incomplete or assigned a provisional grade, and in some cases will merely be returned with comments. Assignments marked Incomplete or not awarded full points may be revised and resubmitted. Quizzes can be retaken until passed, unless otherwise specified.

You will earn points along several **tracks**. Each track is worth up to 100 points. You must progress along ***ALL*** tracks to be successful in this course. Your final grade is based on the ***lowest*** score earned along any track.

Tracks proceed linearly and assignments usually need to be completed in the designated order. For example, for quizzes, the material is cumulative, and you can't earn credit for Quiz 4 if you haven't passed Quiz 3. Often, later assignments in a track presume knowledge you will have acquired by completing earlier assignments.

Some assignments proceed in milestones. In each case, you must proceed along the milestones in order. For example, for a term project, there will often be an initial topic statement, followed by an annotated bibliography (for a paper) or analysis plan (for an analytical project), a draft, and a final report. You cannot submit an annotated bibliography if your topic statement has not been approved, and you cannot submit a draft or final report if you haven't submitted an annotated bibliography or analysis plan.

Grading will conform to the following scale:

* A 93%+
* A- 90 - <93%
* B+ 87 - <90%
* B 83 - <87%
* B- 80 - <83%
* C+ 77 - <80%
* C 73 - <77%
* C- 70 - <73%
* D+ 67 - <70%
* D 63 - <67%
* D- 60 - <63%
* F <60%

## Attendance

0-100 points. Your attendance score is a straight percentage of class session you are present for.

This course meets once a week. Missing *any* class meetings will hamper your ability to complete the work in this course. High-performing students tend to be the ones who attend all class meetings. Struggling students may be struggling for a variety of reasons, but for many of them, lack of attendance is a contributing factor. Your attendance percentage will also indicate the maximum final grade you can earn in this course. If you miss 3 classes, you have attended 78.6% of class meetings. Accordingly, your final grade will not be higher than a C+, *regardless of any other work completed*.

An exception is that missing one class (attending 92.9% of class meetings) will still earn an A in the Attendance Track.

## Quizzes

34 (base score) + 10 points for each of Quiz 1-5 + 3 points for each of Quiz 6-8 + bonus points.

Each topic will conclude with a short, graded SQL quiz, beginning with the third week of class. The quizzes will focus on analysis using SQL SELECT statements. The difficulty level should be comparable or easier than the weekly exercises, so if you complete the exercises, are present for in-class review, and review the exercises afterwards, you should be well-prepared for the quizzes.

The quizzes will be taken outside of class time. You ***may*** use the lecture slides, textbooks, and your own notes during the quiz. I strongly recommend using a printed "cheat sheet" of SQL commands and functions. You ***may not*** use web searches, other people (including other students in the class), or other outside resources.

Your response to each quiz will usually be a single SQL statement. You do not have to include the query resultset (which may be large). The quiz questions sometimes includes a hint as to the expected result. You should not use this hint in your SQL statement! You should only use it to confirm that your result is the expected one.

The quizzes are cumulative. Solving Quiz 5 will use knowledge demonstrated on Quizzes 1-4. Accordingly, you cannot earn points for later quizzes unless you complete all earlier quizzes.

Each week in the semester will be a quiz round. In a typical semester, quizzes will be due on a Thursday and graded on a Friday. If you do not pass a quiz, it will be unlocked for an additional attempt. You will keep taking the quiz until you complete it. When you complete it, you will earn full points for it. There is no penalty for requiring multiple attempts to pass a quiz.

In a week where you have to retake a quiz, you may also take the next quiz in sequence. That is, if you have to retake Quiz 2, you can also take your first attempt at Quiz 3. You may not take Quiz 4 or higher. If you fail Quiz 2 and Quiz 3, you will need to concentrate on completing Quiz 2. You will not get an additional attempt at Quiz 3 until Quiz 2 is completed successfully.

If you don't take any quizzes one week, you have given up one opportunity to progress on the track. The final week of classes will be the last quiz round.

### Quiz 1-5 (10 x five)

* Quiz 1: Basic SELECT
* Quiz 2: Spatial Measurement
* Quiz 3: Aggregate Query
* Quiz 4: Attribute Joins
* Quiz 5: Spatial Joins

### Quiz 6-8 (3 x three)

* Quiz 6: SQL Cumulative Review (?)
* Quiz 7: Spatial Relationships (?)
* Quiz 8: Proximity Analysis (?)

### Exercises (½ x eight)

During the first half of the semester, exercises will be assigned each week based on that week's lecture topic. Only one problem from each exercise will be evaluated, and they will earn you bonus points in the Quizzes track. We will go over select problems from the exercises at the beginning of the following class. In order to benefit from them, you must have completed them before we review them in class. Accordingly, exercises will not be accepted late.

### DataCamp (1 x two)

Two DataCamp courses (approximately 4 hours each) will be assigned early in the semester. Completing them will earn you bonus points in the Quizzes track.

## Database Design Assignments

69 (base score) + 10 points for each assignment.

These assignments will lead you through creating a basic Entity-Relationship Diagram (ERD), normalizing a database, and creating an Exchange-Transform-Load (ETL) process.

You will use the skills you develop in these assignments in your term project. Completing these assignments in a timely manner is crucial, not only because each assignment is worth a full letter grade in your final course grade, but because you will struggle with the term project without the experience of working on these assignments.

Because understanding these assignments is important to your term project, I will go over the solutions in class. If you have not submitted the assignment in question, you will be asked to wait outside the classroom until we finish reviewing the solution.

### Assignment 0: Practice ERD (0)

This assignment is worth 0 points, but will give you practice constructing Entity-Relationship Diagrams (ERDs). You will work on it at home and we will review solutions in class.

Create ERDs by hand for the following scenarios.

1. A university has many students and faculty members. The attributes of students are student ID, first name, last name and student address. A student can take zero, one or many classes. A class must have at least one student. Attributes of professors are professor ID, last name and first name. A professor teaches zero, one or many classes and a class is taught by one professor only. A course may have zero, one or many classes and a class comes from one course only. A class is held in one room but a room has many classes.
2. A company has a number of employees. The attributes of employees include employee ID, Name, address and birth date. The company also has several projects. Attributes of a project include project ID, project name and start date. Each employee may be assigned to one or more projects, or may not be assigned to a project. A project must have at least one employee assigned and may have any number of employees assigned. An employee’s billing rate may vary by project and the company wishes to record the applicable billing rate for each employee when assigned to a particular project.

### Assignment 1: Basic ERD (10)

Create ERDs for the following case studies.

1. A hospital has a large number of registered physicians. Attributes of physicians include physician ID and specialty. Patients are admitted to the hospital by physicians. Attributes of patients include patient ID, name, and DOB (date of birth). An admission must have one patient, one admitting physician, and the date of admission. A patient may be admitted more than once and a physician may admit any number of patients. Once admitted, a given patient must be treated by at least one physician. A particular physician may treat any number of patients, or may not treat any patients. Whenever a patient is seen by a physician, the hospital wishes to record the details of the visit, which include date, time, observed symptoms, and prescribed treatment.
2. Consider a real estate firm that lists property for sale. The firm has a number of sales offices in several states. Attributes of sales offices include office number (identifier) and address. Each sales office is assigned one or more employees. Attributes of employees include employee ID (identifier) and employee name. An employee must be assigned to only one sales office. For each sales office, there is always one employee assigned to manage that office. An employee may manage only the sales office to which they are assigned. The firm lists properties for sale. Attributes of property include property ID (identifier), list price, street address, city, state, zip code. Each unit of property must be listed with one (and only one) of the sales offices. A sales office may have any number of properties lists or may have no properties listed. Each unit of property has one owner. Attributes of owners include owner ID (identifier) and owner name. An owner may own one or more units of property.

Please follow these guidelines:

* Use course conventions for table and column names (lower case with underscores, no embedded spaces, etc.)
* Make sure your tables have sensible primary keys. Indicate primary keys with "PK".
* Use connectors with correct crow-s foot endings to indicate relationships between tables (entities).
* Use "FK" to indicate foreign keys.

**Deliverables**

Put your name and a database title (e.g. "Hospital Database") on the ERD. To submit the assignment, download the diagrams as PDF. Also export the ERD to SQL. If the tool allows, make sure to use the PostgreSQL option when you export. Clean up the exported SQL as necessary, including adding primary keys and foreign keys and removing the unnecessary `CREATE INDEX` statements. Upload the PDFs and SQL scripts to Canvas, and bring printouts of the PDFs to class.

**Evaluation**

* (2 points) Naming conventions: Do the identifiers follow course naming conventions? (All lower case, words separated by underscores, etc.)
* (2 points) Entities & Attributes #1: Does the ERD include the correct entities in question 1, with the correct attributes?
* (2 points) Entities & Attributes #2: Does the ERD include the correct entities in question 2, with the correct attributes?
* (1 point) Cardinalities #1: Does the ERD include the correct cardinalities (one-to-one or one-to-many) for the entities in question 1? Note: You should attempt to determine the optionality of the relationship, i.e. whether the relationship is optional (zero) or required (one or many). However, that will not affect the points awarded for this criteria.
* (1 point) Cardinalities #2: Does the ERD include the correct cardinalities (one-to-one or one-to-many) for the entities in question 2? Note: You should attempt to determine the optionality of the relationship, i.e. whether the relationship is optional (zero) or required (one or many). However, that will not affect the points awarded for this criteria.
* (1 point) SQL #1: Will the SQL script create the indicated ERD for question 1, including foreign key references? SQL can be autogenerated from the ERD. If the ERD is incorrect, points will still be awarded for a SQL statement generated by the incorrect ERD.
* (1 point) SQL #2: Will the SQL script create the indicated ERD for question 1, including foreign key references? SQL can be autogenerated from the ERD. If the ERD is incorrect, points will still be awarded for a SQL statement generated by the incorrect ERD.

#### Using LucidChart

For the Basic ERD assignment, we will use Lucidchart, available as a third-party add-on to Google Drive.

There are many charting, diagramming, and database design tools. In fact, DBeaver has an ERD component, but I don't find it very useful and the visual style is nonstandard. You are welcome to explore alternatives to LucidChart.

Lucidchart is available at a free and paid tier. The free tier only allows three documents (files). However, each document can have multiple pages. Use one document for all assignments, and create a new page for each ERD. A new page can be added from the Insert menu or the circle-plus icon (+) at the bottom of the application window.

Some notes on using Lucidchart ERDs for database modelling:

* Use the three-column table:
    * Primary keys, foreign keys, and indexes go in the first column.
    * Column names go in the middle column.
    * Data types go in the last column.
* Use "PK" to indicate a primary key. If you do so, when you export the SQL from Lucidchart, it will create the correct syntax for a primary key. Lucidchart will correctly handle composite primary keys if you put "PK" in each column that is part of the primary key.
* If you put any other text in the left column, Lucidchart will treat it as the name of an index on that column, and generate a `CREATE INDEX` statement.
* Use "FK" to indicate a foreign key. Also make sure that the relationship lines connect the related columns in the primary and foreign key tables. If you do, Lucidchart will generate a correct `REFERENCES` line in PostgreSQL.
* I've failed in a couple of attempts at importing (autogenerating an ERD from) a PostgreSQL schema.

Lucidchart has a number of useful help pages and tutorial videos. Here are ones specifically focused on working with ERDs:

* [Lucidchart Help Center Entity Relationship Diagrams](https://lucidchart.zendesk.com/hc/en-us/articles/207299756-Entity-Relationship-Diagrams): Several short step-by-step guides, with screenshots, to common actions when creating ERDs
* ERD Tutorial videos:
    * [Entity Relationship Diagram (ERD) Tutorial – Part 1](https://www.youtube.com/watch?v=QpdhBUYk7Kk)
    * [Entity Relationship Diagram (ERD) Tutorial – Part 2](https://www.youtube.com/watch?v=-CuY5ADwn24)
* Tutorial videos on exporting SQL DDL and importing from existing databases:
    * [Lucidchart Tutorials – Export your ERD](https://www.youtube.com/watch?v=q8hdO8Fqjcc)
    * [Lucidchart Tutorials – Import for ERD](https://www.youtube.com/watch?v=yFjeJnV42Lg)

### Assignment 2: Normalizing the Open Source Shakespeare Database (10)

For this assignment, you will analyze the schema of the Open Source Shakespeare database and bring it into 3NF. We will not work with the `wordform` table.

To begin, examine the `work`, `character`, `character_work`, `chapter`, and `paragraph` tables (all tables except `wordform`) and state the highest normal form (up to 3NF) that the table satisfies. (For example, if you state 2NF, you are indicating that the table is not in 3NF). Explain how the table fails to satisfy the requirements of the lowest normal form that it fails. Consider issues of data redundancy, modification anomalies, and functional dependencies.

Then modify all tables in the Shakespeare ERD to bring them into 3NF. An ERD for the current schema will be provided. You can duplicate this schema and then modify your own copy.

You should color code your objects to make clear what is new and what is old:

* You may find that you need to add tables not in the schema. If you do so, apply a green fill to any new tables. Also use green lines for any new relationships, and green text for any new columns in existing tables.
* You may find that you need to delete columns, relationships, or entire tables. Apply a red color to the text, lines, or fill of any columns, relationships, or tables that you intend to delete.
* You may find that some columns can be calculated based on other data in the tables. For example, we saw in an exercise that each character’s speech count can be calculated by counting rows in the `paragraph` table. Therefore, the `speechcount` column in the `character` table is superfluous and could be deleted. This can be replaced by a view (stored query) that calculates the value when needed. Apply a purple color to the names of columns that you could calculate instead of store.

Indicate primary keys and foreign keys in all tables with ""PK and "FK". Remember that a column can be both a PK and FK. Make sure that relationship lines physically connect to the specific columns they reference.

**Deliverables**

Submit one PDF with, first, an image of the new ERD, followed by your discussion of the normal form that each of the original tables satisfied before your modifications.

**Evaluation**

Normalization often requires judgement calls. There may be more than one way to correctly normalize a database schema. Accordingly, grading will largely be based on a holistic assessment of the ERD that you submit.

* (2 points) Correctly identify the highest normal form for the entities in the existing schema.
* (1 point) Correctly identify all or nearly all columns that can be replaced with derived columns (i.e., calculated based on other data in the database).
* (7 points) Propose a new ERD with all entities in 3NF and appropriate relationships among entities.

### Assignment 3: Exchange-Transform-Load Processes (10)

In this assignment, you will script a complete ETL process to import nonspatial data to PostGIS and create a spatial table, with some rudimentary normalization. The source data is the [Street Poles dataset from OpenDataPhilly](https://www.opendataphilly.org/dataset/street-poles). Note that while this data is available as a shapefile, we are going to work with the CSV. One of the things you have to do in this assignment is construct PostGIS geometries from the raw coordinates.

Begin by downloading <http://data.phl.opendata.arcgis.com/datasets/9059a7546b6a4d658bef9ce9c84e4b03_0.csv>, then use ogr2ogr to import this file into PostGIS. See further information on this step below.

The fields in this table, taken from the metadata, are listed below. Not listed are the `x` and `y` coordinate fields, which are included in the CSV but not the shapefile. Note that the field `pole_num` is described as a unique identifier, *but it is not actually unique*. The file contains duplicate records. Cleaning up the duplicate data is a common part of data cleaning, but would add complexity to this assignment. If time permits I will discuss how this can be accomplished after the assignment is graded. In the meantime, you will use `objectid` as the unique identifier for this data.

Your ETL process should be created in *one* SQL script. The SQL statements should be properly terminated so that the script can be executed in one go. Do not use schema-qualified table names anywhere in your script. Instead, each script should begin with a `SET search_path` statement at the top (remember to include the public schema at the end!) so that it can easily be run in an alternate schema. I will run your scripts in a schema named `etl`. Your script should complete without any syntax errors.

The fields `nlumin`, `lum_size`, `height`, `block`, and `plate` have many `NULL` values. A large number of `NULL`s is usually a sign that the table is not properly normalized. According to the metadata, the `nlumin`, `lum_size`, and `height` fields all contain information about pole lighting, and the `block` and `plate` both reference "a map that was used to plot Alley (AEL) Poles". Thus, you will create two related tables to hold this data.

The `type` column contains an acronym/abbreviation, decoded in the metadata shown below. You will create a lookup table with the acronym as its primary key and an additional column for the description.

The `owner` column contains owner names in a combination of descriptive categories (e.g. "Private"), acronyms (e.g. "SEPTA", "PWD"), and abbreviated names (e.g. "U of Penn"). Mostly these are not good keys and subject to misspellings. You will replace this column with an `owner_id` column and create a lookup table populated with the names (this code is given to you below), then replace the owner names with the IDs from the lookup table.

**Evaluation**

* (1 point) Submit a SQL script in one file which runs from start to finish with no errors.
* (1 points) Create the ogr2ogr command to import Street_Poles.csv into PostGIS.
* (0 points) Create a `pole_owner` lookup table.
* (1 point) Create a `pole_type` lookup table.
* (2 point) Create the main `street_pole` table.
* (1 points) Create related tables for the lighting info and the alley pole info.
* (3 points) Transform and insert the data into `street_pole`.
    * 1 point for correctly constructing the point geometry.
    * 1 point for correctly populating the `pole_owner_id` column. If you find that you are unable to do this, change the data type of the `pole_owner_id` column back to varchar (Step 4) and insert the `owner` values.
    * 1 point for correctly populating all other columns.
* (1 point) Insert related data into `pole_light_info` and `alley_pole`.


#### 1. Use ogr2ogr to import Street_Poles.csv into PostGIS

Refer to the lecture slides and ogr2ogr documentation to construct this command. Import the file to a staging table named `import_street_poles`. This is the temporary home for your data.

Use the following command line switches:

* `-lco PRECISION=NO`: This will prevent ogr2ogr from constructing numerics for quantitative data, which is highly undesirable, or adding field size limits to varchar, which is not awful but kind of unnecessary.
* `-oo EMPTY_STRING_AS_NULL=YES` (not demonstrated in class): this makes sure that empty strings (two commas in the CSV file with no characters between them) get imported as SQL NULLs.

Paste the ogr2ogr command that you construct in a comment block at the top of your SQL script.

Do not use data type autodetect (an ogr2ogr option). Do not use ogr2ogr to create geometries from the coordinates during the import. This is an extremely useful feature of ogr2ogr, but I want you to get practice creating geometries in SQL.

If you cannot complete this step, use a GUI tool such as QGIS to import the CSV so that you can continue with the rest of the assignment. You can come back and try to complete this step later, before submitting the assignment.

#### 2. Create a `pole_owner` lookup table

Run the following commands to create a lookup table based on the data in the `owner` column:

```sql
DROP TABLE IF EXISTS pole_owner CASCADE;
CREATE TABLE pole_owner (
    pole_owner_id int GENERATED ALWAYS AS IDENTITY PRIMARY KEY,
    pole_owner varchar
);

INSERT INTO pole_owner (pole_owner)
SELECT DISTINCT owner FROM import_street_pole;

```

As this table does not depend on any other table, you should be able to run this DDL without any problems.

#### 3. Create a `pole_type` lookup table

Create a `pole_type` table with a `pole_type` varchar primary key column, and a `description` varchar column. Use `INSERT` statements to populate this table with rows taken from the metadata (given below) for the `TYPE` field in the original data. Note that two codes are missing. (It is not uncommon for metadata to be incomplete in this way.) When you attempt to insert rows into the `street_pole` table in step 6, you will get foreign key constraint errors. Using these error messages, you will be able to identify the missing codes and add them to your `INSERT`s.

**Metadata**

Source: <http://metadata.phila.gov/#home/datasetdetails/555f8135f15fcb6c6ed4413a/representationdetails/5571b1c4e4fb1d91393c2183/?view_287_page=1>

| ﻿Field Name | Description                                                                                      | Type    |
|------------|--------------------------------------------------------------------------------------------------|---------|
| BLOCK      | References a map that was used to plot Alley (AEL) Poles                                         | Text    |
| HEIGHT     | light height                                                                                     | Integer |
| LUM_SIZE   | light wattages                                                                                   | Integer |
| NLUMIN     | light lumin count                                                                                | Integer |
| OBJECTID   |                                                                                                  | Numeric |
| OID        |                                                                                                  | Integer |
| OWNER      | pole owner                                                                                       | Text    |
| PLATE      | References a map that was used to plot Alley (AEL) Poles                                         | Text    |
| POLE_DATE  | creation date                                                                                    | Date    |
| POLE_NUM   | Unique identifier                                                                                | Integer |
| TAP_ID     | identifies the poles tap pole                                                                    | Integer |
| TYPE       | Acronym that describes the pole type and style. Contact GIS Data Contact below for translations. | Text    |
|            | * AAMP - Avenue of the Arts Mast Arm Pole                                                        |         |
|            | * AAPT - Avenue of the Arts Street Light Pole                                                    |         |
|            | * AEL - Alley Pole                                                                               |         |
|            | * C13 - Traffic C Post 13'                                                                       |         |
|            | * C20 - Traffic C Post 20'                                                                       |         |
|            | * CCP - Center City Pedestrian Pole                                                              |         |
|            | * CCR - Center City Roadway Pole                                                                 |         |
|            | * CHP - Chestnut Hill Street Light Pole                                                          |         |
|            | * D30 - Traffic D Pole                                                                           |         |
|            | * FLP - Franklin Light Pole                                                                      |         |
|            | * MAP - Traffic Mast Arm Pole                                                                    |         |
|            | * MAPT - Traffic Mast Arm Pole (Twin Light)                                                      |         |
|            | * MLP - Millenium Light Pole                                                                     |         |
|            | * MLPT - Millenium Light Pole (Twin Light) * OTH - Other                                         |         |
|            | * OTHT - Other (Twin Light)                                                                      |         |
|            | * PDT - PennDot Pole                                                                             |         |
|            | * PDTT - PennDot Pole (Twin Light)                                                               |         |
|            | * PKY - Parkway Street Light Pole                                                                |         |
|            | * PKYT - Parkway Street Light Pole (Twin Pole)                                                   |         |
|            | * PTA - Post Top Pole (Aluminum)                                                                 |         |
|            | * PTC - Post Top Pole (Concrete)                                                                 |         |
|            | * PTF - Post Top Pole (Fiberglass)                                                               |         |
|            | * PVT - Private Pole                                                                             |         |
|            | * PVTT - Private Pole (Twin Light)                                                               |         |
|            | * RP - Radar Traffic Pole                                                                        |         |
|            | * SLA - Street Light Aluminum                                                                    |         |
|            | * SLAT - Street Light Aluminum (Twin Light)                                                      |         |
|            | * SLF - Street Light Fiberglass                                                                  |         |
|            | * SLFT - Street Light Fiberglass (Twin Light)                                                    |         |
|            | * SM - Structure Mounted                                                                         |         |
|            | * SMP - Strawberry Mansion Bridge Pole                                                           |         |
|            | * SNP - Sign Pole                                                                                |         |
|            | * SWP - Span Wire Pole                                                                           |         |
|            | * TP - Trolley Pole                                                                              |         |
|            | * WP - Wood Pole                                                                                 |         |
|            | * WPT - Wood Pole (Twin Light)                                                                   |         |
|            | * CTP - Chinatown Pole                                                                           |         |
|            | * SSP - South Street Tower Pole                                                                  |         |
|            | * SMB - Septa Millennia Bridge Pole                                                              |         |
|            | * JMB - JFK Blvd Millennia Bridge Pole                                                           |         |
|            | * MMB - Market St Millennia Bridge Pole                                                          |         |
|            | * CMB - Chestnut St Millennia Bridge Pole                                                        |         |
|            | * WMB - Walnut St Millennia Bridge Pole                                                          |         |
|            | * SMAB - Strawberry Mansion Arch Bridge Pole                                                     |         |
|            | * FB - Falls Bridge Pole                                                                         |         |
|            | * RLP - Red Light Camera Pole                                                                    |         |
|            | * TCB - Traffic Control Box                                                                      |         |
|            | * AASP - Avenue of the Arts Signal Pole                                                          |         |
|            | * CP - Carrier Pole                                                                              |         |
| UP_DATE    | data update date                                                                                 | Date    |

#### 4. Create the main `street_pole` table

Write a `CREATE TABLE` statement for the `street_pole` table. You will find it easier to test your script if you include the following line immediately prior to the `CREATE TABLE`:

```sql
DROP TABLE IF EXISTS street_pole CASCADE;
```

This will let you drop and create the table in one execute, without having to drop the table separately or check to see whether it exists.

Create the table as follows:

* Discard the `ogc_fid` column, or any other ID column created during import.
* Discard the `x` and `y` coordinate columns, as you will be constructing a geometry instead.
* Rename the `objectid` column to `gid` (following our course conventions). Make this an identity column using `GENERATED ALWAYS AS IDENTITY PRIMARY KEY`.
* Discard the `oid` (or `oid_`) column.
* Retain the `pole_num` column.
* Rename the `type` column to `pole_type`, since `type` is a SQL reserved keyword.
* Do not include the columns that will be moved to `pole_light_info` (see step 5).
* As `pole_date` and `up_date` are the same for all poles, discard the `up_date` column.
* Rename the `owner` column to `pole_owner_id`.
* Retain the `tap_id` column.
* Do not include the columns that will be moved to `alley_pole` (see step 5).
* Add a `geom` column. This should be of type `geometry(POINT, 2272)`, which corresponds to Pennsylvania State Plane South.

All columns should be of appropriate types. The types should be obvious from perusal of the data in `import_street_pole`. In particular, anything that looks like an integer column *is* an integer column. There are no integer columns that have a string value like `'missing'` hidden somewhere deep in the table.

Additionally, the `pole_owner_id` and `pole_type` columns should be foreign keys to the `pole_owner` and `pole_type` tables.

#### 5. Create related tables for lighting and alley pole info

Construct two `CREATE TABLE` statements for tables named `pole_light_info` and `alley_pole`. Each table should have an integer primary key column named `gid`. `pole_light_info` should have three integer columns named `nlumin`, `lumin_size`, and `height`. `alley_pole` should have two varchar fields named `block` and `plate`.

#### 6. Transform and insert the data into `street_pole`

Use an `INSERT` statement to select data from `import_street_pole` and insert it into `street_pole`. Use the instructions from the step 4 as your guide. For example, where the instructions say "Rename the objectid column to gid", this means that `gid` should appear in your target column list and `objectid` should appear in your `SELECT` list.

The `street_pole` table has an autoincrementing identity column (`gid`). However, we want to preserve the values from the `objectid` column in the original data. In order to insert an explicitly provided value into a generated column, you have to override the default. Use the clause `OVERRIDING SYSTEM VALUE` in your `INSERT` statement. This should come immediately after the list of columns to insert into, and before the `SELECT` statement that generates the rows to insert.

Columns will have to be transformed to the appropriate data type. Use the date type (rather than timestamp) for the `pole_date` column, since the times are all midnight, which really means "We don’t care about the time, we only care about the date."

You may need to handle empty strings, depending on how you imported the original data. If you imported the data with ogr2ogr using `-oo EMPTY_STRING_AS_NULL=YES`, you do not need to do anything special to handle empty strings. If you did not use this command line switch, or used QGIS (or some other tool) instead of ogr2ogr to import your data, you will have empty strings in several columns that will cause errors when you try to cast the column to integer or date. You can handle empty strings using `NULLIF` to replace with `NULL`s before casting to another data type.

Use `ST_Point` to construct geometries from the `x` and `y` coordinates. The coordinates are in WGS84 lat-long. Therefore to complete this step you will need to nest two functions:

* `ST_Point` to construct the geometry, assigning the *current* CRS.
* `ST_Transform` to transform the data to the target CRS.

Insert the `pole_owner_id` (int), rather than the `owner` (text) into the table. To do this you will need to join to the `pole_owner` lookup table.

Since you inserted explicit values into the identity column (`gid`), you also need to update the autoincrementing sequence attached to that column so that it doesn't return a value that is already in the table. (That is, if you the sequence starts at 1, and you insert the numbers 1 through 10, you need to tell the sequence to skip over those numbers the next time you ask it for the next value.) You do this by running the following statement *after* the `INSERT` statement:

```sql
SELECT setval('street_pole_gid_seq', (SELECT max(gid) FROM street_pole));
```

#### 7. Insert related data into `pole_light_info` and `alley_pole`

Insert the appropriate columns from `import_street_pole` into `pole_light_info` and `alley_pole`. Remember to include the `gid` column, as this is the foreign key that links the tables. Remember to transform the data types of the columns where necessary.

The point of doing this is to remove the large number of `NULL` values from the tables, so your `INSERT…SELECT` statement for `pole_light_info` should only include those rows where the additional columns are not `NULL`. (If any of the three columns are `NULL`, they all are, so you can check any one of them for the `NOT NULL` criteria.) Similarly, for inserting into `alley_pole`, only include those rows where the additional columns are not `NULL`.

## Student-Led Tutorial

70 (base score) + up to 30 points as detailed below.

Students will form into teams of 3-4 to present advanced topics in geodatabases. Possible topics include:

* Raster storage and analysis (PiA Ch. 7 & 12; PostGIS docs Ch. 11, 12, 13)
* pgRouting (PiA Ch. 16.1; documentation)
* NoSQL databases (RDD&I Ch. 28), including unstructured storage models (such as Postgres JSONB) and column-store databases (such as Postgres Citus)

Students may select other approved topics based on their interests. Your topic must rely on entirely free and open source tools unless you clear another topic with me. At the very least it must be something that has a free community edition or a free trial period.

The team will need to read documentation, technical blogs, or other tutorials to learn about their topic, and then prepare their own tutorial workshop for the class. The workshop may be based on other tutorials that you find, but should be your own work. At the very least, you should make use of a different dataset than any tutorial that you consult when teaching yourself the topic. Try to use data of real-world interest to the class. Using data specific to Philadelphia or nearby regions is a good choice.

The tutorial team should communicate with the class before the presentation with prep instructions for the workshop, including anything that needs to be installed ahead of time and data or software that needs to be downloaded.

The team should create a tutorial workbook. Do *not* include instructions on installing and setting up a Postgres server. If your topic requires installing a Postgres extension, do include instructions on creating the extension. If your topic requires installing a different RDBMS (such as MongoDB or TimescaleDB), do include instructions on downloading, installing, and configuring that RDBMS. Installation instructions should be relegated to an appendix of your workbook.

Don't reinvent the wheel. Sometimes tutorial teams consult documentation that tells them to install pgAdmin 4 (or some other database management client), and then use pgAdmin 4 in their class workshop. But we are already using DBeaver as our database management client. Use the tools that we are already using! Similarly, students might consult documentation that demonstrates using shp2pgsql to upload shapefiles. But we are already using QGIS or ogr2ogr, so use those instead. On the other hand, you might find that your tutorial *requires* the use of a different tool, such as using raster2pgsql for raster data uploads. Try to integrate the new technology into your (our) existing toolchain, rather than replace it with a completely new toolchain. It will be best to consult with me early as you are developing your tutorial.

The workshop itself should be about 45 minutes to an hour, with hands on activities. Since this is a GIS course, ideally there will be some visual output. Using QGIS will be easiest, as the students will already be familiar with connecting to a Postgres server from QGIS. Unless your tutorial *requires* creating a separate database, please use the existing `universe` database on `localhost`, possibly creating a new schema specifically for your tutorial data.

The workshop does *not* require Powerpoint. It can be entirely demo. If you do want to open up with an overview of the topic, keep it to five minutes max, and slides are still optional. Do not use slides for code (SQL or otherwise).

Team members should rotate roles. Each person should have a chance doing teaching demo at the front of the room. Other team members should be circulating among the class, helping troubleshoot issues that the students are encountering.

**Evaluation**

1. Team conducts a workshop on the scheduled day (10 points).
2. Team sends installation/data download instructions to the class at least 24 hours before their workshop (5 points).
3. Tutorial workbook (10 points, may be revised if full points are not earned).
4. Workshop is well-structured and leaves class with a useful first exposure to the topic (10 points).
5. Team can knowledgeably respond to questions from the class (5 points).

Note that the workbook is the only part of the tutorial that can be revised. The rest of the requirements depend on preparing for an giving the workshop on the scheduled day. If the team is unprepared or outright misses the scheduled day, it cannot be made up.

## Term Project

50 (base score) - 100 points. This will be a database design project involving taking a real world dataset and turning it into a PostGIS database schema suitable for analysis. Points will be awarded for meeting milestones, including finding data, developing and implementing a normalization plan, creating analytical queries, and writing a final report.

Other than the final report, most of the milestones for the term project will be reviewed in class. You will bring in your work and I will discuss it with you, give you feedback, and let you know whether to revise is before progressing to the next milestone.

For this project, you need to identify a publicly available dataset, upload it to PostGIS, test alternative database designs, and combine it with existing data to answer an interesting spatial question.

For example, imagine that you want to investigate a potential correlation between crime and alcohol-serving establishments, as some students of mine did in a previous course. You will probably start with tables of all business locations, which may or may not be geocoded. You may have crimes in aggregate (reported by police precinct, council district, ZIP code…) or maybe you will have individual crime locations. The data may already be spatial, or you may have to spatialize it.

Your workflow may involve the following.

1. Upload the data.
2. Geocode by address (possibly before uploading), geolocate by coordinates, or join by geographic identifier to an existing spatial layer.
3. Join to other appropriate layers. For example, the crimes data should be joined to a population layer (such as census tracts) to turn raw numbers into a crime rate. One approach would be to do a point-in-polygons operation of crimes in census tracts.
4. Use intersections and buffers to determine the crime rate inside and outside of a reasonable target distance.
5. Connect to the layers via client applications (GIS software or statistical software) for visualization.

The final assignment has three parts, database design, Extract-Transform-Load (ETL),  and analysis. The first two parts are more important. The analysis piece is primarily there to motivate your thinking about how the data will be used.

The requirements and specific deliverables are described in detail below.

### Milestone 1: Proof of Concept (5)

This milestone involves obtaining data, demonstrating familiarity with it, uploading it to PostgreSQL, and suggesting possible analytical questions which can be answered.

To begin, you must identify a dataset that you will use for your final project. This should be a vector dataset that is publicly available. Examples include business registrations, cadastral data (i.e., property data maintained by an assessor’s office), crime data, sales data, survey data from any number of government or private sources, etc. It may not be US Census data (either Decennial Census or American Community Survey). It must be in a spatial format (e.g., shapefile, geodatabase, GeoJSON) or data which is capable of being spatialized (e.g., business addresses which can be geocoded, survey data which can be joined to ZIP Codes, etc.).

> If you are already quite familiar with raster analysis, and it will be useful to your future career development to work with raster data, you may propose a final project involving a raster dataset, but you must clear it with me ahead of time.

Among the least interesting data to work with for this kind of project is attribute data that merely joins to a spatial layer representing some administrative unit or analysis boundary. That is, if you would like to analyze crime data, working with crime point locations would lead to an interesting design project (and interesting spatial questions); but a table of crime data already aggregated to townships, states, Census tracts, etc., probably leaves very little design work, and even the spatial analysis component will be pretty basic.

Some data sources are more complex than others. Some will be large flat files, while others will be split into multiple tables. The multiple tables may represent annual releases, or may be a rudimentary normalization. The data may also be split merely to make file sizes smaller for distribution purposes. These are all interesting challenges to solve, but if you find that you are struggling with this milestone, you might have to consider finding a less complex dataset.

This is your project, and you need to familiarize yourself with the dataset. Public data (esp. for research purposes) should come with a data dictionary, which lists the data type, meaning, and allowable values (the domain) of all variables. Some datasets will come with hundreds or thousands of columns, and you will not be expected to know what they all mean, but you need to know the important ones—and getting familiar with your data also means determining which ones are the important ones.

Import your data "as is" to PostgreSQL. Most likely your data are not normalized—do not normalize it at this stage. Do not create a surrogate key. Do create a primary key if suitable column(s) exist. Do launder column names.

If your data are not already spatial (that is, if you are not importing from a spatial format), make your data spatial:

1. If the data has coordinates, create a geometry column based on the coordinates.
2. If the data has an address, geocode it to obtain coordinates, then create a geometry column based on the coordinates.
3. If the data can be georeferenced (it has an ID or name that corresponds to a geographic entity such as a county, ZIP code, school, etc.), identify an additional, spatial data source for the geographic entity, and include that in your import and your ERD.

**Evaluation**

The following will be evaluated in class:

1. You have a project folder on your hard drive with the original data and data dictionary.
2. You are able to discuss the data and demonstrate an understanding of the data, including who (what organization, person, or research group) created or maintains it, what it is used for, what the variables in the dataset mean, including the domain (allowable values). Certain categorical data may be coded, and you should know what the codes mean. For example, if a dataset of an elections dataset has political party affiliation, it's not enough to tell me that the `party` column lists the political party. You have to also know that the `party` column uses numbers to represent political parties and know or be able to refer to the key that shows what the numbers mean (e.g. 1 = Democratic, 2 = Republican, 3 = Green, 4 = Libertarian, etc.).
3. You have uploaded the data to your local PostGIS server. Column and table names have been laundered. The core table (if your dataset has more than one table) has a geometry column. If the data were merely coordinates or addresses, you should already have it geocoded and have created a geometry column from the coordinates.
4. You can connect to and display the data in QGIS. Again, if the data were merely coordinates or addresses, it should have been spatialized so that it displays in QGIS as a map (not just a table).
5. You can run one SQL statement using a filter (WHERE clause) to select no more than 10 records from your data that match the filter criteria. This statement should not use a LIMIT clause. (That is, you can return 10 records by running a query like `SELECT * FROM table1 LIMIT 10;`
6. You have written down and can discuss three examples of spatial questions you can answer using this data. It is OK if these questions require the use of other data, such as Census data. Such additional data sets are *not* part of the project. They do need to be uploaded, but do not have to be normalized.

When the data has been approved, you may proceed to creating your normalization plan for Milestone 2. You should also write up an overview of the dataset to include in your Final Report.

### Milestone 2: Normalization Plan with ERD (10)

Make your data conform to 3NF.

If your data has coded categorical data, you should create lookup tables based on the data dictionary. If your data has categorical data which is not coded, you should create lookup tables and replace the values in the core table with these category codes.

For example, assume you have a table with a column `education`. This could appear in your data in two ways:

1. The table has numeric codes 1-4, which the data dictionary indicates mean "Less than high school", "High school or GED", "Bachelor’s degree", "Graduate degree". You would need to create a lookup table with the codes 1-4 and the values they translate to.
2. The table has values "Less than high school", etc. In this case, you still need to create the lookup table, but  you also need to update the base table and replace all instances of "Less than high school" with 1, all instances of "High school or GED" with 2, etc.

**Evaluation**

You will create an ERD of the normalized schema. You will bring a hard copy of the ERD to class, as I will mark it up as we discuss your normalization plan.

All tables should have a primary key. All columns should be of appropriate types. At least one table should have a geometry column. The coordinate reference system may be a judgment call, but you should be prepared to discuss why you chose the particular coordinate reference system for this data. Relationships among tables should be indicated in the diagram.

When your normalization plan has been accepted, you may proceed to creating the normalization scripts for Milestone 3. You should also add the final ERD and a discussion of the structure of the data to your Final Report.

### Milestone 3: Normalization Scripts (10)

After your normalization plan is approved, you need to actually implement it. At this point in the course you will have completed Database Design Assignment 3, which involves creating an ETL process in SQL for a provided dataset. Milestone 3 involves doing the same thing for your project data. This involves writing SQL scripts which create all necessary tables, primary keys, foreign key references, etc. Lookup tables must be populated with data. Columns which are no longer necessary due to normalization should be dropped. Data may need to be moved from the base table to related tables.

There is a significant danger of your wasting a lot of time implementing a poorly conceived normalization plan. Do not begin this task until your normalization plan is approved (Milestone 2).

**Evaluation**

The following will be evaluated in class:

1. You execute  your normalization script. This will be one multi-statement SQL script with the necessary DDL and DML to create the final, normalized schema (based on Milestone 2) from your data as originally imported (in Milestone 1). You will have run this script previously while working on this assignment, so your script should clean (drop) previously previously created database objects before recreating them.

When the normalization scripts have moved your data to the final ERD, you can begin working on the analytical queries for Milestone 4. You should also include instructions on running the normalization scripts in an appendix of your final report.

### Milestone 4: Analysis and Optimization (10)

Construct three spatial analytical queries based on your data that represent interesting real world questions that could be answered with this data. These queries may combine the data with other spatial datasets. In order to focus on your primary dataset of interest, you should either (a) choose a second dataset that is not overly complex; (b) coordinate with another student who is working with data that you would like to analyze, and share your results from Milestones 1 – 3 with each other.

After constructing the analytical queries, time the results, and think about how the speed can be improved. You should consider the following options:

1. Rewrite the query using the query planner to help investigate.
2. Index columns that are included in joins or filters.
3. Denormalize your tables.

Regardless of whether you find indexing to be helpful for these particular queries, assess your tables for possible improvements using indexing. Which columns will frequently be used in joins or WHERE clause criteria? Create all indexes that you think are appropriate.

**Evaluation**

The following will be evaluated in class:

1. You execute the three analytical queries. If the results can be mapped, display the results in QGIS.
2. You show me any timings you did on the queries, and discuss how you optimized them.
3. You tell me what indexes you created and why.

### Milestone 5: Final Report (15)

The final report is a tutorial style report describing the dataset, the kinds of analytical questions it can be used to answer, and how to work with it. Much of the work from previous milestones will be repurposed here, but some of it will be briefer and some of it will need to be expanded. The report should be conversational, and assume an audience that it familiar with GIS and SQL.

The report should include some visualizations (constructed in a client software such as QGIS or R) of the data, and the analytical results.

The report should be structured so that DDL is relegated to appendices, while the body of the report describes the ETL process at a high level and goes into detail on the analytical process.

The report should include the following:

1. Describe the dataset generally, including its source and purpose. Describe some of the spatial questions you will use it to answer. If you combine your main dataset with other data for you analytical queries, describe those additional datasources, but more briefly.
2. Describe the structure of the data and your normalization process. Provide an ERD of the final schema.
3. Discuss optimizations such as index construction or denormalization.
4. Provide the 3 analytical queries that you developed for Milestone 4. Use only the final, optimized version of each query. For each query, begin by describing the question you are trying to answer, followed by the query itself, followed by a discussion of how the query works. The discussion of the query operation should assume the reader understands basic SQL, but you should explain the spatial operations. Explain any subqueries, CTEs, spatial functions or operators, and complex joins.
5. Your ETL process should be documented in appendices:
    a. One appendix should provide a detailed explanation of how to obtain and load the data.
    b. A second appendix should include your normalization scripts submitted as Milestone 3.
    c. A third appendix should include scripts (if any) for further transformations of your data, such as denormalizations or index construction.
    d. A final appendix should include your data dictionary (summary of all columns, by table, including data type and extremely brief description; make sure to include units for numerical data).

I highly recommend creating the report in Markdown. All queries should appear formatted as code. Do not submit a report with screenshots of any SQL queries.


