# Curavita – DevSecOps CI/CD Pipeline for Secure Medical Records Management

## Project Positioning

**Curavita is a demonstration application (vehicle), while the actual project is the DevSecOps CI/CD Engine developed around it. The healthcare application serves as a real-world workload to demonstrate automated security scanning, CI/CD automation, Docker containerization, vulnerability management, and cloud deployment.**

---

# 1. TITLE OF THE PROJECT

## Title

**Curavita – DevSecOps CI/CD Pipeline for Secure Medical Records Management**

### Explanation

The project focuses on implementing a complete DevSecOps pipeline where every code change automatically undergoes:

* Security scanning
* Automated testing
* Docker image creation
* Container vulnerability scanning
* Deployment to AWS EC2

The Curavita healthcare application is used as the sample application to demonstrate these DevSecOps practices.

---

# 2. CATEGORY

## Primary Category

**DevSecOps and Cloud Computing Project**

## Secondary Category

**Web Application Project**

### Why?

Because:

* Main focus = DevSecOps pipeline
* Secondary focus = Flask healthcare web application

### One-Line Viva Answer

> This is primarily a DevSecOps CI/CD automation project and secondarily a web application project.

---

# 3. INTRODUCTION / SRS

## Problem

Traditional deployment processes are:

* Manual
* Slow
* Error-prone
* Insecure

Healthcare systems handle sensitive patient information, making security critical.

## Solution

The project implements:

* Automated CI/CD pipeline
* Automated security scanning
* Docker containerization
* Cloud deployment
* Role-based access control
* Audit logging

## Objectives

* Automate software delivery
* Integrate security into CI/CD
* Deploy securely on cloud
* Reduce human errors
* Improve application security

---

# 4. DEVELOPMENT TOOLS

## Frontend Tools

### HTML5

Used for:

* Structure of webpages

### Bootstrap 5

Used for:

* Responsive UI
* Faster development

### Chart.js

Used for:

* Analytics graphs
* Dashboard visualization

---

## Backend Tools

### Python

Used because:

* Simple
* Powerful
* Large ecosystem

### Flask

Used because:

* Lightweight
* Easy to integrate
* Flexible architecture

### SQLAlchemy

Used for:

* Database ORM

---

## Database

### PostgreSQL

Used because:

* Open source
* Secure
* Relational database
* ACID compliance

---

## DevSecOps Tools

| Tool           | Purpose                           |
| -------------- | --------------------------------- |
| Git            | Version Control                   |
| GitHub         | Code Repository                   |
| GitHub Actions | CI/CD Automation                  |
| Docker         | Containerization                  |
| Bandit         | Python SAST Scanning              |
| pip-audit      | Dependency Vulnerability Scanning |
| Trivy          | Container Vulnerability Scanning  |
| AWS EC2        | Cloud Hosting                     |

---

# 5. MODULES OF THE PROJECT

## The project contains two layers:

---

## A. DevSecOps Layer

### Module 1: Source Code Management

* Git
* GitHub

### Module 2: Continuous Integration

* GitHub Actions

### Module 3: Security Scanning

* Bandit
* pip-audit

### Module 4: Automated Testing

* Pytest

### Module 5: Containerization

* Docker

### Module 6: Container Security

* Trivy

### Module 7: Continuous Deployment

* AWS EC2

---

## B. Application Layer

### Authentication Module

* Login and session management

### User Management Module

* Role handling

### Medical Records Module

* File upload and management

### Approval Workflow Module

* Approval and rejection process

### Audit Log Module

* Activity tracking

### Notification Module

* Alerts and updates

### Analytics Module

* Reports and charts

---

# 6. DATABASE MODEL / ER DIAGRAM

## ER Relationship Structure

```text
USERS
  |
  |
DEPARTMENTS

USERS
  |
  |
MEDICAL_RECORDS

MEDICAL_RECORDS
  |
  |
APPROVALS

USERS
  |
  |
AUDIT_LOGS

USERS
  |
  |
NOTIFICATIONS
```

## Table Descriptions

### Users

Stores:

* Username
* Email
* Password
* Role

### Departments

Stores hospital departments.

### Medical Records

Stores uploaded files and patient records.

### Approvals

Stores consultant approval/rejection decisions.

### Audit Logs

Stores user activity records.

### Notifications

Stores alerts and updates.

---

# 7. INTERFACE DESIGN

## Login Page

Purpose:

* Authentication

## Admin Dashboard

Purpose:

* User management
* System monitoring

## Doctor Dashboard

Purpose:

* Upload records

## Consultant Dashboard

Purpose:

* Review records

## Patient Dashboard

Purpose:

* View approved records

## Analytics Dashboard

Purpose:

* Visualize data and reports

---

# 8. AREA OF USE / FUTURE ENHANCEMENT

## Current Use

Can be used in:

* Hospitals
* Clinics
* Diagnostic Centers

## Future Enhancements

* Kubernetes deployment
* AI-powered diagnosis assistance
* Blockchain audit verification
* Mobile application
* Multi-hospital integration
* Multi-cloud deployment
* SIEM integration
* Real-time monitoring

---

# 9. INTRODUCTION TO DEVELOPMENT TOOLS

### Git

Version control system.

### GitHub

Remote repository hosting platform.

### GitHub Actions

Automates CI/CD workflows.

### Docker

Packages applications into containers.

### AWS EC2

Provides cloud-based virtual servers.

### Bandit

Scans Python code for vulnerabilities.

### pip-audit

Scans Python dependencies for known vulnerabilities.

### Trivy

Scans Docker images and containers.

### PostgreSQL

Stores application data securely.

### Flask

Backend web framework used for application development.

---

# 10. CONCLUSION

> This project successfully demonstrates a complete DevSecOps CI/CD pipeline integrated with a Flask-based healthcare application. The system automates security scanning using Bandit, pip-audit, and Trivy, performs automated testing, builds Docker containers, and deploys securely to AWS EC2. The project proves how DevSecOps practices can improve software security, deployment speed, reliability, and scalability while reducing manual effort and human errors.

---

# FINAL 30-SECOND INTRODUCTION (VERY IMPORTANT)

### Viva Introduction

> My project is Curavita – DevSecOps CI/CD Pipeline for Secure Medical Records Management. Although Curavita is a Flask-based healthcare web application, the primary focus of the project is the DevSecOps engine built around it. The application serves as a vehicle to demonstrate CI/CD automation, security integration, Docker containerization, vulnerability scanning using Bandit, pip-audit, and Trivy, and automated deployment to AWS EC2 through GitHub Actions. The goal is to achieve secure, automated, and reliable software delivery.
