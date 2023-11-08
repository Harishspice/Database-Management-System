# EXP NO 1 : DATA DEFINITION LANGUAGE COMMANDS IN RDBMS

## DATE : 03/08/23

## AIM :

To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language) :

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

## List of DDL commands :

CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). 

DROP: This command is used to delete objects from the database.

ALTER: This is used to alter the structure of the database. 

TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. 

RENAME: This is used to rename an object existing in the database.

## Query :

### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY :
```
create table student(rollno numeric(10),name char(10),age numeric(5),
address varchar(25),phoneno numeric(15));
```
### OUTPUT :

![D11](https://github.com/Abrinnisha6/G2_DBMS/assets/118889454/63d9d766-c801-4c45-8753-eb31efb4a28e)

### 2) Change the above student table by adding another attribute department.

### SQL QUERY :
```
alter table student add department varchar(15);
```
### OUTPUT :

![D12](https://github.com/Abrinnisha6/G2_DBMS/assets/118889454/86ffd4da-0eac-4ed4-b81d-31cf92739588)

### 3) Drop the student table.

### SQL QUERY :
```
drop table student;
```
### OUTPUT :

![D13](https://github.com/Abrinnisha6/G2_DBMS/assets/118889454/34decc85-11d7-46e4-b71f-b639c322f9d9)

### 4) Delete the student table using truncate keyword.

### SQL QUERY :
```
truncate table student;
```
### OUTPUT :

![D14](https://github.com/Abrinnisha6/G2_DBMS/assets/118889454/fd65bc49-0406-441d-9a5d-270aad6155ed)


### 5) Rename the student table to mystudent.

### SQL QUERY :
```
rename table student to mystudent;
```
### OUTPUT :

![D15](https://github.com/Abrinnisha6/G2_DBMS/assets/118889454/8f7bdfde-5e4d-4a81-a4e0-f7b54c975518)

## RESULT :

The queries got the output and statifies the given question.
