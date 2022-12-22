# Syllabus

Meeting:

 * Thurs 5:30pm - 8pm, Gladfelter 847

Instructor Info:

* Prof. Lee Hachadoorian
* 104 Gladfelter Hall – In GIS Studio, enter 103A
* [Lee.Hachadoorian@temple.edu](mailto:Lee.Hachadoorian@temple.edu)
* Office Hours:
    * Monday 1-2pm (office, virtual)
    * Tuesday 1-2pm (virtual only)
    * Wednesday 1-2pm (office only)

# General Information

## Purpose of the Course

This course is an introduction to the design and management of spatial databases. The relational database model underlies most modern databases. Because of increasing demand to store, analyze, and display geographic data, many major RDBMSes have added spatial features. The course will begin with (nonspatial) database theory and practice, including SQL (Structured Query Language, the language specification that underlies most RDBMSes), the database design process, normalization, and entity-relationship diagramming. It will then move on to spatial data types, spatial indexing, and spatial querying. Specific issues related to spatial data storage, including denormalization, will be addressed.

The course will use PostGIS, a spatial extension to the open source PostgreSQL RDBMS. SQL and the SQL/MM Spatial extension, moreso than other programming languages, are widely adopted standards, and the use of any particular implementation will introduce skills that will be directly portable to other implementations, including Oracle, SQL Server, and SpatiaLite/SQLite.

At the end of the course students are expected to know how to design relational and object-relational schemas for GIS databases, implement database designs in spatial database management systems (RDBMS), and retrieve and manage spatial data in a GIS database. If time permits, we will also discuss recent trends such as unstructured data and column-oriented databases.

## Prerequisites

* Fundamentals of GIS (GUS 5062) or equivalent
* A laptop on which you can install software and data

## Attendance

This course meets once a week. Missing *any* class meetings will hamper your ability to complete the work in this course. Your attendance percentage will also indicate the maximum final grade you can earn in this course. If you miss 3 classes, you have attended 78.6% of class meetings. Accordingly, your final grade will not be higher than a C+, *regardless of any other work completed*. Please see my attendance policy at my Temple web page: https://sites.temple.edu/hachadoorian/specification-grading/.

## Text

