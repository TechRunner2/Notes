Database Theory & Application
========================
Database => relational database
	  \/
	Tables

# Vocabulary:
	- Data
	- Index
	- Instance
	- Tables
	- DDL
		- Data Definition Language
		- Defining Schema
			- Database Structure
	- DML
		- Data Manipulation Language
	- DMS
		- Database Management System
			- Oracle
			- DB2
			- SQL Server
			- MS Access
			- My SQL
		1. GUI
		2. SQL
			1. DML
			2. DDL
	- Database properties
		- endurability
		- atomicity
		- isolation
	- Schema
		- Table, Colum, row, keys
	- ERP
		- Enterprise Resource Planning
	- SAP
		- System Application Production
	- DBMS roles
		- user
		- administrator
		- developer



| id | name | Age | gender |
|:---:|:---:|:---:|:---:|
| 1	| Brandon | 21 | M |
| 2	| Wade | ?	| M |
| 3	| Noah | ?	| M |

accdb -> MS Access

MYSQL -> sql

1. create new database & define schema
2. Support the storage of data
3. enable durability

## 3 properties of database
1. endurability
2. isolation
	- Concurrency Control

3. atomicity
	- autonomy
	- Transaction control
	- Seperation

## Data Size
Kila = 10^3 <br>
Mega = 10^6 <br>
Giga = 10^9 <br>
Tera = 10^12 <br>
Peta = 10^15 <br>

## Code
- SELECT ID, NAME, GENDER FROM STUDENT;
    - select * from student;

SQL -> Query Compiler -> 
query plan -> execution engine -> index manager ->
buffer manager -> storage manager -> DBMS


## Business Intelligence
- tools
	- Excel
	- SPSS
	- SAP

## Query Compiler
1. Query Processor
2. Query Preprocessor
3. Query optimization

## SQL
1. DDL (Schema)
	- Database structure
2. DML (Query)

Data model: A notion for describing data or information

Collect Data -> Filtered Information -> Az, Machine learning Knowledge

Database -> Schema (DDL, Database model) -> Constraints ( Limitations )

- Data model
	1. Relational data model ( Most popular )
	2. Semistructured data model
		- Tree, graph, ...



two fields -> Primary Key = Composite key
Composite keys consist of 2 or more fields[' ]

## Database building process
### Forward Engineering
1. Collect requirements from customers
2. Create model
3. Create tables
4. Insert data

### Reverse Engineering


## Schema Layout
Schema = database structure

set of attributes

database schema

set of schemas


## MS Access
1. Modeling -> relationship
2. database building -> Dabase sheet view, Design view
3. Query (DML SQL)
4. Application -> (Form view, Layout view, form design view)

# SQL commands
```sql2
select (field)
from (table)
```
```
//Multiple table query
Join 
```

# SQL images
- Command-line Clinet
- image.sql
```sql
CREATE TABLE tbl_snack(
	no INT PRIMARY KEY NOT NULL,
	name VARCHAR(45) NOT NULL,
	img BLOB NOT NULL
);
```

```sql
INSERT INTO tbl_snack
	VALUES(1, "coke", "C:\SQL_EX\coke.jpg");
```

```sql
INSERT INTO tbl_snack
	VALUES(2, "taco", "C:\SQL_EX\taco.jpg");
```

```sql 
INSERT INTO tbl_snack
	Values(3, "hamburger", "C:\SQL_EX\hamburger.jpg");
```
## Enumeration
### SET

```sql
CREATE TABLE setTest(
	attrib SET('bold', 'italic', 'underline')
);

INSERT INTO setTest(attrib)
	VALUES('bold');

INSERT INTO setTest(attrib)
	VALUES('bold', 'italic');
```
### ENUM
```sql
Create table enumTest(
	Color ENUM('red', 'green', 'blue')
);

INSERT INTO enumTest(color) VALUES('red');
INSERT INTO enumTest(color) VALUES('gray');//Wrong
INSERT INTO enumTest(color) VALUES('red', 'green');//Wrong
```


# Backup database in workbench

- Environments
	- CLI
		```shell
		mysqldump -u root -p $database > $database.sql
		```
	- GUI

# Relationships
- 1:1
	- One to one
- 1:N
	- One to Many
- N:N
	- Many to Many

## HAS-A Relationships
- The relationships we have been discussing are known as HAS-A relationships:
	- Each entity instance **has a** relationship with each other


