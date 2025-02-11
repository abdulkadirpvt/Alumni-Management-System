# Alumni Management System Database.

1. To create database
create database alumni;

2. To use created database
use alumni;

4. To create Login table
create table login(enrollment varchar(15)primary key,name varchar(15),password varchar(10),user varchar(10));

5. To create info table
create table info(enrollment varchar(15)primary key,name varchar(20),mobile varchar(10),email varchar(30),course varchar(15),college varchar(50),passingyear int,jb varchar(20),cc varchar(20), desig varchar(20),address varchar(30),city varchar(15));

admin data
insert into login values('','Abdul','admin123','Admin');
