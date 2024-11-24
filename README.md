This project is a 4th Semester project developed by me as a acedamic major project , an MCA Fresher graduate from Tumkur University. The goal of the project is to automate attendance systems using face recognition technology. It is designed to recognize and log attendance for individuals based on their facial features, offering a modern solution for educational and institutional attendance tracking. The project uses OpenCV for face detection and recognition, Flask for the web interface, and Firebase for real-time database management.

->>Features
Face Detection & Recognition: The system uses OpenCV and Haar Cascade Classifiers to detect faces in real-time through a webcam.
Attendance Logging: The recognized faces are compared with pre-registered profiles, and attendance is automatically logged into a Firebase database.
Web Interface: A user-friendly web interface built with Flask allows for easy management of attendance records and student profiles.
Real-time Database: The system utilizes Firebase Realtime Database to store attendance data and student profiles, enabling synchronization and easy access across devices.
->>Technologies Used
Python: The primary programming language for implementing the face recognition and logic.
OpenCV: Used for real-time face detection and recognition.
Flask: The web framework used to create the system's interface for viewing and managing attendance.
Firebase: A real-time database used to store attendance records and student information.
HTML/CSS: Used for creating a simple yet effective frontend to interact with the system.

This will launch the application on http://127.0.0.1:5000/.

->>How It Works
Face Registration:
Admins can upload images of individuals (students or staff). These images are processed to extract and store facial encodings for future recognition.
Attendance Marking:
When the webcam captures a face, the system compares it against the stored dataset of face encodings. If a match is found, the system logs the attendance in Firebase with a timestamp.
Web Interface:
The Flask web app provides an interface to view attendance logs, search records, and manage student profiles.
