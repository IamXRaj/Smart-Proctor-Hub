# 🧠 Smart Proctor Hub – Online Exam Proctoring System

## 📖 Overview

**Smart Proctor Hub** is an intelligent and automated online exam proctoring system that leverages AI technologies to ensure academic integrity during remote examinations. It features real-time facial recognition, behavioral monitoring, object and sound detection, and keystroke analysis to prevent cheating and ensure transparency.

---

## 🧩 Problem Statement

With the growth of online education, traditional methods of exam invigilation are no longer effective. The Smart Proctor Hub addresses this issue by providing a scalable and real-time AI-powered monitoring system that ensures secure and fair online assessments.

---

## 🎯 Objectives

- ✅ Facial Recognition and Eye Tracking for student authentication
- ✅ Head Pose Estimation for distraction detection
- ✅ Object Detection using YOLO to spot unauthorized items
- ✅ Audio Monitoring for surrounding voices or disturbances
- ✅ Keystroke Analysis to verify consistent typing behavior
- ✅ Real-time alerts and detailed logging for transparency
- ✅ Scalable architecture integrated with cloud infrastructure
- ✅ API-based support for integration with LMS platforms (e.g., Moodle, Google Classroom)

---

## 🏗️ System Architecture

- **Frontend (Client)**: Web-based interface (HTML/CSS/JS)
- **Backend (Server)**: Flask + Python (API & Logic)
- **Database**: Firebase / MySQL
- **Modules**:
  - Face Detection & Recognition (Dlib CNN)
  - Eye Gaze Tracking
  - Head Pose Estimation
  - Object Detection (YOLOv5)
  - Audio Anomaly Detection
  - Keystroke Dynamics Analysis
- **Alert System**: Real-time proctor alerts and timestamped logs

---

## 🛠️ Key Modules Description

| Module                    | Technology           | Purpose                                                                |
|---------------------------|----------------------|------------------------------------------------------------------------|
| Face Detection            | Dlib CNN              | Real-time face verification and identity matching                      |
| Eye Gaze Tracking         | OpenCV, Dlib          | Detect off-screen gazes                                                |
| Head Pose Estimation      | Facial Landmarks      | Determine attention level and possible cheating gestures               |
| Object Detection          | YOLOv5                | Detect unauthorized items like mobile phones, books, etc.              |
| Audio Monitoring          | Microphone + Python   | Detect background noise, whispering, or conversation                   |
| Keystroke Dynamics        | Python + Scikit-Learn | Compare typing patterns to known profiles for identity verification    |
| Alert & Log System        | Firebase              | Real-time notifications + detailed activity logs                       |

---

## 📊 Performance Metrics

| Feature                     | Accuracy (%) |
|-----------------------------|--------------|
| Face Recognition            | ~96%         |
| Object Detection (YOLO)     | ~92%         |
| Eye Gaze & Head Pose        | ~90%         |
| Audio Detection             | ~88%         |
| Keystroke Analysis          | ~85%         |

---

## 🖥️ System Requirements

### Client Side
- **OS**: Windows / macOS / Linux
- **Browser**: Chrome, Firefox
- **Hardware**: Webcam, Microphone, Minimum 4GB RAM, Stable 2 Mbps internet

### Server Side
- **OS**: Linux / Windows
- **Framework**: Flask (Python)
- **Libraries**: OpenCV, Dlib, YOLOv5, Scikit-learn, NumPy
- **Hardware**: Quad-core CPU, 16GB RAM, 50GB Storage, 100 Mbps network (recommended)

---

## 📈 Results

- Detects behaviors like multiple person presence, looking away from screen, using mobile phones, whispering, or audio disturbances.
- All alerts are logged with timestamps.
- Admin dashboards include real-time alerts and post-exam analysis logs.

---

## 🧠 Future Scope

- Advanced AI models for higher anomaly detection accuracy
- Mobile and tablet compatibility
- Integration with cloud services for scalability
- Liveness detection (anti-spoofing)
- Support for regional/multilingual interfaces
- Automated AI-generated behavioral reports
- Seamless LMS integration

---

## 👨‍💻 Developers

### 🧑‍💼 Mr. Girish Sanjay Borade  
> Final Year B.E. Computer Engineering  
> University of Pune (2024-25)  
> [Loknete Gopinathji Munde Institute of Engineering Education & Research Center, Nashik]

### 👩‍💼 Ms. Srushti Sachin Rahane  
> Final Year B.E. Computer Engineering  
> University of Pune (2024-25)  
> [Loknete Gopinathji Munde Institute of Engineering Education & Research Center, Nashik]

### 👩‍💼 Ms. Nikita Keshav Walke  
> Final Year B.E. Computer Engineering  
> University of Pune (2024-25)  
> [Loknete Gopinathji Munde Institute of Engineering Education & Research Center, Nashik]

### 🧑‍🏫 Under the Guidance of:  
**Prof. R. M. Shaikh**  
Department of Computer Engineering  
Loknete Gopinathji Munde IEERC, Nashik

---

## 🏫 Academic Details

- **Department**: Computer Engineering  
- **Year**: 2024-25  
- **University**: Savitribai Phule Pune University  
- **Project Type**: Final Year B.E. Capstone Project  

---

## 📚 References

1. XAMPRO: Voice-Based Exam Proctoring System – IEEE, 2023  
2. Visual Analytics Approach to Proctoring – CVPRW, 2021  
3. AI for Online Proctoring – IJACSA, 2021  
4. Deep Learning-based Proctoring – IJMLC, 2021  
5. Fraud Detection in Exam Videos – JIVP, 2018  
6. Online Exam Proctoring Using YOLO & FaceNet – JARCSSE, 2024  

---

> For any queries or collaborations, please contact the development team or academic advisor through the institute's Computer Engineering Department.
