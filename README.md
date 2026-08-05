# 🎓 SnapClass

> **AI-Powered Classroom & Attendance Management System**

SnapClass is an AI-powered classroom management system that simplifies classroom administration and attendance tracking. Teachers can create and manage classrooms, generate QR codes for students to join, and monitor attendance records. Students can securely mark attendance using **Face Recognition** or **Voice Recognition**, making the process faster, smarter, and more reliable.

<p align="center">

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Streamlit-success?style=for-the-badge)](https://snapclass-maiin.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Supabase](https://img.shields.io/badge/Supabase-Database-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)

</p>

---

## 🌐 Live Demo

🔗 **https://snapclass-maiin.streamlit.app/**

---

## 📌 Overview

Traditional attendance systems are often time-consuming and susceptible to proxy attendance. SnapClass addresses these challenges by integrating biometric authentication with modern classroom management.

Teachers can create classrooms, generate QR codes for students to join instantly, and monitor attendance records. Students can authenticate themselves using Face Recognition or Voice Recognition before attendance is recorded, ensuring both security and accuracy.

---

# ✨ Features

## 👨‍🏫 Teacher Portal

- 🔐 Secure Teacher Login
- ➕ Create & Manage Classrooms
- 📱 Generate QR Codes for Classroom Joining
- 👥 View Enrolled Students
- 📊 Monitor Attendance Records
- 📚 Manage Multiple Classrooms

---

## 👨‍🎓 Student Portal

- 🔐 Secure Student Login
- 📱 Join Classrooms by Scanning QR Codes
- 📷 Mark Attendance using Face Recognition
- 🎤 Mark Attendance using Voice Recognition
- 📖 View Joined Classrooms

---

# 🤖 AI Features

### 📷 Face Recognition

- Secure biometric attendance verification.
- Prevents proxy attendance.
- Fast and reliable identity authentication.

### 🎤 Voice Recognition

- Voice biometric authentication for attendance.
- Enhances attendance security.
- Accurate and seamless verification.

### 📱 QR Code Classroom Joining

Teachers can generate QR codes that allow students to join classrooms instantly without manually entering classroom details.

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Language** | Python |
| **Framework** | Streamlit |
| **Database** | Supabase |
| **Face Recognition** | face_recognition, dlib |
| **Voice Recognition** | Resemblyzer, Librosa |
| **Authentication** | bcrypt |
| **QR Code Generation** | Segno |
| **Image Processing** | Pillow |
| **Data Processing** | NumPy, Pandas |

---

# 📂 Project Structure

```text
SnapClass/
│
├── src/
│   ├── components/
│   ├── database/
│   ├── pipelines/
│   │   ├── face_pipeline.py
│   │   └── voice_pipeline.py
│   ├── screens/
│   │   ├── home_screen.py
│   │   ├── teacher_screen.py
│   │   └── student_screen.py
│   └── ui/
│
├── app.py
├── requirements.txt
└── README.md
```

---

# 📸 Application Preview

## 🏠 Home Page

> *(Add Home Page Screenshot)*

---

## 👨‍🏫 Teacher Dashboard

> *(Add Teacher Dashboard Screenshot)*

---

## 👨‍🎓 Student Dashboard

> *(Add Student Dashboard Screenshot)*

---

## 📱 QR Code Classroom Joining

> *(Add QR Code Screenshot)*

---

## 📷 Face Recognition Attendance

> *(Add Face Recognition Screenshot)*

---

## 🎤 Voice Recognition Attendance

> *(Add Voice Recognition Screenshot)*

---

## 📊 Attendance Records

> *(Add Attendance Screenshot)*

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/chesta02/Snapclass-main.git
cd Snapclass-main
```

## Create a Virtual Environment (Optional)

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### macOS/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Configure Supabase

Create a `.streamlit/secrets.toml` file and add your credentials:

```toml
SUPABASE_URL="YOUR_SUPABASE_URL"
SUPABASE_KEY="YOUR_SUPABASE_KEY"
```

> **Note:** If you're deploying on Streamlit Community Cloud, configure these values in the app's **Secrets** section instead of committing them to GitHub.

## Run the Application

```bash
streamlit run app.py
```

---

# 🔒 Security

- 🔐 Encrypted Password Storage (bcrypt)
- 📷 Face Recognition Authentication
- 🎤 Voice Recognition Authentication
- ☁️ Secure Cloud Database with Supabase
- 👤 Role-Based Access for Teachers and Students

---

# 🎯 Future Enhancements

- 📱 Mobile Application
- 📊 Attendance Analytics Dashboard
- 📄 Export Attendance Reports (PDF/Excel)
- 📧 Email Notifications
- 📅 Timetable Management
- 🌐 Multi-Institution Support

---

# 👩‍💻 Author

**Chesta Chauhan**

**B.Tech Computer Science & Engineering (AI/ML & Robotics)**  
DIT University

🌐 **Live Demo:** https://snapclass-maiin.streamlit.app/

💻 **GitHub:** https://github.com/chesta02

---

<div align="center">

### ⭐ If you found this project useful, don't forget to star the repository!

**Built with ❤️ using Python, Streamlit & AI**

</div>
