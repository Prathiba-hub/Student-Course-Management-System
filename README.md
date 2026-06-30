# Student Course Management and Learning Progress Tracking System

## Project Overview

The **Student Course Management and Learning Progress Tracking System** is a Full Stack Web Application designed to simplify academic course enrollment and learning management. The system allows students to register, log in, browse available courses, enroll in courses, access learning materials, track their learning progress, and receive notifications.

Administrators can manage students, courses, enrollments, and monitor overall learning progress through an interactive dashboard.

---

# Problem Statement

Many educational institutions still manage course enrollment and student learning progress manually or through multiple disconnected systems. This creates several challenges:

- Students find it difficult to search for available courses.
- Course registration is often time-consuming.
- Learning progress cannot be tracked efficiently.
- Course materials are scattered across different platforms.
- Administrators struggle to manage students, courses, and enrollments.

This project provides a centralized web-based platform that simplifies course management and improves the overall learning experience.

---

# Project Objectives

- Provide secure student registration and login.
- Allow students to browse available courses.
- Enable students to enroll in courses.
- Track learning progress for each course.
- Allow administrators to manage courses and students.
- Generate progress reports.
- Send notifications and updates.
- Maintain secure access to academic information.

---

# Features

## Student Features

- User Registration
- Secure Login
- View Profile
- Browse Available Courses
- Search Courses
- Enroll in Courses
- View Enrolled Courses
- Access Course Materials
- Track Learning Progress
- View Completion Percentage
- Receive Notifications
- Logout

---

## Administrator Features

- Secure Admin Login
- Add New Courses
- Update Course Details
- Delete Courses
- Manage Students
- View Student Enrollments
- Monitor Learning Progress
- Generate Reports
- Dashboard Analytics

---

# Tech Stack

## Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript
- React.js

## Backend

- Node.js
- Express.js

## Database

- MongoDB

## Authentication

- JWT (JSON Web Token)
- bcrypt

## API Testing

- Postman

## Version Control

- Git
- GitHub

## Deployment

- Render
- Vercel
- Railway

---

# Project Structure

```
Student-Course-Management-System/

│
├── frontend/
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── css/
│   ├── js/
│   └── images/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── config/
│
├── database/
│
├── README.md
├── package.json
└── .gitignore
```

---

# User Roles

## Student

Students can:

- Register
- Login
- Browse Courses
- Search Courses
- Enroll in Courses
- View Learning Materials
- Track Progress
- Receive Notifications

---

## Administrator

Administrators can:

- Login Securely
- Manage Courses
- Manage Students
- View Enrollments
- Generate Reports
- View Dashboard Analytics

---

# Application Pages

## Home Page

- Welcome Section
- Navigation Bar
- Featured Courses
- About Project
- Login Button
- Register Button

---

## Login Page

- Email
- Password
- Login Button
- Forgot Password
- Register Link

---

## Register Page

- Name
- Email
- Department
- Password
- Confirm Password
- Register Button

---

## Dashboard

- Welcome Message
- Total Courses
- Enrolled Courses
- Completed Courses
- Progress Bar
- Notifications
- Logout Button

---

# Application Workflow

```
Home Page
      │
      ▼
Register
      │
      ▼
Login
      │
      ▼
Dashboard
      │
      ├── Browse Courses
      ├── Search Courses
      ├── Enroll Course
      ├── Learning Materials
      ├── Track Progress
      └── Logout
```

---

# Database Tables

## Students

- Student ID
- Name
- Email
- Password
- Department

---

## Courses

- Course ID
- Course Name
- Instructor
- Duration
- Description
- Category

---

## Enrollments

- Enrollment ID
- Student ID
- Course ID
- Enrollment Date

---

## Progress

- Progress ID
- Student ID
- Course ID
- Completed Modules
- Progress Percentage

---

# Future Enhancements

- Email Notifications
- Online Assessments
- Assignment Submission
- Certificate Generation
- Discussion Forum
- AI-based Course Recommendation
- Mobile Responsive Design

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Student-Course-Management-System.git
```

Go to the project directory:

```bash
cd Student-Course-Management-System
```

Install dependencies:

```bash
npm install
```

Start the server:

```bash
npm start
```

---

# Project Status

Currently Under Development

---

# Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Create a Pull Request.

---

# License

This project is developed for educational purposes as part of a Full Stack Web Development course.

---

# Author

**Prathiba Devendiran**

B.Sc. Computer Science with Artificial Intelligence

SDNB Vaishnav College for Women
