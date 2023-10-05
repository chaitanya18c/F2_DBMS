# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
create table student(rollno numeric(4), name varchar(50), age numeric(2),
address varchar(10), phoneno numeric(10));
### OUTPUT:
![1](https://github.com/chaitanya18c/F2_DBMS/assets/119392724/13a8bdd4-aa0c-4851-b9e9-77498857dd4e)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department varchar(4);

### OUTPUT:
![2](https://github.com/chaitanya18c/F2_DBMS/assets/119392724/054ac71f-b9fe-46e7-b046-5963b5525820)

### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![3](https://github.com/chaitanya18c/F2_DBMS/assets/119392724/a25cd0e3-ac55-4a2f-88e1-297346d9cd56)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![4](https://github.com/chaitanya18c/F2_DBMS/assets/119392724/44e4b5de-2760-4776-adeb-1412433ef304)

### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to student;

### OUTPUT:
![5](https://github.com/chaitanya18c/F2_DBMS/assets/119392724/524d9009-62ef-4939-9f64-923d59a19fca)

### Result:
To create a student database and execute DDL queries using SQL is executed successfully.
