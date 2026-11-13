<div align="center">

# 👨‍💻 Ibrohim Umarxo'jayev

### **Full-Stack Software Engineer & Enterprise Systems Architect**
**Specializing in Go (Golang) • Python • Flutter • High-Concurrency Platforms & Academic Digital Infrastructures**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-IbrohimUmar-181717?style=for-the-badge&logo=github)](https://github.com/IbrohimUmar)
[![Telegram](https://img.shields.io/badge/Telegram-Contact_Me-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/ibrohim_umar)
[![Email](https://img.shields.io/badge/Email-Direct_Message-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ibrohimumar@gmail.com)
[![Status](https://img.shields.io/badge/Status-Building_Production_Systems-00C853?style=for-the-badge)](https://github.com/IbrohimUmar)

<br/>

</div>

---

## 📌 Executive Summary

Full-stack engineer with hands-on experience designing, developing, and deploying enterprise-grade digital infrastructures, high-performance backends, and multi-platform client applications. Specializing in **Go (Golang)** and **Python**, with extensive experience architecting university-scale ecosystems, national **HEMIS** API integrations, real-time biometric turnstile access control, and retail POS/ERP systems.

- 🏛️ **Academic Digital Infrastructure:** Architecting large-scale university systems (NamDU Campus Ecosystem, HEMIS OAuth2 sync, academic verification, professor KPI engines).
- ⚡ **High-Throughput Backends:** Designing modular monoliths and microservices in Go (Gin, Chi) and Python (Django, DRF, FastAPI) with asynchronous worker queues and caching.
- 📱 **Cross-Platform & Mobile:** Engineering scalable Flutter apps with Riverpod and clean state management across diverse user roles (Students, Parents, University Staff).
- 🖥️ **Desktop & Hardware Automation:** Developing hardware-integrated POS terminals and biometric turnstile applications with PyQt, Flet, and Wails.

---

## 🏛️ Featured Architectures & Enterprise Systems

### 1. 🎓 [NAMDU Mobile Platform](https://github.com/IbrohimUmar/namdu_mobile) — Unified Campus Enterprise Platform
> **Comprehensive digital campus solution for Namangan State University (NamDU)** serving tens of thousands of active students, parents, and university faculty.

```
                           ┌───────────────────────────────┐
                           │      NAMDU Mobile App         │
                           │   (Flutter / Riverpod / Dio)  │
                           └───────────────┬───────────────┘
                                           │
                      ┌────────────────────┼────────────────────┐
                      ▼                    ▼                    ▼
             [ Student Portal ]   [ Parent Dashboard ]   [ Employee Portal ]
             • HEMIS OAuth2       • SMS OTP Access       • Department Info
             • Grades & GPA       • Child Realtime Sync  • Timetables
             • Timetable & Fees   • Turnstile Logs       • Turnstile Presence
                      │                    │                    │
                      └────────────────────┼────────────────────┘
                                           │  HTTPS / REST / WebSocket
                                           ▼
                           ┌───────────────────────────────┐
                           │      Unified Go Core          │
                           │  (Modular Monolith / Gin)     │
                           │  • PostgreSQL Sync Queues     │
                           │  • Asynchronous Workers       │
                           │  • Embedded Next.js Admin SPA │
                           └───────────────┬───────────────┘
                                           │
                     ┌─────────────────────┴─────────────────────┐
                     ▼                                           ▼
         [(HEMIS National API)]                         [(PostgreSQL Cache / DB)]
```

* **Architecture:** Modular Monolith + Clean Architecture packaged into a single deployable high-performance binary.
* **Backend (`Go`):** REST API endpoints, background workers for batch processing, PostgreSQL sync queues, and an embedded Next.js static SPA dashboard for operators.
* **Mobile (`Flutter`):** Riverpod-powered state architecture with role-based routing (Student, Parent, Employee), secure credential storage, and offline-first capabilities.
* **Integrations:** Direct HEMIS OAuth2 authorization, automated student GPA dynamics calculation, semester timetable syncing, and physical turnstile log streaming.

---

### 2. 🏢 University Digital Infrastructure Suite (EdTech & ERP)

| Platform | Core Tech Stack | Architectural Role & Business Value |
|:---|:---|:---|
| **NamSU EcoSystem v2** | `Python`, `Django`, `Vue.js`, `PostgreSQL` | University-wide electronic document flow, automated academic leave management, faculty KPI rating/scoring engine, and digital registrar integration. |
| **UniAssets ERP** | `Django 5.0`, `DRF`, `PostgreSQL`, `REST API` | Centralized university fixed-asset tracking and inventory platform with batch barcode processing, automated audit trails, and multi-department asset movements. |
| **EduRate** | `Python`, `Django`, `Aiohttp`, `Asyncio` | High-concurrency professor and academic department KPI rating engine with asynchronous batch evaluation of faculty performance metrics. |
| **DailyQuiz Engine** | `Go`, `Wails`, `Vue.js`, `Django` | High-security exam testing system featuring real-time question timers, dynamic question/answer shuffling, anti-tamper mechanisms, and instant score computation. |

---

### 3. 🔐 Biometrics, Physical Access Control & Desktop Utilities

* **🎯 NamDU Face Turniket System:**
  * Physical turnstile hardware integration built with **Python**, **Flet**, and **SQLite/PostgreSQL**, compiled to native Windows binaries via PyInstaller.
  * Real-time biometric attendance processing for university employees and students, synchronizing physical checkpoint entries with central databases.
* **🔍 HEMIS Grade & Academic Auditor:**
  * Automated desktop audit tool developed with **PyQt6** and **Flet** for faculty administrators to inspect student course completion, grade integrity, and attendance compliance against official national HEMIS records.

---

### 4. 🛒 Retail, POS & Supply Chain Systems

* **🍔 Shaurma N1 — FastFood POS Suite:**
  * Complete, high-speed Point of Sale ecosystem engineered with **Python 3.12**, **PyQt5**, and **SQLite** optimized for touch terminals.
  * **Core Modules:** Real-time cashier order terminal, Kitchen Display System (KDS), customer-facing TV queue display with automated daily ticket numbering, thermal receipt printing, and comprehensive end-of-day Z-reports.
* **📦 Elituv Warehouse & Supply Chain ERP:**
  * Multi-branch inventory management platform containerized with **Docker & Docker Compose**.
  * Built with **Go (Gin)** for high-throughput stock transactions, **Nuxt.js** for a modern reactive interface, and **PostgreSQL** with strict multi-user permission controls and warehouse transfer tracking.
* **💼 OsonSavdo & Foyda24:**
  * Commercial trading and financial calculation platforms supporting real-time transaction tracking and retail sales analytics.

---

## 🛠️ Technical Arsenal

<div align="center">

### Languages & Core Runtimes
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend Frameworks & Architecture
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/Django_REST-A30000?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Gin](https://img.shields.io/badge/Gin_Gonic-008ECF?style=for-the-badge&logo=go&logoColor=white)
![RESTful APIs](https://img.shields.io/badge/REST_APIs-0052CC?style=for-the-badge&logo=json&logoColor=white)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-2B3A42?style=for-the-badge)

### Frontend, Mobile & Desktop
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Nuxt.js](https://img.shields.io/badge/Nuxt.js-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![PyQt](https://img.shields.io/badge/PyQt5_/_PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![Flet](https://img.shields.io/badge/Flet-FF4B4B?style=for-the-badge&logo=flutter&logoColor=white)
![Wails](https://img.shields.io/badge/Wails-DF0000?style=for-the-badge&logo=go&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Databases, DevOps & Tools
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📊 GitHub Analytics & Productivity

<div align="center">

<table border="0">
  <tr>
    <td width="50%">
      <img src="https://github-readme-stats.vercel.app/api?username=IbrohimUmar&show_icons=true&theme=radical&hide_border=true&count_private=true" width="100%" alt="Ibrohim's GitHub Stats" />
    </td>
    <td width="50%">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IbrohimUmar&layout=compact&theme=radical&hide_border=true" width="100%" alt="Top Languages" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=IbrohimUmar&theme=radical&hide_border=true" width="95%" alt="GitHub Streak" />
    </td>
  </tr>
</table>

</div>

---

## 🤝 Connect & Collaborate

I am always open to discussing technical architecture, enterprise software engineering, EdTech platforms, and high-performance backend systems.

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-@ibrohim__umar-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/ibrohim_umar)
[![GitHub](https://img.shields.io/badge/GitHub-IbrohimUmar-181717?style=for-the-badge&logo=github)](https://github.com/IbrohimUmar)
[![Email](https://img.shields.io/badge/Email-ibrohimumar@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ibrohimumar@gmail.com)

<br/>

<sub>⚡ Crafted with precision by <b>Ibrohim Umarxo'jayev</b> • Designed for production-grade reliability</sub>

</div>
