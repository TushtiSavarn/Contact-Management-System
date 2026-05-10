# 📇 ContactMaster – Contact Management System

A modern and user-friendly **Contact Management System** built using **Python, MySQL, Tkinter, and ttkbootstrap** for an elegant graphical interface and efficient contact management.

This application allows users to seamlessly **add, update, delete, search, and manage contacts** with persistent MySQL database storage and a clean responsive UI.

---

# ✨ Features

✔️ Modern GUI using **Tkinter + ttkbootstrap**
✔️ CRUD Operations – Add, View, Update & Delete Contacts
✔️ Live Search & Sorting Functionality
✔️ Persistent Storage using **MySQL Database**
✔️ Input Validation & Duplicate Prevention
✔️ Responsive and User-Friendly Interface
✔️ Error Handling for Better Reliability

---

# 🛠️ Tech Stack

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| Python       | Core Programming Language |
| Tkinter      | GUI Development           |
| ttkbootstrap | Modern UI Styling         |
| MySQL        | Database Storage          |

---

# 📂 Project Structure

```bash
Contact-Management-System/
│
├── Contactmaster.py
├── requirements.txt
├── README.md
└── schema.sql
```

---

# 🚀 Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/TushtiSavarn/Contact-Management-System.git
cd Contact-Management-System
```

---

## 2️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Configure MySQL Database

Create a database in MySQL:

```sql
CREATE DATABASE contactmaster;
```

Create the contacts table:

```sql
CREATE TABLE contacts (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100) NOT NULL,
    phone VARCHAR(15) UNIQUE,
    email VARCHAR(100) UNIQUE
);
```

---

## 4️⃣ Run the Application

```bash
python Contactmaster.py
```

---

# 🧠 Functionalities

### ➕ Add Contact

Save new contact details securely into the database.

### 🔍 Search Contacts

Quickly search contacts using name, phone number, or email.

### ✏️ Update Contact

Modify existing contact details easily.

### ❌ Delete Contact

Safely remove contacts from the system.

### 📋 View Contacts

Display all stored contacts in an organized format.

---

# 📸 Screenshots

> Add application screenshots here for better project presentation.

Example:

* Main Dashboard
* Add Contact Window
* Search Functionality
* Update/Delete Features

---

# 💡 Future Improvements

✔ Add CSV/Excel Export Feature
✔ Add Import Contacts Feature
✔ Add User Authentication System
✔ Build Executable Desktop Installer (.exe)
✔ Add Dark/Light Theme Toggle
✔ Add Contact Grouping & Tagging

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

* GUI Development with Tkinter
* Database Integration using MySQL
* CRUD Operations
* Input Validation & Error Handling
* Python Application Development
* User Interface Design

---

# 👩‍💻 Author

**Tushti Savarn**
MCA Student | Full-Stack & AI/ML Enthusiast

GitHub: https://github.com/TushtiSavarn
Medium: https://medium.com/@tushtisavran
Linkedln: https://www.linkedin.com/in/tushti-savarn/

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
