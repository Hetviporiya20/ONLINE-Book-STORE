This Website is built for following purpose:-** 
- For Selling books online.
- Maintaining books selling history. -
- Adding and managing books. -
- User Friendly. -
- For Implemention of Generic Servlets in Java. -
This is a Mini-project developed using Java, Jdbc, And Generic Servlets.
Admin Have Following Access for this online store site:
- Add New Books.
-View Books Available.
-Remove Books.
-Increase Books Amount.
Users Have Following Access for this online store site:-
-Create New Account or Register.
-Login.
-View Available Books.
-Select Books to Buy.
-Select Books Quantity.
-Buy Books.
-Get Payment Receipt.
Technologies used:-
Front-End Development:
-Html.
-Css.
-Javascript.
Back-End Development
-Java [JDK 8+]
-Servlet
-MySQL
-Database used.
-MySql
Software And Tools Required
-MySQL
-Eclipse [Enterprise Edition]
-Java [JDK 8+]

##Dummy Database Initialization
_______________________________________________________

create database onlinebookstore;

use onlinebookstore;

create table books(barcode varchar(100) primary key, name varchar(100), author varchar(100), price int, quantity int);

create table users(username varchar(100) primary key,password varchar(100), firstname varchar(100),
    lastname varchar(100),address text, phone varchar(100),mailid varchar(100),usertype int);

insert into books values('10101','C','James',500,5);
insert into books values('10102','Java','Scott ',150,13);
insert into books values('10103','Database','Charles',124,360);
insert into users values('User','Password','First','User','My Home','42502216225','User@gmail.com',2);
insert into users values('Admin','Admin','Mr.','Admin','Haldia WB','9584552224521','admin@gmail.com',1);
insert into users values('mgmg','mgmg','Mgmg','u','high','1236547089','mgmg@gmail.com',2);

commit;
____________________________________________________________
