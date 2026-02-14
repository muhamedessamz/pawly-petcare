# 🐾 Pawly Petcare - Unified Adoption & Veterinary Platform

<div align="center">

![Pawly Petcare Dashboard](Dashboard.png)

[![Frontend](https://img.shields.io/badge/Frontend-React_19-61DAFB?style=for-the-badge&logo=react)](https://github.com/muhamedessamz/Pawly-Petcare-Frontend)
[![Backend](https://img.shields.io/badge/Backend-ASP.NET_Core_8-512BD4?style=for-the-badge&logo=dotnet)](https://github.com/muhamedessamz/Pawly-Petcare-Backend)
[![Dashboard](https://img.shields.io/badge/Admin-Dashboard-FF6B6B?style=for-the-badge&logo=react)](https://github.com/muhamedessamz/Pawly-Petcare-Dashboard)
![Database](https://img.shields.io/badge/Database-SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server)

**A modern, scalable microservices-inspired platform bridging the gap between shelters, veterinarians, and pet lovers.**

[Live Demo](https://pawly-petcare.vercel.app/) • [Documentation](PROJECT_STRUCTURE.md) • [Report Bug](https://github.com/muhamedessamz/pawly-petcare/issues)

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Architecture](#-architecture)
- [Repositories](#-repositories)

## 🚀 Executive Summary

**Pawly Petcare** addresses the fragmented nature of pet adoption and veterinary services. Traditional adoption processes are often manual and slow, while veterinary clinics struggle with digital appointment management.

**This solution provides:**
1.  **Centralized Pet Database**: Real-time tracking of available pets across multiple shelters.
2.  **Digital Adoption Workflow**: A fully automated application process with admin oversight.
3.  **Veterinary Integration**: Seamless appointment booking with verified doctors.
4.  **E-Commerce Capabilities**: Integrated shop for pet essentials, creating a sustainable revenue model.

---

## 🧠 Technical Architecture

The system is architected for **Scalability**, **Maintainability**, and **Security**.

### 🔹 Backend: Use of Clean Architecture
The core API is built on **Clean Architecture (Onion Architecture)** principles to ensure independence of frameworks and UI.

-   **Domain Layer**: Pure C# entities and business rules (Zero dependencies).
-   **Application Layer**: Use Cases, DTOs, and Interfaces (CQRS pattern ready).
-   **Infrastructure Layer**: EF Core implementation, Database migrations, and external services.
-   **Presentation Layer (API)**: Minimal controllers handling HTTP requests.

### 🔹 Frontend: Modern React Ecosystem
Two separate, optimized React applications:
-   **Main Website**: focused on SEO, accessibility, and high performance (Vite + Tailwind).
-   **Admin Dashboard**: Data-heavy interface using **Recharts** for analytics and complex tables for management.

---

## 🛠️ Key Skills Demonstrated

### Backend Engineering
-   **RESTful API Design**: Strict adherence to REST principles, proper status codes, and resource naming.
-   **Security Implementation**:
    -   **JWT Authentication**: Stateless, secure token-based auth.
    -   **RBAC (Role-Based Access Control)**: Granular permissions for Admins, Doctors, and Users.
    -   **Password Hashing**: Industry-standard Bcrypt implementation.
-   **Database Optimization**: Efficient querying with Entity Framework Core, proper indexing, and relationship mapping.

### Frontend Development
-   **Component-Driven UI**: Reusable, atomic components built with TailwindCSS.
-   **State Management**: efficient use of React Context API for global auth state.
-   **Performance**: Code splitting, lazy loading, and optimized asset delivery via Vite.
-   **Responsive Design**: Mobile-first approach ensuring usability across all devices.

---

## 📸 Visual Walkthrough

### 1. comprehensive Admin Dashboard
![Dashboard Stats](Dashboard.png)
*Real-time analytics providing insights into platform health, user growth, and adoption rates.*

### 2. Adoption Request Management
![Adoption Workflow](Adoption%20Requests.png)
*Admins can review detailed applications. The system supports Approval/Rejection workflows with instant status updates.*

### 3. Veterinary Appointment System
![Appointments](Appointments.png)
*A dedicated module for managing doctor schedules and upcoming appointments.*

### 4. Admin Role Management
![Admin Creation](Add%20Admin.png)
*Secure interface for creating new administrative accounts with specific privileges.*

### 5. Product & Inventory Control
![Product Management](Products.png)
*Full CRUD capabilities for the e-commerce module, allowing easy stock management.*

<div style="display: flex; gap: 10px; margin-top: 10px;">
  <img src="Add New Product 1.png" width="48%" alt="Product Form Part 1" />
  <img src="Add New Product 2.png" width="48%" alt="Product Form Part 2" />
</div>
*Detailed product entry forms ensuring rich data collection including images and descriptions.*

---

## 📂 Repository Ecosystem

This project is distributed across three specialized repositories for better CI/CD and maintenance.

| Repository | Purpose | Tech Stack |
|------------|---------|------------|
| [**Pawly-Petcare-Frontend**](https://github.com/muhamedessamz/Pawly-Petcare-Frontend) | Customer-facing website | React, Vite, TailwindCSS |
| [**Pawly-Petcare-Backend**](https://github.com/muhamedessamz/Pawly-Petcare-Backend) | Core API & Business Logic | .NET 8, EF Core, SQL Server |
| [**Pawly-Petcare-Dashboard**](https://github.com/muhamedessamz/Pawly-Petcare-Dashboard) | Admin Control Panel | React, Recharts, Axios |

---

## ⚡ Deployment & DevOps

-   **Containerization**: Ready for Docker deployment (Dockerfiles included in Backend).
-   **CI/CD**: Structured for GitHub Actions pipelines (Build -> Test -> Deploy).
-   **Hosting**: Compatible with Azure App Service, AWS Elastic Beanstalk, or easy Vercel/Netlify deployment for frontend.

---

## 📄 License & Attribution

This project is open-source under the **MIT License**.

Built with ❤️ by **Mohamed Essam**.
-   **GitHub**: [@muhamedessamz](https://github.com/muhamedessamz)
-   **LinkedIn**: [Mohamed Essam](https://www.linkedin.com/in/mohamedessamz/)

---

<div align="center">

**[⬆ Back to Top](#-pawly-petcare---unified-adoption--veterinary-platform)**

</div>
