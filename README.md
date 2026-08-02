# 🎓 SnapClass

> AI-Powered Classroom & Attendance Management System

SnapClass is a smart classroom management system that simplifies classroom administration through AI-powered attendance verification. Teachers can create and manage classrooms, while students can join classes instantly using QR codes and mark attendance securely through Face Recognition or Voice Recognition.

---

## ✨ Features

### 👨‍🏫 Teacher
- Secure Login
- Create & Manage Classrooms
- Generate QR Codes for Classroom Joining
- View Student List
- Monitor Attendance Records

### 👨‍🎓 Student
- Secure Login
- Join Classroom by Scanning QR Code
- Mark Attendance using Face Recognition
- Mark Attendance using Voice Recognition
- View Joined Classrooms

---

## 🤖 AI Features

### 📷 Face Recognition
Verify student identity using facial recognition before recording attendance.

### 🎤 Voice Recognition
Authenticate students using voice biometrics for secure attendance.

### 📱 QR Code Classroom Joining
Teachers can generate a QR code that allows students to instantly join a classroom without manually entering class details.

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Framework | Streamlit |
| Database | Supabase |
| Face Recognition | face_recognition, dlib |
| Voice Recognition | Resemblyzer, Librosa |
| Authentication | bcrypt |
| QR Code | Segno |
| Image Processing | Pillow |
| Data Processing | NumPy, Pandas |

---

## 📂 Project Structure

```
SnapClass/
│
├── src/
│   ├── components/
│   ├── database/
│   ├── pipelines/
│   │   ├── face_pipeline.py
│   │   └── voice_pipeline.py
│   ├── screens/
│   │   ├── teacher_screen.py
│   │   ├── student_screen.py
│   │   └── home_screen.py
│   └── ui/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/your-username/SnapClass.git
cd SnapClass
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Supabase

Add your Supabase credentials.

```python
SUPABASE_URL=YOUR_URL
SUPABASE_KEY=YOUR_KEY
```

### Run

```bash
streamlit run app.py
```

---

## 🔒 Security

- Encrypted Password Storage
- Secure Authentication
- AI-Based Identity Verification
- Cloud Database Integration

---

## 📸 Screenshots

### Home Page

_Add screenshots here_

### Teacher Dashboard

_Add screenshots here_

### Student Dashboard

_Add screenshots here_

---

## 🔮 Future Enhancements

- 📱 Mobile Application
- 📊 Attendance Analytics
- 📈 Student Performance Dashboard
- 📅 Timetable Management
- 📧 Email Notifications
- 🌐 Multi-Class Support

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create your feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 👩‍💻 Author

**Chesta Chauhan**

B.Tech CSE (AI/ML & Robotics)  
DIT University

---

⭐ If you like this project, don't forget to star the repository!
