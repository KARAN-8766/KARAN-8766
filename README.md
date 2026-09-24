<h1 align="center">Hi, I'm Karan 👋</h1>
<h3 align="center">Software Engineer | ASP.NET Core & React | Azure | Multi-Tenant SaaS</h3>

<p align="center">
  <a href="https://linkedin.com/in/karanchaudhary7"><img src="https://img.shields.io/badge/LinkedIn-14213D?style=for-the-badge&logo=linkedin&logoColor=C8A03C" /></a>
  <a href="mailto:karanchaudhary8106@gmail.com"><img src="https://img.shields.io/badge/Email-14213D?style=for-the-badge&logo=gmail&logoColor=C8A03C" /></a>
  <a href="https://github.com/KARAN-8766"><img src="https://img.shields.io/badge/GitHub-14213D?style=for-the-badge&logo=github&logoColor=C8A03C" /></a>
</p>

I'm a Software Engineer specializing in **healthcare SaaS systems** and **scalable APIs** using ASP.NET Core, React, and Azure. I enjoy working with CQRS architecture, clean code practices, and cloud-native deployments — currently building a multi-tenant HRMS product from the ground up with a teammate, alongside shipping production features on a medical coding platform at Chirok Health.

<br>

## ⚡ Tech Stack

| Category | Technologies |
|---|---|
| **Backend** | <img src="https://img.shields.io/badge/C%23-14213D?style=for-the-badge&logo=csharp&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/ASP.NET_Core-14213D?style=for-the-badge&logo=dotnet&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/MediatR-14213D?style=for-the-badge" height="32"/> <img src="https://img.shields.io/badge/CQRS-14213D?style=for-the-badge" height="32"/> |
| **Frontend** | <img src="https://img.shields.io/badge/React-14213D?style=for-the-badge&logo=react&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/TypeScript-14213D?style=for-the-badge&logo=typescript&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/Vite-14213D?style=for-the-badge&logo=vite&logoColor=C8A03C" height="32"/> |
| **Databases** | <img src="https://img.shields.io/badge/SQL_Server-14213D?style=for-the-badge&logo=microsoftsqlserver&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/PostgreSQL-14213D?style=for-the-badge&logo=postgresql&logoColor=C8A03C" height="32"/> |
| **Cloud & DevOps** | <img src="https://img.shields.io/badge/Azure-14213D?style=for-the-badge&logo=microsoftazure&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/Docker-14213D?style=for-the-badge&logo=docker&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/GitHub_Actions-14213D?style=for-the-badge&logo=githubactions&logoColor=C8A03C" height="32"/> |
| **Tools** | <img src="https://img.shields.io/badge/Git-14213D?style=for-the-badge&logo=git&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/Redis-14213D?style=for-the-badge&logo=redis&logoColor=C8A03C" height="32"/> <img src="https://img.shields.io/badge/JWT-14213D?style=for-the-badge&logo=jsonwebtokens&logoColor=C8A03C" height="32"/> |

<br>

## 🏆 Featured Projects

### 🟢 [HRMS SaaS Platform](https://github.com/KARAN-8766)
A **multi-tenant HR platform** that lets small businesses manage attendance, payroll, and support tickets from one dashboard.

- **Multi-tenant architecture**: shared-schema design with `OrganizationId` on every tenant-scoped table and EF Core global query filters enforced centrally, so tenant data never leaks across organizations.
- **Modular monolith**: ASP.NET Core + PostgreSQL, with clean vertical-slice boundaries for Attendance, Payroll, and Ticketing — each module ships independently without touching the others.
- **Auth**: JWT access tokens with hashed, rotating refresh tokens (server-side revocation), and a User/Employee split so employees can exist without ever needing a login.
- **Deployment**: containerized with Docker from day one, CI/CD via GitHub Actions targeting Azure App Service with managed PostgreSQL.

`ASP.NET Core` `React` `PostgreSQL` `Docker` `GitHub Actions` `Azure`

### 🟢 [NeighbourIQ](https://github.com/KARAN-8766)
Helps users research a neighbourhood's safety, amenities, and vibe using **AI-generated insights**.

- Built with Clean Architecture (ASP.NET Core + React), Redis caching, and Mapbox for location-based data aggregation.
- Integrated OpenAI APIs to power natural-language neighbourhood insights, with JWT auth and TanStack Query on the frontend.

`ASP.NET Core` `React/TypeScript` `Redis` `PostgreSQL` `Mapbox` `OpenAI API`

### 🟢 [Ticket Management System](https://github.com/KARAN-8766)
A helpdesk tool where users log complaints and staff resolve them through role-based workflows.

- Admin/Agent/User role system with a real-time dashboard and complete ticket lifecycle tracking.
- Azure SQL via EF Core with indexing and stored procedures for consistent performance under load.

`ASP.NET Core MVC` `EF Core` `Azure SQL` `Bootstrap`

<br>

## 💼 Professional Journey

**Software Developer, Chirok Health** — *Mar 2026 – Present*
Healthcare SaaS platform for medical coding, billing audits, and chart workflows.

- Built 9 CQRS API endpoints in ChempAPI, replacing legacy stored procedures with HIPAA-compliant audit logging.
- Migrated a legacy WebForms app (QueryMgmt) to ASP.NET Core + React using Vertical Slice CQRS with MediatR, including a stage-based workflow engine for document clarifications.
- Led the Azure deployment of an internal audit tool to a private VNet — Application Insights, Serilog, Key Vault, and Managed Identity.
- Built a C# billing audit tool that automatically flags missing CPT code modifiers.
- Set up Azure DevOps CI/CD pipelines with automated secret injection, reducing deployment errors to zero.

<br>

## 🎓 Certifications & Achievements

- 🎓 **B.Tech, Computer Science & Engineering** — Amity University, Uttar Pradesh (2021–2025)
- 📜 [**IBM Generative AI Engineering Professional Certificate**](https://coursera.org/share/dbfc730a09eccdbe9618933ad13d5c81)
- 📄 **Published Researcher, PiCET 2025** — *ML & Meta-Heuristic Approaches for Energy Optimization in WSN* (hybrid PSO + Genetic Algorithm model, up to 67% energy reduction)
- 🧠 **Active DSA Practitioner** — working through Striver's A2Z Sheet on LeetCode

<br>



## 🤝 Connect With Me

Always happy to talk ASP.NET Core, CQRS, Azure architecture, or SaaS product building:

- 💼 LinkedIn: [linkedin.com/in/karanchaudhary7](https://linkedin.com/in/karanchaudhary7)
- 📧 Email: [karanchaudhary8106@gmail.com](mailto:karanchaudhary8106@gmail.com)
- 🐙 GitHub: [github.com/KARAN-8766](https://github.com/KARAN-8766)

<p align="center"><i>"Clean architecture today saves you a rewrite tomorrow."</i></p>