* [PostGIS in Action, 3e](https://www.manning.com/books/postgis-in-action-third-edition), by Obe & Hsu
* [Relational Database Design and Implementation, 4e](https://www.elsevier.com/books/relational-database-design-and-implementation/harrington/978-0-12-804399-8), by Harrington
* The official [PostgreSQL Documentation](https://www.postgresql.org/docs/current/index.html)
* The official [PostGIS Documentation](https://postgis.net/docs/)


*PostGIS in Action* is available directly from the publisher at the link above. The publisher regularly runs sales. If you sign up for their Deal of the Day email far enough in advance, ***there is a good chance you will be able to purchase the text at 40%-50% off***. This is a very hands-on book, with many code examples and implementation recommendations, and you are required to purchase a physical copy. I expect that you will get significant use out of it even after the conclusion of the course.

*Relational Database Design and Implementation* is available to read online for free for the Temple community. Use one of the links from the Temple Library page for this book: <https://librarysearch.temple.edu/catalog/991037042739803811>. However, we will be reading most of the book, so purchasing a physical copy is probably a good idea. The publisher sells a print-on-demand version and often runs sales near the beginning of the semester. Use the link above to the publisher's book page.

The PostgreSQL Documentation is an excellent example of clear, readable software documentation. Since Postgres strives to be a standards-compliant implementation of SQL, the docs, in addition to providing instruction on how to use Postgres, make clear what the standard requires and where and why Postgres SQL sometimes diverges from it. I will be assigning sections from the documentation to read, but you should become familiar with it beyond the specifically assigned sections, as you will refer back to it over and over in your use of Postgres and PostGIS.

# Assignments

## Exercises

Exercises will be assigned each week during the first half of the semester. Only one problem from each exercise will be evaluated, and they will earn you bonus points in the quizzes track. We will go over select problems from the exercises at the beginning of the following class. In order to benefit from them, you must have completed them before we review them in class.

## DataCamp

Two DataCamp courses (approximately 4 hours each) will be assigned early in the semester. Completing them will earn you bonus points in the quizzes track.

## SQL Quizzes

Each topic will conclude with a short, graded SQL quiz, beginning with the third week of class. The quizzes will focus on analysis using SQL SELECT statements. The difficulty level should be comparable or easier than the take-home exercises, so if you complete the exercises, are present for in-class review, and review the problem and answer afterwards, you should be well-prepared for the quizzes.

The quizzes are cumulative. You will not be allowed to progress to the Quiz 2 if you do not pass Quiz 1.

## Homework

There will be three homework assignments focusing on database design, including entity-relationship diagrams (ERDs), normalization, and an ETL (Extract-Transform-Load) process. These will be the equivalent of a short paper in a writing-oriented course.

## Tutorial

Students will form into groups and to present advanced topics in geodatabases. Possible topics include:

* Raster storage and analysis (PiA Ch. 7 & 12; PostGIS docs Ch. 11, 12, 13)
* pgRouting (PiA Ch. 16.1; [documentation](https://docs.pgrouting.org/latest/en/index.html))
* NoSQL databases (RDD&I Ch. 28)
* Geocoding (PiA Ch. 10)

Students may select other approved topics based on their interests.

## Term Project

A more complex project involving planning and executing a database design. Requirements are available at <https://sites.temple.edu/spatialdb/term-project/>.

# Grading

You will earn points along several **tracks**. Each track is worth up to 100 points. Your must progress along ***ALL*** tracks to be successful in this course. Your final grade is based on the ***lowest*** score earned along any track.

Attendance
: 0-100 points. Your attendance score is a straight percentage of the class sessions you are present for.

SQL Quizzes (8)
: 34 + 10 points each for quizzes 1 through 5, and 3 points each for quizzes 6 through 8.

Exercises (8)
: ½ bonus point each added to the SQL Quizzes track.

DataCamp (2)
: 1 bonus point each added to the SQL Quizzes track.

Homework Assignments (3)
: 65 + 10 points for each assignment

Tutorial
: 70-100 points. The tutorial will be awarded up to 30 points based on requirements announced separately.

Term Project
: 50-100 points. The term project will be awarded up to 50 points based on requirements elaborated at https://sites.temple.edu/spatialdb/term-project/.

## Lecture

Each week will include about an hour of lecture. The lecture is intended, as much as possible, to be an interactive environment. Please feel free at any time during lecture to ask a question or make a comment. Conversely, you are expected to respond to discussion questions asked in class.

Lecture will cover some topics not covered in the texts. The lecture slides are not intended to substitute for attendance.

## Lab

The remainder of each class following the lecture will be devoted to hands-on exercises. During lab, students work on lab assignments that provide practical experience in applying the concepts learned in lecture.

## Disability Policy

This course is open to all students who meet the academic requirements for participation. Any student who has a need for accommodation based on the impact of a disability should contact the instructor privately to discuss the specific situation as soon as possible. Contact Disability Resources and Services at 215-204-1280 in 100 Ritter Annex to coordinate reasonable accommodations for students with documented disabilities.

## Academic Honesty

All submitted work should be your own. Please read my guide to Academic Integrity at <https://sites.temple.edu/hachadoorian/course-policies/>.

## Classroom Environment

All persons participating in the course should be respectful of other students and the instructor in order to facilitate a civil learning environment. All persons participating in the course have a right to expect respectful treatment in the classroom.

## Statement on Academic Freedom

Freedom to teach and freedom to learn are inseparable facets of academic freedom. The University has adopted a policy on Student and Faculty Academic Rights and Responsibilities (Policy # 03.70.02) which can be downloaded from http://policies.temple.edu/getdoc.asp?policy_no=03.70.02.

## Working with Other Students

I encourage students to work together on assignments and assist each other in understanding the course material. However, except for explicit group assignments, all contents of each student's work must be authored solely by that student.
