## Projects

|      |   |
|------|---|
| [1. Basics](#1-basics) |  [5. OS Design](#5-os-design) |
| [2. Scenic](#2-scenic) |   |
| [3. Database CLI](#3-database-cli) |   |
| [4. Network Design](#4-network-design) |   |

[Scenic]()

<!-- TOC -->
  * [Projects](#projects)
    * [1. Basics](#1-basics)
    * [2. Scenic](#2-scenic)
    * [3. Database CLI](#3-database-cli)
    * [4. Network Design](#4-network-design)
    * [5. OS Design](#5-os-design)
    * [6. Co-op Webpage](#6-co-op-webpage)
    * [7. RestoApp](#7-restoapp)
    * [8. Robot Shooter](#8-robot-shooter)
    * [9. Left-Right](#9-left-right)
<!-- TOC -->

### 1. [Basics](https://github.com/Harehn/Basics)
_A personal project that demonstrates the basics of a programming language_

I have created this project to act as a cheatsheet for the languages I know. 
This makes it easy to refer back to what I know and also makes sure I have a basic grasp on a language.
The basics include Variable Types, Objects, Type Casting, Comments, Arithmetics, Arrays,
Logic Flow(IfElse, While/for loop etc.), Printing, User Input (Console and interactive),
Randomness, File IO and (Higher Order) Functions. I will occasionally add more depending on the language.

I also intend to add some sorting and miscellaneous code to these branches, so I can refer to them easily.

**Languages(So Far):** Python, Java, Ocaml, C, JavaScript\
**Link:** https://github.com/Harehn/Basics 

### 2. [Scenic](https://github.com/ArenBabikian/Scenic/tree/master)
_Capstone group project – Creating test cases for autonomous driving cars_

This was my final year project for Bachelor of Software Engineering. 
The project was initially forked by our supervisor from [BerkeleyLearnVerify](https://github.com/BerkeleyLearnVerify/Scenic).
Several iterations have been made on the project since. The project's goal is to create a simulation for autonomous vehicles
and to create test cases so that we can be more rigorous in software testing of autonomous vehicles.

Our group focused on the optimisation of SAT solving and NSGA creation of test cases. 

**Supervisor:** [Aren Babikian](https://github.com/ArenBabikian) \
**Team Members:** [Zhekai Jiang](https://github.com/zhekai-jiang), [Jerry Hou-Liu](https://github.com/JryHL), Oliver Huang\
**Language:** Python, Bash, markdown, Json \
**Technologies:** pytest, NSGA, pymoo, Poetry, Toml, Docker, Server integration(ssh, scp, etc), Json data extraction and compilation\
**Link:** https://github.com/ArenBabikian/Scenic/tree/master

### 3. [Database CLI](https://github.com/Harehn/COMP421)
_Group Project to make an interactive CLI to communicate with a remote database_

The goal of the project was to create a simple CLI to communicate with a remote DB2 database and perform
simple insert, select and delete operations. We took necessary steps to handle SQL exceptions. 
The initial table creations and initial insertion of data was done directly using sql files on the server side.

**Team Member:** [David Hamaoui](https://github.com/davidham96)\
**Languages:** Java, SQL(DB2)
**Technologies:** Server integration(ssh, scp, etc.), relational databases\
**Link:** https://github.com/Harehn/COMP421

### 4. [Network Design](https://github.com/Kai-Cheng-WU/ECSE422)
_Group project to use different methods to calculate the reliability of a network_

Given an input of all possible network connections(cost and reliability), we are to find the best network given the cost.
We do this two different way with the first method being the brute method and the second being a more optimum one.
Our approach is to store intermediate values and thus reducing computing time.

**Team Member:** [Kaicheng Wu](https://github.com/Kai-Cheng-WU), [Andrei Sador](https://github.com/andrei-sandor)\
**Languages:** Python\
**Link:** https://github.com/Kai-Cheng-WU/ECSE422


### 5. [OS Design](https://github.com/Harehn/COMP310-WINTER2024)
_Group Project to simulate the basic functions of an OS_

We simulated and debugged several functionalities of an OS such as the interpreter and shell memories. 
We also implemented program scheduling with their pcb and ready queue. 
Finally, we implemented the file system with local files acting as disks.

**Team Member:** [Danlin Luo](https://github.com/dluo6)\
**Languages:** C \
**Technologies:** Docker, MultiThreading \
**Link:** https://github.com/Harehn/COMP310-WINTER2024

### 6. [Co-op Webpage](https://github.com/Harehn/Cooperator)
_A group project to make an online application website for students to register for co-ops_

The goal of the project is to create a landing page to coordinate students' coops.
We made a full stack project using continuous integration(Travis CI), a backend using Java and JavaSpring Restful Services.
Our front end was made using Node.js, HTML and CSS(Using Bootstrap). We made tests using Mockito and followed Test driven development.
We sued ZenHub and Github wiki(deprecated) for documentation and to follow agile methodology. 
We used PostgreSQL and Heroku to deploy our project. 

_The original code is not accessible and a mirror containing most of the code is given here._

**Language:** SQL, Java, Markdown \
**Technologies:** Agile methodology, Zenhub, Github, Restful Services, Gradle, Travis CI, Heroku, Postgresql, JUnit, Mockito\
**Link:** https://github.com/Harehn/Cooperator

### 7. [RestoApp](https://github.com/Harehn/RestoApp)
_Group project to create an app for restaurant reservations_

A group project to help a restaurant with making reservations and walk-ins. The project was made with JavaFX and UML.
A visual of the layout of the restaurant is made and the tables and seats can be selected to make reservations and assign orders.

_The original code is not accessible and a mirror containing most of the code is given here._

**Language:** Java (JavaFX), UML\
**Technologies:** Github, MVC architecture, state diagrams, sequences diagrams\
**Link:** https://github.com/Harehn/RestoApp

### 8. Robot Shooter
_Group project to make an autonomous robot car to shoot towards target goals_

The goal of the project was to build and program a lego robot so that it can navigate a varied terrain and shoot a ping pong ball into a goal.
We tested the various sensors and analysed test data. We used A* algorithm to navigate the terrain. The code was gone in Java with the Lejos library.

**Language:** Java, UML\
**Technologies:** Github, Object Oriented paradigm, Lejos Library, Lego robot Sensors

### 9. [Left-Right](https://harehn.github.io/Testpage/)
_Online interactive exercise to train left-right coordination_

A simple webpage made using JavaScript to train left-right coordination.

**Language:** HTML, Javascript\
**Technologies:** Github, Object Oriented paradigm, Github Pages \
**Link:** https://harehn.github.io/Testpage/