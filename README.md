-------------
Project setup
-------------


---------
JDK setup
---------
Download and install jdk-17.0.2


---------
IDE setup
---------
Download and install Apache NetBeans IDE 13

Create a new project with name 'bank management system'

Create the java files as mentioned in the repository


--------------
Database setup
--------------
Download and install mySQL workbench 8.0 CE  and proceed as mentioned below-


-----------------------------
Connecting Database with java
-----------------------------

Add the below files (provided in repository) to the library of the project 'bank management system'

jcalendar-tz-1.3.3-4.jar

mysql-connector-java-8.0.28.jar

----------------------------------------------------
Database Queries for BANK MANAGEMENT SYSTEM Project
----------------------------------------------------

1 - Create database with name 'bankmanagementsystem' in mysql

create database bankmanagementsystem;

2 - Select the database you just created

use 'bankmanagementsystem';

3 - Create our first Table in the selected database with name signup

create table 'signup' with attributes:

formno varchar(20), name varchar(20), father_name varchar(20), dob varchar(20), gender varchar(20),email varchar(30),
marital_status varchar(20), address varchar(40), city varchar(25), pincode varchar(20), state varchar(25);

4 - Create the second table to store more information of user

create table 'signup2' with attributes:

formno varchar(20), religion varchar(20), category varchar(20), income varchar(20), education varchar(20),
occupation varchar(20), pan varchar(20), aadhar varchar(20), seniorcitizen varchar(20), existingaccount varchar(20);

5 - Create the third table to store the account information of user

create table 'signup3' with attributes:

formno varchar(20), accountType varchar(40), cardnumber varchar(25), pin varchar(10), facility varchar(300);

6 - Create the Login table to store login information

create table login with attributes:

formno varchar(20), cardnumber varchar(25), pin varchar(10);

7 - Now create bank table to store transactions related information 

create table 'bank' with attributes:

pin varchar(10), date varchar(50), mode varchar(20), amount varchar(20);





