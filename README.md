# Home automation system
This is my university project for the Programming Methodologies course. 
The project aims to develop a prototype of a software system for home automation, specifically focusing on automatic lighting control. 
The system utilizes motion and brightness sensors to detect movement and changes in ambient light, enabling it to adjust lighting accordingly. 
Additionally, it features a logging service that allows users to access and retrieve sensor data.

## Project goal
The project's objective was to develop a prototype of a software system using design principles and design patterns covered in the course, while mantaining the code clean and well readable. 
Additionally the implemented functionalities had to be tested to ensure their correct behavior. The design patterns used are:
- Observer. Used for managing sensor notifications to interested systems.
- Visitor: Implemented to handle different sensor event types efficiently.
- Strategy: Utilized to provide flexibility in sorting log entries based on various criteria.
