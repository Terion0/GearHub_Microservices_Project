
# ⚙️ GearHub – Final Degree Project

🚘 **Overview**  
**GearHub** is a full-stack social platform tailored for auto enthusiasts and workshops. It allows users to manage their vehicles, engage in real-time messaging, track maintenance history, and participate in community forums. Workshops can handle services, respond to queries, and improve their visibility. Users can rate workshops and register their vehicles.

Developed as the final project for the **Higher Technician in Multi-platform Application Development** degree.

Cocreated by: **José María García Sánchez** & **Rodrigo Tapiador Cano**

---

## 🧩 Architecture

GearHub is built on a microservice-based architecture and deployed using **Docker Compose**. The system could be further improved by using orchestrators like **Kubernetes** or **Docker Swarm**.

**Main components:**

- 6 ASP.NET Core microservices
- PostgreSQL and MongoDB databases
- Ocelot API Gateway
- Web frontend (React + TailwindCSS)
- Android mobile app (Jetpack Compose + Hilt)

---

## 🔗 Repositories

| Module              | Description                                    | Repo Link                                               |
|---------------------|------------------------------------------------|----------------------------------------------------------|
| **Auth Service**     | Handles JWT, user registration, email verification | [🔗 AuthApi_](https://github.com/Terion0/AuthApi_)         |
| **Profiles Service** | User profiles, followers, image management     | [🔗 ProfApi](https://github.com/Terion0/ProfApi)           |
| **Workshops Service**| Workshop, vehicle, orders, invoices           | [🔗 WebApiTaller](https://github.com/rasitoo/WebApiTaller) |
| **Reviews Service**  | Review system and workshop replies             | [🔗 RevApi](https://github.com/Terion0/RevApi)             |
| **Communities**      | Forums, threads, roles, likes                  | [🔗 gearhub](https://github.com/Terion0/gearhub)           |
| **Messaging Service**| Real-time messaging with SignalR               | [🔗 WebApiMessages](https://github.com/rasitoo/WebApiMessages) |
| **API Gateway**      | Unified routing with Ocelot                    | [🔗 WebApiGateway](https://github.com/rasitoo/WebApiGateway) |
| **Web Frontend**     | React + TailwindCSS + SignalR Frontend        | [🔗 GearHub Web](https://github.com/rasitoo/TFG-social_network_GEARHUB) |
| **Mobile App**       | Android app with Jetpack Compose              | [🔗 GearHubMobile](https://github.com/rasitoo/GearHubMobile) |

---

## 🛠️ Tech Stack

- **Backend**: ASP.NET Core, SignalR, Ocelot, PostgreSQL, MongoDB, Docker
- **Frontend Web**: React, TailwindCSS, SignalR, Nginx
- **Frontend Mobile**: Kotlin, Jetpack Compose, Hilt, Retrofit, DataStore
- **DevOps**: Docker Compose, Docker Hub

---

## 🚀 Features

- User registration and secure login (JWT)
- Vehicle management and maintenance tracking
- Workshop profiles and service offerings
- Real-time messaging between users and workshops
- Community forums (threads, replies, roles)
- Rating and review system for workshops
- Fully containerized and deployable setup
- (Planned) Smart recommendations engine

---

## ⚙️ Deployment
Currently you would need to make some changes in order to deploy this aplication. I will be glad to help you with it. So talk to me in Linkedin or  Instagram (Links in my profile)
If you just wanna use it, here is the login page http://vms.iesluisvives.org:25002/login
Due to Sendgrip, maybe you won´t be able to get a confirmation email so i recommend you to use this user: 
Email : q7o6xpfdr7@cmhvzylmfc.com
Password : 123123

📱 The Android app (APK) can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1YMc2tlJxLj-K0ueN4pxn_d_T2q4AK4QY).

---

## 👨‍💻 Authors

- **José María García Sánchez**  
  [GitHub](https://github.com/Terion0) · [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-mar%C3%ADa-garc%C3%ADa-s%C3%A1nchez-13236b176/)

- **Rodrigo Tapiador Cano**  
  [GitHub](https://github.com/rasitoo) · [LinkedIn](https://www.linkedin.com/in/rodrigo-tapiador-cano)




