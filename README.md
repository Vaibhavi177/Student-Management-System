# Student Management System

A simple and efficient Student Management System written in C/C++ that helps administrators manage student records with ease. The system is designed with a command-line interface and uses CMake for build automation.

## Features

- *Add New Students:* Easily add new student records.
- *Update Records:* Modify existing student details.
- *Delete Students:* Remove student records when necessary.
- *Search and Display:* Look up students by their unique ID or name and display their information.
- *Modular Design:* Organized source code for better maintainability and future enhancements.

## Technologies

- *C/C++:* Core application logic.
- *CMake:* Build system for project configuration and compilation.

## Prerequisites

- A C/C++ compiler (GCC, Clang, or Visual Studio)
- [CMake](https://cmake.org/) (version 3.10 or higher recommended)
- Git (to clone the repository)

## Installation and Build Instructions

1. *Clone the Repository:*

   bash
   git clone https://github.com/Vaibhavi177/Student-Management-System.git
   

2. *Navigate to the Project Directory:*

   bash
   cd Student-Management-System
   

3. *Create a Build Directory and Enter It:*

   bash
   mkdir build && cd build
   

4. *Generate Build Files Using CMake:*

   bash
   cmake ..
   

5. *Build the Project:*

   bash
   make
   

## Running the Application

After building, an executable will be created. Run the executable from the build directory:

bash
./StudentManagementSystem


Follow the on-screen instructions to perform various student management tasks.

## Project Structure

A typical project layout might look like this:


Student-Management-System/
├── student_managment_system/
│   ├── main.cpp          # Main entry point of the application
│   ├── student.cpp       # Source file for student-related operations
│   ├── student.h         # Header file for student data structures
│   └── ...               # Other source files as needed
├── CMakeLists.txt        # CMake build configuration
└── README.md             # Project overview and instructions



