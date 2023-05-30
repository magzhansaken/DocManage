Stage 1. Capstone Project Creation and Setup (special document management system)
The purpose of this exercise is to get real experience in project creation and setup while working in a group under the supervision of your instructor.
Please read carefully and do the following:
Step 1
1. First, you need to generate some ideas for the capstone project. You may use some templates given below:
We have chosen this theme:
•	special document management system
(special subject area, special process, etc.)
We encourage you to create an idea that seems to be fun or interesting to you personally.
Step 2
2. Write down the ideas as High-Level Overviews. To accomplish that, the ideas should include the answers to the following questions:
•	What kind of app would it be?
•	Who is this project for?
•	What needs will it satisfy?
All the subsequent design and implementation steps of your capstone project will be based on this High-Level Overview.
Step 3
3. Create and set up the project environment.
How this task will be evaluated:
Please be aware that we expect the completed task to meet the following criteria:
•	At least two capstone project ideas should be written as High-Level Overviews.
•	The selected idea should be modified according to the instructor's feedback.
•	A Git repository for the project should be created.
•	The task tracking service should be set up.
•	The task should be submitted as doc or pdf document in the form below.
Set up of git repository and task tracking service: A Git repository for the project has been created and the task service is ready for use.
High-Level Overviews of the ideas: At least two High-Level Overviews of the capstone project ideas have been discussed with the instructor and one of them has been selected.
Instructor's feedback implementation: The selected High-Level Overview has been modified in accordance with the instructor's feedback. 
Stage 2. Capstone Project Use Cases (special document management system)
The purpose of this exercise is to get real experience in defining project requirements and creating use case design.
Please read carefully and do the following:
1.	Describe requirements for a chosen system: functional and non-functional.
2.	Based on the requirements, design use cases for the system.
3.	Identify objects, classes, and relationships in the system. Optionally, design CRC cards.
4.	Optionally, design class diagrams picturing classes, their attributes, and relations in the system.
How this task will be evaluated:
Please be aware that we expect the completed task to meet the following criteria:
•	The requirements for a chosen system (functional and non-functional) should be fully described.
•	Use cases for the system that are based on the requirements should be designed.
•	Objects, classes, and relationships of the system should be identified.
•	The task should be submitted as doc or pdf document in the form below.
Objects and their relationships: The objects, classes, and relationships of the system are completely identified.
Functional and non-functional requirements: Functional and non-functional requirements for the system are described.
Use cases: The use cases that are based on the requirements are designed.
 
Stage 3. Capstone Project Database Layer Design (special document management system)
Pre-Task Instructions
Now, you will complete stage 3 of your Capstone Project. It includes one mandatory task: "Capstone Project Database Layer Design".
Please read the detailed descriptions of the tasks below.



This task will help you to structure your knowledge on how to design a database layer for a web application.
A database layer is the core element of every application. To complete the task, please take the following steps:
Step 1: Identify all the entities in the system (the key, weak, associative entities).
Each entity should appear only once in a particular diagram.
Step 2: Identify relationships between the entities.
Step 3: Identify cardinality and ordinality of the relationships.
Step 4: Add attributes for the entities (the key, weak key, derived, multivalued attributes).
Give clear names so that the meaning of attributes can be understood easily.
You may use any digital tool to visualize your ER diagram.
Defining unique entities: At least 5 unique entities are created and given meaningful names.
Identifying the type of entities (key, weak, and associative): All 3 types are identified correctly.
Identifying the relationships between entities: The relationships between entities are depicted correctly, cardinality and ordinality are specified.
Identifying the attributes (key, weak key, derived, multivalued): The attributes of the entities are created, and their types are determined correctly. The names given to the attributes are meaningful. 
Stage 4. Capstone Project Interface Design (special document management system)
This stage includes one mandatory task: "Capstone Project Interface Design" (~12 hours).
Please read the detailed descriptions of the tasks below.
The main purpose of this task is to create a User Interface (UI) representation that will be visible for end users. As mentioned above, to ensure a great user experience, a UI must be as straightforward and clear as possible.
Here are some recommendations:
1.	Make a UI as simple as possible: avoid unnecessary elements, give clear names.
2.	Use common UI icons, labels, patterns. Make use of what your visitors already know to help them get their job done quickly.
3.	Be consistent. After creating a pattern, transfer it to other parts of the app.
4.	Make the best of the page layout, color, and typography. Direct users' attention with the help of changes in the size, placement, fonts, or color of the elements.
5.	Reduce the number of unnecessary actions from a user, such as filling out the forms or searching for information. Use default settings to pre-fill the forms, reduce the number of options or the number of clicks to get to the most popular pages.
Three main stages of the user interface design are:
1.	User Research
2.	Design and Prototyping
3.	Evaluation
In this task, you will be asked to complete all the stages.
Step 1. Define the purpose of your application. How will it be useful for future users?
Step 2. Clarify the users’ objectives. Why will the users want to use your app? Once they have launched the application, what will they be looking for in the first place? Secondly? Define a basic scenario and an advanced one.
Step 3. Identify the most important elements and content for the users. How will you place it on the page? Create a set of schematic wireframes.
 
