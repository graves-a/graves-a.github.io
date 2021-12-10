---
title: "Alan Graves's ePortfolio"
---  
<h1 align="center">
  About Me
</h1>
Hello, I’m Alan Graves.
I started my journey to become a Software Engineer at the end of 2018. For most of my career, I’ve been an electronics technician/engineering technician where I built, tested, and troubleshooted electronic devices in aviation, oil and gas, and most recently, consumer electronics. It wasn’t until I joined the Engineering department and saw the products being developed that inspired me to go to school to become a Software Engineer. Throughout the computer science program at SNHU, I mainly used Java and Python with a little C/C++ here and there. After starting my internship with the high-level team at Garmin, I really grew to love C++. I am now in my final term for my Bachelor’s of Computer Science with a concentration in Software Engineering.

## Java
I am confident in my skills with Java as that is the programming language I’ve spent the most time with throughout the computer science program. I’ve made several programs in the various courses as well as some outside of school. This was the language of choice when doing coding problems on CodeForces to work on my problem-solving skills. I also have some experience with android development where I made a tile game

## Python
Python is the second language I have the most experience with as many classes I took at SNHU used Python. I’ve written several programs both for school and outside of school as well as a program I used while I was an engineering technician to help with radiated emissions testing during data transfer to and from the device under test.

## C++
I don’t have as much experience with C++ as I do with Java and Python, but it is becoming my language of choice here recently. I only had a few classes that were in C++ such as the data structures and algorithms class and OpenGL, but I really started enjoying it during my internship. I have around three months of experience, not including schoolwork, developing in C++ where I worked on elements of the GUI for consumer products as well as speech recognition.

<h1 align="center">
  Project 1: Zoo Authentication
</h1>
<div align="center">
  <a href="https://github.com/graves-a/Zoo_Authentication">GitHub</a>
</div>

Zoo Authentication is an app written in C++ that utilizes sqlite3. It stores usernames and encrypted passwords using SHA2 in the database. When the user logs in, they are able to see their "role" at the zoo as well as update their role, their username, and their password. This app was originally written in Java and the user information and roles were stored in plain text files with no encryption or input validation. I wanted to convert it to C++ to get more experience with that language.

The Zoo Authentication app was created in IT-145 during my first few terms of the computer science program. The main goal of the application was to have a user log in with a username and password, check those credentials against a plain text file and return their "role" from a different text file. I chose to include this project in my portfolio because it has the potential to be used in a real world environment. Some improvements that were made are the SHA2 encryption of the password as well as hiding the password when the user is typing it to enhance security as well as validating user input, converting where the data is stored from text files to a sqlite3 database, and added functionality such as the ability to create a new user, update their role, change their username, and change their password. The program was also converted from Java to C++. The main challenge when enhancing this project was converting it from Java to C++ as C++ isn't my specialty. Also, this was the first time I've built a program from the ground up. 
<div align="center">
  <img src="https://raw.githubusercontent.com/graves-a/graves-a.github.io/master/docs/assets/Zoo_main.jpg">
</div>

<img src="https://github.com/graves-a/graves-a.github.io/blob/master/docs/assets/Zoo_3.png">

<h1 align="center">
  Project 2: Data structures
</h1>
<div align="center">
  <a href="https://github.com/graves-a/Data_Structures">GitHub</a>
</div>

Data Structures is an app written in C++ that allows you to see the time complexity of the different data structures and alogirthms. It is included with a csv file that has around 18,000 entries from a fake auction with details such as bidID, the name of the item, the fund, and the winning bid amount. You are able to load the csv file into a vector, linked list, hash table, and binary search tree. Each time the csv file is loaded, it will tell you how long it took to load all entries as well as the total entries loaded. From here you can do things such as search for an entry, order the entries, delete and entry, and display all entries to the console.

The Data Structures app was created in CS-260 during the summer of 2020. The original program was a series of small programs, one for each data structure that would display the time it took to load data into those strucutres and how long it took to search for a particular item. Some enhancements that were made are combining all the smaller programs into one large one and increasing the amount of items being stored from 140 to around 18,000 to get a better idea of the time the different data strucutrues take. I also cleaned up the code by adding more descriptive comments and removing unnecessary ones as well as improved the naming conventions of some of the variables. A challenge I faced when making this program was with the binary search tree. I was hitting stack overflow errors when trying to load that many items and I found out that the csv file was pretty much already in order making the tree unbalanced.

![Data Structures example](https://github.com/graves-a/graves-a.github.io/blob/master/docs/assets/Structures_main.jpg)

<h1 align="center">
  Project 3: Database creator
</h1>
<div align="center">
  <a href="https://github.com/graves-a/Database_Creator">GitHub</a>
</div>

Database Creator is an app written in C++ that utilizes sqlite3. When the app is first launched, you are given two choices to either create a new database or access an existing one. If you choose to create a new one, it will then prompt you where to save the database. If you choose to access an existing database, you will enter the location of the database and then be greated with the tools needed to maintain it. You can create new tables, get a list of existing tables, insert data into any table, update data, remove entries, and delete the entire table.

Database Creator is an app from DAD-220. The app started off as just a list of SQL commands to showcase my knowledge in SQL. I have taken those commands and created a new user interface that utilizes database manipulation and is written in C++ and uses sqlite3. The user is now able to create a new database and specify where that database will be stored. Once a database is selected, they can create a new table or manipulate an existing one. They can add as many columns to the table as they desire. They see a list of available tables as well as search for an entry, update an entry, and delete an entry. The user can also see all entries in a table as well as delete a selected table. A challenge I faced when making this was how to handle the table information such as the table name along with the name of the columns to make it easier to enter new entries into a table. I started off with a structure that held a column count as an integer, a vector of strings for the columns and a vector of table names. I later decided to just go with an unordered map with the key being the table name the the data being a vector of column names. To make it easier to display and selet the table, I also have a vector of the table names.

![Database Creator example](https://github.com/graves-a/graves-a.github.io/blob/master/docs/assets/Database_main.jpg)

