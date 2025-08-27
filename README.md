# Employee-Leave-Attendance-Management
Employee Leave &amp; Attendance Management (Java Spring Boot + MySQL)
1. Introduction

Purpose: A backend-driven web app for companies to track employee attendance, manage leave requests, and generate reports.

Scope: Employees can request leave. Managers approve/reject requests. Attendance auto-marked daily. HR/Admin manages records.

Users: Employee, Manager, HR/Admin.

2. Functional Requirements

Employee login with JWT authentication.

Daily attendance logging (check-in/check-out).

Leave application & approval workflow.

Manager approval dashboard.

HR/Admin can generate monthly attendance reports.

Notifications on leave approval/rejection.

3. Non-Functional Requirements

RESTful API structure for scalability.

Role-based access control.

Database security with Spring Security.

Responsive web UI (can be integrated with React later).

4. System Models

Database:

Employees (id, name, email, role, department)

Attendance (id, employee_id, date, checkin_time, checkout_time)

Leaves (id, employee_id, start_date, end_date, status, manager_id)
