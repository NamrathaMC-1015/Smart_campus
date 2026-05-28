# Smart_campus
🎓 Single-file student management system — registration, enrollment, grades, fees &amp; analytics. Bulk CSV grade upload, PDF export, department-wise charts. Runs entirely in the browser.
# 🎓 SmartCampus – Student Management System
 
A lightweight, single-file web app for managing student records, grades, enrollments, and fees — no backend, no database, no installation required.
 
---
 
## ✨ Features
 
- **Student Registration & Directory** – Add, search, and filter students by department or name
- **Course Enrollment** – Manage subject enrollments per student
- **Grade Management** – Enter grades manually or bulk-upload via CSV; auto-evaluates letter grades
- **Fee Tracking** – Record fee payments and monitor pending/paid status
- **Analytics Dashboard** – Department-wise performance charts and grade distribution
- **Overview & Toppers** – Ranked student summary with average scores and final grades
- **PDF Export** – Download a full student performance report
- **Offline & Private** – All data lives in your browser's localStorage; nothing is sent to any server
---
 
## 🚀 Getting Started
 
1. Download `smartcampus_final.html`
2. Open it in any modern browser (Chrome, Firefox, Edge)
3. Start adding students, enrollments, and grades — data saves automatically
No npm, no build step, no server.
 
---
 
## 📄 Bulk Grade Upload (CSV Format)
 
Prepare a `.csv` file with the following columns:
 
```
StudentID, StudentName, Course, Score, Remark
```
 
Upload it under **Grades → Bulk Upload**. The system matches student IDs automatically and updates analytics across all sections.
 
---
 
## 🛠️ Tech Stack
 
| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (CSS Variables, Flexbox, Grid) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | Browser localStorage |
| Dependencies | None |
 
---
 
## 📁 Project Structure
 
```
smartcampus_final.html   ← entire app in one file
README.md
```
 
---
 
## 📌 Notes
 
- Data is stored per-browser and per-device. Clearing browser data will erase records.
- Use the built-in **Clear Data** option under Settings to reset all records safely.
- Bulk-uploaded grades are reflected across the Student Directory, Analytics Dashboard, and Overview automatically.
---
 
## 📜 License
 
MIT — free to use, modify, and distribute.
