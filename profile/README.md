# Learning Management System - Assessment and Analytical Platform

## 📌 Project Overview
This project is a **Learning Management System (LMS)** designed to enhance the IT skills of engineering students. It provides an interactive and structured learning experience with automated assessments, analytics, certification, and real-time ranking.

![User](https://github.com/user-attachments/assets/449c54ed-04c9-4cce-9fbd-ae78f1d1d77e)

![LMS](https://github.com/user-attachments/assets/347de76a-b96f-418b-ac47-677d842b7a87)

### 🚀 Sponsored By: **Sumago Infotech Pvt Ltd**

## 🌟 Key Features
- **User Roles:** Super Admin, Admin, Student
- **Content Management:** Structured modules, sections, and video-based learning
- **Video Streaming:** Secure, scalable video streaming using AWS Media Services
- **Assessment System:** Automated tests with instant feedback
- **Real-time Ranking:** Student performance tracking with leaderboards
- **Certificates:** Automatic certificate generation upon course completion
- **Discussion Forum:** Interactive Q&A and discussions for students
- **Admin Dashboard:** User, course, and assessment management
- **Secure Authentication:** OTP-based login, JWT authentication
- **Payment Integration:** Secure payments using Razorpay
- **AI exam monitoring:** Proctoring during tests

## 🛠️ Tech Stack
### **Backend:**
- Django + Django Ninja
- PostgreSQL (Database hosted on AWS RDS)
- AWS for Video On Demand Streaming (S3, Lambda, Elemental MediaConvert, CloudFront, SNS, RDS, Cloudwatch, EventBridge)

### **Frontend:**
- React
- Bootstrap
- Figma (UI/UX designing)

### **AWS Video on Demand Architecture:**
![image](https://github.com/user-attachments/assets/9613dc0c-c855-46ee-991f-4b8eae65a8d9)


[//]: # (### **Cloud & DevOps:**)
<!-- [//]: # (- AWS (RDS, S3, Lambda, API Gateway, CloudFront, SNS)) -->
<!-- [//]: # (- Docker (Containerization)) -->

## 📂 Project Structure
```bash
LMS-Project/
├── backend/    # Django backend
├── frontend/   # React frontend
├── docs/       # Documentation & API references
├── scripts/    # Deployment & utility scripts
└── README.md
```

## ⚙️ Setup Instructions
### 1️⃣ Prerequisites
- Python 3.9+
- PostgreSQL
- AWS account setup

### 2️⃣ Backend Setup (Django)
```bash
git clone <repo-url>
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env  # Add your DB and AWS credentials here
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

### 3️⃣ Frontend Setup (React)
```bash
cd frontend
npm install
npm run dev
```

## 📡 AWS Integration
1. **S3 for Video Storage:** Store raw videos before processing.
2. **MediaConvert for Transcoding:** Convert videos to HLS format.
3. **CloudFront for Streaming:** Deliver videos globally with low latency.
4. **SNS Notifications:** Notify backend upon video processing completion.
5. **RDS (PostgreSQL):** Centralized database for team collaboration.

<!--
## 📝 API Endpoints
- `POST /api/upload-video/` → Upload video
- `GET /api/videos/` → List available videos
- `POST /api/submit-test/` → Submit assessment
- `GET /api/ranking/` → Get student ranking
-->

## 🔥 Future Enhancements
- AI-based personalized learning paths
- Gamification elements for engagement
- Mobile App Integration

## 📧 Contact
For queries, reach out at [ankitworkmail12@gmail.com](ankitworkmail12@gmail.com
) or LinkedIn: [ankitpatne](https://www.linkedin.com/in/ankitpatne/).

---
🎉 **Happy Learning!**

