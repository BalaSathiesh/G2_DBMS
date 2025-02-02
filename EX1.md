# EXP/ NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## Date: 4/8/23

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
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```

### OUTPUT:
![image]![image](https://github.com/BalaSathiesh/G2_DBMS/assets/128462891/20f30f9b-1403-4467-ba8a-79672bc1b46e)


### 2) Change the above student table by adding another attribute department
### SQL QUERY: 
```
alter table student add department char(30);

```
### OUTPUT:
![image](https://github.com/BalaSathiesh/G2_DBMS/assets/128462891/67b186a8-63a8-4156-82ed-aec2ebebd375)




### 3) Drop the student table
### SQL QUERY: 
```
drop table student;

```
### OUTPUT:
![image](https://github.com/BalaSathiesh/G2_DBMS/assets/128462891/9ac144cb-48e4-449a-b0b4-41224cc6cde9)


### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;

```
### OUTPUT:
![image](https://github.com/BalaSathiesh/G2_DBMS/assets/128462891/1f038aff-2fc5-448f-879d-cd155e55c717)


### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;

```
### OUTPUT:
![image](https://github.com/BalaSathiesh/G2_DBMS/assets/128462891/6cbb6795-04a6-416a-8570-2f0ae60a4018)


### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
