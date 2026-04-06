Project Description\n
This project is a console-based cinema ticket reservation system written in C++.
It allows users to browse available movies, select seats, and purchase tickets.

The system supports two roles:

Client – can view movies and reserve seats
Admin – can manage the movie database and system data

Data is stored using files, simulating a simple database.

⚙️ Features
User registration and login system
Role-based access (Admin / Client)
Movie management (add, delete, display)
Seat reservation system (2D matrix representation)
File-based data storage (users, movies, seats)
Input validation and basic error handling
🧠 How It Works
👤 Client
Registers or logs into the system
Views available movies
Selects a movie
Chooses a seat from the available seating layout
Confirms ticket reservation
🛠️ Admin
Logs into the system
Can:
add new movies
delete existing movies
view movie list
reset seating for a selected movie
🧱 System Architecture

The project is based on object-oriented programming:

User – base class for system users
Client – handles ticket purchasing and seat selection
Admin – manages movies and system data
Movie – stores movie information
💻 Technologies Used
C++
Object-Oriented Programming (OOP)
File I/O (data persistence)
STL (vector)
