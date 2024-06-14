# Student Management System

Student Management System v1.0 by Siddharth Kar

# Description - 
In this Project, we aim to solve the traditional Student management issues. The existing system provides a paper-based solution for keeping student records, but it gives overload to Teachers and Administrators. The main issues were inappropriate data keeping, and time wastage in storage. These issues are solved by providing separate student data, Keeping each student’s data separate and easy to access and update in a single click.

This project uses MYSQL as the backend and is developed in Java so it provides features such as platform independence, high performance, and security. It is a desktop application that uses Java Swing and JDBC connectivity frameworks.

It provides some enhanced features such as: an easy interface to add, remove, and update students as well as view students in a Graphical interface table. 

## Steps to configure & run this desktop application on your system:

1. To import this project to your system, you need to first install the following software & libraries: 
   - Eclipse for Java EE Developers and Tomcat server. You can refer to this video: https://youtu.be/9iHKCnxUWqQ
   - MySQL Workbench. You can refer to this video: https://youtu.be/OM4aZJW_Ojs

2. Then get the code from this GitHub repository on your system. You can clone this repository or download it as a zip file.

3. Choose the 'import existing maven project' option in Eclipse. 
<br> You can search for those steps online, just search 'how to import existing maven project in eclipse'. 

4. Then import the database files in your MySQL database. Database files are provided 
<br> You can refer to this video: https://youtu.be/9icY7xwXbJo

5. You can then run this desktop application on your local MySQL server. Make sure you edit the code & add your MySQL Database details.

## Technologies Used -

  
### 1. Back end Technologies:
  - Java JDBC 
  - Java Swing
  
### 2. Database:
  - MySQL
  
### 3. Project management tool:
  - Maven
  
### 4. Webserver:
  - Apache Tomcat

## Features-
  1. Home Page:
      - New Student() - Redirects to Registration Panel
      - Old Student() - Redirects to Search Panel
      - View all Students() - Redirects to View Panel
      
  2. Registration Page:
      - Name() - Add Student's name
      - Age() - Add Student's age
      - Percentage() - Add Student's percentage
      - Email() - Add Student's email address
      - Address() - Add Student's home address
      - Submit() - Collects the data from above jTextfield & updates it on MySQL Database using PreparedStatement query.
      - Clear() - Clears any text on jTextfield boxes. 
      
  3. View Page:
      - jTable() - Shows data in a Graphical Table. Data is retrieved from MySQL database using JDBC Connectivity.
      - ShowData() - used to trigger actionPerformedonClick which then runs the JDBC Connectivity code that executes query to SELECT * from student;
      - Clear() - Clears any text on jTable rows.
        
  4. Search Page:
      - Search() - Collects the RollNo from jTextfield box & runs a MySQL query that shows the student's data on jTable Box.
      - jTable() - Shows data in a Graphical Table. Data is retrieved from MySQL database using JDBC Connectivity.
      - Update Data() - Redirects to Update Page.
      - Delete Data() - Redirects to Delete Page
        
  5. Update Page:
      - Search() - Collects the RollNo from jTextfield box & runs a MySQL query that shows the student's data on jTextField Boxes.
      - Name() - Add Student's name
      - Age() - Add Student's age
      - Percentage() - Add Student's percentage
      - Email() - Add Student's email address
      - Address() - Add Student's home address
      - Update() - Collects the data from above jTextfield & updates it on MySQL Database using PreparedStatement query.
      - 
  6. Delete Page:
      - jTable() - Shows data in a Graphical Table. Data is retrieved from MySQL database using JDBC Connectivity.
      - Delete() - Collects the RollNo from jTextfield box & runs a MySQL query that delete the student's data on MySQL Database.
      - ShowTable() - It runs the jTable query that shows data in a Graphical Table. Data is retrieved from MySQL database using JDBC Connectivity.
      - ClearTable() - It runs a jTable query that clears any text on jTable rows.
   

## Program Images-

1. Home Page

![homepg](https://github.com/JeansPanT/Student-Management-System/blob/main/program_photos/Home.jpg)

2. Registration Page

![Regipg](https://github.com/JeansPanT/Student-Management-System/blob/main/program_photos/Registration.jpg)

3. View Page

![Viewpg](https://github.com/JeansPanT/Student-Management-System/blob/main/program_photos/View.jpg)

4. Search Page

![Searchpg](https://github.com/JeansPanT/Student-Management-System/blob/main/program_photos/Search.jpg)

5. Update Page

![Updatepg](https://github.com/JeansPanT/Student-Management-System/blob/main/program_photos/Update.jpg)

6. Delete Page

![Deletepg](https://github.com/JeansPanT/Student-Management-System/blob/main/program_photos/Delete.jpg)
