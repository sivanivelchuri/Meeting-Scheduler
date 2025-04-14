# Discover the Success Story of .NetForte's Full Stack .NET Journey
🗓️ Meeting Scheduler – Group 11
This Meeting Scheduler project is a significant milestone in my journey toward mastering the .NET ecosystem. Developed collaboratively by Group 11, it stands out among all group projects for offering a robust, scalable, and user-friendly web-based meeting management solution.

🔧 Technologies Used:
.NET Core Web API

Blazor for frontend development

SQL Server as the database

Serilog for structured logging

Followed Microsoft-recommended coding standards and well-defined architecture

📋 Project Description
This web-based platform allows users and administrators to:

Log in securely

Schedule, edit, delete, and view meetings

Receive email reminders for upcoming meetings

Auto-delete past meetings

Generate meeting reports

Role-based dashboards and permissions

👥 Actors:
Users

Admins

✅ Functional Requirements:
User authentication with email ID and password

Secure login with role-based access (User/Admin)

Change password and logout functionality

Manage user and meeting data

Role-specific dashboards:

Users: Can view/edit/delete their own meetings

Admins: Can view all meetings in read-only mode

Filters for meetings (Weekly/Monthly/Yearly)

Auto-deletion of expired meetings

Email notifications/reminders

Generate weekly/monthly reports

📌 Non-Functional Requirements:
Compliance with Microsoft coding standards and design patterns

Layered architecture for maintainability and scalability

Built with extendibility in mind for future enhancements

🔁 Application Flow Chart:
(Insert flow chart here if available)

🧩 Modules Overview:
1. Login Module
UI: Login form with username and password fields

Authentication and role-based authorization

Tables: tblUser, tblRole

2. User Scheduler Module
UI: Meeting creation form

Table: tblMeeting (Agenda, Date, Time, Participants)

3. All Users Scheduler Module
Admin view of all scheduled meetings (read-only)

4. Edit User Module
UI and logic to update scheduled meetings

5. Delete User Module
UI and logic to delete specific meetings

6. Auto-Deletion Module
Logic to automatically delete past meetings

7. Filters Module
Filters by Weekly, Monthly, Yearly for users/admins

8. Email Notification Module
Sends reminders about upcoming meetings via email

9. Change Password Module
UI and backend for password updates

10. Reports Module
Generates weekly/monthly reports based on user selection

📊 Database Tables:
tblUser: Id, Username, Password, RoleId

tblRole: Id, RoleName

tblMeeting: Id, Agenda, Date, Time, Participants

This project reflects teamwork, practical design, and implementation of real-world features — proudly developed by Group 11.