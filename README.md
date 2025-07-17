
# 🐞 Bug Tracking System (BTS) – Scalable Issue Management Platform

## 📋 Overview

The **Bug Tracking System (BTS)** is a full-stack web application developed to streamline the management of software bugs across Agile development teams. It replaces rigid, high-cost third-party tools like JIRA with a lightweight, scalable, and fully customizable platform built with **Java**, **Spring Boot**, **Angular**, and **MySQL**.

The system offers a centralized interface for developers, testers, project managers, and administrators to collaborate efficiently. With features like real-time bug tracking, role-based access, and rich reporting, BTS enables higher productivity, quicker issue resolution, and better product quality.

---

## 🧩 Core Modules & Features

### 🛠️ Admin Module
- ✅ User Management (create, update, delete users by role)
- ✅ Project Management (add/remove projects, assign users)
- ✅ Bug Configuration (set statuses, severity levels, and types)
- ✅ Reporting (generate user/project-level performance reports)

### 🐞 Tester Module
- 📝 Log Bugs with steps, attachments, and severity
- 🗂️ Assign Bugs to relevant developers
- 🔄 Track Bug Status across the lifecycle

### 👨‍💻 Developer Module
- 🔧 View and fix assigned bugs
- 📌 Update bug status and leave resolution comments

### 📅 Manager Module
- 📊 Monitor project progress, open/resolved bug counts
- 👥 Assign work to devs/testers based on load
- ⏱️ Manage sprint timelines and delivery schedules

---

## 🏗️ Tech Stack

| Layer        | Tools & Frameworks |
|-------------|--------------------|
| Frontend    | Angular, TypeScript, Bootstrap, HTML5, CSS3 |
| Backend     | Java, Spring Boot, Spring Security, REST APIs |
| Database    | MySQL |
| Authentication | JWT (JSON Web Tokens) |
| Tools Used  | Postman, Maven, Git, JIRA, VS Code, Eclipse, Spring Tool Suite (STS) |

---

## 🚀 Installation Steps

### 🧠 Backend Setup

```bash
cd backend
./mvnw clean install
./mvnw spring-boot:run
````

### 🌐 Frontend Setup

```bash
cd frontend
npm install
ng serve --open
```

### 🗄️ Database Configuration

Add your MySQL credentials to `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

> 🔁 Replace the above placeholders with your actual MySQL credentials.

If schema or seed scripts are provided, run them before first launch.

---

## 🧭 System Architecture

<img width="1295" height="1951" alt="diagram-export-7-17-2025-11_49_18-PM" src="https://github.com/user-attachments/assets/5d24d38e-4b1b-4c21-9f7a-4f4588aadd07" />

---

## ✨ Key Highlights

* ✅ Replaced legacy tools like JIRA with a lightweight internal BTS
* 🔐 Implemented secure login and role-based access using Spring Security & JWT
* 📡 Built dynamic RESTful APIs and integrated with Angular frontend
* 📊 Added dashboards to show bug severity, status distribution, and resolution rates
* ⚙️ Chose **microservices architecture** for better scalability and faster maintenance
* 📈 Achieved **100% internal adoption**, cut licensing costs, and improved sprint velocity by **20%**

---

## 📈 Future Enhancements

These features are based on business scalability and Agile team feedback:

* 📊 **Advanced Analytics Dashboards**
  Track bug trends, resolution rates, and team KPIs with interactive filters.

* 📬 **Automated Email Notifications**
  Notify users of bug assignments, updates, and SLA violations in real time.

* 🧩 **CI/CD Pipeline Integration**
  Auto-tag bugs from failed builds in Jenkins/GitHub Actions.

* ⏱️ **SLA Management**
  Define issue deadlines and escalate overdue tickets automatically.

* 🔐 **Audit Logging**
  Track every change in bugs, users, and project timelines.

* 📁 **Data Export & Backup**
  Export bug reports or project summaries to CSV, Excel, or PDF formats.

---

## 💼 Use Cases

* Teams looking for a customizable, license-free alternative to JIRA.
* Agile squads wanting tight integration of bug tracking with internal sprint tools.
* Organizations aiming to reduce bug resolution time and improve sprint tracking transparency.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author

**Gauri Mahale**
*Java Full-Stack Developer | Angular Enthusiast*

* 📧 Email: [gaurimahale3@gmail.com](mailto:gaurimahale3@gmail.com)
* 🔗 LinkedIn: [https://www.linkedin.com/in/gaurimahale/](https://www.linkedin.com/in/gaurimahale/)

---

> 💬 Feel free to fork this project, raise issues, or submit a pull request to collaborate!
```
