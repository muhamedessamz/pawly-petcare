# 🐾 Pawly Petcare - Complete Platform Documentation

<div align="center">

![Pawly Petcare Banner](Dashboard.png)

**The All-in-One Pet Adoption & Veterinary Care Platform**

[Frontend Repository](https://github.com/muhamedessamz/Pawly-Petcare-Frontend) • [Backend Repository](https://github.com/muhamedessamz/Pawly-Petcare-Backend) • [Dashboard Repository](https://github.com/muhamedessamz/Pawly-Petcare-Dashboard)

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Architecture](#-architecture)
- [Repositories](#-repositories)
- [Key Features](#-key-features)
  - [Pet Adoption](#-pet-adoption)
  - [Veterinary Services](#-veterinary-services)
  - [E-Commerce](#-e-commerce)
  - [Admin Dashboard](#-admin-dashboard)
- [Tech Stack](#-tech-stack)
- [Gallery](#-gallery)
- [Getting Started](#-getting-started)
- [License](#-license)

---

## 🎯 Project Overview

**Pawly Petcare** is a comprehensive solution designed to modernize the pet adoption process and veterinary care management. It bridges the gap between pet shelters, veterinarians, and pet lovers through a unified digital ecosystem.

The system consists of three main components:
1.  **Customer Website**: For users to browse pets, book appointments, and shop.
2.  **Admin Dashboard**: For staff to manage operations, approve adoptions, and oversee the platform.
3.  **Backend API**: A robust .NET 8 API serving as the central nervous system.

---

## 🏗️ Architecture

The project follows a **Microservices-inspired Monolith** approach, with a clean separation between the frontend and backend.

### Frontend
- **Main Website**: Built with React & TailwindCSS, optimized for SEO and user experience.
- **Dashboard**: A separate React application focusing on data visualization and management tools.

### Backend
- **Core API**: Built with ASP.NET Core 8 following **Clean Architecture**.
- **Database**: SQL Server managed via Entity Framework Core.
- **Security**: JWT Authentication and Role-Based Access Control (RBAC).

---

## 🔗 Repositories

| Component | Repository Link | Description |
|-----------|-----------------|-------------|
| **Frontend** | [Pawly-Petcare-Frontend](https://github.com/muhamedessamz/Pawly-Petcare-Frontend) | The main customer-facing website. |
| **Backend** | [Pawly-Petcare-Backend](https://github.com/muhamedessamz/Pawly-Petcare-Backend) | The API and business logic layer. |
| **Dashboard** | [Pawly-Petcare-Dashboard](https://github.com/muhamedessamz/Pawly-Petcare-Dashboard) | The admin control panel. |

---

## ✨ Key Features

### 🐾 Pet Adoption
Users can browse adoption listings with advanced filters (breed, size, age). The adoption workflow includes:
-   **Submission**: Users submit requests for pets.
-   **Review**: Admins review applications via the dashboard.
-   **Approval/Rejection**: Automated status updates and notifications.

### 🏥 Veterinary Services
-   **Doctor Profiles**: Detailed info on vets including specialties and ratings.
-   **Appointment Booking**: Real-time scheduling system.

### 🛒 E-Commerce
A full-featured online store for pet supplies.
-   **Product Catalog**: Easy-to-manage inventory.
-   **Cart & Checkout**: Secure order processing.

### 📊 Admin Dashboard
A powerful tool for platform administrators.

#### Features:
-   **Real-time Stats**: Track adoptions, revenue, and active users.
-   **User Management**: Control roles and permissions.
-   **Content Management**: Publish blogs and update site content.

---

## 🛠️ Tech Stack

### Frontend
-   **React 19**
-   **Vite**
-   **TailwindCSS v4**
-   **Axios**
-   **Recharts** (Dashboard Stats)

### Backend
-   **ASP.NET Core 8.0**
-   **C# 12.0**
-   **Entity Framework Core**
-   **SQL Server 2022**
-   **JWT Authentication**

---

## 📸 Gallery

### Admin Dashboard Overview
![Dashboard Overview](Dashboard.png)
*A comprehensive view of platform metrics and recent activities.*

### Adoption Requests Management
![Adoption Requests](Adoption%20Requests.png)
*Admins can review, approve, or reject pet adoption applications efficiently.*

### Product Management
![Products List](Products.png)
*manage the e-commerce inventory with ease.*

### Adding New Products
<div style="display: flex; gap: 10px;">
  <img src="Add New Product 1.png" width="48%" />
  <img src="Add New Product 2.png" width="48%" />
</div>
*Detailed product creation forms with image upload support.*

### Creating Admin Accounts
![Add Admin](Add%20Admin.png)
*Role management system for adding new staff members.*

### Appointments View
![Appointments](Appointments.png)
*Track and manage veterinary appointments.*

---

## 🚀 Getting Started

To run the entire platform locally:

1.  **Clone all repositories** into a single folder.
2.  **Setup Backend**:
    -   Navigate to `Pawly-Petcare-Backend`.
    -   Update `connectionStrings` in `appsettings.json`.
    -   Run `dotnet ef database update`.
    -   Run `dotnet run`.
3.  **Setup Frontend**:
    -   Navigate to `Pawly-Petcare-Frontend`.
    -   Run `npm install` && `npm run dev`.
4.  **Setup Dashboard**:
    -   Navigate to `Pawly-Petcare-Dashboard`.
    -   Run `npm install` && `npm run dev`.

---

## 📄 License

This project is licensed under the **MIT License**.

---

<div align="center">

**Made with ❤️ by Mohamed Essam**
[@muhamedessamz](https://github.com/muhamedessamz)

</div>
