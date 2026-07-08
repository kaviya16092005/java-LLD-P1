# Movie Ticket Booking System

A console-based **Movie Ticket Booking System** developed in **Java** that simulates the core functionalities of a movie ticket reservation application. This project demonstrates the implementation of object-oriented programming principles, modular design, and efficient data management using Java Collections.

## Overview

The application enables users to manage movie details and perform ticket booking operations through an interactive menu-driven interface. It is designed as an academic project to strengthen Java programming fundamentals and object-oriented design concepts.

## Features

- Add new movies to the system
- View all available movies
- Search movies using their unique ID
- Book tickets for available movies
- Cancel booked tickets
- Display available seat count
- Interactive console-based menu
- Input validation for smooth user interaction

## Technologies Used

- **Language:** Java
- **Concepts:** Object-Oriented Programming (OOP)
- **Data Structure:** ArrayList
- **IDE:** Eclipse / IntelliJ IDEA / VS Code
- **JDK:** Java 8 or later

## Project Structure

```
Movie-Ticket-Booking-System
│
├── Main.java                # Application entry point
├── bookingticket.java       # Booking and movie management logic
└── movie.java               # Movie model class
```

## Class Description

### Main.java
- Launches the application
- Displays the menu
- Handles user interaction and navigation

### bookingticket.java
Implements the application's core functionality:
- Add movie
- View movies
- Search movie
- Book tickets
- Cancel tickets
- Display available seats

### movie.java
Represents a movie object containing:
- Movie ID
- Movie Name
- Show Time
- Available Seats

Includes constructors, getters, setters, and utility methods.

## Getting Started

### Prerequisites

- Java Development Kit (JDK 8 or above)
- Any Java IDE or command-line terminal

### Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Movie-Ticket-Booking-System.git
```

Navigate to the project directory:

```bash
cd Movie-Ticket-Booking-System
```

Compile the project:

```bash
javac *.java
```

Run the application:

```bash
java Main
```

## Sample Menu

```
1. Add New Movie
2. View All Movies
3. Book Ticket
4. Cancel Ticket
5. Search Movie
6. Display Available Seats
7. Exit
```

## Object-Oriented Concepts Implemented

- Classes and Objects
- Encapsulation
- Constructors
- Method Overloading
- Modular Programming
- Collection Framework (ArrayList)
- Exception-aware User Input Handling

## Future Enhancements

- Persistent database integration (MySQL)
- User authentication and authorization
- Admin and customer modules
- Seat layout visualization
- Online payment gateway
- Booking history
- File handling for persistent storage
- Graphical User Interface (Java Swing/JavaFX)
- Email/SMS booking confirmation

## Learning Outcomes

This project helped in gaining practical experience with:

- Java programming fundamentals
- Object-oriented software design
- Collection Framework
- Console-based application development
- Modular code organization
- User interaction and data management

## Author

**J K Kaviyalakshmi**


---

If you found this project useful or interesting, consider giving the repository a ⭐ to support the project.
