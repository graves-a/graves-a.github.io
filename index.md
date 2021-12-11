---
title: "Alan Graves's ePortfolio"
---
<h1 align="center">
  About Me
</h1>
Hello, I’m Alan Graves.
For most of my career, I have been an electronics/engineering technician where I built, tested, and troubleshot electronic devices in aviation, oil and gas, and most recently, consumer electronics. Once I joined the consumer electronics industry and became a part of the design team, I was inspired to go to school to become an engineer. The Computer Science program at SNHU has taught me many things about being a software engineer. I have learned how to work in a team environment where I can effectively communicate with others, write descriptive comments on the code I write so other developers know how it functions, use appropriate naming conventions so it’s clear what that variable’s purpose is, and how to use Git to collaborate on a project as well as Scrum and the software development life cycle. 
During the program, there were two languages used the most and those are Java and Python, but I also have used C/C++ to develop embedded software, learn the different data structures and algorithms, and design 3-D graphics in OpenGL. I also learned how to make UML diagrams to show how a program will function which can be used to aid in development as well as later if another developer needs to get an understanding of how my code works. I also have learned about SQL databases using MySQL as well as sqlite3 to easily store data. Another key aspect I learned about software development is how to develop secure code such as validating user input to prevent buffer overflows and SQL injections as well as implementing the least number of privileges.


## Java
I am confident in my skills with Java as that is the programming language I’ve spent the most time with throughout the computer science program. I’ve made several programs in the various courses as well as some outside of school. This was the language of choice when doing coding problems on CodeForces to work on my problem-solving skills. I also have some experience with android development where I made a lights out game, inventory app, band database app, dice roller app, and to-do list app.

## Python
Python is the second language I have the most experience with as many classes I took at SNHU used Python. I’ve written several programs both for school and outside of school as well as a program I used while I was an engineering technician to help with radiated emissions testing during data transfer to and from the device under test.

## C++
I don’t have as much experience with C++ as I do with Java and Python, but it is becoming my language of choice here recently. I only had a few classes that were in C++ such as the data structures and algorithms class and OpenGL, but I really started enjoying it during my internship. I have around three months of experience, not including schoolwork, developing in C++ where I worked on elements of the GUI for consumer products as well as speech recognition.

<div align="center">
  <img src="https://raw.githubusercontent.com/graves-a/graves-a.github.io/master/docs/assets/Skills.png" width="600" height="169">
</div>

<h1 align="center">
  Project 1: Zoo Authentication
</h1>
<div align="center">
  <a href="https://github.com/graves-a/Zoo_Authentication">GitHub</a>
</div>

The Zoo Authentication app was created in IT-145 during my first few terms of the computer science program. The main goal of the original artifact was to have a user log in with a username and password, check those credentials against a plain text file, and return their “role” from a different text file and was written in Java. I chose this artifact to include in my portfolio because it has the potential to be used in a real-world environment. Some improvements that were made are encrypting the user’s password with 256-bit encryption as well as hiding the input while the user is typing their password. I also added input validation to prevent buffer overflow as well as to stop a SQL injection. Another improvement I made was changing from text files to a sqlite3 database to store the credentials and the roles. Some new features I added are the ability to create a new user, update the user’s role and change their username/password. The application was also converted to C++. Some challenges I faced were incorporating the sqlite3 database and making sure the user input was correct as well as converting from Java to C++ as C++ isn’t my specialty. Also, since the original application was designed to be used with text files, I had to redesign the majority of the program.
<div align="center">
  <img src="https://raw.githubusercontent.com/graves-a/graves-a.github.io/master/docs/assets/Zoo_main.jpg">
</div>

<h1 align="center">
  Project 2: Data structures
</h1>
<div align="center">
  <a href="https://github.com/graves-a/Data_Structures">GitHub</a>
</div>

The Data Structures app started as a series of single-file applications that would show the time complexity of each data structure and was created in CS-260 during the summer of 2020. Each application would take in a CSV file with about 140 entries, add those entries to the data structure and show the time it took to load them as well as to search for a specific entry. Some enhancements I made are combining them all into an interactive program where the user gets to choose which data structure they would like to utilize as well as increasing the entries to around 18,000 to get a better understanding of the performance differences between the different structures. I also cleaned up the code to get rid of repetitive code, add descriptive comments, improved the variable names, and remove unnecessary comments. A challenge I faced was with the binary search tree causing stack overflow problems when trying to incorporate the larger number of entries. I later realized that the CSV file had the entries pretty much in order already which was causing the tree to be unbalanced. Randomizing the entries solved this problem.
<div align="center">
  <img src="https://raw.githubusercontent.com/graves-a/graves-a.github.io/master/docs/assets/Structures_main.jpg">
</div>

<h1 align="center">
  Project 3: Database creator
</h1>
<div align="center">
  <a href="https://github.com/graves-a/Database_Creator">GitHub</a>
</div>

The Database Creator app was the most fun to develop as it was designed from the ground up. The original artifact was just a list of SQL commands from DAD-220. I decided to take my knowledge of SQL and create a user interface that could be used in the real world, allowing someone to maintain a database without any SQL knowledge. This artifact is written in C++ and utilizes sqlite3. The user can create a new database when on the main screen or access an existing one. Once in an existing database, they can create new tables, specifying how many columns they need for that table and then choose the name of each column. Once a table is created, they can list available tables, insert an entry to a selected table, update the data of an entry, delete an entry and delete an entire table. A challenge I faced was figuring out the appropriate way to keep track of the table information such as the table name as well as the column names. I figured the best solution is to use a hash table where the key is the name of the table and the value is a vector holding the column names. To make displaying the table names easier, especially when you delete a table, I also stored the table names in a vector.
<div align="center">
  <img src="https://raw.githubusercontent.com/graves-a/graves-a.github.io/master/docs/assets/Database_main.jpg">
</div>  
