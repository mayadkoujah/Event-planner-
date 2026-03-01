# Event-planner- 
PROJECT OVERVIEW
The campus management system is a python-based application designed to help university coordinator manage campus activities. The system allows you to create the events, add students, and make sure there is no overlapping in students or events. 
SYSTEM FEATURES
•	Add new event: creates events with unique IDs and checks the time and location for conflicts 
•	Register student: enroll students into existing events using their student ID
•	List all events: view a formatted table of all the events on campus
•	Show attendees: search for events by the ID and see a list of all the students for this event.
HOW TO RUN THE PROGRAM
•	Ensure you have python installed on your machine 
•	Place the Main.py in your desired directory
•	Open the terminal
•	Navigate to the directory and type: python Main.py 
•	Follow the screen menu prompts (option 1 through 5) 
SAMPLE TEST SCENARIOS 
•	Enter a ID that already exists > output > This ID already exists
•	Enter a event that has same time location or date > output > Event already exists 
•	Register a student for a event that does not exist > output > Event does not exist 
TECHNICAL DESGIN 
•	The system uses nested lists to associate the attendees with specific events without the need for an external database.
•	Conflicts: during event creation the system uses a for else loop to go through the database to verify the event has a unique ID and events do not overlap. 
•	Relation Mapping: The “Show Attendees” feature uses a event ID as a primary key to filter and display only students registered for this event exactly. 
AUTHOR & VERSION 
•	Author: Mayad Koujah 
•	Version: 1.0 

