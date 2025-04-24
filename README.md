# 📦 SICAP

## 🧭 Overview
**SICAP** is a robust, enterprise-grade Windows application developed using C# and SQL Server, hosted on internal company infrastructure. The project was initiated as part of my 6-month internship but quickly evolved when, after just 3 months, I was offered a full-time Software Engineer position and granted complete control of the system’s design and development.

Originally tasked with migrating a legacy Visual FoxPro estimation system, I led the modernization into a full-stack, data-driven application—covering everything from UI/UX to database design, user authentication, SAP data import, and reporting.

### Login Screen
![Screenshot](./assets/8.png) <!-- Replace with your image path -->

### Home page
![Screenshot](./assets/7.png) <!-- Replace with your image path -->

### Collect estimation
![Screenshot](./assets/3.png) <!-- Replace with your image path -->

### Manual cover
![Screenshot](./assets/9.png) <!-- Replace with your image path -->

## 💡 Idea & Concept
SICAP was created to modernize and streamline the company’s entire estimation and contract tracking workflow. The legacy process was error-prone and inflexible. My goals were:
- Automate data import from SAP (TXT files with complex validation rules).
- Enable dynamic contract workflows driven by project type.
- Introduce user-friendly interfaces and modular navigation.
- Provide secure and role-based access control.
- Centralize estimation, assignment, and reporting across all projects.

With no external development support, I was responsible for designing the full system architecture, front-end experience, backend integration, database development, data models, QA, and documentation.

## ✨ Features & Functionality
- 🔐 **Secure Login** with:
  - Encrypted passwords
  - Lockout after failed attempts
  - Password reset and access request workflows
  - Environment selector (DEV, QAS, PRD)
- 📁 **SAP Integration**: Import TXT files into SQL Server with validation and categorization rules
- 🗃 **Contract Assignment Module**:
  - Filterable lists of new SAP-imported contracts
  - Manual reassignment logic (technical/admin)
  - Workflow logic driven by department
- 📊 **Estimation Module**:
  - Estimation registration with auto-numbering
  - Grid-based contract viewer with conditional formatting
  - Status tracking (on time, overdue, etc.)
  - Email notification triggers
- 🧭 **Ribbon-Based Navigation UI**:
  - Inspired by Office 2007 ribbon bar design
  - Tabs for Documents, Searches, Operations, Updates, Tools
  - Dynamic tab contents based on user roles
- 📄 **Documentation Hub**:
  - Module manuals
  - Operational procedures
  - Format templates (non-system forms)
- 🔍 **Search Tools**:
  - Search across multiple tables (contracts, vendors, types, employees)
- 📤 **Crystal Reports Integration**:
  - PDF exports for estimates, statuses, and operational summaries
- 📐 **Photoshop-designed UI assets**:
  - Buttons, interface elements, help overlays

## ⚙️ Tech Stack
- **Language**: C#
- **Framework**: WinForms / .NET Framework
- **Database**: SQL Server (with stored procedures, views, constraints)
- **Reporting**: Crystal Reports
- **Design Tools**: Adobe Photoshop
- **Hosting**: Windows Server environments for DEV, QAS, PRD

## 🏗 Architecture & Design
- Full-stack monolithic Windows application
- SQL Server-backed data model with normalization and performance tuning
- Modular ribbon UI to support scalability and multiple departments
- Secure login architecture with environment context selection
- Text-based SAP import scheduler and backend logic using dynamic SQL

## 🚀 Installation & Setup
- **Environments**: DEV, QAS, PRD (environment selected at login)
- **Deployment**: Internal Windows Server
- **Permissions**: Developer had full schema access; DB creation by IT

> **Note**: I handled all dev environments, schema management, QA, and deployment planning.

## 🧑‍💻 My Role & Contributions
- 🎯 Full ownership from design to deployment
- 🗂 SQL schema creation, data modeling, stored procedures
- 🛠 C# full-stack development (UI, backend, logic, integration)
- 🎨 Designed ribbon-based UI and Photoshop visual assets
- 🔁 Developed SAP import logic and backend workflows
- 🧪 QA-tested all workflows and trained stakeholders
- 📚 Authored technical and operational documentation
- 🧠 Proposed and implemented all innovations based on user feedback

## 🧗 Challenges & Learnings
- Migrated and refactored legacy estimation logic to modern architecture
- Managed TXT file parsing and contract workflow generation
- Handled multi-environment dev and testing seamlessly
- Designed scalable, intuitive UX from scratch with zero external help
- Optimized SQL queries and indexes for performance
- Built system processes that later became standards across teams

## 📈 Impact & Performance
- Replaced unreliable legacy Visual Fox system
- Achieved 100% system adoption across departments
- Allowed users to test and validate features in QAS before production releases
- Became a mission-critical system reviewed weekly by directors and engineers
- Reduced manual data entry and estimation cycle time by over 50%

## 📈 Future Enhancements
- Extend module support to handle:
  - Document signing
  - Approval workflows
  - Advance payments and service bundles
  - Contract extensions
- Integrate with digital signature platforms
- Create web-based front-end using Blazor or ASP.NET Core

## 🤝 Contributing
Private internal application. Requests are routed through internal system admin and reviewed by the development lead.

## 🪪 License
⚠️ **License Update**  
Originally released under MIT. As of April 22, 2025, this project follows the **CC BY-NC-ND 4.0** license.  
See LICENSE file for usage limitations.

## 🔗 Additional Resources
- **Related Systems**: SICAP Web, SICAP Updater
- **Microsoft Relevance**: Demonstrates mastery of C#, WinForms, SQL Server, Crystal Reports, and enterprise lifecycle ownership typical of senior Microsoft roles.
