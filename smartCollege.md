# Smart College Management System with AI-Based Predictive Analytics

---

# 1. Title of the Project

## Smart College Management System with AI-Based Predictive Analytics

---

# 2. Category

## Category: Web Application

The project is a web-based application designed to manage academic and administrative activities within educational institutions.

---

# 3. Description / Introduction to Project

## Introduction

**Smart College Management System with AI-Based Predictive Analytics** is a web-based application developed to manage student, faculty, course, attendance, and academic records efficiently.

The system uses **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques to predict student performance and identify students who may be at academic risk.

It provides **role-based access control** for:

* Administrators
* Faculty Members
* Students

The system improves:

* Academic management
* Transparency
* Security
* Decision-making

through predictive analytics and dashboard visualization.

---

# 4. Development Tools

## Front-End Tools

### HTML5

Used for creating web page structures.

### CSS3

Used for styling and layout design.

### Bootstrap 5

Used for responsive user interface development.

### JavaScript

Used for client-side functionality and interactivity.

### Chart.js

Used for analytics dashboards and data visualization.

---

## Back-End Tools

### Python 3.11

Primary programming language used for backend development.

### Flask Framework

Used for developing the web application and handling requests.

### SQLAlchemy ORM

Used for database interaction and object-relational mapping.

### SQLite Database

Used for storing application data.

### Scikit-Learn

Used for machine learning model development and prediction.

### GitHub

Used for source code management and version control.

### Render.com Hosting

Used for cloud deployment and application hosting.

---

# 5. Modules of the Project

## 1. Admin Module

### Functions

* Manage students
* Manage faculty
* Manage courses
* View reports
* User approval

---

## 2. Faculty Module

### Functions

* Attendance management
* Grade management
* Student performance tracking
* Prediction viewing

---

## 3. Student Module

### Functions

* View attendance
* View grades
* Access academic records
* View performance prediction

---

## 4. AI Prediction Module

### Functions

* Student risk prediction
* Admission trend prediction
* Analytics generation

---

## 5. Notification Module

### Functions

* Email notifications
* Alerts and updates

---

# 6. Database Model (ER Diagram Tables)

## Student Table

| Field      | Description               |
| ---------- | ------------------------- |
| Student_ID | Unique Student Identifier |
| Name       | Student Name              |
| Email      | Student Email             |
| Course     | Enrolled Course           |
| Semester   | Current Semester          |

---

## Faculty Table

| Field      | Description               |
| ---------- | ------------------------- |
| Faculty_ID | Unique Faculty Identifier |
| Name       | Faculty Name              |
| Department | Department Name           |
| Email      | Faculty Email             |

---

## Course Table

| Field       | Description              |
| ----------- | ------------------------ |
| Course_ID   | Unique Course Identifier |
| Course_Name | Course Name              |
| Credits     | Course Credits           |

---

## Attendance Table

| Field                 | Description           |
| --------------------- | --------------------- |
| Attendance_ID         | Attendance Record ID  |
| Student_ID            | Student Reference     |
| Course_ID             | Course Reference      |
| Attendance_Percentage | Attendance Percentage |

---

## Grade Table

| Field      | Description       |
| ---------- | ----------------- |
| Grade_ID   | Grade Record ID   |
| Student_ID | Student Reference |
| Marks      | Obtained Marks    |
| Grade      | Assigned Grade    |

---

## Prediction Table

| Field         | Description             |
| ------------- | ----------------------- |
| Prediction_ID | Prediction Record ID    |
| Student_ID    | Student Reference       |
| Risk_Level    | Predicted Academic Risk |

---

## ER Diagram Structure

```text id="w1z3vt"
STUDENT
   |
   | 1:M
   |
ATTENDANCE
   |
   | M:1
   |
COURSE

STUDENT
   |
   | 1:M
   |
GRADE

STUDENT
   |
   | 1:1
   |
PREDICTION

FACULTY
   |
   | 1:M
   |
COURSE
```

---

# 7. Interface Design

## Login Page

### Purpose

Secure authentication for users.

---

## Admin Dashboard

### Purpose

Manage college operations.

Functions:

* Student management
* Faculty management
* Course management
* Reports

---

## Faculty Dashboard

### Purpose

Manage attendance and grades.

Functions:

* Attendance entry
* Grade management
* Student tracking

---

## Student Dashboard

### Purpose

View academic records and AI predictions.

Functions:

* Attendance tracking
* Grade viewing
* Prediction reports

---

## Analytics Dashboard

### Purpose

Display charts, reports, and prediction insights.

Functions:

* Student performance charts
* Risk analysis
* Admission trends

---

# 8. Area of Use / Future Enhancement

## Area of Use

The system can be used in:

* Colleges
* Universities
* Educational Institutions

---

## Future Enhancements

* Mobile Application
* QR-Based Attendance System
* Parent Portal
* Deep Learning Models
* Advanced Predictive Analytics
* NLP-Based Student Feedback Analysis

---

# 9. Introduction to Development Tools

## Python

Used for backend programming and application logic.

---

## Flask

Used for developing web applications and handling requests.

---

## SQLite

Used for storing student and academic records.

---

## SQLAlchemy

Used for database connectivity and ORM operations.

---

## Bootstrap

Used for responsive user interface design.

---

## Chart.js

Used for graphical representation of data.

---

## Scikit-Learn

Used for machine learning model development and predictive analytics.

---

## GitHub

Used for version control and collaborative development.

---

## Render.com

Used for cloud deployment and hosting the application online.

---

# 10. Conclusion

> The Smart College Management System with AI-Based Predictive Analytics is an intelligent and secure web application that helps educational institutions manage academic activities efficiently. The system improves student monitoring, automates workflows, enhances security, and provides AI-based predictions for better academic planning. It offers a modern, scalable, and user-friendly solution for colleges and universities.

---

# 30-SECOND VIVA INTRODUCTION

> My project is Smart College Management System with AI-Based Predictive Analytics. It is a web-based application developed using Python, Flask, SQLite, and Scikit-Learn to manage students, faculty, courses, attendance, and academic records. The system uses Artificial Intelligence and Machine Learning techniques to predict student performance and identify students at academic risk. It provides role-based access control, analytics dashboards, and automated reporting, helping educational institutions improve academic management and decision-making.
