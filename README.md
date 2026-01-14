# Theater Ticketing & Management System (JavaFX)

## 📝 Project Description
This is a Java-based desktop application designed to streamline theater management and the ticket reservation process. It features a **dual-interface system**: 
* **Administrator Portal**: For managing show schedules, pricing, and theater logistics.
* **Reservation Interface**: For handling real-time audience seat bookings and customer data.

## ✨ Key Features
* **Admin Authentication**: Secure login system for authorized personnel.
* **Show Management**: Interface for adding and organizing shows, including genre, price, duration, and scheduling.
* **Dynamic Reservation System**:
    * **Seat Selection**: Visual tracking of seat availability (Free vs. Reserved states).
    * **CRUD Operations**: Comprehensive management (Create, Read, Update, Delete) of reservations with built-in phone number validation.
* **Automated "Today's Show" Detection**: Smart logic that automatically identifies and displays the current day's performance for rapid ticketing.

## 🏗️ Architecture & Design Patterns
The project is built using a **Layered Architecture** (Service-Repository pattern) to ensure a clean separation of concerns and easy maintainability.

* **Controller Layer**: Manages the UI logic and user interactions using **JavaFX** and **FXML**.
* **Service Layer**: Acts as a bridge, encapsulating the core business logic (e.g., reservation rules, show scheduling).
* **Persistence Layer (Repositories)**: Handles data storage and retrieval for Administrators, Shows, Seats, and Reservations.
* **Domain Model**: Defines the core entities: `Spectacol`, `Rezervare`, `Loc`, and `Administrator`.



## 🛠️ Tech Stack
* **Language**: Java 17+
* **GUI Framework**: JavaFX (with FXML for UI layout)
* **Design Pattern**: MVC (Model-View-Controller) / Layered Architecture
* **Data Management**: Repository-based CRUD operations

## 🚀 Getting Started

### Prerequisites
* **Java JDK 17** or higher.
* **JavaFX SDK** configured in your IDE (IntelliJ IDEA or Eclipse).
* A relational database (if using the repository implementation with DB connectivity).

