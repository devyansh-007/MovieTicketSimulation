# 🎟️ Movie Ticket Booking System (C++ & MySQL)

A simple console-based application for booking movie seats using C++ and MySQL.  
This system allows users to **view available seats**, **reserve a ticket**, and **update the reservation in a MySQL database** in real-time.

---

## 📌 Features

- Seat map: 5 rows × 10 seats
- Live seat status from MySQL `Ticket` table
- Prevents double booking
- Uses `INSERT` & `UPDATE` queries to persist seat reservations
- Automatically creates the table if it doesn't exist
- Simple user interface via console

---

## 🧱 Tech Stack

- **Language**: C++
- **Database**: MySQL
- **Libraries**:
  - `<mysql.h>` — MySQL C connector
  - `<windows.h>` — For delay and console clear (Windows only)
  - Standard C++ STL

---

## 🚀 Getting Started

### 🔧 Prerequisites

- MySQL installed and running
- MySQL C++ development libraries (e.g., `libmysqlclient`)
- C++ compiler (e.g., g++, Visual Studio)

---

### ⚙️ Configuration

In `main.cpp`, configure your MySQL credentials and database name:

```cpp
const char* HOST = "localhost";
const char* USER = "root";
const char* PW   = "your_password";
const char* DB   = "mydb";
