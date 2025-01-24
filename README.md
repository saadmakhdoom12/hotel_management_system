---

# 🏨 Hotel Management System

## Introduction
Welcome to the Hotel Management System. This application is designed to manage hotel room bookings efficiently. It allows employees to log in, check availability, and book rooms across three floors.

## ✨ Features
- 🔒 Employee authentication with ID and password.
- 🛏️ Book rooms on the first, second, and third floors.
- 📊 Displays the status of room availability (booked or free).

## 🛠️ How to Run

1. **Clone the repository:**
   ```sh
   git clone https://github.com/saadmakhdoom12/hotel_management_system.git
   cd hotel_management_system
   ```

2. **Compile the code:**
   Ensure you have a C++ compiler installed. You can use `g++`, which is available in GCC.
   ```sh
   g++ main.cpp -o hotel_management_system
   ```

3. **Run the application:**
   ```sh
   ./hotel_management_system
   ```

## 🗂️ Code Structure
- **hotel_management_system.cpp:** The main file containing the logic for the hotel management system.

## 📋 Usage

1. **Login:**
   - Enter your employee ID (e.g., 844 or 930).
   - Enter your password (e.g., 123).

2. **Booking a Room:**
   - Choose a floor to book a room:
     - Press `F` for the first floor.
     - Press `S` for the second floor.
     - Press `T` for the third floor.
     - Press `0` to exit the application.
   - Follow the prompts to book a room.

3. **Exit:**
   - Press `0` at any time to exit the application.

## Example
```sh
    *******************************************************
                WELCOME TO HOTEL MANAGEMENT SYSTEM
    *******************************************************

Enter your ID: 844
Enter your Password: 123

you are login with Employee ID: 844
Press F to book room in first flour
Press S to book room in Second flour
Press T to book room in Third flour
Press 0 to Exit application.
Enter Here: F
 ** Welcome to the First Floor **
Room 5 is booked Second Floor
Room 7 is booked Second Floor
Room 8 is booked Second Floor
Room 10 is booked Second Floor
Booked Room in First Floor: 4
Free Room in First Floor: 6
Press B to book a Room or E to Exit:
```

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
