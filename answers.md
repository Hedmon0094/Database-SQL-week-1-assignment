
QUESTION 1: Components of a database management system
1. Hardware:
i)Physical Storage Devices: These include hard disks, SSDs, and other storage media that store the database files.
ii)Processing Units: CPUs that execute the DBMS software and process user queries.
iii)Input/Output Devices: Keyboards, mice, and monitors for user interaction.
iv)Network Devices: Routers and switches for connecting multiple systems and enabling remote access.
2. Software:
i)DBMS Software: The core software that manages the database, including data definition, manipulation, query, and control.
ii)Operating System: The underlying OS that provides the environment for the DBMS to run.
iii)Utility Programs: Tools for database administration, backup, recovery, and optimization.
3. Data:
i)Database: The collection of interrelated data, organized into tables, records, and fields.
ii)Metadata: Information about the data, such as data types, constraints, and indexes.
4. Database Access Language:
i)Query Language: A language used to interact with the database, such as SQL (Structured Query Language).
ii)Data Manipulation Language (DML): Used to insert, update, delete, and retrieve data.
iii)Data Definition Language (DDL): Used to create, modify, and delete database structures.
iv)Data Control Language (DCL): Used to grant and revoke access permissions.
5. Procedures:
i) Application Programs: Software applications that interact with the DBMS to perform specific tasks.
System Procedures: Built-in procedures provided by the DBMS for database administration and maintenance.
6. Users:
i)Database Administrators (DBAs): Responsible for designing, creating, and maintaining the database.
ii)Application Programmers: Develop applications that interact with the database.
iii)End-Users: Users who interact with the database through applications to perform specific tasks.


QUESTION TWO:RD  and examples
A relational database is a type of database that stores and organizes information into related tables.
Each table consists of rows and columns, with each row representing a record and each column representing a field. 
EXAMPLES: E-Commerce website database , Library database , University database and hospital database.


QUESTION THREE: SQL  and classification
1. Data definition Language(DDL):Used to define and modify the structure of a database.
Commands include:
CREATE: Creates a new database object like a table, index, or view.
ALTER: Modifies the structure of an existing database object.
DROP: Deletes an existing database object.
TRUNCATE: Removes all1 rows from a table, but retains the table structure
2. Data Manipulation Language(DML): Used to manipulate the data within a database.
Commands include:
INSERT: Adds new rows to a table.
UPDATE: Modifies existing data in a table.
DELETE: Removes rows from a table.
SELECT: Retrieves data from one or more tables.
3. Data Control Language(DCL):Used to control access to the database and its objects.
Commands include:
GRANT: Grants privileges to users or roles.
REVOKE: Revokes privileges from users or roles.


QUESTION FOUR:PK and FK
Primary Key:  A primary key is a column (or a combination of columns) that uniquely identifies each row in a table.
Foreign Key:A foreign key is a column (or a combination of columns) in one table that refers to the primary key of another table.


QUESTION FIVE: ERD
An Entity-Relationship Diagram (ERD) is a visual representation of how different entities (objects or concepts) in a database are related to each other.


QUESTION SIX: Advantages of RD
i) Data Integrity- Referential Integrity: Ensures that relationships between tables are maintained, preventing inconsistencies and data loss.   
Data Validation: Enforces data types and constraints to ensure accurate and reliable data.   
ii) Data Consistency- Reduced Data Redundancy: Data is stored in normalized tables, minimizing duplication and improving data consistency.   
Easier Data Updates: Changes made to data in one table are automatically reflected in related tables.   
iii)Data Security- Access Control: Allows for granular control over who can access and modify data.   
Encryption: Protects sensitive data through encryption techniques.
Backup and Recovery: Provides mechanisms for regular backups and disaster recovery.   
iv) Data Flexibility - Adaptability: Can easily accommodate changes in data requirements.   
Scalability: Can handle increasing amounts of data and users.
v) Data Independence - Logical and Physical Independence: Changes to the physical storage of data do not affect the logical view.



QUESTION SEVEN:Types of data stored in tables
i) Integer: Used to store whole numbers, both positive and negative.
Examples: INT, SMALLINT, BIGINT
ii) Decimal: Used to store numbers with decimal points.
Examples: DECIMAL(10,2), NUMERIC(15,4)
iii) Character: Used to store text data.
Examples: CHAR(10), VARCHAR(50)
iv) Date and Time: Used to store date and time values.
Examples: DATE, TIME, DATETIME, TIMESTAMP



QUESTION EIGHT: Purpose of DBMS
A Database Management System (DBMS) is a software system designed to manage and organize data efficiently.
Its primary purpose is to:   
1. Store and Organize Data:It provides a structured way to store large amounts of data.   
It organizes data into tables, rows, and columns, making it easy to manage and retrieve.   
2. Efficient Data Retrieval: It allows users to quickly search and retrieve specific data using SQL (Structured Query Language).   
It can generate reports and analyze data to gain valuable insights.   
3. Data Integrity and Security:It ensures data accuracy and consistency through data validation and constraints.   
It protects data from unauthorized access, corruption, and loss.   
It provides mechanisms for data backup and recovery.   
4. Data Sharing:   
It provides controlled access to data, preventing unauthorized changes.   
5. Data Independence: It separates the data from the applications that use it.
This allows for changes to the database structure without affecting the applications.


   


   

