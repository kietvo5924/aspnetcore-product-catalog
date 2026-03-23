# Product Catalog Management System

A comprehensive web application built with ASP.NET Core Razor Pages to efficiently manage product catalogs, inventory details, and customer information.

## Features
- **Catalog Management:** Full CRUD (Create, Read, Update, Delete) functionality for managing Product Categories (Nhóm Hàng) and Product Details (Chi Tiết Hàng).
- **Master-Detail Views:** Intuitive UI for navigating hierarchical data between categories and their respective products.
- **Customer Management:** Maintain and track customer records (Khách Hàng) and address details (Địa Chỉ).
- **Relational Database:** Designed with Entity Framework Core for robust data mapping and integrity.
- **Responsive UI:** Clean, mobile-friendly interface styled with Bootstrap and custom CSS.

## Tech Stack
- **Framework:** ASP.NET Core Web App (Razor Pages)
- **Language:** C#
- **Database:** SQL Server (via Entity Framework Core)
- **Frontend:** HTML, CSS, Bootstrap, jQuery

## Prerequisites
- .NET SDK (Compatible with the project's target framework)
- SQL Server (or SQL Server Express)
- Visual Studio or Visual Studio Code

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/kietvo5924/](https://github.com/kietvo5924/)[tên-repo-mới].git
   ```
2. Navigate to the project directory:
   ```bash
   cd [tên-repo-mới]/Website_asp.net
   ```
3. Update the Database Connection String:
   Open `appsettings.json` and update the `DefaultConnection` string to match your local SQL Server credentials.
4. Apply Entity Framework Migrations:
   Open your terminal or Package Manager Console and run:
   ```bash
   dotnet ef database update
   ```
5. Run the application:
   ```bash
   dotnet run
   ```
6. Access the application in your browser at `https://localhost:xxxx` (check your console output for the exact port).
