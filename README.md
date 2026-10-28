# ⚖️ LegalEase – Legal Case Management System

LegalEase is a web-based legal assistance and case management application designed to connect clients, lawyers, and judges through a unified platform. It provides access to legal information and offers interfaces for managing case details, user profiles, schedules, feedback, and payment-related workflows.

## ✨ Features

- **Legal Information Portal:** Explore legal information, articles, rights, and legal services.
- **Lawyer Search:** Find lawyers based on their specialization.
- **Role-Based Dashboards:** Separate dashboards for clients, lawyers, and judges.
- **Case Management:** View case details, case status, filing dates, and related documents.
- **Client Management:** Access client profiles and case-related information.
- **Lawyer Profiles:** View lawyer details and areas of specialization.
- **Judge Dashboard:** View assigned cases and related information.
- **Scheduling:** Interfaces for managing hearing schedules.
- **Feedback System:** Submit ratings and feedback.
- **Payment Management:** Support payment-related workflows.
- **Session Management:** PHP sessions support login state and access to role-specific pages.

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Bootstrap Icons

**Backend**
- PHP
- Oracle Database
- PHP OCI8 extension for database connectivity

**Development Environment**
- Android Studio is not required; this is a web application.
- Local PHP development server
- Oracle Database XE

## 📂 Project Structure

```text
LegalEase/
├── index.html
├── login.html
├── register.html
├── login.php
├── logout.php
├── client-dashboard.php
├── client_profile.php
├── case-details.php
├── lawyer-dashboard.php
├── lawyer_profile.php
├── judge-dashboard.php
├── judge_profile.php
├── judge-case-details.php
├── get_lawyers.php
├── get_specializations.php
├── submit-feedback.php
├── submit-payment.php
├── script.js
├── styles.css
├── images/
└── documents/
```

*Note: This is a representative structure. The actual files and folders may vary depending on the contents uploaded to the repository.*

## ⚙️ Prerequisites

To run LegalEase locally, you will need:

- PHP installed and configured.
- Oracle Database XE or a compatible Oracle Database instance.
- PHP OCI8 extension enabled.
- A web server or PHP development server.
- The required Oracle database tables and schema.
- A modern web browser.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Soumyajha17/LegalEase.git
cd LegalEase
```

### 2. Configure the database

- Set up Oracle Database and create the required tables.
- Configure the database connection using local environment variables or a separate configuration file.
- Ensure PHP OCI8 is installed and enabled.
- Verify that the database connection settings match your local Oracle installation.

**Important:** Do not upload database passwords, API keys, or other sensitive credentials to GitHub.

### 3. Start the PHP development server

From the project directory, run:

```bash
php -S localhost:8000
```

Open the application in your browser:

http://localhost:8000/index.html

Database-dependent features require a properly configured Oracle database and the necessary schema.

## 🗄️ Database

The uploaded PHP files reference Oracle tables such as:

- `CLIENT`
- `LAWYER`
- `JUDGE`
- `CASES`
- `NAME`
- `CJUDGE`
- `SCHEDULE`
- `FEEDBACK`
- `PAYMENT`

The database schema, relationships, constraints, and setup scripts should be documented separately if available.

## 👥 Team Members & Contributions

### Backend Development
- **Soumya Jha** — Backend Development
- **Prisha Chadda** — Backend Development

Responsibilities include server-side functionality using PHP, Oracle database connectivity, and case management workflows.

### Frontend Development
- **Tanisha Mathur** — Frontend Development

Responsibilities include developing the user interface using HTML, CSS, JavaScript, and Bootstrap.

## 🔐 Security Considerations

- Keep database credentials outside the source code.
- Use password hashing and secure password verification.
- Validate user input on the server.
- Apply appropriate authentication and authorization checks.
- Avoid uploading confidential legal documents or personal client information.
- Exclude local configuration files and secrets from version control.

## 🔮 Future Enhancements

- Improve authentication and password security.
- Enhance case tracking and scheduling workflows.
- Improve responsive design and accessibility.
- Add automated testing and input validation.
- Document database setup and deployment procedures.

## 🎓 Project Information

**Project Name:** LegalEase – Legal Case Management System

**Project Type:** Academic Team Project

**Institution:** Manipal Institute of Technology, MAHE

**Domain:** Web Development and Database Management

## 📌 Project Status

LegalEase is an academic project demonstrating a web-based approach to legal information access and case management. Features that depend on the Oracle database require the appropriate local configuration to operate.

---

*Developed collaboratively by Soumya Jha, Prisha Chadda, and Tanisha Mathur.*
