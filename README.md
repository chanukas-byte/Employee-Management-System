# Employee-Management-System
is that Desktop Applications we called as using employee Management ,Salaries Assigning , Attendance kind of features available here develop using simply C++  language with modern wayy using financial rerpesentations with simply  Application

# Employee Management System

A Windows desktop application for managing employees, built with C++ and wxWidgets.

## Features

- User authentication with different roles (Admin, Manager, Employee, Accountant)
- Employee management (Add, Edit, Delete)
- Attendance tracking
- Salary management
- Search and filter functionality
- Role-based access control

## Prerequisites

- CMake (version 3.10 or higher)
- C++ compiler with C++17 support
- wxWidgets library
- SQLite3

## Building the Application

1. Install the required dependencies:
   - On Windows:
     ```
     vcpkg install wxwidgets:x64-windows
     vcpkg install sqlite3:x64-windows
     ```

2. Create a build directory and generate the build files:
   ```bash
   mkdir build
   cd build
   cmake ..
   ```

3. Build the application:
   ```bash
   cmake --build .
   ```

## Running the Application

After building, you can run the application from the build directory:
```bash
./EmployeeManagementSystem
```

## Default Login Credentials

- Admin:
  - Username: admin
  - Password: admin123

## Project Structure

- `src/` - Source files
  - `main.cpp` - Application entry point
  - `models/` - Data models
  - `ui/` - User interface components
  - `database/` - Database management
  - `auth/` - Authentication system
- `include/` - Header files
- `CMakeLists.txt` - Build configuration

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 

