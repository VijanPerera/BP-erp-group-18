# BP erp group 18

University ERP - Attendance Tracking Module (UI/UX Design)

This repository contains the prototype for a University ERP Attendance Tracking module. This project is the deliverable for the UI design assignment and is based on the business processes defined in the Task 03 report.

The entire 13-screen application flow, from login to role-based dashboards, has been designed in Figma.

---

THE FIGMA PROTOTYPE AND DESIGN

The complete, high-fidelity, and interactive prototype is available to view publicly.

Figma Link: [https://www.figma.com/design/St3WvF3YhgEubNpKlcEb9Y/erp-new?node-id=0-1&t=s84CwVkb5AodY8Ej-1]

---

PROJECT OVERVIEW & FEATURES

This UI design translates the complex business logic from the Task 03 report into a clean, usable, and professional desktop application.

Task 03 Report: [[ERP Module Analysis Report_ Attendance Tracking (1)](https://github.com/VijanPerera/BP-erp-group-18/commit/f7c9773aa26b2543a9f90261e4c4e4857c18afb5)](./Task 03 Report.pdf)

Key Features Designed:
Separate User Portals: A main portal (Screen 1) directs users to two separate, secure login screens (Screens 2 & 3) for the Lecturer and Administrator roles.

Role-Based Dashboards: After login, users are directed to a unique dashboard tailored to their tasks.

Complete Lecturer Flow (5 Screens):
Lecturer Dashboard: A home page to start a live session for a course like "BP ERP".
Live Attendance Modal: The pop-up with the QR code and a real-time list of checked-in students (using your provided student names like "RAVM Perera").
My Courses: A gallery to see all assigned courses (e.g., "BP ERP", "Software Architecture").
Manual Mark Modal: A pop-up form to handle exceptions for students.
Lecturer Course Report: A data table showing the final attendance % for all students in one course.

Complete Administrator Flow (5 Screens):
Admin Dashboard (Policy Manager): A settings page to control the core business rules (e.g., "Require Gate Punch-in," "Minimum 70%").
Student Lookup: A search page to find any student in the university (e.g., "SS Munasinghe").
University Reports: A high-level analytics dashboard with charts for attendance by faculty (Computing, Business, Engineering).
Admin Student Drill-Down: A complete profile of a single student, showing their attendance across all modules (e.g., "BP ERP", "HCI", "Data Structures").
Student Attendance Log: A detailed, granular audit log showing every successful and failed attendance attempt for a student.

---

DESIGN SYSTEM

The UI was designed with a clean, modern, and accessible aesthetic.

Primary Color: A professional, rich Green (#006400) is used for all primary buttons, navigation, and "Pass" status indicators.

Secondary Colors:
Red (#dc3545): Used for "Error" messages, "At-Risk" status, and danger buttons.
Yellow (#ffc107): Used for "Warning" status.

Typography: The entire interface uses the Inter font family for its excellent readability on screens.

Layout: A consistent 2-column layout (a dark green side-navigation bar and a light gray content area) is used on all internal screens to create a predictable user experience.
