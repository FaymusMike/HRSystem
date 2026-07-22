# HRSystem

# Personnel Management Information System (PMIS)

<p align="center">
  <img src="./assets/images/logo/logo.png" alt="PMIS Logo" width="120">
</p>

<h1 align="center">Personnel Management Information System</h1>

<p align="center">
A modern Human Resource Management web application built with <strong>HTML5, CSS3, Bootstrap 5, Vanilla JavaScript, and Local Storage</strong>.
</p>

---

## 📖 Project Overview

The **Personnel Management Information System (PMIS)** is a modern web-based Human Resource Management application designed to simplify the administration of employee records within an organization.

The system enables Human Resource (HR) personnel to securely manage employee information, monitor departmental records, generate reports, and perform personnel-related administrative tasks through an intuitive and responsive user interface.

Unlike traditional HR systems that rely on backend servers and databases, this project demonstrates how a complete personnel management solution can be implemented entirely on the client-side using **HTML5**, **CSS3**, **Bootstrap 5**, **Vanilla JavaScript**, and **Browser Local Storage**.

This project was developed as a **Final Year Computer Science Project** titled:

> **Design and Implementation of a Personnel Management Information System**

---

# 🎯 Objectives

The objectives of this project are to:

- Digitize personnel record management
- Eliminate paper-based employee records
- Improve data organization and retrieval
- Reduce administrative workload
- Provide an intuitive HR management dashboard
- Demonstrate CRUD operations without a backend database
- Showcase modern frontend software engineering practices
- Provide a responsive and accessible user experience

---

# ✨ Key Features

## 🔐 Authentication

- Administrator Login
- Local Storage Authentication
- Session Management
- Protected Pages
- Logout Functionality
- Remember Login Session

---

## 📊 Dashboard

- Total Employees
- Active Employees
- Inactive Employees
- Suspended Employees
- Retired Employees
- Male Employees
- Female Employees
- Total Departments
- New Employees This Month

### Interactive Dashboard

- Animated Statistic Cards
- Real-time Data Updates
- Department Charts
- Gender Distribution
- Employee Status Statistics
- Recent Employees Table
- Quick Action Buttons

---

## 👨‍💼 Employee Management

Complete CRUD Operations

- Add Employee
- View Employee
- Update Employee
- Delete Employee

Employee Details Include

- Employee ID
- Passport Photograph
- Personal Information
- Contact Information
- Employment Information
- Salary Information
- Emergency Contact
- Employment Status

---

## 🏢 Department Management

- Add Department
- Edit Department
- Delete Department
- Search Departments
- Employee Count per Department

---

## 📈 Reports & Analytics

- Employees by Department
- Employees by Gender
- Employees by Status
- Monthly Employee Registration
- Department Distribution
- Interactive Charts using Chart.js

---

## 🔎 Search & Filtering

- Live Search
- Instant Filtering
- Sort by Name
- Sort by Department
- Sort by Date Added
- Sort by Employment Date
- Pagination

---

## 📄 Export & Printing

- Export Employees to CSV
- Import Employees from CSV
- Backup Application Data
- Restore Application Data
- Export Employee Profile to PDF
- Print Employee Card

---

## 🌙 User Experience

- Dark Mode
- Light Mode
- Responsive Layout
- Animated Cards
- Bootstrap Toast Notifications
- Loading Spinner
- Confirmation Dialogs
- Smooth Page Transitions
- Mobile Friendly
- Accessible Interface

---

# 🖥️ Technology Stack

| Technology | Purpose |
|------------|----------|
| HTML5 | Application Structure |
| CSS3 | Styling |
| Bootstrap 5 | Responsive UI Framework |
| Vanilla JavaScript (ES6) | Application Logic |
| Bootstrap Icons | Icons |
| Chart.js | Reports & Charts |
| html2pdf.js | PDF Generation |
| Local Storage | Data Persistence |

---

# 📂 Project Structure

```text
Personnel-Management-System/
│
├── index.html
├── dashboard.html
├── employees.html
├── employee-form.html
├── employee-profile.html
├── departments.html
├── reports.html
├── settings.html
│
├── assets/
│
│   ├── css/
│   │      style.css
│   │      components.css
│   │      responsive.css
│   │
│   ├── js/
│   │      app.js
│   │      storage.js
│   │      employee.js
│   │      dashboard.js
│   │      ui.js
│   │      main.js
│   │
│   ├── images/
│   ├── icons/
│
├── vendor/
│      bootstrap/
│      chartjs/
│      html2pdf/
│
└── README.md
```

---

# 💾 Local Storage Architecture

The application stores all information inside the browser using Local Storage.

```text
users
employees
departments
settings
theme
currentUser
lastEmployeeNumber
```

