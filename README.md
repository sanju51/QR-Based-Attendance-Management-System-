# 📌 QR Based Attendance Management System

---

## 🔹 Project Summary

A **web-based attendance system** that replaces manual roll calls with **QR code scanning**.  
Each student has a **unique digital ID (QR Code)**, which is scanned by faculty/admin to mark attendance.  
The system provides **real-time attendance tracking**, **personal dashboards for students**, and **reporting tools for faculty**.

---

## ❓ Why This Project?

- Manual attendance is **time-consuming** and prone to **errors/fraud**.  
- **QR codes are fast, secure, and easy to deploy** (works on any device with a camera).  
- Suitable for **colleges, schools, events, and offices**.  
- Uses **modern tech stack (React + Firebase)** → scalable.

---

## ✨ Key Features

### **Student Side**
- **Profile Creation:** Name, email, student ID.  
- **Digital QR ID:** Unique QR code generated per student (can be saved or shown on screen).  
- **Attendance History:** View logs by date/class.  

### **Faculty/Admin Side**
- **QR Code Scanner:** Scan QR via webcam/mobile → instantly mark attendance.  
- **Live Attendance Dashboard:** Real-time count of present/absent students; filter by class/subject/date.  
- **Report Generation:** Export attendance to **Excel/PDF**.  

---

## 🔮 Future Enhancements

- Auto email/SMS alerts for low attendance.  
- Multi-role support (faculty, admin, student).  
- Class schedules + attendance integration.  
- Leaderboard/rewards for high attendance.  

---

## 🛠 Tech Stack

### **Frontend**
- React.js (component-based UI)  
- TailwindCSS (professional, responsive design)  
- Libraries: `qrcode.react`, `react-qr-reader`

---

## 🔄 System Flow

**1️⃣ Student Registration & QR Generation**  
Student enters details → System generates unique QR code → Stored in DB + displayed on dashboard.  

**2️⃣ Attendance Marking (Faculty)**  
Faculty scans student QR → Matches student in DB → Marks attendance.  

**3️⃣ Dashboard & Reports**  
Admin dashboard shows real-time stats → Export daily/weekly/monthly reports.  
