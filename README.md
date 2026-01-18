# Prints Studio 🎨

**Prints Studio** is a modern, full-stack web application designed for users to customize, design, and order printed materials such as business cards, wedding invitations, and personalized products. Built with a focus on high-performance UI and a robust backend, the platform bridges the gap between customers and professional designers.

---

## 🚀 Project Overview

The application leverages **Blazor WebAssembly** for a seamless client-side experience and **ASP.NET Core** for a secure, scalable backend. It follows **Clean Architecture** principles to ensure a clear separation of concerns across Domain, Application, Infrastructure, and Server layers.

### Key Features

* **Role-Based Access:** Specialized dashboards and permissions for Admins, Designers, and Customers.
* **Dynamic Customization:** Interactive design interface where users can modify paper types, sizes, font families, and colors.
* **Template Gallery:** A rich showcase of pre-designed templates with live previews and filtering.
* **Designer Marketplace:** Users can browse designer portfolios, view their specialized work, and hire them for custom projects.
* **Order Management:** Comprehensive workflow including shopping cart management, order summaries, and checkout.
* **Admin Management Panel:** Centralized control for product catalogs, designer approvals, and platform-wide analytics.
* **Messaging & Queries:** Integrated system for user support and direct communication between parties.

---

## 🛠️ Technologies Used

### Frontend (Client-Side)

* **Framework:** Blazor WebAssembly
* **Styling:** Bootstrap 5, HTML5, and CSS3
* **Interactivity:** JavaScript Interop (for custom alerts, modals, and confirmations)
* **State Management:** Local Storage API for session persistence
* **Forms:** Blazor EditForms with two-way data binding and validation

### Backend (Server-Side)

* **Framework:** ASP.NET Core 8.0
* **Database ORM:** Entity Framework Core (Code First)
* **Architecture:** Clean Architecture (Domain, Application, Infrastructure, Presentation)
* **Security:** ASP.NET Core Identity for role-based authentication and authorization
* **API:** RESTful API Services using Controllers and DTOs

---

## 👥 User Roles

1. **Customer:** Browses the catalog, customizes templates, manages a cart, and tracks order history.
2. **Designer:** Manages a professional profile, uploads new design templates, and handles custom bookings.
3. **Admin:** Oversees the entire ecosystem, including user role management, content moderation, and business analytics.

---

## ⚙️ Setup & Installation

### Prerequisites

* [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0)
* [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
* Visual Studio 2022 or VS Code

### Steps to Run

1. **Clone the Repository:**
```bash
git clone https://github.com/pupucit/blazor-project-taha.git

```


2. **Database Configuration:** Update the connection string in the `appsettings.json` file located in the Server project.
3. **Apply Migrations:**
```bash
dotnet ef database update --project YourProjectName.Server

```


4. **Launch the Project:** Run the application via Visual Studio (F5) or using the CLI:
```bash
dotnet run

```



---
