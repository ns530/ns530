<div align="center">

# Hi, I'm Nadun Sulochana 👋

### Aspiring Software Architect · Full-Stack Engineer · ML Systems Builder

*Designing systems that scale. Building software that matters.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nadun-sulochana-41923029b)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nadunsulochana92@gmail.com)
[![Portfolio](https://img.shields.io/badge/SkyCrop-Live%20Demo-22C55E?style=for-the-badge&logo=vercel&logoColor=white)](https://skycrop.vercel.app)

</div>

---

## About Me

I'm a BSc (Hons) Cyber Security student at **Sri Lanka Technological Campus** with a deep passion for software architecture, machine learning systems, and building production-grade applications that solve real problems.

I don't just write code — I design systems. From microservices architectures and ML inference pipelines to cross-platform mobile apps, I think about scalability, reliability, and clean design from day one.

- 🏗️ **Aspiring Software Architect** — studying system design, distributed systems, and architectural patterns daily
- 🌱 **Currently learning** — Cloud architecture (AWS), advanced system design, design patterns
- 🚀 **Built** — SkyCrop, a production ML-powered precision farming platform with 5 microservices, deployed on Railway & Vercel
- 🔐 **Security-aware** — BSc in Cyber Security, real internship experience in threat mitigation and incident response
- 📍 **Based in** — Mawathagama, Sri Lanka · Open to remote opportunities worldwide

---

## Featured Project — SkyCrop 🌾

> *The project that defines how I think as an architect.*

**SkyCrop** is a production-grade, ML-powered precision farming platform I designed and built from the ground up — solo. It is not a tutorial project. It is a real system with real architecture decisions, real trade-offs, and real deployment.

### What I built

| Service | Stack | Purpose |
|---|---|---|
| REST API Gateway | Node.js, Express, TypeScript | Field management, auth, routing |
| ML Inference Service | Python, Flask, ONNX Runtime | Satellite image processing |
| ML Training Pipeline | Python, TensorFlow, Keras | U-Net model training |
| React Native Mobile App | Expo, TypeScript | Farmer-facing mobile client |
| React Web Dashboard | React, TypeScript | Management & analytics UI |

### Architecture decisions I made

- **Polyglot persistence** — PostgreSQL + PostGIS for geospatial data, MongoDB for time-series health records, Redis for caching and job queues
- **ONNX export** — trained the U-Net model in TensorFlow, exported to ONNX for framework-agnostic, high-performance production inference
- **Sliding-window inference** — engineered a custom tiling algorithm to process large Sentinel-2 satellite images through the model in overlapping tiles with polygon post-processing
- **Async notification pipeline** — Bull + Redis queue for email (SendGrid) and push notifications (Firebase FCM) without blocking request threads
- **RBAC + multi-tenant** — role-based access control, team management, and field sharing across organisations

### Numbers that matter

```
137 commits · 4 sprints · 104+ tests (51 unit, 27 integration, 21 E2E, 5 load)
92 Lighthouse score · 4.2s mobile load time · 25 open PRs · Live on Vercel + Railway
```

### Core capabilities shipped

- 🛰️ **Satellite field boundary detection** — U-Net segmentation on Sentinel-2 imagery, reducing field-mapping effort by 70%
- 📊 **NDVI / NDWI / TDVI health monitoring** — time-series crop health scoring with anomaly detection and trend analysis
- 🌾 **Yield prediction** — Random Forest model with confidence intervals, revenue estimation, and harvest date forecasting
- 💡 **Recommendation engine** — priority-ranked fertilizer, irrigation, and pest control recommendations
- ☁️ **Weather integration** — historical and forecast data via OpenWeather API
- 🔔 **Real-time alerts** — WebSocket notifications + push via Firebase FCM

**→ [View SkyCrop on GitHub](https://github.com/ns530/skycrop) · [Live Demo](https://skycrop.vercel.app)**

---

## Tech Stack

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

### Frameworks & Libraries
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## Other Projects

| Project | Stack | Highlights |
|---|---|---|
| [BookStore App](https://github.com/ns530/BooKStore) | Flutter, Firebase | Real-time inventory, CRUD, auth — 50% faster than manual tracking |
| [Quiz App](https://github.com/ns530/QuizApp) | Flutter, Firebase | Dynamic question sets, live scoring, cross-platform |
| [Invoice System](https://github.com/ns530/Invoice_system) | PHP, MySQL | Multi-client billing, PDF export, RBAC, role-based admin panel |

---

## Work Experience

**Website Security Engineer Intern** · Nugegoda, Sri Lanka · *June – November 2025*

- Assessed 10+ security technologies and shaped the organisation's long-term security tooling decisions
- Conducted vulnerability assessments and penetration tests on WordPress applications, identifying and remediating 15+ weaknesses including XSS and SQL injection
- Reduced mean threat-detection time by 30% through network monitoring and anomaly analysis
- Facilitated security awareness workshops for 20+ staff members

---

## On My Way to Software Architect

Being a Software Architect is not just my job title goal — it is my design philosophy right now. With every project I build, I ask:

- *What happens when this needs to serve 100x more users?*
- *What breaks first and how do I design around that?*
- *Is this the right database for this access pattern?*
- *How do the services communicate without tight coupling?*

SkyCrop is my proof that I already think this way. A solo-built, multi-service, polyglot-persistence, ML-integrated, production-deployed platform with a real API spec, a real test suite, and real monitoring.

**Currently studying:** AWS Solutions Architect fundamentals · Advanced system design · Domain-Driven Design · Event-driven architecture

---

## Education

🎓 **BSc (Hons) in Cyber Security** — Sri Lanka Technological Campus (SLTC Research University)
*Expected January 2026 · Relevant: Network Security, Cryptography, Ethical Hacking, Secure Software Development*

---

<div align="center">

*"Architecture is not about the tools you use. It is about the decisions you make."*

**Open to Software Engineer Intern, Junior Developer, and remote opportunities.**
Let's build something great together.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nadun-sulochana-41923029b)
[![Email](https://img.shields.io/badge/Send%20me%20an%20email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nadunsulochana92@gmail.com)

</div>
