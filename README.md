# Hotel Management System

## Introduction
This is a simple console-based Hotel Management System written in C++. It allows users to book rooms, view room status, customer information, edit data, and handle administrative tasks such as changing passwords and viewing old records.

## Features
- **Book a Room**: Users can book a room by providing personal details.
- **View Room Status**: Displays the status of all rooms.
- **View Room Information**: Provides detailed information about a specific room.
- **View Customer Information**: Displays information about a specific customer.
- **Edit Data**: Allows editing the details of a specific room.
- **Leave Room**: Handles the checkout process for a room.
- **Advanced Room Status**: Displays room status with password protection.
- **View Old Record**: Displays records of previous customers.
- **Change Password**: Allows the admin to change the password.

## Prerequisites
- A C++ compiler (e.g., GCC)
- Basic understanding of C++ and file handling in C++

## How to Run
1. **Clone the Repository**: Download or clone the repository to your local machine.
2. **Compile the Code**: Open a terminal and navigate to the directory where the code is located. Run the following command to compile the code:
   ```sh
   g++ -o hotel_management main.cpp

Usage
When you run the program, a menu will be displayed with the following options:

Press 1 to book a room: Enter details to book a room.
Press 2 to view all rooms status: View the status of all rooms.
Press 3 to view room information: Enter a room number to view its information.
Press 4 to view customer information: Enter a customer's name to view their information.
Press 5 to edit the data: Edit the details of a specific room.
Press 6 to leave the room: Enter details to check out of a room.
Press 7 to view advance room status: View the status of all rooms (password protected).
Press 8 to view old record: View records of previous customers.
Press 9 to change password: Change the admin password (requires passcode).
Press 0 to exit: Exit the program.
Files
main.cpp: The main source code file containing the implementation of the Hotel Management System.
record.txt: File where current room bookings are stored.
prevreco.txt: File where previous customer records are stored.
pass.txt: File where the admin password is stored.
Notes
The default passcode to change the password is 1234.
Ensure that the record.txt, prevreco.txt, and pass.txt files are in the same directory as the executable.
Future Improvements
Implement a GUI for a better user experience.
Add more functionalities such as online booking, payment integration, and more detailed customer records.
Improve data security and encryption for sensitive information.

Author
Prasad Shivaji Ambekar

For any queries or issues, please contact: prasad.s.ambekar26@gmail.com
