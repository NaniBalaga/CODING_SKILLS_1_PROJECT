# STUDENT LOGIN & MANAGEMENT SYSTEM (C PROGRAM)

A complete file-based Student Login & Management System written in C with
role-based authentication, secure password masking, and full student data management.

This system uses plain text files for storage, making it simple and portable.

---

## Features

### 1. Login System
- Credentials stored in credentials.txt
- Roles supported: admin, staff, guest
- Password characters are hidden using *
- Works on Windows and Linux

---

## Role-Based Access

Admin: Add, Display, Search, Update, Delete Students
Staff: Add, Display, Search, Update Students
Guest: Display & Search only

---

## Student Database

Stored in students.txt  
Format:

roll name mark

Example:

101 John 89.50
102 Alice 75.25

---

## Credentials File Format

File: credentials.txt  
Format:

username password role

Example:

admin admin123 admin
staff1 staff123 staff
guest1 guest123 guest

---

## Menus

Admin Menu:
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Logout

Staff Menu:
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Logout

Guest Menu:
1. Display Students
2. Search Student
3. Logout

---

## Project Structure

project/
├── main.c
├── students.txt
├── credentials.txt
└── README.txt

---

## Compile & Run

gcc main.c -o sms  
./sms (Linux)  
sms.exe (Windows)

---

## Example students.txt

101 Rohith 89.50
102 Nani 75.25
103 Charan 92.00
104 Karthik 66.00
105 Arjun 78.20
106 Priya 88.40
107 Ananya 91.00
108 Rakesh 72.50
109 Meena 84.25
110 Suresh 69.75
111 Harini 95.00
112 Manoj 81.20
113 Kavya 93.10
114 Akash 77.00
115 Divya 86.50
116 Teja 82.25
117 Varun 74.60
118 Sindhu 90.75
119 Rahul 68.40
120 Lakshmi 88.90
121 Naveen 79.55
122 Sneha 92.60
123 Vamsi 83.40
124 Keerthi 94.20


---

## Example credentials.txt

rohith_admin Rht@123 admin
karthik_admin Krk@789 admin
meena_staff Mna#452 staff
rakesh_staff Rks@885 staff
ananya_staff Any@665 staff
sindhu_guest Snd@221 guest
rahul_guest Rhl#902 guest
varun_guest Vrn@774 guest
priya_admin Pry@550 admin
naveen_staff Nvn#330 staff
  

---
