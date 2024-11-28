## SQL Assignment Week 1

# 1.Components of a DBMS(Database Management System)

(i).Hardware

- Physical devices necessary for the operation of the DBMS.i.e;Computers,Storage Devices,I/O.

(ii).Software

- encompasses all programs that manage and control the database.i.e;DBMS,Operating system,application program.

(iii).Data

- representing the raw facts stored within the database.Include operational data and metadata.

(iv).Procedures

- documented processes and rules that govern how data is managed within the DBMS.  
  Operational Procedures: Guidelines for using the DBMS effectively.
  Maintenance Procedures: Rules for backing up data and ensuring data integrity

(v)Database access Language

- languages used to communicate with database,e.g SQL

# 2.Relational Databases.

Relation database are type of database that organizes data into structured tables, which consist of rows and columns.  
Examples include MySQL,Oracle Database,Postgres,MariahDB.

# 3.Classifications of SQL.

(i).Data Defination Language(DDL)

- used to define and manage all database structures, including tables, indexes, and schemas. It is essential for setting up the database schema and modifying its structure.Common commands include ; CREATE,ALTER,DROP.

(ii).Data Manipulation Language(DML)

- focused on manipulating the data stored in the database. It allows users to insert, update, delete, and retrieve data.Common commands ; SELECT,INSERT,UPDATE,DELETE.

(iii).Data Control Language(DCL)

- used to control access to data within the database. It manages permissions and user access rights.

# 4.Difference between a Primary Key and a Foreign Key?

Primary key - is a unique identifier for each record in a database table. It ensures that no two rows can have the same value for this key, thus maintaining the uniqueness of each record.  
Foreign key - is a field (or collection of fields) in one table that uniquely identifies a row of another table. It establishes a relationship between the two tables by referencing the primary key of another table.

# 5.Entity-Relationship Diagram

a visual representation that illustrates the relationships between various entities within a database. It serves as a crucial tool in database design, helping to conceptualize the structure and organization of data.

# 6.Advantages of relational databases?

(i).Data Integrity and Accuracy
Relational databases enforce data integrity through constraints such as primary keys and foreign keys, ensuring that data remains accurate and consistent.

(ii).High Security
These databases provide robust security features, allowing for fine-grained access control. Users can be granted specific permissions to access certain tables or data, protecting sensitive information from unauthorized access.

(iii).Flexibility and Scalability
Relational databases support a flexible schema design, allowing changes to the database structure without disrupting existing applications.

(iv).Efficient Querying with SQL
The use of Structured Query Language (SQL) enables efficient querying and manipulation of data.

# 7.Data type used to store data in tables

(i)Numeric Data type - Include INT,FLOAT
(ii)Character - Incude CHAR,VARCHAR.
(iii)DATE - DATE,TIME.
(iv)Binary Data type - BLOB.

# 8.Purpose of a database management system (DBMS)?

(i).Data Storage and Retrieval
Provide a reliable platform for storing vast amounts of structured data. It enables users to create, read, update, and delete data efficiently, ensuring that information is easily accessible when needed.

(ii).Data Integrity and Consistency
A DBMS enforces rules and constraints that help maintain data integrity, ensuring that the data stored is accurate and consistent.

(iii).Security Management
Security is a significant concern in data management. A DBMS provides robust security features, allowing administrators to set permissions for different users based on their roles within the organization. This ensures that sensitive data is protected from unauthorized access and manipulation.

(iv).Concurrency Control
In environments where multiple users need to access and modify the database simultaneously, a DBMS manages concurrency effectively.
