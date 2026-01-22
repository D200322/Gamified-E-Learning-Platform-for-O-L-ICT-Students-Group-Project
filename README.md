# KVJP_1-SmartOLICT
   KVJP_1-SmartOLICT
Gamified Learning System for O/L ICT Students

 Project Overview:
KVJP_1-SmartOLICT is a full-stack web application designed to provide an engaging and interactive learning experience for Ordinary Level (O/L) ICT students in Sri Lanka.
The platform uses gamification techniques to improve student motivation, participation, and learning outcomes.
The system supports students, teachers, and administrators, with secure authentication, role-based access control, and comprehensive content management features.

Objectives:
Improve student engagement in ICT learning
Provide interactive lessons and quizzes
Track student progress and performance
Support teachers and admins in managing educational content
Apply gamification principles to e-learning

Key Features-

Authentication & Authorization:
User registration and login
Google OAuth and local authentication
JWT-based authentication
Role-based access control (Admin > Teacher > Student)

Content Management:
Create, edit, delete, and restore lessons and quizzes
Video-based lessons with file uploads
Dynamic lesson and quiz rendering
Soft delete functionality for content recovery

Gamification:
Points and badges
Leaderboards
Progress reports
Motivation through achievements

Interactive Learning:
Quizzes with multiple attempts
Instant feedback
Progress tracking
Notifications for updates and achievements

Admin Dashboard:
User management
Content management
View login logs and feedback
Analytics and reports

Security:
Password hashing using bcrypt
Protected API routes
Secure role registration
Activity and login logging

System Architecture-

Frontend – Smart_O/L_ICT:
React Single Page Application (SPA)
Handles UI for:-
   Authentication
   Dashboards
   Lessons and quizzes
   Admin and teacher panels

Backend – Server:
Node.js with Express.js
RESTful APIs
Business logic and authentication
Database interaction using Mongoose

Database:
MongoDB (MongoDB Atlas)
Structured models for users, lessons, quizzes, progress, and gamification data

File Storage:
Local uploads directory for video files
Served as static resources

Technologies Used-

Frontend:
React (v19.1.1)
Vite
React Router
Axios
Bootstrap
Lucide React Icons

Backend:
Node.js
Express.js (v5.2.1)

Database:
MongoDB
Mongoose
MongoDB Atlas

Additional Libraries & Tools:
Git

Database Models:
User (Student, Teacher, Admin)
Lesson
Quiz
Question
QuizAttempt
ProgressReport
Leaderboard
GamificationPoints
Notification
Feedback
InstantMessage
ContentLog
LoginLog
VideoFile