Step 4. Develop a mockup – a static representation of your app. Add shapes, fonts, colors, and navigations.
Step 5. Create an interactive prototype based on the mockup. The prototype should reflect the actions and their results depending on the basic use case scenario.
Step 6. Test your prototype and implement changes.
Step 7. Transfer your prototype to an HTML/JS version. It should be possible to open it in any web browser without errors or overlaps and to complete both basic and advanced scenarios.
Defining the goal and users' objectives: The application goals are defined. Basic and advanced scenarios are identified based on users' objectives.
Designing the wireframes: The wireframes are designed for all pages and represent layouts, important elements, and a type of content.
Designing the mockups: The use of shapes, fonts, colors, navigation elements is consistent throughout all the pages.
Creating the prototype: The prototype fully represents the basic use case scenario: users' actions and their results in each step.
Developing a web version: All elements are implemented in HTML/JS and can be opened in any web browser without errors or overlaps. Both basic and advanced scenarios can be executed successfully.
 
Stage 5. Capstone Project Web App Implementation (special document management system)
Pre-Task Instructions
In this module, you will begin working on stage 5 of your Capstone Project. It includes one mandatory task: "Web App Implementation". Below you will find detailed instruction and criteria against which you will be assessed.

Tech Stack
We encourage you to use Spring Boot and RDBMS (MySQL, Postgres, or similar free solutions) to build your web app.
Web App Development Milestones
In the previous modules you defined the purpose of your app, what its main use cases are, and what kind of entities it will manage. Now it's time to proceed to the code.
The task is complex: you must design and implement lots of classes and interfaces. Let's take it step by step:
Click each heading to see more information.
 Step 1: Design the Layers and Modules
It is recommended to implement three-tier architecture - a well-established software application architecture that organizes applications into three logical and physical computing tiers:
•	the presentation tier, or user interface;
•	the application tier, where data is processed;
•	and the data tier, where the data associated with the application is storage.
You are required to use this model and provide layers of controllers, services and data access.
 Step 2: Define a Data Access Solution
There are two ways to establish access to the database from within your app:
1.	to implement JDBC (Java Database Connectivity) - it manages connection to a database, enables issuing queries and commands, and handling result sets obtained from the database.
2.	to leverage an ORM solution (Hibernate) - Spring allows you to use JPA Entity Managers, Hibernate Session Factories, or Spring Data approach. 
 Step 3: Choose and Set up a Template Engine
You may choose an Internal Views based on JSPs or an advanced template engine like Thymeleaf or Freemarker. Msure to properly configure view resolving accordingly.
 Step 4: Design General Interfaces and Classes
Start with inter-layer communication. Do not try to create complex solution in one iteration, but design simple Services, DAO and UI layers that can help you to deploy and start your application as soon as possible.
 Step 5: Implement Your Application
Start with introducing domain entities and appropriate attributes and relations. Then implement related classes of Service and DAO layers, then Views and Controllers.
 Step 6: Run Unit and Integration Tests
