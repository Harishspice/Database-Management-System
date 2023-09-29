# EXP 1: DATA DEFENITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

## List of DDL commands: 

CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.

## Query:
1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
CREATE TABLE STUDENTT(rollno INT PRIMARY KEY,name1 VARCHAR(255),age INT,address VARCHAR(255),phoneno VARCHAR(15));

### OUTPUT:
![image](https://github.com/Harishspice/Database-Management-System/assets/117935868/be69f271-ddfe-46ca-8b46-e8b3a5e75eb7)

2) Change the above student table by adding another attribute department


### SQL QUERY: 
ALTER TABLE STUDENTT ADD dept VARCHAR(50);

### OUTPUT:
![image](https://github.com/Harishspice/Database-Management-System/assets/117935868/b4839039-c99a-4e52-9af5-5d5c03837a5a)


3) Drop the student table

### SQL QUERY: 
 DROP TABLE STUDENTT;

### OUTPUT:
![image](https://github.com/Harishspice/Database-Management-System/assets/117935868/e5f80cf2-1309-4c44-a663-aea6719866cb)


4) Delete the student table using truncate keyword

### SQL QUERY: 
TRUNCATE TABLE STUDENTTT;

### OUTPUT:
![image](https://github.com/Harishspice/Database-Management-System/assets/117935868/5abdc2a9-393e-4d4d-8823-5476e31ffbe7)



5) Rename the student table to mystudent

   
### SQL QUERY: 
ALTER TABLE STUDENTT RENAME TO mystudent;


### OUTPUT:
![image](https://github.com/Harishspice/Database-Management-System/assets/117935868/3f1960c8-15ee-4535-8e6d-f6aadea78ab6)



