# EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands

## AIM :

To create a database and execute DDL queries using SQL.

## DDL (Data Definition Language) :

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.

## List of DDL commands :

INSERT : The insert command is used for inserting one or more rows into a database table with specified table column values. 

UPDATE : The UPDATE command in SQL is used to modify or change the existing records in a table. If we want to update a particular value, we use the WHERE clause along with the UPDATE clause. If you do not use the WHERE clause, all the rows will be affected.

DELETE : SQL is a part of the Data Manipulation Language, a sub-language of SQL that allows modification of data in databases. This command is used to delete existing records from a table.


## Query :

INSERT: It is used to insert data into a table.

## SQL QUERY :

insert into employee1 values('nisha',19,'AI&DS');
insert into employee1 values('brindha',19,'AI&DS');
insert into employee1 values('yogi',18,'AI&DS');
insert into employee1 values('pavi',18,'AI&DS');

## OUTPUT :

![Screenshot 2023-09-25 215150](https://github.com/Abrinnisha6/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118889454/a621c8da-f19a-4d13-8425-ef9682166a02)

## Query :

UPDATE: It is used to update existing data within a table.

## SQL QUERY :

UPDATE employee1 SET name='mercy' WHERE age=18;

## OUTPUT :

![Screenshot 2023-09-25 215326](https://github.com/Abrinnisha6/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118889454/f8f720a0-720b-40cb-8d19-74f6bda4fb45)

## Query :

DELETE: It is used to delete records from a database table.

## SQL QUERY:

DELETE FROM employee1 WHERE name='mercy';

## OUTPUT:


![Screenshot 2023-09-25 215451](https://github.com/Abrinnisha6/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118889454/81da491d-a48b-4b36-8c53-f4def86931dc)

## RESULT :

Thus the all the queries got the output.






