Apply TDD approach and cover your code with unit or integration tests. Even though, it is optional, we strongly recommend you do this: it will provide you with confidence that the application will run smoothly. Try to reach at least 50% of code coverage.
 Step 7: Manage Users' Access
Consider using Spring Security to manage user access to your web app. Spring Security is the most common way to authenticate users and deal with their privileges.

Task Tracking
We encourage you to use task tracking services like GitLab Issues and Boards, or Trello with simple models of three columns: To Do, In Progress, and Done.
Decompose big milestones, like data access or controller layer implementation, into smaller tasks, and put them on the board. That will help to plan workload and better understand the current project status.
Requirements
Let us consolidate all the requirements into a single check list:
•	The web app obtains a GUI.
•	There are three layers: persistence (or data access) layer, service layer and view layer.
•	Persistence layer requirements:
o	The web app is connected to a database.
o	There areat least 4 entities in a database.
o	There are relationships between entities.
o	Recommended: at least one many-to-many relationship is designed.
o	Web app containsa persistencelayer.
o	Persistencelayer is isolated from other layers.
•	Service layer requirements:
o	Services use dependencies from persistence layer to access data and do not interact with a database on their own.
o	Services do not deal with views.
o	Services handlemainbusiness processes of the web app.
•	View layer requirements:
o	Controllers of view layer do not use dependencies from persistence layer or interact with a database.
o	Controllers of view layer may use dependencies from service layer.
o	There are at least 6 views.
•	Recommended: unit and/or integration tests are applied.
•	The project is completed: all the functions are implemented.
•	The project demo is given.
The web app is functional: Your web app implements all the functions described at project design stages.
The web app is layered: Your web app contains all the layers: persistence, services, and view.
Database: There is a database in your web app.
Entities: There are at least 4 entities in the database.
Relationships: There are at least one many-to-many relationship.
Persistence layer isolation: The persistence layer is isolated from other layers.
Business Processes: Services handle main business processes of your web app.
Service layer isolation: Services do not use views. Services use dependencies from persistence layer to access data and do not interact with a database on their own.
View Layer Isolation: Controllers of view layer must not use dependencies from persistence layer or interact with a database.
Views: There are at least 3 views.
Test Coverage: You use integration or system tests.
 
Stage 6. Presenting the Final Solution (special document management system)
After you are ready with your solution, prepare for a live presentation.
Please be aware that your presentation should take no longer than 15 minutes including time for questions.
After the live presentation, record a short self-presentation video, which you can add to your professional portfolio. You will find the instructions for the video below.
Take your time getting ready for the live presentation. Make sure to do the following:
•	Prepare a few slides to demonstrate the main features of your solution. It will help you stick to your point and stay on track
•	Think about what you will say. Try to keep short and simple
•	Practice your answers to the possible questions from the instructor
Below you will find the main structure of the presentation:
Click each heading to see more information.

 Introduction
1.	Briefly introduce yourself.
2.	Provide a brief description of the application, including:
o	purpose
o	target users
o	major features
o	implemented user stories
 
Main part
3.	Share the screen and make a live presentation of the application:
•	Demonstrate the main features and explain how they were implemented.
•	Describe what was not implemented and what was improved/added.
4.	Explain the application architecture:
•	Explain the solution architecture (the list of components, the purposes of components, technologies used in each component).
•	Explain the structure and the architecture of the data access layer and its classes.
•	Explain the architecture of the user interface and the presentation logic (types, views, controllers, view models, UI design).
•	Demonstrate unit tests if they are implemented.

 Conclusion
5.	Make a short conclusion and get ready to answer questions.
Please record your online session in Teams. Ask your instructor to start the recording once you are ready for it. After the presentation, attach your slide deck in a PDF format on the platform.
Project Introduction: You have presented what your web app is, its purpose and its target audience.
Main features: You have presented the main features of your web app in action, and they were fully functional.
Code structure: You have presented project code structure, solutions, and how it works.
Questions: You have successfully answered all the questions.

