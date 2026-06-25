# 🏥 Hospital Management System

A Hospital Management System developed using **Python**, **Tkinter**, and **Oracle Database** to manage hospital operations efficiently. The application provides a user-friendly graphical interface for handling patients, doctors, appointments, rooms, and billing records.

## 🚀 Features

* Add and manage patient records
* Add and manage doctor information
* Room allocation and management
* Appointment booking system
* Billing generation
* View records in tabular format
* Oracle Database integration
* User-friendly GUI built with Tkinter

## 🛠️ Technologies Used

* Python
* Tkinter
* Oracle Database
* SQL
* OracleDB Python Driver

## 📂 Project Structure

```
hospital-management-system/
│
├── hospital_management_system.py
├── database.sql
├── README.md
└── screenshots/
```

## 🗄️ Database Tables

* PATIENT
* DOCTOR
* ROOM
* APPOINTMENT
* BILL

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/riyahardeepkaur-gif/hospital-management-system.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure Oracle Database

Update the database credentials in the Python file:

```python
conn = oracledb.connect(
    user="YOUR_USERNAME",
    password="YOUR_PASSWORD",
    dsn="localhost/xe"
)
```

### 4. Create database objects

Run the SQL script:

```sql
database.sql
```

### 5. Start the application

```bash
python hospital_management_system.py
```

## 📸 Screenshots

Add screenshots of:

* Dashboard
* Add Patient
* Add Doctor
* Appointment Booking
* Billing System

## 🎯 Learning Outcomes

* Database Design and Management
* Oracle SQL Queries
* GUI Development using Tkinter
* CRUD Operations
* Python Application Development
* Database Connectivity

## 🔮 Future Enhancements

* User Authentication
* Search and Filter Functionality
* Patient Medical History
* Report Generation
* Email Notifications
* Advanced Analytics Dashboard

## 👩‍💻 Author

**Riya Hardeep Kaur**

GitHub: https://github.com/riyahardeepkaur-gif

---

⭐ If you found this project useful, consider giving it a star.
