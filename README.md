# Employee Management System


## 📋 Overview

The Employee Management System is a comprehensive C++ application designed for organizations to efficiently manage their workforce. With its intuitive interface and robust functionality, the system helps administrators handle employee information, manage parking allocations, and streamline workforce management processes.

## ✨ Features

- **User Authentication System**
  - Secure login for administrators
  - Password recovery functionality
  - New user registration

- **Employee Management**
  - Add, update, and remove employee records
  - View employee details and employment history
  - Search functionality for quick access to employee information

- **Parking Management**
  - Efficient parking space allocation system
  - Check-in and check-out tracking
  - Real-time parking availability monitoring

- **Role-Based Access Control**
  - Administrator privileges
  - Manager-specific functionalities
  - Employee-level access restrictions

## 🛠️ Technology Stack

- **Language**: C++
- **Build System**: Standard C++ compiler
- **Data Storage**: File-based storage system
- **UI**: Console-based user interface with colored text

## 📁 Project Structure

```
Employee-Management-System/
├── include/
│   ├── Admin.h          - Administrator class definition
│   ├── Employee.h       - Employee class definition
│   ├── Manager.h        - Manager class definition
│   ├── Person.h         - Base Person class definition
│   └── Parking.h        - Parking management system
├── src/
│   └── Main.cpp         - Program entry point
├── data/
│   └── checkIn_info.txt - Parking check-in data
└── README.md            - This file
```

## 📚 Class Hierarchy

```
Person
├── Employee
├── Manager
└── Admin
```

## 🚀 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Employee-Management-System.git
   cd Employee-Management-System
   ```

2. **Compile the program**
   ```bash
   g++ -o ems src/Main.cpp -std=c++11
   ```

3. **Run the application**
   ```bash
   ./ems
   ```

4. **Follow the on-screen instructions**
   - Use option 1 to create a new administrator account
   - Use option 2 to login to an existing account
   - Use option 3 if you've forgotten your password
   - Use option 4 to exit the program

## 💻 User Interface

The system features a colorful, console-based user interface that guides users through various operations with clear instructions and visual cues.

## 🚗 Parking Management

The parking system allows for:
- Allocation of parking spaces to employees
- Real-time tracking of occupied spaces
- Check-in and check-out functionality with timestamp recording
- Automatic updating of parking records

## 🔐 Security Features

- Password encryption
- Session management
- Role-based access control
- Password recovery mechanism

## 📊 Future Enhancements

- Graphical user interface
- Database integration
- Employee attendance tracking
- Performance evaluation system
- Reports and analytics dashboard

## 👥 Contributors

- Arsal Ajmal
- Mahad Ghauri

## 📞 Contact

For questions, feedback, or support, please contact:
- Email: arsal.ajmal621@gmail.com


---
