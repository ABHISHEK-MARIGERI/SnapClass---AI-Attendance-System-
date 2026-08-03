<div align="center">

# 🎓 SNAPCLASS
### AI-Powered Smart Attendance Management System

<p align="center">
An AI-powered classroom attendance platform that automates attendance using <b>Face Recognition</b>, <b>Voice Recognition</b>, and <b>QR-based Subject Enrollment</b>.
</p>

<img src="images/landing.png" width="90%">

</div>

---

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?logo=streamlit)
![Supabase](https://img.shields.io/badge/Supabase-Database-green?logo=supabase)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red?logo=opencv)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Dlib](https://img.shields.io/badge/Dlib-Face%20Recognition-success)
![Librosa](https://img.shields.io/badge/Librosa-Audio-blue)
![Resemblyzer](https://img.shields.io/badge/Resemblyzer-Speaker%20Recognition-lightgrey)
![Vercel](https://img.shields.io/badge/Vercel-Landing%20Page-black?logo=vercel)

</p>

---

# 📖 Table of Contents

- About the Project
- Features
- Demo
- System Architecture
- Technology Stack
- Face Recognition Pipeline
- Voice Recognition Pipeline
- Student Workflow
- Teacher Workflow
- Installation
- Project Structure
- Database Design
- Future Improvements
- Author

---

# 🚀 About the Project

SNAPCLASS is an AI-powered attendance management system designed to automate classroom attendance using Computer Vision and Speaker Recognition.

Instead of manually marking attendance, teachers can upload classroom photos or record classroom audio. The system automatically identifies students using Machine Learning models and stores attendance records securely in Supabase.

Students can join classes instantly using a QR code or subject code without requiring manual registration by the teacher.

The project is fully deployed online using **Streamlit Community Cloud**, while the landing page is deployed separately using **Vercel**.

---

# ✨ Features

## 👨‍🎓 Student Portal

- Student Registration
- Password Login
- Face Login
- QR Code Enrollment
- Subject Code Enrollment
- View Attendance
- View Attendance Percentage
- Unenroll from Subjects

---

## 👨‍🏫 Teacher Portal

- Teacher Registration
- Secure Authentication
- Create Subjects
- Generate QR Codes
- Share Subject Links
- Manage Subjects
- Take Attendance using Photos
- Take Attendance using Voice
- View Attendance Reports

---

## 🤖 Artificial Intelligence

- Face Recognition
- Voice Recognition
- Facial Embeddings
- Speaker Embeddings
- Machine Learning Classification
- Attendance Verification

---

# 🎥 Demo

## Landing Page

<img src="images/landing.png" width="100%">

---

## Student Portal

<img src="images/student.png" width="45%">
<img src="images/student-login.png" width="45%">

---

## Teacher Portal

<img src="images/teacher.png" width="45%">
<img src="images/teacher-login.png" width="45%">

---

# 🏗️ System Architecture

```text
                    Teacher
                       │
                       ▼
            Streamlit Web Application
                       │
        ┌──────────────┼───────────────┐
        ▼                              ▼
 Face Recognition Pipeline      Voice Recognition Pipeline
        │                              │
        ▼                              ▼
   Student Identification      Speaker Identification
        │                              │
        └──────────────┬───────────────┘
                       ▼
               Attendance Decision
                       │
                       ▼
                 Supabase Database
                       │
                       ▼
             Attendance Reports Dashboard
```

---

# ⭐ Key Highlights

✅ AI-powered attendance automation

✅ Face Recognition using Dlib

✅ Voice Recognition using Resemblyzer

✅ QR Code based enrollment

✅ Teacher & Student portals

✅ Streamlit deployment

✅ Vercel landing page

✅ Supabase cloud database

✅ Modern responsive UI

---

# 📊 Project Statistics

| Feature | Status |
|---------|--------|
| Face Recognition | ✅ |
| Voice Recognition | ✅ |
| QR Enrollment | ✅ |
| Attendance Reports | ✅ |
| Streamlit Deployment | ✅ |
| Vercel Landing Page | ✅ |
| Cloud Database | ✅ |

---
