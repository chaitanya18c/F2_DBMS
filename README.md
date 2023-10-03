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
![Screenshot 2023-10-02 203221](https://github.com/Adhithyaram29D/F2_DBMS/assets/119393540/e6cb9b88-0de6-4b6b-9415-8309f456d714)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department varchar(4);

### OUTPUT:

![Screenshot 2023-10-02 203409](https://github.com/Adhithyaram29D/F2_DBMS/assets/119393540/2d7244ab-c40d-48cd-a2b7-ddd4662aec60)

### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![Screenshot 2023-10-02 203543](https://github.com/Adhithyaram29D/F2_DBMS/assets/119393540/8a20bdb5-ddf5-4aa4-89f7-466e82bf054e)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![Screenshot 2023-10-02 204108](https://github.com/Adhithyaram29D/F2_DBMS/assets/119393540/374dc94c-1518-45f5-ab73-2033e223294b)

### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to student;

### OUTPUT:
![Screenshot 2023-10-02 204156](https://github.com/Adhithyaram29D/F2_DBMS/assets/119393540/9614eea4-5444-4149-9733-6e2e670c055c)

### Result:
To create a student database and execute DDL queries using SQL is executed successfully.
