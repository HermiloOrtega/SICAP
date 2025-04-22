# 📦 SICAP

## 🧭 Overview
**SICAP** is a comprehensive Windows application developed using C# and SQL Server, hosted on a company Windows Server. Originally created during my internship, SICAP was designed to modernize the legacy Visual Fox application's estimating module. The system automates data import, project categorization, contract assignment, and estimation tracking—all supported by secure login mechanisms with encrypted passwords and detailed reporting via Crystal Reports.

## 💡 Idea & Concept
SICAP was developed to migrate and enhance the estimating module. Key processes include:
- **Data Import:** Automatically downloading txt files from an SAP internal environment and uploading new project/contract data into SQL Server.
- **Project Categorization:** Applying business rules to classify projects into types (administrative, technical, operations/field) and dynamically altering screen behavior and status workflows.
- **Contract Assignment:** Notifying managers to assign or reject contracts through an internal inbox.
- **Estimation Processing:** Receptionists register new estimations by searching for contracts, auto-generating estimation numbers, and entering details.
- **Notifications & Reporting:** Status change email notifications and printable reports using Crystal Reports.
- **Security:** Encrypted login and user lockout after three failed attempts.

## ✨ Features & Functionality
- **Data Import & Upload:** Pulls txt files from SAP and updates the project/contract database.
- **Dynamic Behavior:** Screens and workflows adapt based on contract/project type.
- **Secure Login:** Encrypted credentials and lockout mechanism for unauthorized access.
- **Contract Assignment:** Internal inbox for contract approval or rejection by managers.
- **Estimation Module:** Registers estimations, auto-generates numbers, and logs details with email proof.
- **Error Logs & Help:** Troubleshooting tools and detailed views on double-click.
- **Crystal Reports:** Generates printable reports and summaries with every status change.

## ⚙️ Tech Stack
- **Platform:** Windows Application
- **Programming Language:** C#
- **Database:** SQL Server
- **Reporting:** Crystal Reports
- **Hosting:** Windows Server

## 🏗 Architecture & Design
- Secure access via encrypted login and role-based controls.
- Data pipelines to import and process SAP data.
- Adaptive interface based on project types.
- Status-tracked workflows for contract and estimation management.
- Reporting powered by Crystal Reports.
- Hosted across DEV, QAS, and PRD environments for stability and release management.

## 🚀 Installation & Setup
- **Environments:** DEV, QAS, PRD for development, QA, and production
- **Prerequisites:** Windows OS, .NET Framework, SQL Server
- **Deployment:** Hosted internally on company infrastructure

> **Note:** Setup and support provided in collaboration with the IT team.

## 🧑‍💻 Usage
1. Automatic SAP data import to update contracts/projects.
2. Contract assignment and review via internal inbox.
3. Reception logs new estimations, which are auto-numbered and stored.
4. Email notifications sent at each status transition.
5. View errors and access help via in-app tools.
6. Generate reports using Crystal Reports as needed.

## 🔍 My Role & Contributions
- 💼 Migrated legacy estimation system from Visual Fox to C#
- 🧱 Developed data import, project categorization, and secure login
- 🐞 Integrated email alerts, dynamic UI, and estimation workflows
- 🤝 Built detailed reporting and collaborated with IT for deployment

## 🧗 Challenges & Learnings
- Migrating and refactoring legacy logic from Visual Fox
- Maintaining data integrity during automated SAP imports
- Implementing adaptable workflow logic
- Securing the system with encryption and access control
- Coordinating dependencies across modules

## 📈 Impact & Performance
- Replaced legacy app with modern, fast, and user-friendly system
- Boosted adoption due to simplicity, reliability, and performance
- Became a core application for project and estimation management

## 📈 Future Enhancements
- Add new contract lifecycle modules
- Implement analytics and KPI dashboards
- Improve UI and UX based on user feedback
- Automate more error detection and reporting

## 🤝 Contributing
Internal project — suggestions can be shared with the project lead or development team.

## 🪪 License
Internal use only. Not for public distribution.

## 🔗 Additional Resources
- **Related Systems:** Integrated with SAP and internal contract management tools
- **Microsoft Relevance:** Built using C#, SQL Server, and Crystal Reports in an enterprise-grade architecture.