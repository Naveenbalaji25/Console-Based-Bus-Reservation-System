**Bus Reservation System**

**A Console-Based Application Developed in Core Java**

**Overview**
The Bus Reservation System is a console-based Java application designed to manage bus details and handle ticket bookings efficiently.
The project demonstrates strong usage of Object-Oriented Programming (OOP) principles such as classes, objects, encapsulation, and constructors.
Data is temporarily stored using Java Collections, and the system validates bookings based on seat availability.

This project serves as a foundation for integrating advanced features such as MySQL database connectivity, admin modules, and GUI-based interfaces.

**Key Features**

**Bus Management**

Stores bus number, AC/Non-AC type, and seating capacity.

**Ticket Booking**

Allows users to enter booking details.

Validates availability before confirming bookings.

**OOP-Based Implementation**

Clean class structure: Bus, Booking, and BusDemo (main)

Uses constructors and encapsulated attributes.

**Collection-Based Storage**

Uses ArrayList to store buses and bookings dynamically.

**Project Structure**
|-- BusReservationSystem
    |-- Bus.java        // Bus properties and validation
    |-- Booking.java    // Booking details and logic
    |-- BusDemo.java    // Main program entry point

**How to Run the Application**
Prerequisites

Java JDK 8 or above

Any IDE (Eclipse, IntelliJ, VS Code) or command-line terminal

**Steps**

Clone or download the project.

Open a terminal inside the project folder.

Compile all Java files:

javac *.java


**Run the program:**

java BusDemo

****Sample Console Output
------------ Bus Reservation System ------------

1. Book Ticket
2. Exit

Enter your choice: 1
Enter Passenger Name: Naveen
Enter Bus Number: 101

Seat Available → Booking Confirmed ✔

**Future Enhancements**

MySQL database integration for permanent storage

Admin dashboard for managing buses and schedules

Ticket cancellation module

Reporting module (daily bookings, revenue, etc.)

GUI using JavaFX / Swing

REST API version using Spring Boot

**Technologies Used**

Java (Core Java)

Collections Framework

OOP Concepts

**Author**

Naveenbalaji R
naveenraju.2505@gmail.com
Aspiring Java Developer 
Committed to building real-world Java applications.
