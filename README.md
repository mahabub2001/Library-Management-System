# Library-Management-System


Library_Management_System Database command.
we used XAMP server.

1.create database library_ms

2.create table users(id int PRIMARY key AUTO_INCREMENT not null,name varchar(100),password varchar(100),email varchar(100),contact varchar(100));

3.create table book_details(book_id int PRIMARY key not null,book_name varchar(100),author_name varchar(100),quantity int);

4.create table student_details(student_id int PRIMARY key not null,student_name varchar(100),course varchar(50),branch varchar(50));

5.create table issue_book_details(id int PRIMARY Key AUTO_INCREMENT not null,book_id int,book_name varchar(50),student_id int,student_name varchar(50),issue_date date,due_date date,status varchar(50));
