# 🎓 STUDENT LOGIN & MANAGEMENT SYSTEM (C PROGRAM)

A complete **file-based Student Login & Management System** written in C with:
- Role-based authentication (Admin, Staff, Guest)
- Secure password masking using `*`
- Full CRUD operations for student records
- Simple, portable storage using text files
- Works on both **Windows & Linux**

---

## 🚀 Features

### 🔐 Login System
- User credentials stored in **credentials.txt**
- Validates username + password + role
- Password input is hidden (* masking)

---

## 🧑‍💻 Role-Based Access

| Feature | Admin | Staff | Guest |
|--------|:----:|:----:|:----:|
| Add Student | ✔ | ✔ | ❌ |
| Display Students | ✔ | ✔ | ✔ |
| Search Student | ✔ | ✔ | ✔ |
| Update Student | ✔ | ✔ | ❌ |
| Delete Student | ✔ | ❌ | ❌ |

---

## 🗂 Student Database

📌 Stored in **students.txt**  
Format:
roll name mark


Example:
101 Nikhil 91.20
102 Manoj 88.75

---

## 🔑 Credentials File Format

📌 Stored in **credentials.txt**  
Format:
username password role


Example:
admin admin123 admin
staff1 staff123 staff
guest1 guest123 guest


---

## 🧭 Menus

### Admin Menu
Add Student

Display Students

Search Student

Update Student

Delete Student

Logout

### Staff Menu
Add Student

Display Students

Search Student

Update Student

Logout


### Guest Menu
Display Students

Search Student

Logout

---

## 📁 Project Structure

Student-Management-System/
├── main.c
├── students.txt
├── credentials.txt
└── README.md


## 🛠 Compile & Run

### 📌 Windows
gcc main.c -o sms.exe
sms.exe

---

### 📌 Linux / Mac
gcc main.c -o sms
./sms

---

## 📌 Example students.txt (Updated)

101 Nikhil 91.20
102 Manoj 88.75
103 Bala 79.80
104 Surya 90.40
105 Sam 86.50
106 Satwik 92.10
107 Hari 84.90
108 Priya 88.40
109 Ananya 91.00
110 Rakesh 72.50
111 Harini 95.00
112 Kavya 93.10
113 Akash 77.00
114 Divya 86.50
115 Varun 74.60
116 Sindhu 90.75
117 Rahul 68.40
118 Lakshmi 88.90
119 Sneha 92.60
120 Vamsi 83.40
121 Keerthi 94.20
122 Suresh 80.55
123 Charan 89.50
124 Teja 82.25
125 Karthik 87.00
126 Meena 84.25
127 Naveen 79.55

---

## 🔐 Example credentials.txt

nikhil_admin Nik@101 admin
manoj_admin Mnj@102 admin
bala_staff Bla#103 staff
surya_staff Sry@104 staff
sam_guest Sam#105 guest
satwik_staff Stw@106 staff
hari_guest Hari@107 guest



> ⚠️ Change usernames/passwords before real deployment.

---

## ⭐ Future Enhancements
✔ Sorting by Name / Marks / Roll  
✔ Additional fields: phone, course, email  
✔ GUI-based system  
✔ Auto generate reports  