All data is serialized as JSON.

---

# 🔑 Default Login Credentials

Administrator Account

```text
Username: admin
Password: 12345
```

These credentials are automatically created the first time the application is launched.

---

# 📸 Employee Information

Each employee record contains:

### Personal Information

- Employee ID
- Profile Photo
- First Name
- Middle Name
- Last Name
- Gender
- Date of Birth
- Marital Status
- Nationality
- State
- Local Government Area

### Contact Information

- Phone Number
- Email Address
- Residential Address

### Employment Information

- Department
- Position
- Employment Type
- Employment Date
- Salary Grade
- Monthly Salary
- Employment Status

### Emergency Contact

- Contact Name
- Relationship
- Contact Number

---

# 📊 Dashboard Statistics

The dashboard automatically displays:

- Total Employees
- Active Employees
- Inactive Employees
- Suspended Employees
- Retired Employees
- Male Employees
- Female Employees
- Total Departments
- Employees Added This Month

All statistics update automatically whenever employee data changes.

---

# 📈 Reports

The Reports Module provides:

- Employee Distribution by Department
- Employee Gender Analysis
- Employment Status Analysis
- Monthly Employee Registration
- Department Statistics

Charts are generated using **Chart.js**.

---

# 📤 Export Features

The application supports:

- Export Employees as CSV
- Import Employees from CSV
- Backup Local Storage
- Restore Backup
- Export Employee Profile as PDF
- Print Employee Information

---

# 🎨 User Interface Features

- Bootstrap 5 Responsive Layout
- Modern Dashboard
- Glassmorphism Cards
- Gradient Headers
- Professional Color Palette
- Responsive Sidebar
- Offcanvas Navigation
- Bootstrap Tables
- Bootstrap Modals
- Bootstrap Toast Notifications
- Responsive Forms
- Animated Counters
- Interactive Charts
- Breadcrumb Navigation

---

# 🌙 Dark Mode

The application includes a complete Dark Mode.

Features include:

- One-click Theme Switching
- Automatic Theme Persistence
- Local Storage Theme Saving
- Optimized Color Contrast

---

# 🔒 Security Features

Although this project operates entirely on the client side, it implements several security-oriented practices suitable for a frontend-only application:

- Session Authentication
- Route Protection
- Input Validation
- Required Field Validation
- Email Validation
- Duplicate Employee Prevention
- Confirmation Before Deletion
- Local Storage Data Validation

---

# 📱 Responsive Design

The application is fully responsive across:

- Desktop
- Laptop
- Tablet
- Mobile Devices

Powered by Bootstrap 5 Grid System.

---

# 🚀 Future Improvements

Potential enhancements include:

- Backend Integration
- MySQL Database
- REST API
- Role-Based Authentication
- Multi-User Access
- Payroll Management
- Attendance Tracking
- Leave Management
- Performance Evaluation
- Email Notifications
- Cloud Storage
- Audit Logs
- Two-Factor Authentication
- QR Code Employee Cards
- Biometric Attendance
- Real-time Notifications

---

# 📚 Learning Outcomes

This project demonstrates practical implementation of:

- CRUD Operations
- Client-side Authentication
- Local Storage Management
- DOM Manipulation
- Modular JavaScript Architecture
- Responsive Web Design
- Data Visualization
- PDF Generation
- CSV Processing
- User Experience Design
- Human Resource Information Systems

---

# ⚠️ Project Limitations

This project intentionally uses **Local Storage** instead of a traditional database for academic demonstration purposes.

As a result:

- Data is stored only within the current browser.
- Clearing browser data removes all records.
- The application is designed for demonstration and educational purposes.
- Multi-user collaboration is not supported.
- Server-side authentication is not implemented.

---

# 👨‍💻 Developer

**Project Title**

Design and Implementation of a Personnel Management Information System

**Developer**

Michael Adedeji Fayoyiwa

**Programme**

Bachelor of Science (B.Sc.) in Computer Science

**Project Type**

Final Year Project

---

# 📄 License

This project is developed strictly for academic purposes as part of the requirements for the award of a Bachelor of Science (B.Sc.) degree in Computer Science.

Feel free to use this project for learning and educational purposes.

---

# ⭐ Acknowledgements

Special appreciation to:

- Project Supervisor
- Department of Computer Science
- Bootstrap Team
- Chart.js Contributors
- html2pdf.js Contributors
- Open Source Community

---

<p align="center">
<strong>Personnel Management Information System (PMIS)</strong><br>
Built with ❤️ using HTML5, CSS3, Bootstrap 5, Vanilla JavaScript, Chart.js, html2pdf.js, and Local Storage.
</p>