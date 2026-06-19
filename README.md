<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=200&section=header&text=Aaniya%20Jain&fontSize=50&animation=fadeIn" alt="Header">
</div>

# 👩‍💻 Aaniya Jain - Master Development Portfolio & Issue Tracker

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=AaniyaJain&color=blueviolet&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views">
  <a href="https://github.com/AaniyaJain">
    <img src="https://img.shields.io/github/followers/AaniyaJain?style=flat-square&color=blueviolet" alt="GitHub followers">
  </a>
  <img src="https://img.shields.io/badge/Status-Actively_Maintained-success?style=flat-square" alt="Status">
</div>

<br>

Welcome to my central **Master Project Repository**! I am a **B.Tech Computer Science Engineering student** at **SRM Institute of Science and Technology**. 

This repository serves as a monorepo-style portfolio, centralized issue tracker, and project management hub for the major academic, personal, and freelance projects I've engineered over the past two years. By centralizing my workflow here, I maintain a unified timeline of my continuous integration, architectural decisions, and version control across multiple disparate codebases.

---

## 🚀 Featured Projects Portfolio

### 🏥 1. MediVue - Comprehensive Healthcare Management
A robust, secure healthcare management system designed to digitize and streamline hospital administration, doctor appointments, and patient medical records.
* **Tech Stack:** Java, JDBC, SQL, JavaFX
* **Architecture:** Model-View-Controller (MVC) Pattern with strict Database Normalization (3NF).
* **Key Features:**
  * **Role-Based Access Control (RBAC):** Distinct dashboards for Patients, Doctors, and Admins.
  * **Medical History Tracking:** Immutable record-keeping for previous diagnoses and prescriptions.
  * **Automated Scheduling:** Collision-free appointment scheduling using SQL transaction locks.
* **Current Status:** Deployed in local beta testing. Database optimization phase complete.

### 🩸 2. Blood Bank Management System
A mission-critical web application built to connect blood donors with hospitals and recipients with zero latency during emergencies.
* **Tech Stack:** Node.js, Express.js, MongoDB, Mongoose, REST APIs
* **Architecture:** Microservices-oriented backend with a NoSQL document database.
* **Key Features:**
  * **Real-time Inventory Tracking:** Geospatial queries to find the nearest blood banks with required blood groups.
  * **Urgent Broadcast System:** Push notifications/SMS triggers for rare blood group requirements (e.g., O-negative).
  * **Donor Verification:** OTP-based registration and eligibility cooldown tracking.
* **Current Status:** API layer finalized. Frontend integration in progress.

### 🍔 3. SRMiggy - Smart Campus Canteen Application
A hyper-local food ordering platform designed specifically to handle high-concurrency traffic during SRM campus lunch rushes.
* **Tech Stack:** HTML5, CSS3 (Flexbox/Grid), Vanilla JavaScript, Node.js backend.
* **Architecture:** Client-Server model with WebSocket integration for live updates.
* **Key Features:**
  * **Live Order Tracking:** State-machine based order progression (Placed ➔ Cooking ➔ Ready).
  * **Cart State Management:** Client-side local storage synchronization with server-side validation.
  * **Vendor Dashboard:** Real-time incoming order queue for kitchen staff.
* **Current Status:** Core UI completed. WebSocket load testing underway.

### 📦 4. Shipment Tracking System
An enterprise-grade logistics solution to monitor package delivery statuses, route optimizations, and fleet management.
* **Tech Stack:** Java, MySQL, Graph Algorithms (Dijkstra's)
* **Architecture:** Service-Oriented Architecture (SOA).
* **Key Features:**
  * **Route Optimization:** Algorithmic calculation of the shortest delivery paths between regional hubs.
  * **State Machines:** Strict transition rules for package states (e.g., In Transit cannot jump to Delivered without Reaching Hub).
  * **Reporting Engine:** Automated weekly PDF reports for fleet efficiency.
* **Current Status:** Algorithm optimization phase.

### 📜 5. Certificate Generator API
An automated python tool for generating bulk certificates for college events, hackathons, and workshops.
* **Tech Stack:** Python, Pandas, Jinja2 HTML/CSS Templates, pdfkit
* **Architecture:** CLI-based batch processing pipeline.
* **Key Features:**
  * **Dynamic Templating:** Inject participant data into highly customizable CSS-driven templates.
  * **Batch Processing:** Ability to generate 1000+ PDFs in under 2 minutes using multi-threading.
  * **Email Integration:** Automated SMTP dispatch of certificates directly to participants.
* **Current Status:** Stable release. Used in 3 recent campus events.

---

## 🛠️ Technical Skills & Tools

| Category | Technologies |
| :--- | :--- |
| **Languages** | Java, Python, JavaScript (ES6+), SQL, HTML5, CSS3 |
| **Databases** | MySQL, MongoDB, PostgreSQL |
| **Backend** | Node.js, Express.js, RESTful APIs, JDBC |
| **Tools & DevOps** | Git, GitHub Actions, Postman, Docker (Basics), VS Code |
| **Core CS** | Data Structures, Algorithms, Object-Oriented Programming (OOP), DBMS |

---

## 📈 About My Version Control Workflow

If you are exploring my commit history, you will notice a high volume of consistent, incremental commits over a two-year span. 

**Why so many commits?**
I strongly adhere to Agile methodologies and iterative development. Instead of massive, monolithic uploads, I break my work down into micro-tasks:
1. **Database Schema Setup** ➔ *Commit*
2. **Core Logic Implementation** ➔ *Commit*
3. **UI/UX Tweaks & CSS Fixes** ➔ *Commit*
4. **Bug Fixes & Refactoring** ➔ *Commit*

This repository acts as the **central aggregation point** for all these micro-commits across the 5 disparate projects listed above, allowing me to track my continuous daily progress, manage cross-project dependencies, and maintain a unified developer timeline.

---

<div align="center">
  <i>"Code is like humor. When you have to explain it, it’s bad." – Cory House</i>
  <br><br>
  <b><a href="mailto:aaniyajain20343@gmail.com">📫 Reach out to me via Email</a></b>
</div>
