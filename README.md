#  Job Portal – Full Stack Web Application

The **Job Portal** is a comprehensive full-stack web application developed for learning and demonstration of real-world job marketplace functionality. It connects job seekers and employers while allowing admin oversight. The platform enables job posting, application tracking, subscription management, and user control.

##  Project Overview

This platform supports:

-  **Employers/Companies** to buy subscriptions, post job openings, manage listings, and view & shortlist applicants based on their active plan.
-  **Job Seekers** to register, browse jobs, apply for positions, and track application status.
-  **Admins** to manage users, CRUD subscription packages, monitor posted jobs, and track platform metrics.

##  Key Features

-  Subscription-based job posting for companies
-  Job posting, editing, and deleting (restricted by active subscription)
-  Job searching, filtering, and application by job seekers
-  Employers can view applicant lists based on subscription and **shortlist applicants with interview date**
-  Role-based access: Admin, Employer, Job Seeker
-  Admin dashboard for tracking job statistics and user activity
-  Admin can create, update, delete subscription plans
-  Resume upload and profile management

## Tech Stack

### Frontend
- **Angular 19**
- **Bootstrap 5**

### Backend
- **Java 21**
- **Spring Boot 3**
- **Spring Security 6 (JWT-based authentication)**

### Database
- **Oracle 19c**

## 🏗 Modules

- **Authentication**: JWT-based secure login and registration
- **User Roles**: Job Seeker, Employer, Admin
- **Job Management**: Create, update, delete, and view job listings
- **Subscription System**:
  - Employers must purchase a subscription to post jobs and view applicants.
  - Subscription determines number of jobs and applicant views.
- **Application Management**:
  - Job seekers apply for jobs.
  - Companies view applicants based on subscription.
  - Shortlist applicants and assign interview dates.
- **Admin Panel**:
  - Manage users and jobs
  - CRUD operations on subscription plans
  - View statistics

## 🚀 Getting Started

### Prerequisites

- Java 21
- Node.js + Angular CLI
- Oracle DB 19c
- Spring Boot
- Maven

### Clone the Repository

```bash
git clone https://github.com/jahid0123/job-portal.git
cd job-portal

```

> Ensure backend and frontend are configured and run in separate terminals with correct environment variables.

---

## 📸 Screenshots

> *(Add screenshots here if available: Job Listing Page, Admin Dashboard, Apply Job Form, etc.)*

---

## Educational Objective

The Job Portal project is created to practice and demonstrate:
- Full-stack development with role-based UI
- Backend-frontend communication
- Job application workflows
- Authentication and secure access control
- CRUD and filtering functionality

---

## 🙋‍♂️ Author

**Jahid Ahmed**  
Student | Full Stack Developer  
🌐 Java | Spring Boot | Angular | Oracle | Flutter
