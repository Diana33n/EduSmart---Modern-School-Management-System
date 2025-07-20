# EduSmart - Modern School Management System

EduSmart is a **web-based and mobile-friendly platform** designed to automate and optimize the daily operations of modern schools. It provides an integrated solution for administration, teachers, students, and parents, focusing on flexibility, scalability, and security.

---

## Overview

With the increasing number of students and staff, schools face challenges in managing registrations, schedules, communication, and payments. EduSmart addresses these challenges with a comprehensive digital system enabling:

* Efficient schedule management
* Real-time communication
* Secure payments and accounting
* Assignment and exam management
* Smart reporting and analytics

EduSmart supports both remote and in-person learning, ensuring continuity even during emergencies such as COVID-19.

---

## Key Features

### Communication

* Teacher-student and teacher-parent messaging
* Announcements and notification system
* Auto-generated online meeting links
* Collaborative forums for subjects

### Task and Schedule Management

* Automatic load-balancing for assignments
* Student-specific calendars with reminders
* Weekly plan automation approved by principals

### Accounting

* Online fee payments with tracking and reminders
* Automated payroll and financial reporting
* Inventory management for school supplies

### Management

* Grade publishing with notifications
* Biometric attendance for staff
* Complaint tracking system
* Gamification features to engage students

### Registration

* Online student registration with document upload
* Automated seat availability tracking
* Teacher application portal with filters and interview scheduling

---

## Technical Overview

* Follows Agile methodology for iterative delivery
* Three-Tier Architecture (UI, Business Logic, Data Layer)
* Role-Based Access Control (RBAC) and data encryption
* Scalable infrastructure with load balancers
* Mobile integration for attendance and notifications

---

## Demo and Diagrams

The system flow, use-cases, and architecture diagrams are available in the attached PDF and Lucidchart links.

---

## Team

| Name            | Student Number |
| --------------- | -------------- |
| Sarah Hassouneh | 1210068        |
| Dana Hafithah   | 1211234        |
| Doaa Hatu       | 1211088        |
| Leen Daraghmeh  | 1210904        |
| Diana Naseer    | 1210363        |

Instructor: Dr. Samer Zein
Course: COMP433 - Phase 4
Date: 15 Jan 2025

---

## Installation

### Prerequisites

* Python 3.x
* Node.js and npm (for frontend)
* MySQL or PostgreSQL database
* Docker (optional for containerized deployment)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/<your-org>/EduSmart.git
```

2. Install backend dependencies:

```bash
cd EduSmart/backend
pip install -r requirements.txt
```

3. Install frontend dependencies:

```bash
cd ../frontend
npm install
```

4. Configure environment variables:
   Create a `.env` file in both frontend and backend directories with required settings.

5. Run the application:

```bash
# Start backend
cd backend
python manage.py runserver

# Start frontend
cd ../frontend
npm start
```

---

## License

This project is developed as part of COMP433 - Group Assignment Phase 4 and is intended for academic use only.

---
