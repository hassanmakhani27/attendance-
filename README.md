# Attendance Management System

This is a cross-platform attendance tracking system built using Flutter for the mobile application and React for the web interface. The backend is powered by Firebase, providing real-time updates, user authentication, and data storage.

## Features

- Role-based authentication (Teacher / Student)
- Dynamic user registration
- Teachers can mark attendance as Present, Absent, or Late
- Students can view personal and class-wide attendance
- Attendance history with date filtering
- Export attendance reports
- Real-time updates and in-app notifications
- Separate dashboards for teachers and students
- Free-tier Firebase services only

## Mobile App (Flutter)

### Structure

- Developed using Flutter
- Firebase Authentication and Firestore for backend
- Two main user interfaces: Teacher Dashboard and Student Dashboard

### Getting Started

1. Clone the repository
2. Install dependencies:

   ```bash
   flutter pub get
Configure Firebase by adding the google-services.json (Android) or GoogleService-Info.plist (iOS)

Run the app:

bash
Copy
Edit
flutter run
Web App (React)
Structure
Built with React.js

Firebase integration for Authentication and Firestore

Fully responsive UI

Getting Started
Navigate to the web folder

Install dependencies:

bash
Copy
Edit
npm install
Add Firebase configuration in firebase.js

Start the development server:

bash
Copy
Edit
npm start
Technology Stack
Frontend (Mobile): Flutter

Frontend (Web): React.js

Backend: Firebase (Authentication, Firestore, Hosting)

Development Environment: Visual Studio Code

User Roles
Teacher
Mark attendance as Present, Absent, or Late

View and manage attendance records for all students

Export reports for analysis or record-keeping

Student
View personal attendance history

View overall class attendance

Receive notifications for absences or updates

Example Users
Name	Role
Mushtaq	Teacher
Sameer	Student
Saif	Student
Aslam	Student
Firebase Services Used
Firebase Authentication

Cloud Firestore

Firebase Hosting

(Planned) Firebase Cloud Messaging for notifications

Future Enhancements
Add profile photos and user editing features

Push notifications for absentees

Support for multiple classes and subjects

Admin-level analytics and reporting dashboard

Contribution
Contributions are welcome. Please open an issue to propose changes or enhancements before submitting a pull request.

License
This project is licensed under the MIT License.

Developer
Created and maintained by Hassan



Let me know if you'd like this turned into a downloadable `.md` file or need help pushing it to a
