<h1 align="center">✨ RecruitEase - A Career Recruitment Web Application ✨</h1>

<p align="center">
  <img src="/public/images/image.png" alt="Demo App" width="700"/>
</p>

---

## 🌟 Highlights

- 🏢 **Centralized Recruitment Platform** – Connects **Candidates** and **Institutions** (Schools, Colleges & Professional Organizations) on a single portal.  
- 👤 **Role-Based Access Control** – Dedicated modules for **Admin**, **Candidates**, and **Institutions** with secure permissions.  
- 🔒 **Secure Authentication & Authorization** – JWT-based login, **email verification**, and **admin approval** to ensure trust.  
- 📑 **Vacancy Management** – Institutions can **add, update, delete** job postings, manage applications, and shortlist candidates for interviews.  
- 📊 **Real-Time Updates** – Track job application status instantly, with notifications and candidate status updates.  
- 🛠️ **Admin Dashboard** – Full system control: user management, institution approvals, vacancy moderation, and candidate monitoring.  
- 🎨 **Dynamic UI with EJS** – Server-side rendering using **EJS templates** combined with **Bootstrap & CSS** for responsive design.  
- ⚡ **Optimized Workflow** – Automates hiring, reduces paperwork, and ensures efficient recruitment decisions.  
- ☁️ **Deployment Ready** – Easily deployable on **Render** or **AWS CloudFront** for scalability.  

---

## 🎯 Objectives

- Provide a **centralized online platform** for candidates and institutions.  
- Ensure **secure registration & authentication** with email verification and admin approval.  
- Facilitate **seamless communication** between recruiters and applicants.  
- Enable institutions to find the **right candidates** while helping applicants reach their **dream jobs**.  

---

## 🛠️ Tech Stack

**Frontend (Views):** ![EJS](https://img.shields.io/badge/EJS-FFB13B?style=flat&logo=ejs&logoColor=black) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)  
**Backend:** ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)  
**Database:** ![MongoDB](https://img.shields.io/badge/MongoDB-4DB33D?style=flat&logo=mongodb&logoColor=white) 
**Version Control:** ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)  
**Tools:** ![VS Code](https://img.shields.io/badge/VS%20Code-0078d7?style=flat&logo=visual-studio-code&logoColor=white)  
**Deployment:** ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=black) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazon-aws&logoColor=white)  

---

## 🔑 User Roles

### 👨‍💼 Administrator
- Manage **users, institutions, and vacancies**.  
- Approve or block candidates & institutions.  
- Full control over system operations and data security.  

### 👤 Candidate
- Register, verify email, and get admin approval.  
- Update profile, apply for jobs, and track application status.  
- Manage account (password change / deactivation).  

### 🏢 Institutions (Schools/Colleges/Organizations)
- Register and verify through email + admin approval.  
- Post/manage vacancies, review candidate applications, and shortlist applicants.  
- Manage interview selections and recruitment decisions.  

---

## 📈 SWOT Analysis

**Strengths** – Automates hiring, centralized platform, role-based access, real-time updates.  
**Weaknesses** – Dependent on admin approval, requires large user base.  
**Opportunities** – Partnerships with institutions, social media integration, branding.  
**Threats** – Competition from job portals, data privacy concerns.  

---

## ⚙️ Methodology

1. **Requirement Analysis** – Identify roles and functionalities.  
2. **System Design** – Database schema (MongoDB), Views (EJS), API logic (Express.js).  
3. **Implementation** – JWT authentication, CRUD for vacancies, candidate & institution modules.  
4. **Testing** – Unit + integration testing for features.  
5. **Deployment** – Deploy via **Render** or **AWS CloudFront**.  

---

## 🧪 .env Setup

```env
ADMIN_SECRET_KEY = ""
RECRUITER_SECRET_KEY = ""
CANDIDATE_SECRET_KEY = ""
MONGO_URI = ""
PORT = 
