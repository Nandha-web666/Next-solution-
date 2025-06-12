# Face Recognition Attendance System (Java)

## 📌 Overview

This project is a **Face Recognition-based Attendance System** built using **Java**. It uses image processing and machine learning techniques to detect and recognize faces and mark attendance automatically. The system captures real-time video, detects faces, matches them with pre-registered data, and logs the attendance.

## 🎯 Features

- Real-time face detection using OpenCV
- Face recognition with LBPH (Local Binary Pattern Histograms)
- User registration (face image dataset creation)
- Automatic attendance logging
- Attendance storage in CSV/Database
- User-friendly GUI (Swing/JavaFX)
- Daily attendance report generation

## 🛠️ Technologies Used

- **Java SE**  
- **OpenCV** (Java bindings)  
- **Java Swing / JavaFX** (for UI)  
- **MySQL / SQLite** (for storing attendance records)  
- **CSV File Handling** (optional for logs)  

## 📦 Project Structure

```bash
face-recognition-attendance/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── app/
│   │   │   │   ├── Main.java
│   │   │   │   ├── CameraService.java
│   │   │   │   ├── FaceDetector.java
│   │   │   │   ├── FaceRecognizer.java
│   │   │   │   ├── AttendanceLogger.java
│   │   │   │   └── DatabaseHandler.java
│   └── resources/
├── dataset/                # Contains face images
├── attendance_logs/        # Daily attendance records
├── lib/                    # OpenCV native libraries
├── README.md
└── pom.xml / build.gradle  # Dependency manager# Next-solution-