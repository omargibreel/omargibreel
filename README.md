<h1 align="center">Hi 👋, I'm Omar Osama Gibreel</h1>
<h3 align="center">.NET Backend Developer | Microsoft Dynamics 365 & Power Platform Developer | Clean Architecture Enthusiast</h3>

<p align="center">
  📍 Cairo, Egypt <br/>
  📧 omargibreell@gmail.com
</p>

<p align="center">
  <a href="https://github.com/omargibreel">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github" />
  </a>
  
  <a href="https://linkedin.com/in/omargibreel">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin" />
  </a>
</p>

---

# 🚀 About Me

Software developer who bridges traditional .NET backend engineering with Microsoft Dynamics 365 / Power Platform — building scalable APIs and database-driven systems on one side, and architecting Dataverse solutions on the other.

- 🎓 B.Sc. in Computer Science — HTI (GPA: 3.33 / 4.0)
- 🏫 ITI Professional Development & BI-Infused CRM Trainee — Intake 46
- 🏗️ Solution Architect & Technical Lead on **Buildora**, a 6-person Power Platform graduation project
- 💻 Focused on Backend Development, Database Engineering, and Dataverse Solution Architecture
- ⚡ Interested in API Design, SQL Optimization, and Software Architecture

---

# 🛠️ Tech Stack

## 💻 Backend
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet)
![Entity Framework](https://img.shields.io/badge/Entity_Framework-512BD4?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=flat-square)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square)

---

## 🗄️ Database
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver)
![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?style=flat-square)
![SSRS](https://img.shields.io/badge/SSRS-CC2927?style=flat-square)

---

## ⚙️ CRM & Power Platform
![Dynamics 365](https://img.shields.io/badge/Dynamics_365-002050?style=flat-square&logo=microsoft)
![Dataverse](https://img.shields.io/badge/Dataverse-742774?style=flat-square)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate)
`PCF (PowerApps Component Framework)` `Power Fx` `Business Process Flows` `Custom Plugins`

---

## 🏗️ Architecture
`Clean Architecture`
`Onion Architecture`
`N-Tier Architecture`
`CQRS`
`SOLID`
`Repository Pattern`
`Unit of Work`

---

## 🌐 Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss)

---

# 💻 Featured Projects

## 🏗️ Buildora
### AI-Powered Construction Project Management Platform (Microsoft Power Platform)

Enterprise Dataverse solution for managing construction projects end-to-end — milestones, contracts, invoicing, payments, and risk — built as Solution Architect & Technical Lead for a 6-person team.

### 🔹 Features
- 16-table Dataverse schema: 12 purpose-built tables (Project, Milestone, Milestone Chapter, Contract, Document, Risk, Payment Certificate, Invoice Item, Payment, Project Setup, BPF Payment, Project Member) plus 4 reused Microsoft tables (Account, Contact, Invoice, User)
- Automatic milestone completion-percentage rollups from chapter-level progress
- Financial workflow spanning Payment Certificates → Invoices → Invoice Line Items → Payments as dedicated, auditable tables
- Document management via a custom-built PCF control that uploads files straight to SharePoint
- Risk tracking with configurable probability/severity choice sets
- Multi-environment portability using environment variables instead of hardcoded values

### 🔹 Tech Stack
- Microsoft Power Platform & Dataverse
- Power Automate (Cloud Flows)
- Power Fx (calculated formulas)
- PCF (PowerApps Component Framework, TypeScript)
- C# Plugins (Dataverse SDK)
- Business Process Flows
- SharePoint Online integration

### 🔹 Highlights
- Designed the full 16-table Dataverse schema as Solution Architect
- Built **5 custom C# plugins** registering **10 plug-in steps** — including pre-image-based Create/Update/Delete handling to keep milestone completion percentages in sync, plus plugin-enforced validation for milestone dates, chapter sequencing, invoice amounts, and payment-certificate eligibility
- Automated **12 Power Automate cloud flows** for deadline notifications, invoice status checks, and SharePoint document uploads
- Configured **4 processes** — 2 Business Process Flows (Project Setup, Payment) and 2 background workflows — plus 4 global choice sets for status and risk fields
- Built a custom PCF control (**Buildora File Upload Control**, v2.0.0) that uploads a file to SharePoint via an HTTP-triggered flow and writes the resulting URL straight back onto the Dataverse form
- Solution spans 16 tables, 5 plugin assemblies, 3 environment variables, and 4 security roles
- Delivered as both a graduation project and the technical foundation for a commercial construction-management SaaS product

🔗 **GitHub Repository**  
https://github.com/omargibreel/BuildoraCRM

---

## 🏨 Noqosh API
### Travel Booking Backend System

Backend booking system built using ASP.NET Core 8 and Onion Architecture.

### 🔹 Features
- JWT Authentication
- Google OAuth
- Stripe Payment Integration
- SignalR Real-Time Notifications
- OTP Verification
- Swagger API Documentation
- Fully Async APIs

### 🔹 Tech Stack
- ASP.NET Core 8
- SQL Server
- Entity Framework Core
- Onion Architecture
- Stripe
- SignalR

### 🔹 Highlights
- Built 30+ REST API endpoints
- Applied Repository & Specification patterns
- Secure payment workflow implementation
- Structured using 6-layer architecture

🔗 **Live API**  
https://noqosh.runasp.net/swagger/index.html

🔗 **GitHub Repository**  
https://github.com/Noqosh/NoqoshAPI

---

## 📝 Examination System Database
### SQL Server Database Project

Complete examination management database system designed using SQL Server and T-SQL.

### 🔹 Features
- Randomized exam generation using `NEWID()`
- Auto-grading workflows
- Referential integrity using foreign keys
- Stored procedures for business logic
- Reporting system using SSRS

### 🔹 Database Metrics

| Metric | Count |
|---|---|
| Tables | 17 |
| Core Tables | 9 |
| Junction Tables | 8 |
| Stored Procedures | 112+ |
| SSRS Reports | 10+ |
| Normalization | 3NF |

### 🔹 Technical Highlights
- One-to-many & many-to-many relationships
- Query optimization
- Modular SQL logic
- Reusable stored procedures
- Normalized relational schema

🔗 **GitHub Repository**  
https://github.com/omargibreel/ExaminationSystem-Database

---

## 🏋️ Gym Management System

Gym management web application built using ASP.NET Core MVC.

### 🔹 Features
- Role-Based Authorization
- Dashboard Analytics
- CRUD Operations
- Subscription Management
- Attendance Tracking

### 🔹 Tech Stack
- ASP.NET Core MVC
- SQL Server
- Entity Framework Core

🔗 **GitHub Repository**  
https://github.com/omargibreel/GymManagementSystem

---

## 🌐 Client-Side Examination Platform

Responsive online examination platform.

### 🔹 Features
- Timed Exams
- Question Shuffling
- Instant Auto-Scoring
- Responsive UI

### 🔹 Tech Stack
- JavaScript
- Tailwind CSS
- DaisyUI

🔗 **Live Demo**  
https://omargibreel.github.io/ExaminationSystem-ITI

---

# 🎯 Currently Learning

- Microsoft Power Platform certifications (PL-200, MB-280)
- Advanced SQL Optimization
- Docker
- Redis
- Unit Testing
- Azure Deployment

---

# 📫 Connect With Me

<p align="left">
<a href="https://linkedin.com/in/omargibreel" target="blank">
<img align="center" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="linkedin" height="30" width="40" />
</a>

<a href="https://github.com/omargibreel" target="blank">
<img align="center" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="github" height="30" width="40" />
</a>
</p>

---

<h3 align="center">⭐ Always Building. Always Learning.</h3>
