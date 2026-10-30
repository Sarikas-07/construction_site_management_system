# Construction Site Management System (CSMS)

A desktop-based application developed using C# Windows Forms and SQL Server to manage construction site operations, workforce records, materials, suppliers, financial transactions, and reports in one place.

## 📌 Overview

The **Construction Site Management System (CSMS)** is designed to simplify the management of construction-related activities through a centralized desktop application.

It provides administrative and management modules for maintaining project records, managing workers and materials, tracking task completion, handling transactions, and generating reports.

The system also supports monitoring pending tasks, helping managers and supervisors identify work that still requires attention.

## ✨ Features

- **Admin Management** — Access administrative functions through the application.
- **Project and Site Management** — Maintain construction project and site-related records.
- **Worker Management** — Organize and maintain worker information.
- **Material Management** — Manage construction material records.
- **Supplier Management** — Maintain supplier information.
- **Task Management** — Track completed and pending tasks.
- **Pending Task Notifications** — Display popup notifications for pending tasks.
- **Transaction Management** — Manage construction-related transaction records.
- **Payment Management** — Maintain payment-related information.
- **Reports** — Access reports for supported application modules.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Programming Language | C# |
| Application Type | Windows Desktop Application |
| User Interface | Windows Forms (WinForms) |
| Database | Microsoft SQL Server |
| Development Environment | Microsoft Visual Studio |
| Reporting | Crystal Reports / Microsoft ReportViewer dependencies |

*The exact reporting components required depend on the installed project references and the environment used to build the application.*

## 🏗️ Project Structure

The project is organized into modules for different construction management operations.

```text
Construction-Site-Management-System/
│
├── Admin/          # Administrative modules
├── Master/         # Master data management
├── Transaction/    # Transaction-related modules
├── Report/         # Reporting modules
├── Images/         # Application images and resources
│
├── app.config      # Application configuration
├── connection.cs   # Database connection logic
├── Program.cs      # Application entry point
├── README.md       # Project documentation
└── .gitignore      # Git exclusion rules
```

*This is a high-level overview. Individual filenames and additional folders may vary in the actual repository.*

## ⚙️ Prerequisites

Before running the application, ensure you have the required environment:

- Windows operating system
- Microsoft Visual Studio with the appropriate C#/.NET development components
- Compatible .NET Framework targeting support
- Microsoft SQL Server
- A configured CSMS database
- Any required Crystal Reports and Microsoft ReportViewer components referenced by the project

## 🚀 Getting Started

### 1. Clone the Repository

Open PowerShell or a terminal and run:

```bash
git clone https://github.com/Sarikas-07/construction_site_management_system.git
```

### 2. Open the Project

1. Open the cloned project folder.
2. Locate and open the Visual Studio solution (`.sln`) file.
3. Allow Visual Studio to load the project and its references.

### 3. Configure the Database

The application uses SQL Server for data storage.

1. Ensure the required CSMS database is available in SQL Server.
2. Review `connection.cs` and `app.config` for the current database connection configuration.
3. Update the connection settings to match your local SQL Server instance and database location.
4. Verify that the application can connect to the database.

**Important:** The database setup instructions and distributable database files or SQL setup script must be provided separately if they are not included in this repository.

### 4. Build and Run

1. Select the appropriate build configuration in Visual Studio.
2. Restore or install any missing project dependencies.
3. Build the solution.
4. Resolve any missing reference or database configuration errors.
5. Run the application from Visual Studio.

## 🔐 Configuration and Security

- Do not commit passwords, private keys, or other sensitive credentials.
- Keep local database files and generated build artifacts out of version control.
- Configure database connection settings for the environment where the application is being run.
- Review database access permissions before deploying the application to another machine.

## 🎯 Project Objectives

- Simplify construction site record management.
- Centralize worker, material, supplier, and transaction information.
- Improve visibility into task completion and pending work.
- Make relevant management information accessible through reports.
- Reduce reliance on disconnected manual record-keeping processes.

## 🔮 Future Enhancements

Potential improvements include:

- A documented database initialization and setup process.
- A portable database configuration for different machines.
- Improved input validation and database error handling.
- Enhanced dashboard and reporting capabilities.
- A guided application installation and deployment process.
- Additional automated testing and security improvements.

## 👩‍💻 Author

**Sarika Ghorpade**

GitHub: [@Sarikas-07](https://github.com/Sarikas-07)

## 📄 License

No license has been specified yet. Unless a license is added to the repository, reuse and redistribution permissions should not be assumed.

---

*Construction Site Management System — A centralized desktop solution for managing construction operations and records.*
