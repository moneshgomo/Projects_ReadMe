# Dev16 Blog Platform

A robust, cloud-native blog platform featuring secure administration, monolithic architecture, and modern development  techniques

---

## Overview

**Dev16 Blog** is a full-featured content management system designed for professional blogging and seamless content delivery. The platform isfocused  on   <Strong>scaling</Strong>

- ⚙️ Note: The backend server is hosted on Render’s free tier, which means it may enter an idle state after inactivity — so it can take a few seconds to spin up (cold start) when you first access it.
---

## System Architecture

- **Frontend:** Deployed on Firebase 
- **Backend:** Hosted on Render for scalable REST API services.
- **Database:** Managed MySQL instance provisioned via Aiven Cloud

**Architecture Diagram:**

```bash
[User] ⇄ [Firebase Frontend ] ⇄ [Render REST API] ⇄ [Aiven MySQL]
```

---

## Technology Stack

### Backend

| Component       | Technology                        |
|-----------------|-----------------------------------|
| Framework       | Spring Boot 3, Spring Security    |
| Authentication  | JWT (JSON Web Tokens)             |
| Database        | MySQL (Aiven Cloud)               |
| API Design      | RESTful                           |
| Deployment      | Render Cloud                      |

### Frontend

| Component       | Technology                        |
|-----------------|-----------------------------------|
| Languages       | HTML,CSS, Javascript                       |
| Hosting         | Firebase Hosting                  |
| Domain          | [Here](https://blog-1fcl.onrender.com) |

---
### 🔗 **Project Access**

- **Frontend:**  
  [![Firebase Frontend](https://img.shields.io/badge/Firebase-Frontend-FFCA28?style=for-the-badge&logo=firebase)](https://dev16-blog.web.app)

- **Backend:**  
  [![Render Backend](https://img.shields.io/badge/Render-Backend-46E3B7?style=for-the-badge&logo=render)](https://blog-1fcl.onrender.com)  
  ⚙️ *Note:* The backend server is hosted on **Render’s free tier**, so it may take a few seconds to **wake up (cold start)** after being idle.

- **User Access:**  
  <p align="left">
    <img src="https://img.icons8.com/color/48/web.png" width="60" height="60" alt="Web Icon"/>
    <br/>
    👉 <a href="https://blog-1fcl.onrender.com/">Backend Server Status</a>
  </p>

- **Admin Panel:**  
  <p align="left">
    <img src="https://img.icons8.com/stickers/100/admin-settings-male.png" width="60" height="60" alt="Admin Icon"/>
    <br/>
    👉 <a href="https://gomodevblogs.netlify.app/">Open Admin Panel</a>
  </p>

---


### 🖥️ **Project Screenshots**

---

#### 🧠 **Server Status Page**
<img width="1600" height="1300" alt="Server" src="https://github.com/user-attachments/assets/3e0eab54-702d-4d17-9559-01dd8bce84a9" />

- This page is used to **check the backend server status** — it ensures the API is live and connected before any frontend requests are processed.

---

#### 🏠 **Home UI**
<img width="1600" height="1300" alt="Home" src="https://github.com/user-attachments/assets/1efc2011-ff7e-4f31-8e28-43f9760f3fbf" />

- The home screen of **Dev16-Blog**, displaying a clean and responsive **frontend UI** for readers to explore posts.

---

#### 📰 **App (Blog Display Page)**
<img width="1600" height="1300" alt="App" src="https://github.com/user-attachments/assets/0ff051d4-861b-4a0a-8c31-c678e7d7c5b7" />

- This section lists **all published blogs with pagination** for better navigation and user experience.

---

#### 🧑‍💼 **Admin Dashboard**
<img width="1600" height="1300" alt="Admin" src="https://github.com/user-attachments/assets/9f5244eb-81c6-477e-91ce-f09af2f7fe3a" />

- A **secured admin panel** for managing blog posts — includes **login credentials, CRUD operations,** and analytics dashboard.

---


## Core Features

### Administration

- Secure JWT-based authentication and authorization
- Dedicated admin dashboard for content and user management
- Role-based access control (RBAC)
- Automated email notifications on user registration

### User Experience

- Responsive, mobile-first UI
- Clean, accessible blog interface
- Real-time feedback and error handling

### Infrastructure

- Decoupled frontend/backend for independent scaling and deployment
- Managed MySQL database with automated backups (Aiven)
- Environment variable management for secure configuration

---

- Curious to know more about me visit here : [🌐](https://moneshgomo.netlify.web.app)

---
