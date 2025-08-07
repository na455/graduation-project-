# 🛡️ Advanced Zero Trust Network Architecture – SDP-Based Cybersecurity Framework

> *“Success is not a coincidence – it's the outcome of persistence, precision, and passion for solving real-world problems.”*

This graduation project is a **fully integrated, enterprise-grade cybersecurity framework** designed and implemented by a team of network engineers and security enthusiasts. It leverages the power of **Zero Trust principles** and **Software-Defined Perimeter (SDP)** architecture to provide a next-generation, invisible and unbreachable network perimeter.

## 📌 Executive Summary

This project bridges theory and real-world application by transforming abstract security models into a **working, secure, and modular system** using open-source technologies and professional-grade protocols.

The solution introduces **pre-authentication access control**, **identity-driven security**, and **micro-segmentation**, ensuring that **no device or user gains access until explicitly verified and authorized**.

## 🧩 Core Architecture Components

### 🔑 1. Single Packet Authorization (SPA)
- AES-CBC encrypted SPA packet with rotating keys
- RSA-encrypted IV exchange for confidentiality
- UDP-based stealth listener to reduce attack surface
- Zero initial visibility without valid SPA

### 🧠 2. SDP Controller (Custom Python Daemon)
- Token validation (JWT) and role-based access
- mTLS certificate generation and distribution
- Real-time dynamic firewall policy enforcement
- Service whitelisting and session timeouts

### 🧍 3. Identity & Access Management (IAM) with Keycloak
- Centralized authentication and SSO
- Role-Based Access Control (RBAC)
- Integration with LDAP for enterprise-scale deployments

### 🔒 4. mTLS-Backed Reverse Proxy via NGINX
- Encrypted, authenticated routing to private services
- Service isolation and per-user policy enforcement
- Auto-renewed certificates using OpenSSL + CRON

### 👁️ 5. Logging, Monitoring & Alerting
- Integrated with **Wazuh SIEM** for log aggregation
- **Elastic Stack (ELK)** dashboards for real-time analysis
- Slack & email alerts for policy violations and anomalies

### 🖥️ 6. GUI Interface for Operational Control
- Built with **CTkinter** for a clean, intuitive UI
- Real-time device status, SPA generation, logs
- Role-based view separation (Admin/User)

## 🧪 Tech Stack

| Category             | Technology Used                        |
|----------------------|----------------------------------------|
| Language             | Python (3.10+)                         |
| Security Layer       | OpenSSL, RSA/AES, mTLS                 |
| Access Control       | Keycloak, JWT, RBAC                    |
| Infrastructure       | NGINX, iptables                        |
| Monitoring & SIEM    | Wazuh, ELK Stack, Filebeat             |
| UI/UX                | CTkinter (Tkinter + Custom Themes)     |
| OS & Environment     | Ubuntu Server 22.04, Debian, CentOS    |

## 📎 Project Resources

- 📘 [Full Technical Report](https://lnkd.in/d9fg4VSJ)  
- 🎬 [Demo Video – Full System Walkthrough](https://lnkd.in/dwBpku84)  
- 📂 Source Code available in this repository (modular and documented)


## 👥 Authors

-  **Nada Hussein Khamis**  
-  **Mohamed Nader**  
-  **Youssef Mohy**  
-  **Hesham Sayed** 
- 🎓 Supervised by: **Prof. Ihab Ali**


---

> 💡 *This project showcases a production-level simulation of real-world Zero Trust infrastructure, demonstrating our expertise in system hardening, secure-by-design principles, and advanced Linux-based network control.*

📬 **Let’s connect:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nada%20Hussein-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/nada-hussein-khamis-8b6b44274/)  
[![GitHub](https://img.shields.io/badge/GitHub-na455-black?style=for-the-badge&logo=github)](https://github.com/na455)  
[![Gmail](https://img.shields.io/badge/Gmail-nadanodo455%40gmail.com-red?style=for-the-badge&logo=gmail)](mailto:nadanodo455@gmail.com)

---

