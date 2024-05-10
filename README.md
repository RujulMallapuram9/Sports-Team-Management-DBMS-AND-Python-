# SPORTS TEAM MANAGEMENT 

## 1. Introduction:
Managing a sports team involves various administrative tasks, including player management, scheduling, training, and performance analysis. Traditional methods of managing these tasks manually can be time-consuming and prone to errors. Therefore, there is a need for an efficient and automated solution to streamline these processes.

## 2. Application Architecture:
The Sports Team Management Application is developed using Python programming language for the backend logic and MySQL database for data storage. The application follows a client-server architecture, where the Python scripts serve as the backend server, and the user interacts with the application through a command-line interface (CLI).

## 3. Functionality:
The application provides several key functionalities:

Authentication: The application authenticates team managers using their username and password stored in the MySQL database.
Player Management: Managers can view player statistics, display players by batting average or strike rate, and assign training schedules to players.
Match Scheduling: Managers can schedule matches by selecting players for specific roles (batsmen, bowlers) based on predefined requirements.
Training Schedule Management: Managers can assign training schedules to players and specify details such as duration, equipment required, and coaching staff involved.

## 4. Implementation Details:
The application is implemented using Python's mysql.connector module for database connectivity and querying. User authentication is performed by verifying credentials against the Manager table in the MySQL database. Player and coach information, along with training schedules, are stored in respective tables within the database.

## 5. Output Analysis:
The report includes sample outputs demonstrating various functionalities of the application, such as assigning training schedules, displaying player statistics, and scheduling matches. The outputs illustrate the application's ability to interact with the MySQL database and perform CRUD (Create, Read, Update, Delete) operations efficiently.

## 6. Conclusion:
The Sports Team Management Application provides an efficient solution for managing various aspects of sports team administration. By leveraging Python and MySQL, the application offers scalability, reliability, and ease of use. Future enhancements may include user interface improvements, additional statistical analysis features, and integration with external APIs for real-time data updates.


## THE TABLES USED:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/822b9ad6-4488-4910-a061-28ec1b6c051d)

## THE TABLE LAYOUT FOR EACH TABLE:

### COACHES TABLE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/83f88eef-d10e-488c-a54b-fd162395eb61)

### MANAGER TABLE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/b65f3031-dbc7-4764-b89e-40ba2e5106dd)

### MATCH_LINEUP TABLE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/d696f66d-c56f-4645-8b0a-4cf91b5018a5)

### MATCHES TABLE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/9291042b-4c4e-4a79-be90-7f4feebf73a3)

### PLAYER_STATS TABLE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/01577df8-c7d8-44f0-87dc-ae69e7ad08ca)

### PLAYERS TABLE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/31eaf98d-de6a-480f-9cba-eff88981d611)

### TRAINING_SCHEDULE TABLE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/1f2b32f4-a174-40c4-9acb-5dd978463956)

## FRONT END:

### USER AUTHENTICATION:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/7c75b797-999b-4269-b564-2d0f6c3f5b07)

### ACTION CHOICE:
![image](https://github.com/RujulMallapuram9/Sports-Team-Management-DBMS-AND-Python-/assets/118895292/67612f0d-aac1-43b6-8e2e-0709476121cc)
