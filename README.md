# Bank-Management-System

PROJECT SYNOPSIS

A fully automated basic Bank Management System built using Python and MySQL, has been designed keeping in mind the objective facilitate a fully computerized automated system over the existing manual system. It has been observed that the present system contains many loop-holes which lead to faulty system outputs and data redundancy. Lots of manual/handwritten processes are involved in the current system which have been improved and converted to automated forms to produce error-less outputs.

The proposed system has the following silent features:
1. All the modules are loosely coupled and highly cohesive.
2. Lesser user intervention is achieved.
3. Variety of reports generation introduced.
4. Hassle free data entry.


DBMS: MySQL

Host : localhost

User: root 

Pass: root 

DataBase: Bank 

SQL COMMANDS TO CREATE BOTH TABLES :

1) Account table:

mysql> CREATE TABLE ACCOUNT(

Accno INT(15) NOT NULL PRIMARY KEY,

Name VARCHAR(25) NOT NULL,

Age INT(5) NOT NULL,

Occu VARCHAR(15) NOT NULL,

Address VARCHAR(50) NOT NULL,

Mob BIGINT NOT NULL,

Aadharno BIGINT,

amt DOUBLE(20,5),

AccType VARCHAR(15) NOT NULL );


2) Amt table:

mysql> CREATE TABLE amt(

Accno INT(15),

Amtdeposit DOUBLE(20,5),

month VARCHAR(15) NOT NULL );
