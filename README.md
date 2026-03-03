# 🏥 ZenoCare — Multi-Tenant Hospital Operations Platform  

ZenoCare is a full-stack SaaS-based hospital management platform that allows multiple hospitals to operate independently on a shared system. Each hospital functions as an isolated tenant with secure role-based access and a complete patient lifecycle workflow.

The project focuses on multi-tenant architecture, strict data isolation, JWT authentication, and real-world hospital operations management.

---

## ✨ Features  

Multi-tenant architecture with hospital-level data isolation  
Admin approval workflow for new hospital registrations  
Role-based access control (Super Admin / Hospital Admin / Doctor / Receptionist)  
JWT authentication with secure password hashing  
Complete patient lifecycle management (Registration → Appointment → Diagnosis → Billing)  
Double-booking prevention for appointments  
Invoice generation with PDF support  
Email notifications for approvals and system actions  
Analytics dashboard for hospital insights    

---

## 🛠️ Tech Stack  

Frontend: React (Vite), CSS  
Backend: Node.js, Express.js  
Database: MongoDB, Mongoose  
Authentication: JWT, bcryptjs  
Services: Nodemailer  
PDF Generation: PDFKit   

---

## 🚀 Deployment  

Frontend deployed on Render   
Backend deployed on Render   
Database hosted on MongoDB Atlas  

---

## 🏗️ Project Structure  
```text
zenocare/  
├── frontend/   # React frontend  
└── backend/    # Node.js backend  
```
---

## ⚙️ Running Locally  

```bash
git clone https://github.com/KENZY004/ZenoCare
cd zenoCare

cd backend
npm install
npm run dev

cd ../frontend
npm install
npm run dev
```

---

## 🌐 Live Demo  

🔗 https://zenocare-frontend-ofyn.onrender.com/  

---
