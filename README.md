#  Student Management System

## 📌 Project Overview

The **Student Management System** is a web application developed to manage student records efficiently.
It allows administrators and staff members to add, update, view, and delete student information through a simple and user-friendly interface.

This project is built using **Python, Django, HTML, CSS, Bootstrap, and SQLite**, and demonstrates the implementation of authentication, role-based access control, and CRUD operations.

## Features

*  **User Authentication**

  * Login and Logout system
  * Secure user authentication

*  **Role-Based Access**

  * Admin can view all students
  * Staff can only manage students they added

*  **Dashboard**

  * Shows total students
  * Shows total staff
  * Displays student's data insights

*  **Add Student**

  * Add new student details including:

    * Name
    * Email
    * Age
    * Place
    * Gender
    * State
    * Skillset

*  **Student List**

  * Displays all students in a table format
  * Search students by name
  * Pagination for better navigation

*  **Student Details**

  * Click on student name to view full details

*  **Edit Student**

  * Update existing student details

*  **Delete Student**

  * Remove student records securely

---

## 🛠 Technologies Used

* **Backend:** Python, Django
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite
* **Visualization:** Chart.js (for dashboard charts)

---

## 📂 Project Structure

```
student_management/
│
├── app/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── migrations/
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── add_student.html
│   ├── student_list.html
│   ├── student_detail.html
│
├── manage.py
├── db.sqlite3
└── requirements.txt
```

---

## ⚙️ Installation

1️⃣ Clone the repository

```
git clone https://github.com/yourusername/student-management-system.git
```

2️⃣ Navigate to the project folder

```
cd student-management-system
```

3️⃣ Install dependencies

```
pip install -r requirements.txt
```

4️⃣ Run migrations

```
python manage.py migrate
```

5️⃣ Create superuser

```
python manage.py createsuperuser
```

6️⃣ Run the development server

```
python manage.py runserver
```

7️⃣ Open in browser

```
http://127.0.0.1:8000/
```

---

##  Future Improvements

* Student profile photo upload
* Export student data to Excel
* Advanced dashboard analytics
* REST API integration
* Deployment on cloud platforms

---

## 👨‍💻 Author

**Shavala Sundar Raju**

* B.Tech Graduate
* Interested in Python Full Stack, HTML, CSS, JavaScript, Django, SQL, Machine Learning.

---

## ⭐ Acknowledgment

This project was developed as part of a learning exercise to understand **Django web development and full-stack application design**.
