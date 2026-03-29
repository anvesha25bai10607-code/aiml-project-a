♻️ WASTE DISPOSAL MANAGER SYSTEM

📌 PROJECT OVERVIEW
The Waste Management Request System is a simple Python-based application designed to manage waste disposal requests efficiently. The system allows users to register waste collection requests, update the status of requests, view all requests, and generate statistics regarding waste collection.
This project demonstrates the practical implementation of Object-Oriented Programming (OOP) concepts using Python. It models real-world waste management processes such as tracking waste types, managing pickup locations, and monitoring the status of each request.
The system can be useful for understanding how a basic waste management workflow can be represented in software using classes and methods.

🎯 OBJECTIVES OF THE PROJECT
The main objectives of this project are:
    To create a simple system for managing waste collection requests.
    To demonstrate the use of Python classes and objects.
    To manage and organize waste collection data efficiently.
    To track the status of waste disposal requests.
    To calculate useful statistics about waste collection.
    To build a small but practical Python project for learning purposes.
    
🧠 CONCEPTS USED IN THIS PROJECT
This project uses several important programming concepts, including:
    Object-Oriented Programming (OOP)
    Classes and Objects
    Class Variables
    Instance Variables
    Lists and Dictionaries
    Loops and Conditional Statements
    Data Aggregation
    Basic Data Analysis
    These concepts help in organizing the code efficiently and making the program easier to maintain and expand.
    
🏗 SYSTEM ARCHITECTURE
The system is built using two main classes:
    WasteRequest
    WasteManager
    Each class is responsible for a specific part of the waste management process.
📦 Class 1: WasteRequest
The WasteRequest class represents a single request for waste collection.
Each request contains details about the type of waste, the weight of the waste, and the pickup location.
Attributes
request_id
A unique identifier automatically assigned to each request.
waste_type
Specifies the category of waste such as:
Recyclable
Hazardous
General
weight_kg
Represents the estimated weight of the waste in kilograms.
location
The pickup address or location for waste collection.
status
Indicates the current state of the request:
Pending
Scheduled
Completed
Special Feature
The class uses a class-level variable (next_id) to automatically generate unique IDs for each new request.
🗂 Class 2: WasteManager
The WasteManager class is responsible for managing all waste collection requests.
It stores the requests and provides methods to perform different operations on them.
Main Responsibilities
Storing all waste requests
Adding new requests
Updating request status
Displaying all requests
Generating statistics about waste collection

⚙️ METHODS IN WASTEMANAGER
1. add_request()
This method adds a new waste request to the system.
It stores the request in the list of requests and confirms that the request has been successfully registered.
2. update_status()
This method updates the status of a specific request using its request ID.
Possible status values include:
   Pending
   Scheduled
   Completed
   If an invalid request ID is entered, the system displays an error message.
3. view_all_requests()
This method prints all waste requests currently stored in the system.
Each request displays:
   Request ID
   Waste type
   Weight
   Location
   Status
   This helps administrators easily monitor the system.
4. get_statistics()
This method calculates and displays statistics about the waste management system.
The statistics include:
   Total number of requests
   Total weight of waste collected
   Waste weight grouped by waste type
   Number of requests by status
   This information helps in analyzing waste collection performance.

▶️ PROGRAM WORKFLOW
The demonstration part of the program performs the following steps:
   Creates a WasteManager object.
   Registers multiple waste collection requests.
   Displays all current requests.
   Updates the status of selected requests.
   Displays the updated requests.
   Generates waste management statistics.
   This workflow simulates a simple real-world waste management system.

📈 FUTURE ENHANCEMENTS
This project can be improved with additional features such as:
   User input interface for adding requests
   Graphical User Interface (GUI) using Tkinter
   Database integration using SQLite or MySQL
   Web-based application using Flask or Django
   Real-time location tracking
   Waste pickup scheduling system
   Admin dashboard for monitoring waste collection
   These improvements can make the system more practical and suitable for real-world applications.

