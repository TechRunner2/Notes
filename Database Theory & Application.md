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
