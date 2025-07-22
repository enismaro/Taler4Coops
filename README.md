# Taler4Coops

**Privacy-preserving digital payments toolkit for cooperatives**

---

## 🌱 Overview

**Taler4Coops** is an open-source toolkit that helps cooperatives and community-based organisations adopt **privacy-preserving digital payments** with [GNU Taler](https://taler.net/).  

Today, most digital payment systems are expensive, invasive, and built around proprietary platforms that conflict with the democratic, inclusive ethos of cooperatives.  
Taler4Coops makes it simple and affordable for cooperatives of all sizes to deploy and operate GNU Taler in a way that preserves privacy, supports transparent accounting, and avoids vendor lock-in.

This project is developed as part of the [NGI TALER](https://nlnet.nl/taler/) programme, contributing to the digital commons.

---

## 🌟 Key Features

- 🌍 Web-based payment portal for customers and cashiers
- 🛠️ Admin dashboard with cooperative-friendly workflows
- 🔧 CLI tools for advanced users and automation
- 📄 Comprehensive, multilingual documentation
- 🔗 Fully open-source and aligned with GNU Taler standards
- 🧩 Designed for self-hosting or cloud deployment

---

## 📐 Architecture

Taler4Coops builds on the GNU Taler reference implementation and adds layers designed specifically for cooperatives:
- Frontend web portal for cashier and customer interactions
- Admin backend for member management, transaction oversight, and audit reporting
- REST APIs and CLI tools for integration and scripting
- Lightweight and deployable on standard servers or even constrained hardware

Architecture diagrams and details are available in the [`/docs`](docs/) folder.

---

## 🚀 Getting Started

1. Install GNU Taler core components:  
   [GNU Taler Installation Guide](https://docs.taler.net/)

2. Clone this repository:  
```bash
git clone https://github.com/enismaro/taler4coops.git
cd taler4coops
