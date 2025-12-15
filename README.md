# Online Bus Booking System 🚌

**Online Bus Booking System** (also known as True Bus) is a dynamic and automated bus reservation software built with **PHP, MySQL, and Bootstrap**. It is designed to manage bus inventories, fares, routes, schedules, and bookings efficiently, offering distinct interfaces for Admins, Agents, and Users.

## 📂 Repository Structure

The codebase is organized into modular folders to handle the frontend, backend, and database logic effectively:

### 1\. Core Application (`root/`)

  * **`index.php`:** The main entry point for the user interface, displaying available buses and search options.
  * **`bus_info.php`:** Detailed view for a specific bus, allowing users to select seats and book tickets.
  * **`bus.sql`:** The complete database schema containing tables for users, orders, buses (`posts`), and routes.

### 2\. Administration (`admin/`)

  * **`admin/index.php`:** The central dashboard for administrators to view stats, manage buses, and oversee the system.
  * **Management Scripts:** Includes scripts for adding buses, managing routes, viewing bookings, and processing cancellations.

### 3\. Components & Utilities (`includes/`)

  * **`db.php`:** Handles the database connection to MySQL.
  * **`header.php` / `footer.php`:** Reusable UI components to maintain a consistent layout across all pages.
  * **`navigation.php`:** Contains the main menu and login/registration links.

## ✨ Key Features

### 👤 User Module

  * **Registration & Login:** Secure user accounts for managing bookings.
  * **Bus Search:** Find buses by route, date of journey, and availability.
  * **Seat Selection:** Visual interface to view and select available seats.
  * **Ticket Booking:** Integrated booking flow with promo code support and payment options.

### 🛠 Admin Module

  * **Fleet Management:** Add, update, or delete bus details, routes, and schedules.
  * **Booking Oversight:** View all active bookings, passenger details, and cancellation requests.
  * **Route & Pricing:** Manage boarding/dropping points and set fares for different routes.
  * **User Management:** View registered users and manage agent accounts.

## 🚀 Getting Started

### Prerequisites

  * **Server:** XAMPP, WAMP, or LAMP (Apache/MySQL/PHP).
  * **Browser:** Any modern web browser (Chrome, Firefox, Edge).

### Installation Steps

1.  **Download & Extract:**
    Download the project zip file and extract it into your server's root directory (e.g., `C:/wamp/www/` or `C:/xampp/htdocs/`).

2.  **Database Configuration:**

      * Open **phpMyAdmin** (`http://localhost/phpmyadmin`).
      * Create a new database named `bus`.
      * Import the `bus.sql` file provided in the project folder.

3.  **Run the Project:**
    Open your browser and navigate to:

    ```
    http://localhost/Online Bus Booking System
    ```

### 🔑 Default Login Credentials

To access the Admin Panel:

  * **Username:** `amit`
  * **Password:** `amit`

## 🛠 Tools Used

  * **HTML5 & CSS3:** For structure and layout.
  * **Bootstrap:** To ensure a mobile-friendly, responsive design.
  * **JavaScript:** For client-side interactivity.
  * **PHP:** Server-side scripting language for backend logic.
  * **MySQL:** Relational database for storing user and bus data.

*Created by [Pushti Kadia](https://github.com/pushtikadia)*



