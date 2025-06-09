# 📱 Smart Engineer - Polytechnic Study Assistant
[![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)](https://play.google.com/store/apps/details?id=com.softylasa.smartengineer)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**All-in-one academic toolkit for BTEB engineering students**  
*Centralized access to textbooks, tools, and resources for Bangladeshi polytechnic institutes*
<div align="center">
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20Home.png?alt=media&token=0d0aec3e-678f-48e0-8c6b-17b81d4ba2bd" width="23%" alt="Home Screen">  
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20Study.png?alt=media&token=621a213f-e825-4df6-8128-1435593c44b6" width="23%" alt="Study Materials">
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20Updates%20-%20Book.png?alt=media&token=7efd4c99-d026-4050-a80c-890c5c45d236" width="23%" alt="Book Updates">
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20Updates%20-%20Notice.png?alt=media&token=b5c32585-9e38-4a8e-bb5c-3221a093843d" width="23%" alt="Notice Updates">
  
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20Semester.png?alt=media&token=bcb78a16-6035-4cc6-8df0-0c6ff232a1d0" width="23%" alt="Semester View">
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20Details.png?alt=media&token=7b98d2f2-4eef-4195-9555-9433a2738817" width="23%" alt="Book Details">
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20Department.png?alt=media&token=b1bd5231-907b-469a-8754-7f15e81953cb" width="23%" alt="Department Selection">
  <img src="https://firebasestorage.googleapis.com/v0/b/smart-engineer-sl.firebasestorage.app/o/screenshot%2FSS%20-%20CGPA.png?alt=media&token=36198f78-18f1-4c45-adda-1647b5a62e4e" width="23%" alt="CGPA Calculator">
</div>

## 🧩 Features

### Student App
- **📚 Unit-wise Book Library** - Filter by department/semester
- **🧮 CGPA Calculator** - Track academic performance
- **📢 Real-time Notices** - Exam dates and results
- **🔐 Secure Authentication** - Google/email login
- **🌗 Dark Mode** - Eye-friendly reading
- **📥 Offline Access** - Download materials for offline use

### Admin Panel
- **📊 Content Management** - Manage books, notices, resources
- **👥 User Analytics** - Monitor usage patterns
- **🏫 Institute Database** - Manage institution info
- **📤 Bulk Upload** - Upload multiple resources at once
- **🔔 Push Notifications** - Broadcast important updates

## ⚙️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | Kotlin, XML, Jetpack Components |
| **Backend** | Firebase Auth, Firestore, SOL |
| **Storage** | NGINX Server (HTTPS) |
| **Admin Panel** | Firebase Admin SDK |
| **Architecture** | MVVM, Repository Pattern |

## 🗂️ Project Structure

```
📦 Smart-Engineer
├── 📂 student-app      # Main Android app
│   ├── 📂 app
│   │   ├── src/main
│   │   │   ├── java/com/softylasa/smartengineer
│   │   │   │   ├── auth        # Authentication
│   │   │   │   ├── features    # App features
│   │   │   │   ├── di          # Dependency injection
│   │   │   │   └── utils       # Utilities
│   │   │   └── res             # Resources
│   │   └── google-services.json
│
├── 📂 admin-panel      # Admin CMS
│   ├── src
│   │   ├── components  # React UI components
│   │   ├── services    # Firebase services
│   │   └── pages       # Admin views
│
└── 📂 server           # Resource server
    ├── storage         # PDF resources
    └── scripts         # Server utilities
```

## 📜 Compliance
✅ GDPR-compliant data deletion  
✅ HTTPS encryption for all transfers  
✅ Educational fair use compliance  
✅ Non-affiliation disclaimer  
✅ DMCA takedown process  

## 🚀 Roadmap
- Interactive quizzes
- Video lecture integration
- Discussion forums
- Premium subscription
- Multi-language support

> ⚠️ **Disclaimer**: Not affiliated with BTEB or Bangladesh government
