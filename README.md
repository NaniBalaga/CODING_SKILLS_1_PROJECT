# Student Management System (C Program)

A simple file-based Student Management System written in C with role-based login support (Admin, Staff, Guest).  
The system allows managing student records stored in text files.

## Features

### Login System
Reads login credentials from:
- credentials.txt

Roles:
- admin
- staff
- guest

### User Roles
| Role | Permissions |
|------|-------------|
| Admin | Add, Display, Search, Update, Delete students |
| Staff | Add, Display, Search, Update students |
| Guest | View and search students only |

## Student Record Storage
Stored in:
students.txt

Format:
roll name mark

Example:
101 John 89.5

## File Structure
project/
│
├── main.c
├── students.txt
├── credentials.txt
└── README.md

## Credentials File Format
username password role

Example:
admin admin123 admin
staff1 staff123 staff
guest1 guest123 guest

## Menus

### Admin Menu
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Logout

### Staff Menu
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Logout

### Guest Menu
1. Display Students
2. Search Student
3. Logout

## How to Run

Compile:
gcc main.c -o sms

Run:
./sms
