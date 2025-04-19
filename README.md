# EpinHell – ASP.NET Core MVC Web Application

**EpinHell** is a full-stack web application built using ASP.NET Core MVC and Entity Framework Core. It is designed to simulate a digital marketplace where users can register, browse and purchase digital game keys (E-pins), while administrators manage inventory, users, and orders through a secure dashboard.

---

## 🌟 Key Features

- 🔐 **Authentication & Authorization**
  - Secure user registration and login
  - Role-based access control for users and administrators

- 🛒 **E-pin Marketplace**
  - Browse available products and digital codes
  - Purchase and instantly access digital content
  - Filter and manage inventory availability

- 🛠️ **Admin Panel**
  - Add, update, or delete E-pin codes
  - Manage product listings and categories
  - View and manage user information

- 💾 **Database Integration**
  - Local SQLite database with Entity Framework Core
  - Database migrations included
  - Seeded test data available for immediate use

---

## 🧱 Technologies Used

- ASP.NET Core MVC (C#)
- Entity Framework Core
- Razor Views
- SQLite
- LINQ
- HTML5, CSS, Bootstrap
- Visual Studio 2022

---

## 📁 Project Structure Overview

```
EpinHell/
├── Controllers/         → MVC controllers (User, Admin, Auth, etc.)
├── Models/              → Entity models for EF Core
├── Views/               → Razor view templates for UI rendering
├── Data/                → Database context and seeding logic
├── wwwroot/             → Static assets (CSS, JS, images)
├── Migrations/          → EF Core database migrations
├── EpinHell.db          → SQLite database file
├── Program.cs           → Application entry point
├── appsettings.json     → Configuration settings
```

---

## ⚙️ How to Run the Project

1. Clone the repository:
   ```
   git clone https://github.com/UKBey/EpinHell.git
   ```
2. Open the solution file `EpinHell.sln` in **Visual Studio 2022**.
3. Build the solution and run the project using IIS Express or Kestrel.
4. The web application will launch in your default browser.
5. Use pre-seeded login credentials or create a new account.

---

## 👤 Author

**Ukbe Taha Şahinkaya**  

---

## 📄 License

This project is open-source and available for educational and portfolio use.
