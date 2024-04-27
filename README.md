# Hotel Booking Management System

This repository contains the source code for a Hotel Booking Management System developed as a part of the DBMS project. The system is built using PHP and MySQL.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Database Structure](#database-structure)
  
## Introduction

The Hotel Booking Management System is designed to streamline the process of managing hotel bookings,room availability, and reservations.

## Features

- **User Authentication:** Secure login and registration system for hotel staff and guests.
- **Room Management:** Add, edit, and delete rooms with details such as room type, price, and availability.
- **Booking Management:** Book rooms, view booking history, and manage reservations.
- **Reporting:** Generate reports on room occupancy, revenue, and guest statistics.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/username/hotel-booking-management.git
   ```

2. Import the `database.sql` file into your MySQL database to create the necessary tables.

3. Update the `config.php` file with your MySQL database credentials.

4. Start the PHP development server or configure your web server to serve the application.

## Usage

1. Access the application through your web browser.
2. You can register your own name and password and then automatically log in into your account.
3. Explore and use the different features of the Hotel Booking Management System.

## Database Structure

The database consists of the following tables:
- `users`: Stores user information for authentication.
- `rooms`: Contains details about the hotel rooms.
- `bookings`: Tracks booking information.
- `payments`: Records payment transactions.
- `logs`: Maintains system activity logs.

For a detailed schema, refer to the `database.sql` file.
