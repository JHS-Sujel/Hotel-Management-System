Project: Hotel Management System In Java

Hotel Management System is a desktop based application made using Swing, a concept of Java Core and Database I have used is MySQL.
This project to build a Desktop based application using Swing.

Language Used -  Java Core 

Concept Used - Swing

Database Used - MySQL

IDE Used - Netbeans

Hotel management system is a free and open source project. 
This application is pretty simple and easy to use. 
The whole system is built in Java programming language with the help of NetBeans IDE. 
Also to make records available for future use it’s back-end is hms database. 
This is simple yet complete hotel management system. 
This system performs all the necessary tasks that a hotel application performs.

About The System

Talking about the system, it lacks one basic thing that is the login panel for the administrator. 
You can simply add the login panel to make it more secure and private. 
The system is all from the admin side. 
Admin has the full access to the system. 
The user can only book and reserve hotel rooms. 
The user can either book room which is paid, 
or can reserve the room for later confirmation 
or simply can book rooms. After that, 
then the user can make payments and the admin and the application generates the payment invoice.
Not only this the admin can easily add rooms and its services types. 
The admin can create many other facilities required for the guests in a hotel. 
Also, the user can book other miscellaneous activities in the hotel booking system. 
As a whole, this system is very much effective and user-friendly.

How to run?

Open your NetBeans and mysql

create database myhotel;

use myhotel;

create table login(username varchar(40), password varchar(40));

insert into login values('admin','12345');

create table customer(id varchar(30), number varchar(30), name varchar(30), gender varchar(30), country varchar(30), room_number varchar(30), status varchar(30), deposi varchar(30));

create table room(room_number varchar(20), availability varchar(20), clean_status varchar(20), price varchar(20), bed_type varchar(30));

create table employee(name varchar(30), age varchar(10), gender varchar(30), job varchar(30), salary varchar(30), phone varchar(30), aadhar varchar(30), email varchar(40));

create table driver(name varchar(30), age varchar(10), gender varchar(20), company varchar(30), brand varchar(30), available varchar(10), location varchar(50));

create table department(department varchar(30), budget varchar(30));

Run your project 
You must follow this content otherwise you can't run the project 
1. Add your library: MySQL JDBC Driver
 2. Add JAR in your library:  rx2xml.jar

ALl classes you must be included in the package named hotel.management.system

To create a new folder 📁 
Hotel->Management->System-> 📁 













