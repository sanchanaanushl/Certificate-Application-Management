# Certificate Application Management System

## 📌 Project Overview

The **Certificate Application Management System** is a Python-based desktop application developed to simplify and manage the process of applying for, reviewing, approving, and generating certificates in an educational institution.

The application provides separate interfaces for administrators and students. It uses Tkinter to create a graphical user interface and SQLite to store and manage student details, administrator information, and certificate applications.

The system reduces manual paperwork, improves record management, and makes certificate processing more organized and efficient.

## 🎯 Objectives

* To develop a user-friendly certificate management application.
* To maintain student information digitally.
* To provide separate login facilities for administrators and students.
* To allow students to apply for certificates and track their application status.
* To enable administrators to approve or reject certificate applications.
* To generate and download certificates in PDF format.
* To generate student reports and export information to Excel.
* To reduce manual work and minimize data-entry errors.

## ✨ Key Features

### 👨‍💼 Administrator Module

* Secure administrator login.
* Dashboard with student and application statistics.
* Add, edit, delete, search, and view student records.
* View and manage certificate applications.
* Approve or reject applications.
* Generate course completion certificates.
* View reports and export student information to Excel.
* Change administrator password.

### 🎓 Student Module

* Student login using register number and password.
* View student dashboard and profile.
* Apply for certificates.
* View submitted applications.
* Track application status: Pending, Approved, or Rejected.
* Access approved certificates.
* Download certificates in PDF format.
* Change password.

## 🛠️ Technologies Used

| Technology | Purpose                             |
| ---------- | ----------------------------------- |
| Python     | Application logic and functionality |
| Tkinter    | Graphical User Interface (GUI)      |
| SQLite     | Database management                 |
| Pillow     | Image and logo handling             |
| ReportLab  | PDF certificate generation          |
| OpenPyXL   | Excel report generation and export  |

## 🗂️ Main Project Modules

* `main.py` – Main page and login selection.
* `admin_login.py` – Administrator authentication.
* `admin_dashboard.py` – Student management, applications, certificates, reports, and settings.
* `student_login.py` – Student authentication.
* `student_dashboard.py` – Student profile, applications, and certificate downloads.
* `database.py` – Database creation and table management.
* `certificate_generator.py` – Certificate generation.
* `scrollable_frame.py` – Reusable scrollable interface component.

## 🗄️ Database Design

The application uses an SQLite database named `certificate.db`.

The database contains three main tables:

* **admin:** Stores administrator login information.
* **students:** Stores student details, course information, and related records.
* **applications:** Stores certificate application details, application dates, certificate types, and application statuses.

## 💻 System Requirements

### Hardware

* Computer or laptop.
* Minimum 4 GB RAM.
* At least 1 GB of free storage.

### Software

* Windows operating system.
* Python 3.x.
* Tkinter.
* SQLite.
* Pillow.
* ReportLab.
* OpenPyXL.

## 🚀 How to Run the Project

1. Install Python 3.x on your computer.

2. Download or clone this repository.

3. Open the project folder in your code editor or terminal.

4. Install the required libraries:

   ```bash
   pip install Pillow reportlab openpyxl
   ```

5. Run the database setup script if the database has not been initialized:

   ```bash
   python database.py
   ```

6. Start the application:

   ```bash
   python main.py
   ```

**Note:** Running `database.py` recreates the database in the documented implementation and can delete existing database records. Back up your database before running it again.

## 🔒 Security and Reliability

The application provides separate login facilities for administrators and students, password-change functionality, and parameterized database queries for user-related operations. These features help organize access and reduce certain database security risks.

## 🔮 Future Enhancements

* Online certificate application access.
* Email notifications for application status updates.
* Cloud database integration.
* Support for multiple educational institutions.
* Additional certificate types and reporting features.

## 🏁 Conclusion

The Certificate Application Management System provides a structured digital solution for managing student records and certificate applications. By combining Python, Tkinter, and SQLite, the project simplifies application processing, certificate generation, and report management through a user-friendly desktop interface.

## 👩‍💻 Project Information

**Project Name:** Certificate Application Management System
**Project Type:** Desktop Application
**Programming Language:** Python
**Database:** SQLite
**Interface:** Tkinter GUI

---

*Developed as an academic project to improve certificate application and management processes in educational institutions.*
